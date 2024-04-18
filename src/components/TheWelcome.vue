<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <div id="profileGrid">
    <div class="profilePic">
      <img src="@/assets/imgs/OliPB.png" alt="OliPB">
    </div>
    <div class="section__text">
      <p class="section__text__p1">Hello, I'm</p>
      <h1 class="title">Oliver S Sartori</h1>
      <p class="section__text__p2">Frontend Developer And Photographer</p>
      <div class="btn-container">
        <button class="btn btn-color-2" @click="downloadCV">Download CV</button>
        <button class="btn btn-color-1" @click="toggleContactInfo">Contact Info</button>
      </div>
      <div id="socials-container">
        <img src="@/assets/imgs/linkedin.png" alt="My Linkedin profile" class="icon" @click="openLinkedin">
        <img src="@/assets/imgs/GithubBlue.png" alt="My github profile" class="icon" @click="openGithub">
      </div>
      <transition name="slide">
      <div v-show="showContactInfo" id="contact-info" ref="contactInfo">
          <p>Email: Oliver.S.Sartori@gmail.com</p>
          <p>Phone: +4560175399</p>
          <p>IG @OLIVERSTREANDERSARTORI</p>
          <!-- Add more contact information as needed -->
        </div>
      </transition>
    </div>
  </div>
</template>

<script>
import { gsap } from 'gsap';

export default {
  data() {
    return {
      showContactInfo: false,
      contactInfoHeight: 0
    };
  },
  methods: {
    toggleContactInfo() {
  const contactInfoElement = this.$refs.contactInfo;
  const isShowing = !this.showContactInfo;

  if (isShowing) {
    // Before showing the contact info, set its height to 0 and make it visible
    contactInfoElement.style.height = '0';
    contactInfoElement.style.visibility = 'visible';
  }

  gsap.to(contactInfoElement, { 
    height: isShowing ? "7vh" : 0, // Toggle height based on whether it's being shown or hidden
    duration: 0.3, 
    ease: 'power2.inOut',
    onComplete: () => {
      // After animation completes, hide the contact info if it's being closed
      if (!isShowing) {
        contactInfoElement.style.visibility = 'hidden';
      }
    }
  });

  this.showContactInfo = isShowing;
}
    // Other methods
  }
};
</script>

<style scoped>
.slide-enter-active, .slide-leave-active {
  transition: max-height 0.3s ease-out;
}

.slide-enter, .slide-leave-to {
  max-height: 0;
  overflow: hidden;
}
#contact-info {
  max-height: 200px; /* Adjust height as needed */
  border: 2px solid;
  border-color:#1e82af ;
  overflow: hidden; /* Ensure content within the box is hidden when collapsed */
  position: relative;
  margin-top: 2rem;
  border-radius: 3rem;
}

#contact-info p {
  color: silver;
}


#profileGrid {
  display: grid;
  grid-template-columns: 1fr 4fr 4fr 1fr;  
  grid-template-rows: 1fr 1fr 1fr;
  height: 80vh;
  }
  
  .profilePic{
    grid-row: 2;
    grid-column: 2;
    width: 40rem;
    height: 40rem;
    justify-self: end;
    margin-right: 5rem;
  }

  .section__text {
    grid-column: 3;
    grid-row: 2;
    justify-self: start;
    align-self: center;
    margin-left: 3rem;
  }

  #socials-container {
    display: flex;
    justify-content: center;
    margin-top: 1rem;
    gap: 1rem;
}
  .title {
    font-size: 5rem;
    text-align: center;
    color: silver;
} 
.section__text {
    align-self: center;
    text-align: center;

}

.section__text.p {
    font-weight: 600;

}

.section__text__p1 {
    text-align: center;
    color: silver;
}

.section__text__p2{
    font-size: 1.75rem;
    margin-bottom: 1rem;
    color: silver;
}


</style>