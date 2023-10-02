<template>
    <div class="resume">
            <h2>Education</h2>
            <div class="education">
                <img src="../assets/imgs/Washington_Huskies_Logo_.png"/>
                <div>
                    <h3>University of Washington (Undergraduate Degree) | 2015 - 2020</h3>
                    <p>Bachelor of the Arts in Communications, Minor in Informatics</p>
                </div>
            </div>
            <div class="education">
                <img src="../assets/imgs/code_fellows.png"/>
                <div>
                    <h3>Code Fellows Bootcamp (Certification) | 2020 - 2021</h3>
                    <p>Certification of Completion: Full Stack JavaScript Development</p>
                </div>
            </div>
    </div>
</template>

<style scoped lang="scss">
    .resume {
        margin-left: 2em;

        .education {
            display: flex;
            align-items: center;

            div {
                margin-left: 1em;
            }

        }

        img {
            height: 65px;
        }
    }
    
</style>