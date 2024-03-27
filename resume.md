<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
    <link rel="stylesheet" href="resume.css">
    <style>
        /* You can poke around this CSS if you want to customize your formatting / styling further */
/* You can even import custom fonts! */

@import url('https://www.resume.lol/fonts/cm/fonts.css');

/* meta */
body {
    font-family: "Computer Modern Serif", serif;
    font-size: 11pt;
    font-weight: 500;
}

.spacer {
    margin: 0px auto;
}

/* styling content */
h1, h2, h3, h4, p, a, li {
    color: black;
}

h2 {
    padding: 0;
    margin-bottom: 5pt;
    margin-top: 5pt;
}

h3, h4 {
    margin: 0;
    margin-left: 0.15in;
}

h1 {
    color: black;
    text-align: center;
    font-size: 32pt;
    margin: 0;
    padding: 0;
    margin-top: -0.1in;
    font-family: 'Times New Roman', Times, serif;
    font-weight: 500;
}

h2 {
    border-bottom: 1px solid #000000;
    text-transform: uppercase;
    font-size: 11pt;
    font-weight: normal;
}

h2::first-letter {
    font-size: 14pt;
}

h3 {
    display: flex;
    font-size: 11pt;
    padding: 0;
    justify-content: space-between;
    margin-top: 8px;
}

.indent {
    margin-left: 0.15in;
    /* margin-bottom: px; */
}

.tech-stack {
    font-style: normal;
    font-weight: normal;
}

h4 {
    display: flex;
    font-size: 11pt;
    font-weight: normal;
    font-style: italic;
    padding: 0;
    margin-top: 0;
    margin-bottom: 0;
    justify-content: space-between;
}

p {
    margin: 0;
    padding: 0;
}

a {
    color: black;
    text-underline-offset: 4px;
}

ul {
    margin: 1pt 0;
    margin-left: 0.3in;
    padding-left: 24px;
    padding-right: 24px;
    font-size: 11pt;
    
}
ul > li {
    margin-bottom: 1pt;
}

ul > li:first-child {
    padding-top: -4px;
}

ul > li:last-child {
    margin-bottom: 5pt;
}


/* header info content */
.headerInfo > ul {
    display: flex;
    text-align: center;
    justify-content: center;
    margin: 0px auto 0pt !important;
    margin-top: -1pt;
    padding: 0;
}

.headerInfo > ul > li {
    display: inline;
    white-space: pre;
    list-style-type: none;
}

.headerInfo > ul > li:not(:last-child) {
    margin-right: 8px;
}

.headerInfo > ul > li:not(:last-child):after {
    content: "|";
    margin-left: 8px;
}

.cef a{
    text-decoration: none;
}
.cef span{
  
    
}
@page {
  size: letter;
  margin: 0.5in;
}

    </style>
</head>

<body>
@REDACTED=true
@NAME=Nguyễn Tấn Dũng||Hidden Name
@EMAIL=nguyentandung037@gmail.com|| dung.nguyen42@hcmut.edu.vn

@REDACTED=false
@NAME=Nguyễn Tấn Dũng||Hidden Name
@EMAIL=nguyentandung037@gmail.com|| none

@PHONE=0394996424
@LINKEDIN=ngtandung
@GITHUB=dungnguyen73

# {NAME} 
<br/>
<span class=""> <h>CONTACT :</h3> </span>
<div class="section headerInfo">

- {PHONE}
- [{EMAIL}](mailto:{EMAIL})
- [linkedin.com/in/{LINKEDIN}](https://linkedin.com/in/{LINKEDIN})
- [github.com/{GITHUB}](https://github.com/{GITHUB})

</div>

## Education


### Ho Chi Minh University of Technology <span class="spacer"></span><span class="normal">Aug. 2021 &ndash; present</span>

<!-- optionally include GPA if >=3.7 -->
<!-- Generally, don't include coursework. If you do, only if you're a student & if they're upper level courses. -->

#### Bachelor of Science in Computer Science<span class="spacer"></span>Thu Duc, Ho Chi Minh City
#### Current GPA: 3.4/4.0 

### Nguyen Binh Khiem High School for the Gifted <span class="spacer"></span><span class="normal">Aug. 2018 &ndash; May 2021</span> 
#### <span>GPA: 9.1/10 </span> <span class="spacer"></span>Tam Ky, Quang Nam

#### 

<!-- ## Experience -->
<!-- 
### Undergraduate Research Assistant <span class="spacer"></span><span class="normal"> Jul 2021 &ndash; Present </span>

#### Texas A&M University <span class="spacer"></span> College Station, TX

- Developed a REST API using FastAPI and PostgreSQL to store data from learning management systems
- Developed a full-stack web application using Flask, React, PostgreSQL and Docker to analyze GitHub data
- Explored ways to visualize GitHub collaboration in a classroom setting

### Information Technology Support Specialist<span class="spacer"></span><span class="normal"> Sep. 2018 &ndash; Present </span>

#### Southwestern University <span class="spacer"></span> Georgetown, TX

- Communicate with managers to set up campus computers used on campus
- Assess and troubleshoot computer problems brought by students, faculty and staff
- Maintain upkeep of computers, classroom equipment, and 200 printers across campus

### Artificial Intelligence Research Assistant<span class="spacer"></span><span class="normal"> May 2019 &ndash; July 2019 </span>
#### Southwestern University <span class="spacer"></span> Georgetown, TX

- Explored methods to generate video game dungeons based off of The Legend of Zelda
- Developed a game in Java to test the generated dungeons
- Contributed **50K+** lines of code to an established codebase via Git
- Conducted a human subject study to determine which video game dungeon generation technique is enjoyable
- Wrote an 8-page paper and gave multiple presentations on-campus
- Presented virtually to the World Conference on Computational Intelligence -->

<!-- Older resume bits can be commented out so that you can keep the info without deleting it -->

<!-- ### Information Technology Support Specialist<span class="spacer"></span><span class="normal"> Sep. 2018 &ndash; Present </span>

### Artificial Intelligence Research Assistant<span class="spacer"></span><span class="normal"> May 2019 &ndash; July 2019 </span> -->

## Projects
### [UniMarket](https://github.com/dungnguyen73/UniMarketWeb)<span class="tech-stack">&nbsp;| *Pug, Bootstrap, ExpressJs, MongoDB, Figma, Github*</span><span class="spacer"></span><span class="normal">September 2023 &ndash; December 2023</span>
Project description: A web-based platform in C2B2C model for university students to buy and sell second-hand items, including an Admin site for managing items and accounts, and a User site for browsing and purchasing products.
- Initiated the project concept, idea and proposed project name.
- Engaged in collaborative efforts to refine and iterate on the [UI/UX](https://www.figma.com/file/CPP2YygZSJOSajKSPqdjS9/UniMarket?type=design&node-id=1378%3A1757&mode=design&t=L8A9Oh5zCBL2RbvH-1) designs, with a primary focus on pages related to the Admin site and authentication processes. 
- Developed APIs, focusing on CRUD operations, to facilitate the management of selling items in the backend using Express.js.
-  Designed and implemented the frontend interface for the Admin side of the web application, utilizing Bootstrap and Pug templates.
- Enforced role-based access control mechanisms to regulate access for various types of administrators on the backend site.



### [CostumeHaven](https://costumehaven.vercel.app/)<span class="tech-stack">&nbsp;| *Nestjs, Nextjs, Typescript, NodeJs, Postman, Trello, Github*</span><span class="spacer"></span><span class="normal">May 2018 &ndash; May 2020</span>

Project description:  An e-commerce store that provides customers with a convenient platform to find and purchase high-quality costumes for various occasions.
- Prepare comprehensive documentation outlining the functionality, usage, and specifications of the APIs.
- Assist in shaping the data schema and defining dataset attributes.
- Design, develop, and integrate backend APIs, including thorough testing with other developers and continuous enhancement of API functionality over time.
- Conducting user testing to gather feedback and iterate on the design and functionality.
- Execute targeted email marketing campaigns to drive website traffic, resulting in the acquisition of approximately 100 new visitors.

## Technical Skills

<span class="indent"></span>**Languages**: C/C++, Python, SQL, JavaScript, HTML, CSS, PHP.

<span class="indent"></span>**Frameworks**:  NestJs, ExpressJs, React Native, Node.js, Expo, Bootstrap, WordPress, Material-UI.

<span class="indent"></span>**Developer Tools**: Github, Jira, Azura DevOps, Confluence, VS Code, Figma, Behance, Overleaf.


## Certificates/ Awards
<div class = "cef">

<span class="indent">**[EF SET English Certificate 78/100 (C2 Proficient)](https://cert.efset.org/mHyKBX)**</span>

<span class="indent">**IELTS: 7.0**</span>


<span class="indent">**[Agile with Atlassian Jira](https://www.coursera.org/account/accomplishments/certificate/SFXB36C4577E)**</span>



<span class="indent">**TOFAS National Programming Contest: Top 25**</span>

<span class="indent">**Star Awards 2023 - HCMC cluster final: Third Prize**</sp

</body>