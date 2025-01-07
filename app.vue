<template>
  <div class="min-h-screen flex flex-col items-center" style="background-color: #2c3e50;"> 
    <header class="bg-black bg-opacity-100 shadow w-full p-5">
      <h1 class="text-3xl font-bold text-center text-white">Ivan AryaPutra Rachmadhani Portfolio</h1>
      <nav class="mt-4">
        <ul class="flex justify-center space-x-6">
          <li><a href="#about" class="text-white hover:text-green-500">About Me</a></li>
          <li><a href="#projects" class="text-white hover:text-green-500">Projects</a></li>
          <li><a href="#experience" class="text-white hover:text-green-500">Experience</a></li>
          <li><a href="#skills" class="text-white hover:text-green-500">Skills</a></li>
          <li><a href="#contact" class="text-white hover:text-green-500">Contact</a></li>
        </ul>
      </nav>
    </header>

    <main class="flex flex-col items-center mt-2 mb-5 px-4 w-full">
      <section id="about" class="mb-0">
        <div class="flex flex-col items-center">
          <img src="/assets/img/p3.png" alt="Profil Arya Putra Ivan" class="w-full mt-1 fade-in" />          <p class="transition duration-300 hover:text-green-500 text-center max-w-full text-white mb-10 text-lg">
            "Hello, I am a 3rd semester student majoring in Information Technology, Faculty of Vocational Studies, Universitas Brawijaya with interests in Photography and Content Design with experience in the Social Media Specialist. I have fairly good skills in content design, photo & video editing, copywriting, and creating press releases with mastery of several editing applications such as Canva, CapCut, Adobe Photoshop, Adobe Premiere Pro, and word processing applications such as Microsoft Office. I am highly curious, able to work collaboratively and individually, focused on completing tasks and committed to delivering the best results."
          </p>
        </div>
      </section>

      <section class="mb-12">
    <div class="bg-white rounded-lg overflow-hidden shadow">
        <div class="aspect-w-16 aspect-h-9">
            <video src="/assets/img/bumper1.mp4" 
                   frameborder="0" 
                   allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                   allowfullscreen autoplay loop></video>
        </div>
    </div>
</section>
      
      <section id="skills" class="w-full mb-10">
  <h2 class="text-xl font-semibold mb-4 text-white text-center">Skills</h2> <!-- Ukuran judul lebih kecil -->
  <div class="flex justify-center flex-wrap">
    <div class="flex flex-col items-center mx-6 skill-item"> <!-- Mengurangi margin horizontal -->
      <img src="/assets/img/sk.svg" alt="Photoshop" class="skill-logo mb-2 w-12 h-12" /> <!-- Ukuran gambar lebih kecil -->
      <span class="text-white text-xs">Coding (HTML)</span> <!-- Ukuran teks lebih kecil -->
      <div class="popup hidden">Create web pages using HTML</div>
    </div>
    <div class="flex flex-col items-center mx-6 skill-item">
      <img src="/assets/img/sk2.svg" alt="Premiere" class="skill-logo mb-2 w-12 h-12" />
      <span class="text-white text-xs">Photo & Video Editing</span>
      <div class="popup hidden">Edit and create stunning visuals</div>
    </div>
    <div class="flex flex-col items-center mx-6 skill-item">
      <img src="/assets/img/sk3.svg" alt="Public Speaking" class="skill-logo mb-2 w-12 h-12" />
      <span class="text-white text-xs">Public Speaking</span>
      <div class="popup hidden">Deliver compelling messages in public</div>
    </div>
    <div class="flex flex-col items-center mx-6 skill-item">
      <img src="/assets/img/sk4.png" alt="Press Release" class="skill-logo mb-2 w-12 h-12" />
      <span class="text-white text-xs">Press Release</span>
      <div class="popup hidden">Create press releases to be posted on the website</div>
    </div>
    <div class="flex flex-col items-center mx-6 skill-item">
      <img src="/assets/img/sk6.png" alt="Photo & Videography" class="skill-logo mb-2 w-12 h-12" />
      <span class="text-white text-xs">Photo & Videography</span>
      <div class="popup hidden">Capture photos and videos</div>
    </div>
    <div class="flex flex-col items-center mx-6 skill-item">
      <img src="/assets/img/sk5.png" alt="Workteam" class="skill-logo mb-2 w-12 h-12" />
      <span class="text-white text-xs">Workteam</span>
      <div class="popup hidden">Collaborate effectively with teams</div>
    </div>
    <div class="flex flex-col items-center mx-6 skill-item">
      <img src="/assets/img/sk7.png" alt="Time Management" class="skill-logo mb-2 w-12 h-12" />
      <span class="text-white text-xs">Time Management</span>
      <div class="popup hidden">Manage your time efficiently</div>
    </div>
    <div class="flex flex-col items-center mx-6 skill-item">
      <img src="/assets/img/sk8.png" alt="Speak English" class="skill-logo mb-2 w-12 h-12" />
      <span class="text-white text-xs">Speak English</span>
      <div class="popup hidden">I can speak basic English and Indonesian fluently.</div>
    </div>
  </div>
</section>

      <section id="skills" class="w-full mb-10">
  <h2 class="text-3xl font-semibold mb-4 text-white text-center w-full">Software Handled</h2> <!-- Menambahkan w-full -->
  <div class="flex justify-center flex-wrap">
    <div class="flex flex-col items-center mx-16">
      <img src="/assets/img/soft1.png" alt="Photoshop" class="skill-logo mb-2" />
      <span class="text-white">Photoshop</span>
    </div>
    <div class="flex flex-col items-center mx-16">
      <img src="/assets/img/soft2.png" alt="Premiere" class="skill-logo mb-2" />
      <span class="text-white">Premiere</span>
    </div>
    <div class="flex flex-col items-center mx-16">
      <img src="/assets/img/soft3.png" alt="CapCut" class="skill-logo mb-2" />
      <span class="text-white">CapCut</span>
    </div>
    <div class="flex flex-col items-center mx-16">
      <img src="/assets/img/soft4.png" alt="Canva" class="skill-logo mb-2" />
      <span class="text-white">Canva</span>
    </div>
    <div class="flex flex-col items-center mx-12">
      <img src="/assets/img/soft5.png" alt="Figma" class="skill-logo mb-2" />
      <span class="text-white">Figma</span>
    </div>
  </div>
</section>
    
<section class="experience w-full px-4" id="experience"> <!-- Menambahkan w-full dan px-4 -->
  <h2 class="text-3xl font-semibold mb-12 text-white text-center">Education & Experience</h2>
  <div class="timeline-items max-w-6xl mx-auto"> <!-- Menambahkan max-w-6xl dan mx-auto -->
    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-date">2020 - 2023</div>
      <div class="timeline-content bg-gray-800 p-4 rounded-lg shadow-md"> <!-- Menambahkan background, padding, dan shadow -->
        <h2 class="text-xl font-semibold mb-2 text-white">Vocational High School 2 Bojonegoro</h2>
        <p>Computer & Networking Engineering.<ul>GPA: 88.36 / 100</ul></p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-date">2022, Jan - Jun</div>
      <div class="timeline-content bg-gray-800 p-4 rounded-lg shadow-md"> <!-- Menambahkan background, padding, dan shadow -->
        <h2 class="text-xl font-semibold mb-2 text-white">CV. Bee Digital Prestasi Nusantara - PT. Harmoni Kreasi Digital (INTERNSHIP) </h2>
        <h3 class="text-lg font-semibold mb-2">- Social Media Specialist.</h3>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-date">2023, Aug - Now</div>
      <div class="timeline-content bg-gray-800 p-4 rounded-lg shadow-md"> <!-- Menambahkan background, padding, dan shadow -->
        <h2 class="text-xl font-semibold mb-2 text-white">Brawijaya University</h2>
        <p>Faculty of Vocational Studies, Information Technology Major. <ul>GPA: 3.81 / 4.00</ul></p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-date">2024, March - Now </div>
      <div class="timeline-content bg-gray-800 p-4 rounded-lg shadow-md"> <!-- Menambahkan background, padding, dan shadow -->
        <h2 class="text-xl font-semibold mb-2 text-white">Pengelola Sistem Informasi dan Kehumasan Fakultas Vokasi</h2>
        <h3 class="text-lg font-semibold mb-2">- Social Media Specialist.</h3>
        <h3 class="text-lg font-semibold mb-2">- Copywriter & Reporter.</h3>
        <h3 class="text-lg font-semibold mb-2">- Photo & Videographer.</h3>
      </div>
    </div>
  </div>
</section>

<section id="projects" class="w-full mb-20">
  <h2 class="text-2xl font-semibold mb-4 mt-16 text-white text-center w-full mx-auto">Recent Projects</h2>
  <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
    <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
      <img src="/assets/img/project7.jpg" alt="Proyek 2" class="w-full h-64 object-cover rounded-t-lg mb-2" />
      <h3 class="font-bold text-white text-center">Dies Natalis 62 UB : Drama Kolosal Hikayat Raja Brawijaya</h3>
      <p class="text-white text-center">Videographer & Editor</p>
    </div>
    <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
      <img src="/assets/img/project6.jpg" alt="Proyek 4" class="w-full h-64 object-cover rounded-t-lg mb-2" />
      <h3 class="font-bold text-white text-center">Company Profile Sanggar Wayang : Gumelaring Sasangka Aji</h3>
      <p class="text-white text-center">Photo & Videographer</p>
    </div>
    <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
      <img src="/assets/img/project2.jpg" alt="Proyek 2" class="w-full h-64 object-cover rounded-t-lg mb-2" />
      <h3 class="font-bold text-white text-center">Globalizing Universitas Brawijaya : Wayang Karakter Brawijayan</h3>
      <p class="text-white text-center">Videographer & Editor</p>
    </div>
    <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
      <img src="/assets/img/project1.jpeg" alt="Proyek 1" class="w-full h-64 object-cover rounded-t-lg mb-2" />
      <h3 class="font-bold text-white text-center">Brawijaya One Learning</h3>
      <p class="text-white text-center">Brone Videos Editor Crew PSIK FV UB</p>
    </div>
    <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
      <img src="/assets/img/project3.jpg" alt="Proyek 3" class="w-full h-64 object-cover rounded-t-lg mb-2" />
      <h3 class="font-bold text-white text-center">Vokasi in Podcast : Podcast On The Street</h3>
      <p class="text-white text-center">Social Media Design and Reporter Team</p>
    </div>
    <div class="bg-black bg-opacity-85 p-5 rounded-lg shadow-md transition duration-500 transform hover:scale-105 hover:shadow-lg mb-4">
      <img src="/assets/img/project4.jpg" alt="Proyek 4" class="w-full h-64 object-cover rounded-t-lg mb-2" />
      <h3 class="font-bold text-white text-center">GCC Tourism 2022 SMK Negeri 2 Bojonegoro</h3>
      <p class="text-white text-center">Photo & Videographer Team</p>
    </div>
  </div>
</section>

<section id="portfolio" class="w-full bg-gray-800 rounded-lg py-4 mb-20">
    <h2 class="text-lg font-semibold text-white text-center mb-4">Some of My Design Results</h2> <!-- Mengatur ukuran teks medium -->
    <div class="relative overflow-hidden">
      <div class="carousel flex transition-transform duration-500" :style="{ transform: `translateX(-${currentSlide * 100}%)` }">
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design1.png" alt="Desain 1" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 1</h3> <!-- Ukuran teks -->
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p> <!-- Ukuran teks -->
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design2.png" alt="Desain 2" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 2</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design3.png" alt="Desain 3" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 3</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design4.jpg" alt="Desain 4" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 4</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design5.png" alt="Desain 4" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 5</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design6.png" alt="Desain 4" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 5</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design7.png" alt="Desain 4" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 5</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design8.png" alt="Desain 4" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 5</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design9.png" alt="Desain 4" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 5</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design10.png" alt="Desain 4" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 5</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design11.png" alt="Desain 4" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 5</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
        <div class="carousel-item flex-shrink-0 w-[280px] h-[280px]"> <!-- Mengatur ukuran menjadi 300x300 -->
          <img src="/assets/img/design12.png" alt="Desain 4" class="w-full h-full object-cover" />
          <div class="p-2">
            <h3 class="text-sm text-white">Desain 5</h3>
            <p class="text-gray-400 text-xs">Deskripsi singkat tentang desain ini.</p>
          </div>
        </div>
      </div>
      <button class="absolute top-1/2 left-2 transform -translate-y-1/2 text-white bg-gray-800 rounded-full p-2 text-xs" @click="prevSlide">❮</button>
      <button class="absolute top-1/2 right-2 transform -translate-y-1/2 text-white bg-gray-800 rounded-full p-2 text-xs" @click="nextSlide">❯</button>
    </div>
</section>

<section id="press-release" class="w-full bg-gray-900 bg-opacity-85 rounded-lg py-4 mb-10">
    <h2 class="text-xl font-semibold text-white text-center mb-6">Press Release Results</h2>
    <div class="px-4">
        <div class="press-item bg-gray-800 rounded-lg p-4 mb-4">
            <h3 class="text-lg font-bold text-white">KEMERIAHAN KRIDA MAHASISWA 2 FAKULTAS VOKASI UB DENGAN TEMA STUDENT DAY</h3>
            <p class="text-gray-400 text-base">Malang, 21 September 2024</p>
            <p class="text-gray-300 text-base">Fakultas Vokasi Universitas Brawijaya sukses menyelenggarakan acara Krida Mahasiswa pada hari ini. Dihadiri oleh lima program studi dari dua departemen, yaitu Teknologi Informasi dan Desain Grafis dari Departemen Industri Kreatif dan Digital, kemudian Administrasi Bisnis, Keuangan dan Perbankan, serta Manajemen Perhotelan dari Departemen Bisnis dan Hospitality</p>
            <a href="https://vokasi.ub.ac.id/kemeriahan-krida-mahasiswa-2-fakultas-vokasi-ub-dengan-tema-student-day/" class="text-blue-400 hover:underline text-sm">Baca Selengkapnya</a>
        </div>
        <div class="press-item bg-gray-800 rounded-lg p-4 mb-4">
            <h3 class="text-lg font-bold text-white">Kampung Lingkar Kampus “Karnaval Budaya RW. 03 Sumbersari Kota Malang”</h3>
            <p class="text-gray-400 text-base">Malang, 1 September 2024</p>
            <p class="text-gray-300 text-base">Fakultas Vokasi Universitas Brawijaya (UB) kembali menunjukkan komitmennya dalam mendukung pelestarian budaya dan pengembangan komunitas lokal dengan meliput event Karnaval Budaya RW 03 Sumbersari, Kota Malang.</p>
            <a href="https://vokasi.ub.ac.id/podcast-on-the-street-kampung-lingkar-kampus-karnaval-budaya-rw-03-sumbersari-kota-malang/" class="text-blue-400 hover:underline text-sm">Baca Selengkapnya</a>
        </div>
        <div class="press-item bg-gray-800 rounded-lg p-4 mb-4">
            <h3 class="text-lg font-bold text-white">PKKMB YUWARAJA XVI 2024 FAKULTAS VOKASI SUKSES DIGELAR</h3>
            <p class="text-gray-400 text-base">Malang, 18 Agustus 2024</p>
            <p class="text-gray-300 text-base">Kegiatan Pengenalan Kehidupan Kampus bagi Mahasiswa Baru (PKKMB) Yuwaraja Fakultas Vokasi Universitas Brawijaya memasuki hari ketiga dengan penuh semangat dan antusiasme.</p>
            <a href="https://vokasi.ub.ac.id/pkkmb-yuwaraja-xvi-2024-fakultas-vokasi-sukses-digelar/" class="text-blue-400 hover:underline text-sm">Baca Selengkapnya</a>
        </div>
        <div class="press-item bg-gray-800 rounded-lg p-4 mb-4">
            <h3 class="text-lg font-bold text-white">Inisiasi Kerjasama Fakultas Vokasi Universitas Brawijaya dengan Swinburne University of Technology, Australia</h3>
            <p class="text-gray-400 text-base">Malang, 2 Juli 2024</p>
            <p class="text-gray-300 text-base">Fakultas Vokasi Universitas Brawijaya (UB) mengadakan acara penting yaitu “Pembahasan Inisiasi Kerjasama dengan Swinburne University of Technology, Australia” dan presentasi oleh KPS D4 Desain Grafis FV UB terkait “Digitalization of Indonesia Local Culture”.</p>
            <a href="https://vokasi.ub.ac.id/inisiasi-kerjasama-fakultas-vokasi-universitas-brawijaya-dengan-swinburne-university-of-technology-australia/" class="text-blue-400 hover:underline text-sm">Baca Selengkapnya</a>
        </div>
        <div class="press-item bg-gray-800 rounded-lg p-4 mb-4">
            <h3 class="text-lg font-bold text-white">Pemanfaatan Teknologi AI Untuk Meningkatkan Kualitas Penulisan Publikasi Internasional</h3>
            <p class="text-gray-400 text-base">Malang, 4 Juli 2024</p>
            <p class="text-gray-300 text-base">Dekan Fakultas Vokasi Universitas Brawijaya Bapak Muhammad Kholid Mawardi, S.Sos., M.A.B., Ph.D mengadakan acara kuliah tamu khusus bagi Dosen Fakultas Vokasi yang telah diundang untuk mengikuti pembahasan materi tentang “pemanfaatan teknologi AI untuk meningkatkan kualitas penulisan publikasi internasional” yang dilaksanakan di Ruang Sidang Lantai 4 Gedung Vokasi Jalan Veteran No.</p>
            <a href="https://vokasi.ub.ac.id/pemanfaatan-teknologi-ai-untuk-meningkatkan-kualitas-penulisan-publikasi-internasional/" class="text-blue-400 hover:underline text-sm">Baca Selengkapnya</a>
        </div>
        <div class="press-item bg-gray-800 rounded-lg p-4 mb-4">
            <h3 class="text-lg font-bold text-white">Inbound Universitas Brawijaya dan Universitas Teknologi Petronas Malaysia</h3>
            <p class="text-gray-400 text-base">Malang, 22 April 2024</p>
            <p class="text-gray-300 text-base">Universitas Brawijaya dan Universitas Teknologi Petronas menggelar acara inbound pada hari ini, acara ini dilaksanakan di Gedung Laboratorium dan Industri Kreatif Fakultas Vokasi Universitas Brawijaya.</p>
            <a href="https://vokasi.ub.ac.id/inbound-universitas-brawijaya-dan-universitas-teknologi-petronas-malaysia/" class="text-blue-400 hover:underline text-sm">Baca Selengkapnya</a>
        </div>
    </div>
</section>

<section id="mockup-display" class="w-full bg-gray-800 bg-opacity-85 rounded-lg py-4 mb-10">
    <h2 class="text-lg font-semibold text-white text-center mb-4">Mockup Design Results</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 px-4">
        <div class="mockup-item bg-gray-700 rounded-lg overflow-hidden">
            <img src="/assets/img/mockup1.png" alt="Mockup 1" class="w-full h-[auto] aspect-[3/4] object-cover" />
            <div class="p-2">
                <h3 class="text-md font-bold text-white">Mockup T-Shirt VoksMerch</h3>
                <p class="text-gray-400 text-sm">Use Photoshop.</p>
            </div>
        </div>
        <div class="mockup-item bg-gray-700 rounded-lg overflow-hidden">
            <img src="/assets/img/jersey1.png" alt="Mockup 2" class="w-full h-[auto] aspect-[3/4] object-cover" />
            <div class="p-2">
                <h3 class="text-md font-bold text-white">Mockup Jersey Futsal /Front</h3>
                <p class="text-gray-400 text-sm">Use Photoshop.</p>
            </div>
        </div>
        <div class="mockup-item bg-gray-700 rounded-lg overflow-hidden">
            <img src="/assets/img/jersey2.png" alt="Mockup 3" class="w-full h-[auto] aspect-[3/4] object-cover" />
            <div class="p-2">
                <h3 class="text-md font-bold text-white">Mockup Jersey Futsal /Back</h3>
                <p class="text-gray-400 text-sm">Use Photoshop.</p>
            </div>
        </div>
    </div>
</section>

<section id="contact" class="w-full mb-10">
    <h2 class="text-xl font-semibold text-white text-center mb-6">Contact</h2>
    <div class="flex justify-center space-x-6">
        <a href="https://www.instagram.com/ivannaryaa/?__pwa=1#" class="flex items-center text-white hover:text-blue-400">
            <i class="fab fa-instagram fa-2x"></i>
            <span class="ml-2 text-lg">Instagram</span>
        </a>
        <a href="https://github.com/ivar-ui" class="flex items-center text-white hover:text-blue-400">
            <i class="fab fa-github fa-2x"></i>
            <span class="ml-2 text-lg">GitHub</span>
        </a>
        <a href="https://www.linkedin.com/in/ivan-aryaputra-rachmadhani-3b7222275?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" class="flex items-center text-white hover:text-blue-400">
            <i class="fab fa-linkedin fa-2x"></i>
            <span class="ml-2 text-lg">LinkedIn</span>
        </a>
    </div>
</section>

<!-- Include Font Awesome CDN for icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
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
  },
  data() {
    return {
      currentSlide: 0,
    };
  },
  computed: {
    totalSlides() {
      return this.$el.querySelectorAll('.carousel-item').length;
    },
  },
  methods: {
    nextSlide() {
      this.currentSlide = (this.currentSlide + 1) % this.totalSlides;
    },
    prevSlide() {
      this.currentSlide = (this.currentSlide - 1 + this.totalSlides) % this.totalSlides;
    },
  },
  mounted() {
    const skillItems = document.querySelectorAll('.skill-item');
    skillItems.forEach(item => {
      item.addEventListener('mouseenter', () => {
        const popup = item.querySelector('.popup');
        popup.classList.remove('hidden');
      });
      item.addEventListener('mouseleave', () => {
        const popup = item.querySelector('.popup');
        popup.classList.add('hidden');
      });
    });
  }
}

</script>

<style>

/* Tambahkan margin-top pada main untuk menghindari konten tertutup header */
main {
  margin-top: 80px; /* Sesuaikan dengan tinggi header */
}

#skills h2 {
  width: 100%; /* Memastikan teks heading mengambil lebar penuh */
  padding: 20px 0; /* Menambahkan padding atas dan bawah untuk ruang ekstra */
}

#projects h2 {
  width: 80%; /* Atur lebar heading sesuai kebutuhan */
  margin: 0 auto; /* Pusatkan heading */
  padding: 30px 0; /* Menambah padding atas dan bawah */
}

body {
  background-color: #1e1e1e; /* Latar belakang gelap */
  color: white; /* Warna teks */
  font-family: Arial, sans-serif;
}

.timeline {
  padding: 50px 15px;
}

.timeline-items {
  position: relative;
  padding: 0px 10; /* Menyesuaikan padding vertikal */
}

.timeline-item {
  position: relative;
  margin: 40px 0; /* Menambah margin antar item */
  padding: 40px; /* Menambah padding untuk tampilan yang lebih baik */
  border-radius: 10px;
  background: rgba(255, 255, 255, 0.1);
  border: 1px solid #00bcd4; /* Warna garis tepi */
  box-shadow: 0 0 20px rgba(0, 188, 212, 0.7); /* Menambah bayangan */
  width: 95%; /* Mengatur lebar item lebih besar */
  margin-left: auto;
  margin-right: auto;
}

.timeline-dot {
  height: 30px; /* Memperbesar ukuran titik */
  width: 30px; /* Memperbesar ukuran titik */
  background-color: #00bcd4; /* Warna titik */
  border-radius: 50%;
  position: absolute;
  left: -15px; /* Mengatur posisi titik */
  top: 40px; /* Mengatur posisi titik */
  box-shadow: 0 0 10px rgba(0, 188, 212, 0.7);
}

.timeline-date {
  font-weight: bold;
  color: #00bcd4; /* Warna tahun */
  margin-bottom: 20px; /* Menambah jarak bawah */
  font-size: 1.5em; /* Memperbesar ukuran font */
}

.timeline-content {
  padding-left: 40px; /* Memberikan ruang untuk titik */
  font-size: 1.2em; /* Memperbesar ukuran font konten */
  padding: 20px; /* Adjust padding for smaller screens */
}

/* Responsif */
@media (max-width: 768px) {
  header {
    padding: 10px;
  }
}

.skill-item {
    position: relative; /* Agar popup dapat diposisikan relatif */
  }

  .popup {
    position: absolute;
    bottom: 100%; /* Letakkan di atas elemen */
    left: 50%;
    transform: translateX(-50%);
    background-color: rgba(0, 0, 0, 0.8);
    color: white;
    padding: 5px 10px;
    border-radius: 4px;
    white-space: nowrap; /* Menghindari teks terputus */
    opacity: 0; /* Mulai dengan transparansi */
    transition: opacity 0.3s ease, transform 0.3s ease; /* Transisi untuk efek */
  }

  .skill-item:hover .popup {
    opacity: 1; /* Tampilkan popup saat hover */
    transform: translateX(-50%) translateY(-5px); /* Sedikit naik saat muncul */
  }

.skill-logo {
    width: 40px; /* Smaller icons for mobile */
    height: 40px;
  }

.fade-in {
  opacity: 0;
  animation: fadeIn 7s forwards; /* Menambahkan animasi */
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}
        
.social-links {
            list-style: none;  /* Menghapus bullet */
            padding: 0;        /* Menghapus padding */
            text-align: center; /* Mengatur teks menjadi center */
            margin: 0;         /* Menghapus margin */
        }

        .social-links li {
            display: inline-block; /* Menampilkan item dalam satu baris */
            margin: 0 10px;      /* Jarak antar item */
        }

        .social-links img {
            width: 40px;        /* Atur ukuran gambar sesuai kebutuhan */
            height: auto;       /* Mengatur tinggi otomatis */
        }
      
        .carousel {
  display: flex;
}
.carousel-item {
  transition: transform 0.5s ease;
}
</style>
