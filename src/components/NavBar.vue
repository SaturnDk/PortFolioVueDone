</script>

<template>
    <nav id="desktop-nav">
        <div class="logo"> Oliver S Sartori</div>
        <div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li> 
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>
</template>

<style scoped>

<RouterLink to="/">Home</RouterLink>
<RouterLink to="/about">About</RouterLink>
<RouterLink to="/Projects">Projects</RouterLink>

<template>
    <nav id="desktop-nav">
        <div class="logo"> Oliver S Sartori</div>
        <div>
            <ul class="nav-links">
                <RouterLink to="/">Home</RouterLink>
                <RouterLink to="/about">About</RouterLink>
                <RouterLink to="/Projects">Projects</RouterLink>
            </ul>
        </div>
    </nav>
</template>