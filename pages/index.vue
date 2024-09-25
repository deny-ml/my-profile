<template>
  <div class="min-h-screen bg-gradient-to-r from-gray-100 to-blue-100 flex items-center justify-center">
    <div class="max-w-3xl bg-white shadow-lg rounded-lg overflow-hidden">
      <div class="flex items-center justify-between p-8 bg-gradient-to-r from-primary to-blue-500 text-white">

        <!-- Profile -->
        <img src="/foto-profil.jpg" alt="Profile Picture" class="w-32 h-32 rounded-full border-4 border-white shadow-md">
        <div class="ml-8">
          <h1 class="text-4xl font-semibold">Deny Arya Setiawan</h1>
          <p class="text-lg text-secondary">Data Analyst | Blockchain Enthusiast</p>
          <div class="flex space-x-4 mt-4">
            <a href="https://www.linkedin.com/in/deny-arya-setiawan-224831246/" target="_blank" class="text-white hover:text-secondary transition-colors">
              <i class="fab fa-linkedin-in fa-lg"></i>
            </a>
            <a href="https://github.com/deny-ml" target="_blank" class="text-white hover:text-secondary transition-colors">
              <i class="fab fa-github fa-lg"></i>
            </a>
            <a href="https://twitter.com/your-profile" target="_blank" class="text-white hover:text-secondary transition-colors">
              <i class="fab fa-twitter fa-lg"></i>
            </a>
            <a href="https://instagram.com/denyaryaaa" target="_blank" class="text-white hover:text-secondary transition-colors">
              <i class="fab fa-instagram fa-lg"></i>
            </a>
          </div>
        </div>
      </div>
      <div class="p-8">

        <!-- About Me Section -->
        <section class="mb-8">
          <h2 class="text-2xl font-bold text-primary">About Me</h2>
          <p class="mt-4 text-gray-700 leading-relaxed">
            I am currently pursuing an Associate Degree at Brawijaya University, majoring in data analysis and blockchain technology.
            As a Data Analyst, I focus on interpreting complex data sets to help organizations make data-driven decisions. 
            I am passionate about blockchain technology and its potential to revolutionize industries, and I actively explore how data and blockchain can merge to create innovative solutions.
          </p>
        </section>

        <!-- Skills Section -->
        <section class="mb-8">
          <h2 class="text-2xl font-bold text-primary">Skills</h2>
          <ul class="mt-4 grid grid-cols-2 gap-4">
            <li class="bg-blue-50 p-4 rounded-lg shadow hover:shadow-md transition-shadow duration-300">
              <span class="font-medium text-primary">Big Data Analysis</span>
            </li>
            <li class="bg-blue-50 p-4 rounded-lg shadow hover:shadow-md transition-shadow duration-300">
              <span class="font-medium text-primary">Blockchain Technology</span>
            </li>
            <li class="bg-blue-50 p-4 rounded-lg shadow hover:shadow-md transition-shadow duration-300">
              <span class="font-medium text-primary">SQL, Database Management</span>
            </li>
            <li class="bg-blue-50 p-4 rounded-lg shadow hover:shadow-md transition-shadow duration-300">
              <span class="font-medium text-primary">Python, Data Visualization</span>
            </li>
            <li class="bg-blue-50 p-4 rounded-lg shadow hover:shadow-md transition-shadow duration-300">
              <span class="font-medium text-primary">Machine Learning Concepts</span>
            </li>
            <li class="bg-blue-50 p-4 rounded-lg shadow hover:shadow-md transition-shadow duration-300">
              <span class="font-medium text-primary">Problem Solving & Critical Thinking</span>
            </li>
          </ul>
        </section>


        <!-- Experience Section -->
        <section class="mb-8">
          <h2 class="text-2xl font-bold text-primary">Experience</h2>
          <ul class="mt-4 space-y-6">
            <li class="bg-gray-100 p-6 rounded-lg shadow">
              <div class="font-semibold text-primary">Lorem ipsum dolor sit amet</div>
              <div class="text-sm text-gray-500">Jan 2023 - Present</div>
              <p class="mt-2 text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris dapibus dui id felis tristique, at pellentesque est blandit. Nullam ac nisi mi. Fusce aliquam congue nunc, in dapibus augue pulvinar sed.
              </p>
            </li>
            <li class="bg-gray-100 p-6 rounded-lg shadow">
              <div class="font-semibold text-primary">Lorem ipsum dolor sit amet</div>
              <div class="text-sm text-gray-500">Sep 2022 - Dec 2022</div>
              <p class="mt-2 text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris dapibus dui id felis tristique, at pellentesque est blandit. Nullam ac nisi mi. Fusce aliquam congue nunc, in dapibus augue pulvinar sed.
              </p>
            </li>
          </ul>
        </section>

        <!-- Education Section -->
        <section class="mb-8">
          <h2 class="text-2xl font-bold text-primary">Education</h2>
          <ul class="mt-4 space-y-4">
            <li class="bg-gray-100 p-6 rounded-lg shadow">
              <div class="font-semibold text-primary">Associate Degree in Computer Science</div>
              <div class="text-sm text-gray-500">Brawijaya University, 2023 - Present</div>
            </li>
          </ul>
        </section>
      </div>
    </div>
  </div>
</template>
