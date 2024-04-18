<!-- <template>
  <section id="about">
        <p class="section__text__p1"> Get To Know More</p>
        <h1 class="title"> About Me</h1>
        <div class="section-container">
            <div class="section__pic-container">
                <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/AboutBillede.png" alt="profile picture" class="about-pic"/></div>

            <div class="about-details-container">
                <div class="about-containers">
                    <div class="details-container">
                        <img src="./assets/experience.png" 
                        alt="experience icon"
                        class="icon"
                        />
                        <h3>Experience</h3>
                        <p>2+ years <br /> Frontend Development </p>
                    </div>
                    <div class="details-container">
                        <img src="./assets/education.png" 
                        alt="education icon"
                        class="icon"
                        />
                        <h3>Education</h3>
                        <p>Currently at DMJX <br /> Media and English STX </p>

                    </div>
                </div>
                <div class="text-container">
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Enim velit explicabo perspiciatis omnis illum fugit accusantium, neque commodi adipisci asperiores? Officia vel aliquam minima aperiam eum quam dolores expedita excepturi quaerat, cupiditate, sit earum inventore quae numquam? Ea velit ab minima commodi in voluptatibus laborum, quam amet eos ipsa doloremque!</p>
                </div>
            </div>
        </div>
        <img src="./assets/arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='./#experience'">

    </section>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style> -->
<template> 
<div id="aboutGrid">
  <!-- <section id="about"> -->
        <!-- <p class="section__text__p1"> Get To Know More</p>
        <h1 class="title"> About Me</h1> -->
        <!-- <div class="section-container"> -->
            <div class="section__pic-container-about">
                <img src="@/assets/imgs/AboutBillede.png" alt="profile picture" class="about-pic"/></div>
                
                <div class="text-container">
                    <p>I am a former soldier who has transitioned into the world of design, coding, and education. After my time in the military, I chose to pursue my passions and am now a dedicated student at DMJX. With a background in the military, I bring a disciplined approach to my studies while eagerly seeking to learn and develop my skills in design and coding. I look forward to combining my military experiences with my newfound knowledge to make meaningful contributions in this exciting field.</p>
                </div>
              
                <div class="coded-container">
                  <div class="coded-container-title"> <h3>CODING</h3> </div>
                    <div class="skills1"> 

                      <div class="html-skill">
                        <!-- <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon"> -->
                        <h3>HTML</h3>
                        <p>Basic</p>
                      </div>
                    
                      <div class="css-skill">
                        <!-- <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon"> -->
                        <h3>CSS</h3>
                        <p>Basic</p>
                      </div>
                    
                    
                      <div class="js-skill">
                        <!-- <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon"> -->
                        <h3>JS</h3>
                        <p>Basic</p>
                      </div>

                      <div class="proc-skill">
                        <!-- <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon"> -->
                        <h3>PROCESSESING</h3>
                        <p>Basic</p>
                      </div> 
                      <div class="check-mark1">
                        <img src="@/assets/imgs/badge-check.png" alt="Experience icon" class="icon">
                      </div>
                      
                    </div>
                  </div>

                  <div class="coded-container2">
                  <div class="coded-container2-title"> <h3>OTHER</h3> </div>
                    <div class="skills2"> 

                      <div class="photo-skill">
                        <!-- <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon"> -->
                        <h3>PHOTOGRAPHY</h3>
                        <p>Experienced</p>
                      </div>
                    
                      <div class="lightroom-skill">
                        <!-- <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon"> -->
                        <h3>Lr, Cap1, Ps</h3>
                        <p>Intermediate</p>
                      </div>
                    
                    
                      <div class="videography-skill">
                        <!-- <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon"> -->
                        <h3>VIDEOGRAPHY</h3>
                        <p>Intermediate</p>
                      </div>

                      <div class="blender-skill">
                        <!-- <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon"> -->
                        <h3>BLENDER</h3>
                        <p>Basic</p>
                      </div>
                      
                      <div class="check-mark2">
                        <img src="@/assets/imgs/badge-check.png" alt="Experience icon" class="icon">
                      </div>

                    </div>
                  </div>
                </div>

              

                <!-- <div id="coding">
    <div class="coding-text">
      <article class="article">
        <h3>HTML</h3> <br>
        <p>Basic</p> <br>
        <div class="item">
          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon">
          <div>
          </div>
        </div>
      </article>
      <div class="coding-text">
      <article class="article">
        <div class="item">
          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon">
          <div>
            <h3>CSS</h3>
            <p>Basic</p>
          </div>
        </div>
      </article>
      <div class="coding-text">
      <article class="article">
        <div class="item">
          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon">
          <div>
            <h3>HTML</h3>
            <p>Basic</p>
          </div>
        </div>
      </article>
      <div class="coding-text">
      <article class="article">
        <div class="item">
          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon" class="icon">
          <div>
            <h3>HTML</h3>
            <p>Basic</p>
          </div>
        </div>
      </article>
    </div>
  </div>
</div>
</div> -->



      
                      <!-- <article>
                          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                          class="icon">
                          <div>
                              <h3>CSS</h3>
                              <p>Basic</p>
                          </div>
                      </article>
                      <article>
                          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                          class="icon">
                          <div>
                              <h3>PROCESSESING</h3>
                              <p>Basic</p>
                          </div>
                      </article>
                      <article>
                          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                          class="icon">
                          <div>
                              <h3>JS</h3>
                              <p>Basic</p>
                          </div>
                      </article> -->
                    <!-- </div>
                </div> -->
            <!-- <div class="about-details-container">
                <div class="about-containers1">
                  <div class="details-container1">
                  <h2 id="experience-sub-title2">Coding</h2>
                  <div class="article-container">
                      <article>
                          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                          class="icon">
                          <div>
                              <h3>HTML</h3>
                              <p>Basic</p>
                          </div>
                      </article>
                      <article>
                          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                          class="icon">
                          <div>
                              <h3>CSS</h3>
                              <p>Basic</p>
                          </div>
                      </article>
                      <article>
                          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                          class="icon">
                          <div>
                              <h3>PROCESSESING</h3>
                              <p>Basic</p>
                          </div>
                      </article>
                      <article>
                          <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                          class="icon">
                          <div>
                              <h3>JS</h3>
                              <p>Basic</p>
                          </div>
                      </article>
                  </div>
              </div>
                  <div class="details-container">
                    <h2 id="experience-sub-title">Other</h2>
                    <div class="article-container">
                        <article>
                            <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                            class="icon">
                            <div>
                                <h3>Photograhpy</h3>
                                <p>Experienced</p>
                            </div>
                        </article>
                        <article>
                            <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                            class="icon">
                            <div>
                                <h3>Lightroom & Photoshop</h3>
                                <p>Experienced</p>
                            </div>
                        </article>
                        <article>
                            <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                            class="icon">
                            <div>
                                <h3>Blender</h3>
                                <p>Basic</p>
                            </div>
                        </article>
                        <article>
                            <img src="/Users/Saturn/PortfolioVue/src/assets/imgs/badge-check.png" alt="Experience icon"
                            class="icon">
                            <div>
                                <h3>Videography</h3>
                                <p>Intermediate</p>
                            </div>
                        </article>
                    </div>
                </div>
                </div>
            </div> -->
        <!-- </div> -->
        <!-- <img src="./assets/arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='./#experience'"> -->

    <!-- </section> -->
  <!-- </div> -->
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}

#aboutGrid {
  display: grid;
  grid-template-columns: repeat(8, 1fr);
  grid-template-rows: repeat(2, 1fr);
  margin-top: 10rem;
  width: 100vw;
  gap: 1rem;
  position: absolute;
  height: 50vh;
  } 

  .section__pic-container-about
  {
    grid-row: 1;
    grid-column: 4;
    width: 25rem;
    justify-self: start;
    margin-bottom: 1rem;
  } 

  .text-container 
  {
    grid-row: 1;
    grid-column-start: 5;
    grid-column-end: 7;
    align-self: center;
    text-align: center;
    margin-bottom: 1rem;
  } 

  .coded-container {
    /* box-shadow: 1px 1px 2rem #1e82af; */
    border: #1e82af 0.1rem solid;
    grid-row: 2;
    grid-column-start: 2;
    grid-column-end: 5;
    background-color: black;
    border-radius: 5rem;
    color: silver;
    height: fit-content;
    margin-right: 7rem;
    margin-left: 7rem;
}

.coded-container-title {
  color: silver;
  font-size: 2rem;
  position: relative;
  width: 100%;
  text-align: center;
  background: none;
  margin-bottom: 1rem;
} 

.skills1 
{
  display: flex;
  width: 100%;
  justify-content: space-evenly;
  margin-bottom: 1rem;
  text-align: center;
} 

.skills1 p {
  color: grey;
  text-align: center;

}

.coded-container2 {
    /* box-shadow: 1px 1px 2rem #1e82af; */
    border: #1e82af 0.1rem solid;
    grid-row: 2;
    grid-column-start: 5;
    grid-column-end: 8;
    background-color: black;
    border-radius: 5rem;
    color: silver;
    height: fit-content;
    margin-right: 5rem;
}

.coded-container2-title {
  color: silver;
  font-size: 2rem;
  position: relative;
  width: 100%;
  text-align: center;
  background: none;
  margin-bottom: 1rem;
} 

.skills2
{
  display: flex;
  width: 100%;
  justify-content: space-evenly;
  margin-bottom: 1rem;
  text-align: center; 
} 

.skills2 p {
  color: grey;
  text-align: center;
}




  /* #coding { */
  /* Center the items horizontally */
  /* display: flex;
  justify-content: center;
  grid-row: 3;
  grid-column-start:2 ;
} */

/* .coding-text {
  /* Display items as a horizontal list */
  /* display: flex;
  gap: 20px; Adjust the gap between items
} */ 

/* .article { */
  /* Style each item */
  /* background-color: black;
  color: silver;
  border-radius: 5rem;
  padding: 20px;
  display: flex;
  margin: 2rem;
  align-items: center; /* Center items vertically * */
/* } */

/* .item {
  /* Style individual item content */
  /* display: flex;
  align-items: center;
} */

/* .icon { */
  /* Style the badge image */
  /* width: 30px; /* Adjust the width as needed */
  /* height: auto;
  margin-right: 10px; Adjust the spacing between the badge and text
} */ 

  /* #coding {
    padding: 1.5rem;
    background: black; */
    /* border-radius: 5rem;
    border: #1e82af 0.1rem solid;
    border-color: rgb(163, 163, 163); */
    /* box-shadow: 2px 2px 30px #1e82af;
    border-radius: 5rem;
    text-align: center;
    color: silver;
    grid-row: 3;
    grid-column: 2; 
  } */

  /* .coding-text {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    padding-top: 3rem;
    align-self: center;
    justify-content: center;
  } 

  .icon {
    justify-self: center;
    align-self: center;
  }

  .coding-text h3 {
    padding: 1rem;
    align-self: end;
    justify-self: center;
  } */

  /* .about-containers {
    grid-row: 3;
    grid-column: 2;
  } */

  .about-details-container
  /* {
    grid-row: 4;
    grid-column-start: 2 ;
    grid-column-end: 4;
    margin-top: 0rem;
    margin: 2rem;
    padding: 2rem;
    align-self: end;
  }  */

  .details-container1 {
    padding: 1.5rem;
    background: black;
    /* border-radius: 5rem;
    border: #1e82af 0.1rem solid;
    border-color: rgb(163, 163, 163); */
    box-shadow: 2px 2px 30px #1e82af;
    border-radius: 5rem;
    text-align: center;
    color: silver;
    grid-row: 4;
    grid-column: 2; 

 }

  /* .about-containers {
    grid-row: 4;
  } */


  #experience-sub-title {
    font-size: 2rem;
    text-decoration: underline;
    text-decoration-color: #1e82af;
  }

  #experience-sub-title2 {
    font-size: 2rem;
    text-decoration: underline;
    text-decoration-color: #1e82af;
  }

</style>
