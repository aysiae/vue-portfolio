<script setup lang="ts">
import '../assets/body.scss'
</script>

<template>
    <div class="dreambig-parralax"></div>
    <div class="about-container">
        <div class="about" id="about">
            <div>
                <h2>About Me</h2>
                <h3>Hi, my name is Aysia and. . .</h3>
                <p><strong>I'm a passionate front-end developer</strong> with a flair for crafting engaging and intuitive user interfaces <strong>using cutting-edge technologies like React, Vue, and TypeScript</strong>. My journey in web development has been driven by a love for creating digital experiences that captivate and resonate with users.</p>
                <p>In the realm of front-end development, I thrive on turning ideas into reality, whether it's <strong>implementing complex state management in React using Redux, designing sleek and responsive Vue components, or leveraging the type safety of TypeScript to ensure code reliability</strong>. Every project feels like a puzzle to solve, and I find immense satisfaction in seeing the pieces come together to form a seamless and beautiful application.</p>
                <p>But I'm not just limited to the front end. I also have a knack for backend development, and <strong>I enjoy writing APIs using Node.js. This full-stack capability allows me to bridge the gap between client and server,</strong> ensuring that data flows seamlessly and securely between the two.</p>
                <p>Ultimately, coding isn't just a profession for me; it's a passion. It's the joy of exploring new technologies, the thrill of solving intricate challenges, and the immense satisfaction of watching an entire application come together as a functional masterpiece. I'm excited to continue this journey, pushing the boundaries of what's possible in web development and creating meaningful digital experiences for users.</p>
                <h3>This portfolio website. . .</h3>
                <p> is a testament to my passion for innovative web development. Crafted with Vue.js and powered by TypeScript, it seamlessly blends creativity and functionality.</p>
                <h3>Outside of a digital playground. . .</h3>
                <p>I am a full-time pet mom to a golden retriever, and three cats; I'm passionate about wildlife and animal welfare. I enjoy playing around in Blender creating 3D renders, drawing, and embarking on adventure in Dungeons & Dragons, books, and videogames. </p>
            </div>
            <div>
                <img src="../assets/imgs/Aysia_Headshot.jpg"/>
            </div>
        </div>
        <div class="marquee">
            <div class="marquee-text">
                <p>"Passionate, innovative, and eager to learn."</p>
            </div>
        </div>
    </div>
    
</template>

<style scoped lang="scss">
.dreambig-parralax {
        background-image: url('../assets/imgs/breathe-neon.jpg');
        background-size: cover;
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        height: 800px;
    }

.about-container {
    display: flex;
    flex-direction: column;

    
.marquee {
    background-color: black;
    height: 100px;
    color: #fff;
    overflow: hidden;
    position: relative;
    width: 100%;
    h2 {
        margin-left: 1em;
    }

    .marquee-text {
        font-size: 32px;
        p {
            text-align: center;
        }
    }
}

.about {
    margin-bottom: 3em;
    max-width: 100em;
    display: flex;
    img {
        margin-top: 8em;
        margin-right: 2em;
        width: 30em;
        border-radius: 25px;
    }
    div {
        margin-left: 2em;
        margin-top: 1em;
    }

    }   
}


</style>