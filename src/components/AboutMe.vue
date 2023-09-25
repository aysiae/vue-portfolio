<template>
    <div class="dreambig-parralax"></div>
    <div class="about-container">
        <div>
            <h2>About Me</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor. Cras elementum ultrices diam. Maecenas ligula massa, varius a, semper congue, euismod non, mi. Proin porttitor, orci nec nonummy molestie, enim est eleifend mi, non fermentum diam nisl sit amet erat.</p>
        </div>
    </div>
</template>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Rock+Salt&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap');

.dreambig-parralax {
        background-image: url('../assets/imgs/breathe-neon.jpg');
        background-size: cover;
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        height: 800px;
    }
.about-container {
    img {
        width: 100vw;
    }
    div {
        margin-left: 2em;
        margin-top: 1em;
    }
    h2 {
        font-family: 'Rock Salt', cursive;
    }

    p {
        font-family: 'Josefin Sans', sans-serif;
    }
}

</style>