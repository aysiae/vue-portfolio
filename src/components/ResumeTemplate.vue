<template>
    <div class="resume" id="resume">
        <div class="resume-top">
            <div class="education-container">
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
        <div class="tech">
            <h2>Technologies</h2>
            <ul>
                <li><strong>Languages:</strong> JavaScript, TypeScript, HTML, CSS, Java</li>
                <li><strong>Libraries & Frameworks:</strong> React, Redux, Vue, Pinnia, NodeJS, PostgresSQL,MongoDB, Express, Jest, Vitest</li>
                <li><strong>Tools:</strong>Git, GitHub, AWS (Elastic Beanstalk, S3 Buckets Lambdas, DynamoDB, OpenSearch), Firebase (Auth, Cloudstore Database), Azure (Lambdas, SSO)</li>
                <li><strong>Certifications:</strong> Azure 900</li>
            </ul>
        </div>
        </div>
        <div class="exp">
            <h2>Experience:</h2>
            <h3>Software Engineer @ Slalom Build | June 2021 - September 2023</h3>
            <p>Working at Slalom Build afforded me the experience to work within tech consulting in a space that was conducive to learning and growth. I was pivotable amongst diverse teams of engineers to create seamless experiences for clients. We followed the Agile development cycle to stay ahead of velocity, while meeting deadlines and making ideas reality.</p>
            <ul>
                <li><strong>Retail Client (React, Typescript, NodeJS, AWS):</strong> Joined the team as a Front End leader in React, where I was able to showcase my deep knowledge of the Front End by being a subject matter expert to newer developers and aiding them in expanding their wheelhouse with React. We were developing an internal CRM tool where I worked closely with our back-end lead to seamlessly switch the application's search from DynamoDB to ElasticSearch. </li>
                <li><strong>Retail Client (Vue, Pinnia, NuxtJS, TypeScript, NodeJS):</strong> During this engagement, I was apart of a diverse team of engineers working to make an E-Commerce platform for an independent retailer. I picked up a functional understanding of Vue and Pinnia to create scalable components to be used throughout the e-commerce platform, as well utilizing clean state management for the cart/checkout process. I was responsible for handling API calls to the backend to add/remove/update our cart on the Front End. </li>
                <li><strong>Financial Client (React, JavaScript, NodeJS, Azure):</strong> Worked togehter with an small close knit team to develop and internal search tool for their database; worked with implementing the Front End in React and using Material UI to closely match UX designs. Our backend was powered by NodeJS and Azure where we also worked to make Microsoft Single Sign On functional.</li>    
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap');

    li {
        font-family: 'Josefin Sans', sans-serif;
    }
    .resume {
        margin-left: 2em;

        .resume-top {
            display: flex;
            flex-direction: row;

            
            .education-container {
                width: 60em;

                .education {
                display: flex;
                align-items: center;

                    div {
                        margin-left: 1em;
                    }

                    
                    img {
                        height: 65px;
                    }

                }   
            }

            .tech {
                margin-left: 2em;
                max-width: 700px;
            }
        }

        .exp {
            width: 40em;
        }
 
    }
    
</style>