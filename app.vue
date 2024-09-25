<template>
  <div class="min-h-screen flex flex-col items-center" style="background: linear-gradient(to bottom, black, #2c3e50);">
    <header class="bg-black bg-opacity-100 shadow w-full p-5">
      <h1 class="text-3xl font-bold text-center text-white">Ivan AryaPutra Rachmadhani Portfolio's</h1>
      <nav class="mt-4">
        <ul class="flex justify-center space-x-6">
          <li><a href="#about" class="text-white hover:text-green-500">About Me</a></li>
          <li><a href="#projects" class="text-white hover:text-green-500">Projects</a></li>
          <li><a href="#experience" class="text-white hover:text-green-500">Experience</a></li>
          <li><a href="#contact" class="text-white hover:text-green-500">Contact</a></li>
          <li><a href="/assets/portfolio.pdf" class="text-white hover:text-green-500" download>Download Portfolio</a></li>
          <li><a href="/assets/cv.pdf" class="text-white hover:text-green-500" download>Download CV</a></li>
        </ul>
      </nav>
    </header>

    <main class="flex flex-col items-center mt-10 mb-5 px-12 w-full">
      <section id="about" class="bg-black bg-opacity-75 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 w-full mb-5">
        <div class="flex flex-col items-center">
          <div class="w-48 h-48 overflow-hidden rounded-full mb-4 shadow-lg">
            <img src="/assets/img/profile.jpg" alt="Foto Profil" class="w-full h-full object-cover" />
          </div>
          <h2 class="text-2xl font-semibold mb-2 text-white">About Me</h2>
          <p class="transition duration-300 hover:text-yellow-700 text-center max-w-full text-white">
            I am a 2nd semester student in Information Technology major with interest in Social Media Specialist and Content Design. I have sufficient skills in design, copywriting, and creating press releases with mastery in several editing applications such as Canva, CapCut, Photoshop, WordPress, and Ms. Office applications. I am highly curious, able to work collaboratively and individually, and focused on completing tasks and committed to delivering the best results.
          </p>
        </div>
      </section>

      <section id="projects" class="w-full mb-5">
        <h2 class="text-2xl font-semibold mb-4 text-white text-center">Recent Project</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
          <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
            <img src="/assets/img/project1.jpeg" alt="Proyek 1" class="w-full h-64 object-cover rounded-t-lg mb-2" />
            <h3 class="font-bold text-white text-center">Brawijaya One Learning</h3>
            <p class="text-white text-center">Brone Videos Editor Crew PSIK FV UB</p>
          </div>
          <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
            <img src="/assets/img/project2.jpg" alt="Proyek 2" class="w-full h-64 object-cover rounded-t-lg mb-2" />
            <h3 class="font-bold text-white text-center">Brawijaya One Learning</h3>
            <p class="text-white text-center">Brone Videos Operator Crew PSIK FV UB</p>
          </div>
          <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
            <img src="/assets/img/project3.jpg" alt="Proyek 3" class="w-full h-64 object-cover rounded-t-lg mb-2" />
            <h3 class="font-bold text-white text-center">Podcast On The Street</h3>
            <p class="text-white text-center">Social Media Design and Reporter Team</p>
          </div>
          <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
            <img src="/assets/img/project4.jpg" alt="Proyek 3" class="w-full h-64 object-cover rounded-t-lg mb-2" />
            <h3 class="font-bold text-white text-center">GCC Tourism 2022 SMK Negeri 2 Bojonegoro</h3>
            <p class="text-white text-center">Photo & Videographer Team</p>
          </div>
        </div>
      </section>

      <section id="experience" class="w-full mb-5">
        <h2 class="text-2xl font-semibold mb-4 text-white text-center">Work Experience</h2>
        <div class="bg-black bg-opacity-75 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mt-4 mb-4">
          <h3 class="text-xl font-semibold mb-2 text-white">Social Media Specialist</h3>
          <h4 class="text-md font-semibold mb-2 text-gray-300">Pengelola Sistem Informasi dan Kehumasan Fakultas Vokasi Universitas Brawijaya</h4>
          <ol class="text-white text-left list-decimal list-inside mb-4">
            <li>Creating educational, holiday greetings, and information designs about the faculty and university.</li>
            <li>Editing podcast video highlights to be posted on the Faculty's Instagram and TikTok accounts.</li>
            <li>Manage the content planner.</li>
          </ol>
          <h3 class="text-xl font-semibold mb-2 text-white">Copywriter & Reporter</h3>
          <h4 class="text-md font-semibold mb-2 text-gray-300">Pengelola Sistem Informasi dan Kehumasan Fakultas Vokasi Universitas Brawijaya</h4>
          <ol class="text-white text-left list-decimal list-inside">
            <li>Creating educational, holiday greetings, and information designs about the faculty and university.</li>
            <li>Editing podcast video highlights to be posted on the Faculty's Instagram and TikTok accounts.</li>
            <li>Manage the content planner.</li>
          </ol>
        </div>

        <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mt-4 mb-4">
          <h3 class="text-xl font-semibold mb-2 text-white">Social Media Management</h3>
          <h4 class="text-md font-semibold mb-2 text-gray-300">CV. Bee Digital Prestasi Nusantara (PT. Harmoni Kreasi Digital)</h4>
          <ol class="text-white text-left list-decimal list-inside mb-4">
            <li>Manage 3 accounts with the main target of increasing engagement by 2 - 10% per week.</li>
            <li>Create poster, educational, and advertising designs.</li>
            <li>Create 1 copywriting content per day on WordPress about education or other informative topics.</li>
            <li>Manage content planner and analyze strategy using Google Analytics.</li>
            <li>Became part of the Social Media Management Team with "Excellent" internship results.</li>
          </ol>
        </div>
          </section>

          <section id="experience" class="w-full mb-5">
        <h2 class="text-2xl font-semibold mb-4 text-white text-center">Organizational Experience</h2>
        <div class="bg-black bg-opacity-75 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mt-4 mb-4">
          <h3 class="text-xl font-semibold mb-2 text-white">Human Resources Development</h3>
          <h4 class="text-md font-semibold mb-2 text-gray-300">Unit Kegiatan Mahasiswa Marching Band Ekalavya Suara Brawijaya</h4>
          <ol class="text-white text-left list-decimal list-inside">
            <li>Develop work programs to improve the quality of human resources.</li>
            <li>Help solve internal and external problems.</li>
          </ol>
        </div>
        </section>

        <section id="experience" class="w-full mb-5">
        <h2 class="text-2xl font-semibold mb-4 text-white text-center">Other Experience</h2>
        <div class="bg-black bg-opacity-75 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mt-4 mb-4">
            <ol class="text-white text-left list-decimal list-inside">
            <li>Videos Editor in Brawijaya One Learning PSIK Fakultas Vokasi Universitas Brawijaya.</li>
            <li>Coordinator in Open Recruitment Internship Pengelola Sistem Informasi dan Kehumasan FV UB.</li>
            <li>Event Division Staff in Open Recruitment UKM Marching Band Ekalavya Suara Brawijaya.</li>
            <li>Videographer Team  GCC Tourism 2022 Video Competition SMK Negeri 2 Bojonegoro.</li>
          </ol>
        </div>
        </section>

        <section id="skills" class="w-full mb-5">
  <h2 class="text-2xl font-semibold mb-4 text-white text-center">Software Skills's</h2>
  <div class="flex justify-center flex-wrap">
    <div class="flex flex-col items-center mx-4">
      <img src="/assets/img/soft1.png" alt="Canva" class="skill-logo mb-2" />
      <span class="text-white">Photoshop</span>
    </div>
    <div class="flex flex-col items-center mx-4">
      <img src="/assets/img/soft2.png" alt="CapCut" class="skill-logo mb-2" />
      <span class="text-white">Premiere</span>
    </div>
    <div class="flex flex-col items-center mx-4">
      <img src="/assets/img/soft3.png" alt="Photoshop" class="skill-logo mb-2" />
      <span class="text-white">Capcut</span>
    </div>
    <div class="flex flex-col items-center mx-4">
      <img src="/assets/img/soft4.png" alt="Photoshop" class="skill-logo mb-2" />
      <span class="text-white">Canva</span>
    </div>
    <div class="flex flex-col items-center mx-4">
      <img src="/assets/img/soft5.png" alt="Figma" class="skill-logo mb-2" />
      <span class="text-white">Figma</span>
    </div>
  </div>
</section>

<section id="projects" class="w-full mb-5">
        <h2 class="text-2xl font-semibold mb-4 text-white text-center">Other Skill</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
          <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
            <img src="/assets/img/skill1.jpg" alt="Proyek 1" class="w-full h-64 object-cover rounded-t-lg mb-2" />
            <h3 class="font-bold text-white text-center">Design Feed & Media Handling</h3>
          </div>
          <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
            <img src="/assets/img/skill2.jpg" alt="Proyek 2" class="w-full h-64 object-cover rounded-t-lg mb-2" />
            <h3 class="font-bold text-white text-center">Press Release</h3>
          </div>
          <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
            <img src="/assets/img/skill3.jpg" alt="Proyek 3" class="w-full h-64 object-cover rounded-t-lg mb-2" />
            <h3 class="font-bold text-white text-center">Video & Photographer</h3>
          </div>
        </div>
      </section>

      <section id="contact" class="w-full mb-5">
        <h2 class="text-2xl font-semibold mb-4 text-white text-center">Kontak</h2>
        <p class="text-white text-center">SIlahkan Hubungi Saya, Jika Tertarik Untuk Bekerja Sama:D</p>
        <p class="text-white text-center">085707960079 | ivanarya990@gmail.com</p>
      </section>
    </main>
    
    <footer class="mt-auto bg-black w-full p-2 text-center">
      <p class="text-white">&copy; 2024 Portfolio</p>
    </footer>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Portfolio Saya',
      meta: [
        { hid: 'description', name: 'description', content: 'Portfolio menggunakan Nuxt.js dan Tailwind CSS' }
      ]
    };
  }
};
</script>

<style>
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

.main-section {
  animation: fadeIn 1s ease-in;
}

.skill-logo {
  width: 64px; 
  height: 64px; 
  object-fit: contain; 
}
</style>
