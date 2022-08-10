<template>
  <div>
    <div id="header" class="bg-[url('/hero-bg.jpg')] px-20">
      <div id="menu" class="grid grid-cols-2 py-5">
        <div id="menu-left">
          <img src="logo.png" class="w-[120px]" alt="" />
        </div>

        <div id="menu-right">
          <ul class="grid grid-cols-6 text-lg font-oswald text-white text-center uppercase pt-5">
            <li>About Me</li>
            <li>Education</li>
            <li>Experience</li>
            <li>Skills</li>
            <li>Portfolio</li>
            <li>Contacts</li>
          </ul>
        </div>
      </div>

      <div class="grid grid-cols-2 pb-10 pt-10">
        <img src="HaftBody.png" class="pr-2 mt-10" alt="" width="700" height="600" />
        <div>
          <h1 class="text-8xl text-white text-center font-lilita uppercase">
            I'm Zong Wei
          </h1>
          <h2 class="text-6xl text-white text-center font-lilita uppercase my-5">
            Hello and Welcome to My Webpage and Portfile
          </h2>
          <p class="text-white font-roboto font-light text-center">
            Data Science | Data Analyst | Business Intelligence | Web Developer | AI | Machine Learning
            | Deep Learning | React JS | React Native | Python | SQL | NoSQL
            | Qlik View & Sense | Power BI | Tableau | LabVIEW
          </p>
        </div>
      </div>
    </div>

    <div id="section-1" class="text-center pb-60 bg-cover">
      <AboutMe />
    </div>
  </div>
</template>
