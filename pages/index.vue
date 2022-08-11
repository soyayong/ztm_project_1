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

    <div id="section-1" class="text-center">
      <AboutMe />
    </div>

    <div id="section-2" class="bg-indigo-400 py-10 px-20">
      <div class="grid grid-cols-3 text-center text-neutral-900 xl:px-52">
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-20 w-20 block mx-auto"
            fill="none"
            viewBox="0 0 16 16"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M8 0a.5.5 0 0 1 .447.276L8.81 1h4.69A1.5 1.5 0 0 1 15 2.5V11h.5a.5.5 0 0 1 0 1h-2.86l.845
              3.379a.5.5 0 0 1-.97.242L12.11 14H3.89l-.405 1.621a.5.5 0 0 1-.97-.242L3.36 12H.5a.5.5 0 0 1
              0-1H1V2.5A1.5 1.5 0 0 1 2.5 1h4.691l.362-.724A.5.5 0 0 1 8 0ZM2 11h12V2.5a.5.5 0 0 0-.5-.5h-11a.5.5 0 0 0-.5.5V11Zm9.61 1H4.39l-.25 1h7.72l-.25-1Z"
            />
          </svg>
          <p class="font-medium font-oswald text-2xl uppercase my-5 text-white">LEAD Stories</p>
          <p class="font-light font-roboto px-5 pb-5 text-white">
            How Zong Wei Became a Data Scientist In a Year (With No Tech Background)
          </p>
          <a
            class="font-oswald uppercase bg-blue-500 hover:bg-blue-700 text-white py-2 px-8 rounded"
            href="https://thelead.io/stories/zong-wei/"
          >Read Me
          </a>
        </div>
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-20 w-20 block mx-auto"
            fill="none"
            viewBox="0 0 16 16"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="1"
              d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175
              1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554
              1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908
              8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216
              1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"
            />
          </svg>
          <p class="font-medium font-oswald text-2xl uppercase my-5 text-white">Linkedin</p>
          <p class="font-light font-roboto px-5 pb-5 text-white">
            We can communicate to know each other and read my latest post
            such as python exercise or video course
          </p>
          <a
            class="font-oswald uppercase bg-blue-500 hover:bg-blue-700 text-white py-2 px-8 rounded"
            href="https://www.linkedin.com/in/yongzongwei-930410/"
          >Connect Me
          </a>
        </div>
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-20 w-20 block mx-auto"
            fill="none"
            viewBox="0 0 16 16"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="1"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38
              0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01
              1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95
              0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0
              1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87
              3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"
            />
          </svg>
          <p class="font-medium font-oswald text-2xl uppercase my-5 text-white">GitHub</p>
          <p class="font-light font-roboto px-5 pb-5 text-white">
            Try to explore Github repositories, maybe some projects can apply
            and remember to fork or star it
          </p>
          <a
            class="font-oswald uppercase bg-blue-500 hover:bg-blue-700 text-white py-2 px-8 rounded"
            href="https://github.com/soyayong"
          >Follow Me
          </a>
        </div>
      </div>
    </div>
  </div>
</template>
