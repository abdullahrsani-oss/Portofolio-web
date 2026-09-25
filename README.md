1<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Abdullah Rajab Sani, S.T. | Environmental Engineering Consultant</title>
  <meta name="description" content="Portofolio profesional Abdullah Rajab Sani, S.T. — Environmental Engineering Consultant. Spesialis perencanaan sistem pengelolaan sampah (RIPS), DED IPAL, kualitas air, GIS spasial, dan dokumen AMDAL.">
  <meta name="keywords" content="Abdullah Rajab Sani, Teknik Lingkungan, Konsultan Lingkungan, RIPS, IPAL, AMDAL, GIS, Analisis Air, Padang">
  <meta name="author" content="Abdullah Rajab Sani">

  <!-- Google Font: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              50: '#edf7f4',
              100: '#d3ece3',
              500: '#0d5c46', /* Deep Forest Emerald */
              600: '#0a4937',
              700: '#08372a',
              900: '#041d16'
            },
            surface: {
              light: '#fcfcfc',
              dark: '#0c0f12',
              cardLight: '#ffffff',
              cardDark: '#14191f',
              borderLight: '#e4e7ec',
              borderDark: '#232b36'
            }
          }
        }
      }
    }
  </script>

  <!-- Inline Style Enhancements -->
  <style>
    /* Custom scrollbar */
    ::-webkit-scrollbar {
      width: 8px;
    }
    ::-webkit-scrollbar-track {
      background: transparent;
    }
    ::-webkit-scrollbar-thumb {
      background: #cbd5e1;
      border-radius: 9999px;
    }
    .dark ::-webkit-scrollbar-thumb {
      background: #334155;
    }
    .grid-bg-pattern {
      background-size: 32px 32px;
      background-image: linear-gradient(to right, rgba(0, 0, 0, 0.03) 1px, transparent 1px),
                        linear-gradient(to bottom, rgba(0, 0, 0, 0.03) 1px, transparent 1px);
    }
    .dark .grid-bg-pattern {
      background-image: linear-gradient(to right, rgba(255, 255, 255, 0.02) 1px, transparent 1px),
                        linear-gradient(to bottom, rgba(255, 255, 255, 0.02) 1px, transparent 1px);
    }
    .modal-backdrop-blur {
      backdrop-filter: blur(6px);
      -webkit-backdrop-filter: blur(6px);
    }
  </style>
</head>

<body class="bg-[#fcfcfc] dark:bg-[#0c0f12] text-zinc-900 dark:text-zinc-100 font-sans antialiased transition-colors duration-300 selection:bg-emerald-800 selection:text-white">

  <!-- Top Navigation Bar -->
  <header class="fixed top-0 left-0 right-0 z-40 bg-[#fcfcfc]/90 dark:bg-[#0c0f12]/90 backdrop-blur-md border-b border-zinc-200/80 dark:border-zinc-800/80 transition-colors">
    <div class="max-w-6xl mx-auto px-5 sm:px-8 h-20 flex items-center justify-between">
      
      <!-- Brand Logo -->
      <a href="#" class="group flex items-center gap-3">
        <span class="w-9 h-9 rounded-lg bg-emerald-900 text-emerald-100 dark:bg-emerald-600 dark:text-white flex items-center justify-center font-bold text-sm tracking-wider shadow-sm group-hover:scale-105 transition-transform">
          ARS
        </span>
        <div class="flex flex-col">
          <span class="font-semibold tracking-tight text-sm text-zinc-900 dark:text-zinc-50">Abdullah Rajab Sani</span>
          <span class="text-[11px] text-zinc-500 dark:text-zinc-400 font-medium">Environmental Engineer</span>
        </div>
      </a>

      <!-- Desktop Navigation Links -->
      <nav class="hidden md:flex items-center gap-7 text-sm font-medium text-zinc-600 dark:text-zinc-300">
        <a href="#about" class="hover:text-emerald-800 dark:hover:text-emerald-400 transition-colors">Tentang</a>
        <a href="#services" class="hover:text-emerald-800 dark:hover:text-emerald-400 transition-colors">Layanan</a>
        <a href="#portfolio" class="hover:text-emerald-800 dark:hover:text-emerald-400 transition-colors">Portofolio</a>
        <a href="#experience" class="hover:text-emerald-800 dark:hover:text-emerald-400 transition-colors">Pengalaman</a>
        <a href="#activities" class="text-zinc-600 dark:text-zinc-300 hover:text-emerald-700 dark:hover:text-emerald-400 font-medium transition-colors">Aktivitas & Sertifikasi</a>
        <a href="#contact" class="hover:text-emerald-800 dark:hover:text-emerald-400 transition-colors">Kontak</a>
      </nav>

      <!-- Utilities (Theme Toggle & CTA) -->
      <div class="flex items-center gap-3">
        <!-- Dark Mode Toggle Button -->
        <button id="themeToggleBtn" aria-label="Toggle Color Theme" class="p-2.5 rounded-lg border border-zinc-200 dark:border-zinc-800 hover:bg-zinc-100 dark:hover:bg-zinc-800 text-zinc-600 dark:text-zinc-300 transition-colors">
          <!-- Sun Icon -->
          <svg id="sunIcon" class="w-4 h-4 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h-1M4 12H3m15.364 6.364l-.707-.707M6.343 6.343l-.707-.707m12.728 0l-.707.707M6.343 17.657l-.707.707M16 12a4 4 0 11-8 0 4 4 0 018 0z" />
          </svg>
          <!-- Moon Icon -->
          <svg id="moonIcon" class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z" />
          </svg>
        </button>

        <!-- CTA Consult Button -->
        <a href="#contact" class="hidden sm:inline-flex items-center gap-2 px-4 py-2 text-xs font-semibold text-white bg-emerald-800 hover:bg-emerald-900 dark:bg-emerald-700 dark:hover:bg-emerald-600 rounded-lg shadow-sm transition-all hover:translate-y-[-1px]">
          <span>Contact US</span>
          <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"/>
          </svg>
        </a>

        <!-- Mobile Hamburger Button -->
        <button id="mobileMenuBtn" aria-label="Open Navigation Menu" class="md:hidden p-2.5 rounded-lg border border-zinc-200 dark:border-zinc-800 hover:bg-zinc-100 dark:hover:bg-zinc-800 text-zinc-600 dark:text-zinc-300">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
      </div>

    </div>

    <!-- Mobile Dropdown Menu -->
    <div id="mobileMenu" class="hidden md:hidden border-t border-zinc-200 dark:border-zinc-800 bg-[#fcfcfc] dark:bg-[#0c0f12] px-6 py-4 space-y-3 text-sm font-medium">
      <a href="#about" class="block py-2 text-zinc-600 dark:text-zinc-300 hover:text-emerald-700">Tentang</a>
      <a href="#services" class="block py-2 text-zinc-600 dark:text-zinc-300 hover:text-emerald-700">Layanan</a>
      <a href="#portfolio" class="block py-2 text-zinc-600 dark:text-zinc-300 hover:text-emerald-700">Portofolio</a>
      <a href="#experience" class="block py-2 text-zinc-600 dark:text-zinc-300 hover:text-emerald-700">Pengalaman</a>
      <a href="#contact" class="block py-2 text-zinc-600 dark:text-zinc-300 hover:text-emerald-700">Kontak</a>
      <a href="#contact" class="block text-center mt-3 py-2.5 text-xs font-semibold text-white bg-emerald-800 dark:bg-emerald-700 rounded-lg">Konsultasi Proyek</a>
    </div>
  </header>

  <main class="pt-24">
   <!-- HERO SECTION WITH PROFILE PHOTO -->
<section id="hero" class="relative pt-32 pb-20 md:pt-40 md:pb-28 overflow-hidden">
  <div class="max-w-6xl mx-auto px-6 lg:px-8">
    <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
      
      <!-- Kolom Teks (Kiri) -->
      <div class="lg:col-span-7">
        <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full text-xs font-semibold tracking-wide uppercase bg-emerald-50 dark:bg-emerald-950/60 text-emerald-800 dark:text-emerald-300 border border-emerald-200/80 dark:border-emerald-800/50 mb-6">
          <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
          Tersedia untuk Konsultasi & Studi Lingkungan
        </div>
        <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight text-zinc-900 dark:text-zinc-100 leading-tight">
          Abdullah Rajab Sani, <span class="text-emerald-700 dark:text-emerald-400">S.T.</span>
        </h1>
        <p class="mt-4 text-lg font-medium text-emerald-800/90 dark:text-emerald-300">
          Environmental Engineering Consultant & Analyst
        </p>
        <p class="mt-4 text-base sm:text-lg text-zinc-600 dark:text-zinc-400 leading-relaxed max-w-xl">
          Fokus pada perencanaan sistem persampahan terpadu (RIPS/FS/DED TPST), studi kelayakan teknis & finansial, drafter AMDAL, serta pengujian kualitas air berbasis data ilmiah.
        </p>

        <!-- CTA Buttons -->
        <div class="mt-8 flex flex-wrap items-center gap-4">
          <a href="#projects" class="px-6 py-3 rounded-xl bg-emerald-700 hover:bg-emerald-800 text-white font-medium shadow-sm transition-all">
            Lihat Portofolio Proyek
          </a>
          <a href="#contact" class="px-6 py-3 rounded-xl border border-zinc-300 dark:border-zinc-700 text-zinc-800 dark:text-zinc-200 hover:bg-zinc-100 dark:hover:bg-zinc-800/60 font-medium transition-all">
            Hubungi Saya
          </a>
        </div>
      </div>

      <!-- Kolom Foto Profil (Kanan) -->
      <div class="lg:col-span-5 flex justify-center">
        <div class="relative w-64 h-64 sm:w-72 sm:h-72 lg:w-80 lg:h-80">
          <!-- Dekorasi Bingkai Halus (Aksen Hijau Lingkungan) -->
          <div class="absolute -inset-2 rounded-3xl bg-gradient-to-tr from-emerald-600/30 to-zinc-400/20 dark:from-emerald-500/20 dark:to-zinc-700/20 blur-lg opacity-70"></div>
          
          <!-- Bingkai Utama Foto -->
          <div class="relative w-full h-full rounded-2xl overflow-hidden border-2 border-zinc-200 dark:border-zinc-800 bg-zinc-100 dark:bg-zinc-800 shadow-xl">
            <img 
              src="PAS FOTO IJAZAH.jpg" 
              alt="Foto Profil Abdullah Rajab Sani, S.T." 
              class="w-full h-full object-cover object-top hover:scale-105 transition-transform duration-500"
              onerror="this.src='https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80'"
            />
          </div>

          <!-- Badge Mengambang: Pengalaman Teknis -->
          <div class="absolute -bottom-4 -left-4 px-4 py-2.5 rounded-xl bg-white/95 dark:bg-zinc-900/95 backdrop-blur border border-zinc-200 dark:border-zinc-800 shadow-lg flex items-center gap-3">
            <div class="w-8 h-8 rounded-lg bg-emerald-100 dark:bg-emerald-950/60 text-emerald-700 dark:text-emerald-400 flex items-center justify-center font-bold text-xs">
              S.T.
            </div>
            <div>
              <p class="text-xs font-bold text-zinc-900 dark:text-zinc-100">Teknik Lingkungan</p>
              <p class="text-[10px] text-zinc-500">Universitas Andalas</p>
            </div>
          </div>

        </div>
      </div>

    </div>
  </div>
</section>

    <!-- Tentang Saya (About) Section -->
    <section id="about" class="py-24 px-5 sm:px-8 border-b border-zinc-200/80 dark:border-zinc-800/80">
      <div class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
          
          <div class="lg:col-span-4">
            <span class="text-xs font-semibold tracking-wider text-emerald-800 dark:text-emerald-400 uppercase font-mono">01 // Profil Singkat</span>
            <h2 class="text-2xl sm:text-3xl font-bold tracking-tight text-zinc-950 dark:text-zinc-50 mt-2">
              Pendekatan Berbasis Sains, Ketelitian Spasial & Rekayasa Teruji.
            </h2>
            <div class="h-1 w-12 bg-emerald-800 dark:bg-emerald-500 rounded mt-4"></div>
          </div>

          <div class="lg:col-span-8 space-y-6 text-zinc-600 dark:text-zinc-300 text-sm sm:text-base leading-relaxed">
            <p>
              Saya adalah lulusan Sarjana Teknik Lingkungan Universitas Andalas (IPK 3,44). Fondasi analitis saya dibangun melalui keahlian kimia lingkungan (D1 Analis Kimia SMK SMAK Padang) serta pengalaman memimpin operasional pengujian di Laboratorium Kualitas Air Universitas Andalas.
            </p>
            <p>
              Dalam setiap pekerjaan teknis, saya menggabungkan validitas pengujian laboratorium fisika-kimia-mikrobiologi dengan visualisasi sistem informasi geografis (ArcGIS/QGIS) dan gambar kerja presisi (AutoCAD). Pendekatan ini memastikan dokumen seperti Rencana Induk Persampahan (RIPS), studi kelayakan TPST, maupun Detail Engineering Design (DED) IPAL memiliki akurasi kalkulasi dan keterterapan lapangan yang tinggi.
            </p>
            
            <!-- Scientific Pillars -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 pt-4">
              <div class="p-4 rounded-xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900/60">
                <div class="text-emerald-800 dark:text-emerald-400 font-mono text-xs font-semibold mb-1">01. DATA DRIVEN</div>
                <h4 class="font-semibold text-zinc-900 dark:text-zinc-100 text-sm">Empiris & Baku Mutu</h4>
                <p class="text-xs text-zinc-500 dark:text-zinc-400 mt-1">Mengacu pada standar SNI, Permen LHK, dan metode standar APHA.</p>
              </div>

              <div class="p-4 rounded-xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900/60">
                <div class="text-emerald-800 dark:text-emerald-400 font-mono text-xs font-semibold mb-1">02. SPATIAL MODELING</div>
                <h4 class="font-semibold text-zinc-900 dark:text-zinc-100 text-sm">GIS & Zonasitas</h4>
                <p class="text-xs text-zinc-500 dark:text-zinc-400 mt-1">Pemetaan multi-kriteria kesesuaian lahan TPST, rute angkut, dan zonasi risiko.</p>
              </div>

              <div class="p-4 rounded-xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900/60">
                <div class="text-emerald-800 dark:text-emerald-400 font-mono text-xs font-semibold mb-1">03. SUSTAINABILITY</div>
                <h4 class="font-semibold text-zinc-900 dark:text-zinc-100 text-sm">LCA & Efisiensi Energi</h4>
                <p class="text-xs text-zinc-500 dark:text-zinc-400 mt-1">Orientasi pemulihan sumber daya dan reduksi jejak karbon menuju target ESG.</p>
              </div>
            </div>

          </div>

        </div>
      </div>
    </section>

    <!-- Keahlian & Layanan (Services) Section -->
    <section id="services" class="py-24 px-5 sm:px-8 bg-zinc-50/60 dark:bg-zinc-900/30 border-b border-zinc-200/80 dark:border-zinc-800/80">
      <div class="max-w-6xl mx-auto">
        
        <div class="flex flex-col md:flex-row md:items-end justify-between mb-16">
          <div>
            <span class="text-xs font-semibold tracking-wider text-emerald-800 dark:text-emerald-400 uppercase font-mono">02 // Layanan & Keahlian</span>
            <h2 class="text-2xl sm:text-3xl font-bold tracking-tight text-zinc-950 dark:text-zinc-50 mt-1">
              Solusi Konsultasi Rekayasa Lingkungan
            </h2>
          </div>
          <p class="text-xs sm:text-sm text-zinc-500 dark:text-zinc-400 max-w-md mt-3 md:mt-0">
            Membantu pemerintah daerah, BUMN, dan industri swasta menyusun perencanaan teknis yang patuh regulasi dan viabel secara ekonomi.
          </p>
        </div>

        <!-- 6 Grid Services Cards -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
          
          <!-- Card 1 -->
          <div class="group p-6 rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200/80 dark:border-zinc-800 hover:border-emerald-600/50 dark:hover:border-emerald-500/50 transition-all duration-200 flex flex-col justify-between hover:shadow-lg">
            <div>
              <div class="w-10 h-10 rounded-lg bg-emerald-50 dark:bg-emerald-950/60 text-emerald-800 dark:text-emerald-400 flex items-center justify-center mb-5 font-mono font-bold text-sm">
                01
              </div>
              <h3 class="text-base font-semibold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                Perencanaan Sistem Persampahan (RIPS / RISPS)
              </h3>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-2.5 leading-relaxed">
                Penyusunan dokumen Rencana Induk Pengelolaan Sampah Kota/Kabupaten: proyeksi timbulan, neraca massa 3R, optimasi rute ritasi, dan penataan kelembagaan operasional.
              </p>
            </div>
            <div class="pt-5 mt-4 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between text-xs text-zinc-500">
              <span>Output: Dokumen RIPS & Masterplan</span>
              <span class="text-emerald-700 dark:text-emerald-400 font-mono">Permen PU/LHK</span>
            </div>
          </div>

          <!-- Card 2 -->
          <div class="group p-6 rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200/80 dark:border-zinc-800 hover:border-emerald-600/50 dark:hover:border-emerald-500/50 transition-all duration-200 flex flex-col justify-between hover:shadow-lg">
            <div>
              <div class="w-10 h-10 rounded-lg bg-emerald-50 dark:bg-emerald-950/60 text-emerald-800 dark:text-emerald-400 flex items-center justify-center mb-5 font-mono font-bold text-sm">
                02
              </div>
              <h3 class="text-base font-semibold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                AMDAL, UKL-UPL & Dokumen Lingkungan
              </h3>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-2.5 leading-relaxed">
                Penyusunan formulir telaah lingkungan, identifikasi dampak penting hipotetik (DPH), rencana pengelolaan & pemantauan (RKL-RPL) serta pertek pembuangan limbah cair/emisi.
              </p>
            </div>
            <div class="pt-5 mt-4 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between text-xs text-zinc-500">
              <span>Output: Persetujuan Lingkungan</span>
              <span class="text-emerald-700 dark:text-emerald-400 font-mono">Amdalnet Ready</span>
            </div>
          </div>

          <!-- Card 3 -->
          <div class="group p-6 rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200/80 dark:border-zinc-800 hover:border-emerald-600/50 dark:hover:border-emerald-500/50 transition-all duration-200 flex flex-col justify-between hover:shadow-lg">
            <div>
              <div class="w-10 h-10 rounded-lg bg-emerald-50 dark:bg-emerald-950/60 text-emerald-800 dark:text-emerald-400 flex items-center justify-center mb-5 font-mono font-bold text-sm">
                03
              </div>
              <h3 class="text-base font-semibold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                Studi Kelayakan & Analisis CAPEX/OPEX
              </h3>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-2.5 leading-relaxed">
                Kajian kelayakan finansial & teknis pembangunan TPST/TPA/RDF: estimasi biaya modal konstruksi (CAPEX), beban operasional (OPEX), analisa NPV, IRR, dan Payback Period.
              </p>
            </div>
            <div class="pt-5 mt-4 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between text-xs text-zinc-500">
              <span>Output: Financial & Technical Feasibility</span>
              <span class="text-emerald-700 dark:text-emerald-400 font-mono">B/C Analysis</span>
            </div>
          </div>

          <!-- Card 4 -->
          <div class="group p-6 rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200/80 dark:border-zinc-800 hover:border-emerald-600/50 dark:hover:border-emerald-500/50 transition-all duration-200 flex flex-col justify-between hover:shadow-lg">
            <div>
              <div class="w-10 h-10 rounded-lg bg-emerald-50 dark:bg-emerald-950/60 text-emerald-800 dark:text-emerald-400 flex items-center justify-center mb-5 font-mono font-bold text-sm">
                04
              </div>
              <h3 class="text-base font-semibold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                Perencanaan Pengolahan Air Limbah (IPAL)
              </h3>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-2.5 leading-relaxed">
                Desain sistem biologis anaerob-aerob, koagulasi-flokulasi, dan penanganan lumpur untuk limbah domestik perkantoran/RS maupun limbah industri beban organik tinggi (agroindustri).
              </p>
            </div>
            <div class="pt-5 mt-4 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between text-xs text-zinc-500">
              <span>Output: Diagram Alir & Dimensi Unit</span>
              <span class="text-emerald-700 dark:text-emerald-400 font-mono">BOD/COD Removal</span>
            </div>
          </div>

          <!-- Card 5 -->
          <div class="group p-6 rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200/80 dark:border-zinc-800 hover:border-emerald-600/50 dark:hover:border-emerald-500/50 transition-all duration-200 flex flex-col justify-between hover:shadow-lg">
            <div>
              <div class="w-10 h-10 rounded-lg bg-emerald-50 dark:bg-emerald-950/60 text-emerald-800 dark:text-emerald-400 flex items-center justify-center mb-5 font-mono font-bold text-sm">
                05
              </div>
              <h3 class="text-base font-semibold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                Kualitas Air & Audit Sistem SPAM
              </h3>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-2.5 leading-relaxed">
                Evaluasi kinerja unit sedimentasi, filtrasi, reservoir, serta hidrolika jaringan perpipaan air minum kampus/kawasan berdasarkan baku mutu Permenkes.
              </p>
            </div>
            <div class="pt-5 mt-4 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between text-xs text-zinc-500">
              <span>Output: Audit Kinerja & Rekomendasi</span>
              <span class="text-emerald-700 dark:text-emerald-400 font-mono">Permenkes 2/2023</span>
            </div>
          </div>

          <!-- Card 6 -->
          <div class="group p-6 rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200/80 dark:border-zinc-800 hover:border-emerald-600/50 dark:hover:border-emerald-500/50 transition-all duration-200 flex flex-col justify-between hover:shadow-lg">
            <div>
              <div class="w-10 h-10 rounded-lg bg-emerald-50 dark:bg-emerald-950/60 text-emerald-800 dark:text-emerald-400 flex items-center justify-center mb-5 font-mono font-bold text-sm">
                06
              </div>
              <h3 class="text-base font-semibold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                DED Teknis & Pemetaan Spasial (CAD/GIS)
              </h3>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-2.5 leading-relaxed">
                Pembuatan gambar kerja DED (Denah, Potongan, Isometri utilitas) via AutoCAD/Sketchup, serta analisis spasial kesesuaian lahan & tematik AHP melalui ArcGIS Pro.
              </p>
            </div>
            <div class="pt-5 mt-4 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between text-xs text-zinc-500">
              <span>Output: Gambar DED 2D/3D & Peta SHP</span>
              <span class="text-emerald-700 dark:text-emerald-400 font-mono">AutoCAD & GIS</span>
            </div>
          </div>

        </div>

      </div>
    </section>

    <!-- Portofolio & Studi Kasus Section -->
    <section id="portfolio" class="py-24 px-5 sm:px-8 border-b border-zinc-200/80 dark:border-zinc-800/80">
      <div class="max-w-6xl mx-auto">
        
        <div class="flex flex-col md:flex-row md:items-end justify-between mb-10">
          <div>
            <span class="text-xs font-semibold tracking-wider text-emerald-800 dark:text-emerald-400 uppercase font-mono">03 // Portofolio Terpilih</span>
            <h2 class="text-2xl sm:text-3xl font-bold tracking-tight text-zinc-950 dark:text-zinc-50 mt-1">
              Studi Kasus & Proyek Keteknikan
            </h2>
          </div>
          
          <!-- Category Filter Buttons -->
          <div class="flex flex-wrap gap-2 mt-6 md:mt-0" id="filterContainer">
            <button data-filter="all" class="filter-btn active px-3.5 py-1.5 rounded-lg text-xs font-medium bg-emerald-800 text-white dark:bg-emerald-700">Semua</button>
            <button data-filter="waste" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs font-medium bg-zinc-100 dark:bg-zinc-800 text-zinc-600 dark:text-zinc-300 hover:bg-zinc-200 dark:hover:bg-zinc-700">Sampah & TPST</button>
            <button data-filter="water" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs font-medium bg-zinc-100 dark:bg-zinc-800 text-zinc-600 dark:text-zinc-300 hover:bg-zinc-200 dark:hover:bg-zinc-700">Air & IPAL</button>
          </div>
        </div>

        <!-- Project Cards Grid -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6" id="projectsGrid">
          
          <!-- Case 1: RIPS Payakumbuh -->
          <div class="project-card group rounded-2xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900 overflow-hidden flex flex-col justify-between hover:shadow-lg transition-all cursor-pointer" 
               data-category="waste"
               onclick="openProjectModal('rips')">
            <div class="p-6">
              <div class="flex items-center justify-between text-xs mb-3">
                <span class="text-emerald-800 dark:text-emerald-400 font-mono font-medium">Kajian Kota / Kabupaten</span>
                <span class="px-2 py-0.5 rounded bg-zinc-100 dark:bg-zinc-800 text-zinc-500 text-[11px]">2026</span>
              </div>
              <h3 class="text-lg font-bold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                Rencana Induk Sistem Pengelolaan Sampah (RIPS)
              </h3>
              <p class="text-xs text-zinc-500 dark:text-zinc-400 mt-1 font-mono">Kota Payakumbuh</p>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-3 line-clamp-3">
                Analisis timbulan harian sampah perkotaan, perancangan skema pemilahan sumber, perhitungan proyeksi volume 20 tahun, dan evaluasi kapasitas TPA regional, Rencana Program Pengelolaan Sampah.
              </p>
            </div>
            <div class="px-6 py-4 bg-zinc-50/70 dark:bg-zinc-800/40 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between">
              <span class="text-xs font-medium text-emerald-800 dark:text-emerald-400 flex items-center gap-1">
                Buka Detail Studi <span class="group-hover:translate-x-1 transition-transform">→</span>
              </span>
              <span class="text-[11px] text-zinc-400">Masterplan</span>
            </div>
          </div>

          <!-- Case 2: Studi Kelayakan TPST Lima Puluh Kota -->
          <div class="project-card group rounded-2xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900 overflow-hidden flex flex-col justify-between hover:shadow-lg transition-all cursor-pointer" 
               data-category="waste"
               onclick="openProjectModal('tpst')">
            <div class="p-6">
              <div class="flex items-center justify-between text-xs mb-3">
                <span class="text-emerald-800 dark:text-emerald-400 font-mono font-medium">Studi Kelayakan (FS)</span>
                <span class="px-2 py-0.5 rounded bg-zinc-100 dark:bg-zinc-800 text-zinc-500 text-[11px]">2024</span>
              </div>
              <h3 class="text-lg font-bold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                Studi Kelayakan TPST 3R
              </h3>
              <p class="text-xs text-zinc-500 dark:text-zinc-400 mt-1 font-mono">Kabupaten Lima Puluh Kota</p>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-3 line-clamp-3">
                Penyusunan kelayakan teknis dan pembiayaan TPST: analisis pemilihan teknologi pengolahan (komposting & RDF), site selection berbasis GIS & SNI , serta estimasi CAPEX/OPEX unit.
              </p>
            </div>
            <div class="px-6 py-4 bg-zinc-50/70 dark:bg-zinc-800/40 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between">
              <span class="text-xs font-medium text-emerald-800 dark:text-emerald-400 flex items-center gap-1">
                Buka Detail Studi <span class="group-hover:translate-x-1 transition-transform">→</span>
              </span>
              <span class="text-[11px] text-zinc-400">GIS & CAPEX</span>
            </div>
          </div>
          <!-- Case 4: Survey FS SPAM Unand -->
          <div class="project-card group rounded-2xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900 overflow-hidden flex flex-col justify-between hover:shadow-lg transition-all cursor-pointer" 
               data-category="water"
               onclick="openProjectModal('spam')">
            <div class="p-6">
              <div class="flex items-center justify-between text-xs mb-3">
                <span class="text-emerald-800 dark:text-emerald-400 font-mono font-medium">Audit Sistem Air Minum</span>
                <span class="px-2 py-0.5 rounded bg-zinc-100 dark:bg-zinc-800 text-zinc-500 text-[11px]">2024</span>
              </div>
              <h3 class="text-lg font-bold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                Audit Teknis SPAM Kawasan
              </h3>
              <p class="text-xs text-zinc-500 dark:text-zinc-400 mt-1 font-mono">Universitas Andalas</p>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-3 line-clamp-3">
                Evaluasi headloss, tekanan hidrolik jaringan distribusi, serta pengujian mutu air berkala (kekeruhan, pH, sisa klor, dan mikrobiologis E. coli) di unit pengolahan dan keran konsumen.
              </p>
            </div>
            <div class="px-6 py-4 bg-zinc-50/70 dark:bg-zinc-800/40 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between">
              <span class="text-xs font-medium text-emerald-800 dark:text-emerald-400 flex items-center gap-1">
                Buka Detail Studi <span class="group-hover:translate-x-1 transition-transform">→</span>
              </span>
              <span class="text-[11px] text-zinc-400">Hidrolika & Uji Lab</span>
            </div>
          </div>
          <!-- Case 6: Microbial Fuel Cell Research -->
          <div class="project-card group rounded-2xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900 overflow-hidden flex flex-col justify-between hover:shadow-lg transition-all cursor-pointer" 
               data-category="water"
               onclick="openProjectModal('mfc')">
            <div class="p-6">
              <div class="flex items-center justify-between text-xs mb-3">
                <span class="text-emerald-800 dark:text-emerald-400 font-mono font-medium">Riset Inovasi Energi</span>
                <span class="px-2 py-0.5 rounded bg-zinc-100 dark:bg-zinc-800 text-zinc-500 text-[11px]">Tugas Akhir S1</span>
              </div>
              <h3 class="text-lg font-bold text-zinc-900 dark:text-zinc-100 group-hover:text-emerald-800 dark:group-hover:text-emerald-400 transition-colors">
                Penyisihan Organik & Bio-Listrik via MFC
              </h3>
              <p class="text-xs text-zinc-500 dark:text-zinc-400 mt-1 font-mono">Microbial Fuel Cell Reaktor</p>
              <p class="text-xs sm:text-sm text-zinc-600 dark:text-zinc-400 mt-3 line-clamp-3">
                Kajian reduksi COD air limbah restoran secara anaerob sekaligus memanen listrik mikrobiologis. Mendapat pengakuan di kompetisi karya tulis ilmiah tingkat nasional.
              </p>
            </div>
            <div class="px-6 py-4 bg-zinc-50/70 dark:bg-zinc-800/40 border-t border-zinc-100 dark:border-zinc-800/80 flex items-center justify-between">
              <span class="text-xs font-medium text-emerald-800 dark:text-emerald-400 flex items-center gap-1">
                Buka Detail Studi <span class="group-hover:translate-x-1 transition-transform">→</span>
              </span>
              <span class="text-[11px] text-zinc-400">Waste-to-Energy</span>
            </div>
          </div>

        </div>

      </div>
    </section>

    <!-- Pengalaman & Pendidikan Section -->
    <section id="experience" class="py-24 px-5 sm:px-8 bg-zinc-50/60 dark:bg-zinc-900/30 border-b border-zinc-200/80 dark:border-zinc-800/80">
      <div class="max-w-6xl mx-auto">
        
        <div class="mb-16">
          <span class="text-xs font-semibold tracking-wider text-emerald-800 dark:text-emerald-400 uppercase font-mono">04 // Jejak Langkah</span>
          <h2 class="text-2xl sm:text-3xl font-bold tracking-tight text-zinc-950 dark:text-zinc-50 mt-1">
            Pengalaman Profesional & Pendidikan
          </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
          
          <!-- Column 1: Pengalaman Kerja & Asistensi -->
          <div>
            <h3 class="text-base font-bold text-zinc-900 dark:text-zinc-100 mb-6 flex items-center gap-2">
              <span class="w-2.5 h-2.5 rounded-full bg-emerald-800 dark:bg-emerald-400"></span>
              Pengalaman Profesional & Laboratorium
            </h3>

            <div class="space-y-8 border-l border-zinc-200 dark:border-zinc-800 pl-5 ml-1">
              
              <!-- Item 1 -->
              <div class="relative">
                <span class="absolute -left-[26px] top-1.5 w-3 h-3 rounded-full border-2 border-white dark:border-zinc-900 bg-emerald-800 dark:bg-emerald-400"></span>
                <span class="text-xs font-mono text-zinc-400 dark:text-zinc-500">Jan 2024 — Jul 2025</span>
                <h4 class="text-sm font-semibold text-zinc-900 dark:text-zinc-100 mt-0.5">Koordinator Asisten Laboratorium Air</h4>
                <div class="text-xs text-emerald-800 dark:text-emerald-400 font-medium">Universitas Andalas</div>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-2 leading-relaxed">
                  Memimpin uji analisis air limbah, air permukaan, dan air minum sesuai Standard Methods (APHA). Mengawasi SOP K3 keselamatan bahan kimia dan validasi data pengujian mahasiswa & riset.
                </p>
              </div>

              <!-- Item 2 -->
              <div class="relative">
                <span class="absolute -left-[26px] top-1.5 w-3 h-3 rounded-full border-2 border-white dark:border-zinc-900 bg-zinc-400 dark:bg-zinc-600"></span>
                <span class="text-xs font-mono text-zinc-400 dark:text-zinc-500">Jul 2024 — Jul 2025</span>
                <h4 class="text-sm font-semibold text-zinc-900 dark:text-zinc-100 mt-0.5">Asisten Pengajar Laboratorium GIS</h4>
                <div class="text-xs text-emerald-800 dark:text-emerald-400 font-medium">Teknik Lingkungan Universitas Andalas</div>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-2 leading-relaxed">
                  Instruktur praktikum ArcGIS dan QGIS: analisis spasial multi-kriteria (AHP), layout peta tematik, pemodelan kemiringan lereng (DEM), dan batas hidrologi DAS.
                </p>
              </div>

              <!-- Item 3 -->
              <div class="relative">
                <span class="absolute -left-[26px] top-1.5 w-3 h-3 rounded-full border-2 border-white dark:border-zinc-900 bg-zinc-400 dark:bg-zinc-600"></span>
                <span class="text-xs font-mono text-zinc-400 dark:text-zinc-500">Jan 2023 — Jul 2025</span>
                <h4 class="text-sm font-semibold text-zinc-900 dark:text-zinc-100 mt-0.5">Asisten Pengajar Menggambar Rekayasa</h4>
                <div class="text-xs text-emerald-800 dark:text-emerald-400 font-medium">AutoCAD & Sketchup Engineering</div>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-2 leading-relaxed">
                  Membimbing desain teknik 2D/3D untuk sistem perpipaan sanitasi, sanitary landfill, serta unit sedimentasi/flokulasi sesuai kaidah standar rekayasa sipil/lingkungan.
                </p>
              </div>

              <!-- Item 4 -->
              <div class="relative">
                <span class="absolute -left-[26px] top-1.5 w-3 h-3 rounded-full border-2 border-white dark:border-zinc-900 bg-zinc-400 dark:bg-zinc-600"></span>
                <span class="text-xs font-mono text-zinc-400 dark:text-zinc-500">Mei 2024 — Jun 2024</span>
                <h4 class="text-sm font-semibold text-zinc-900 dark:text-zinc-100 mt-0.5">HSE & Environmental Monitoring Intern</h4>
                <div class="text-xs text-emerald-800 dark:text-emerald-400 font-medium">PT. Harafiel Tri Jaya (Proyek RS Padang Eye Center)</div>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-2 leading-relaxed">
                  Inspeksi K3 lapangan harian, mitigasi limbah konstruksi, pemantauan emisi debu, serta kepatuhan standar sanitasi lingkungan kerja proyek.
                </p>
              </div>

            </div>
          </div>

          <!-- Column 2: Pendidikan & Prestasi -->
          <div>
            <h3 class="text-base font-bold text-zinc-900 dark:text-zinc-100 mb-6 flex items-center gap-2">
              <span class="w-2.5 h-2.5 rounded-full bg-emerald-800 dark:bg-emerald-400"></span>
              Pendidikan Formal & Keilmuan
            </h3>
              <!-- Edu  -->
              <div class="relative">
                <span class="absolute -left-[26px] top-1.5 w-3 h-3 rounded-full border-2 border-white dark:border-zinc-900 bg-zinc-400 dark:bg-zinc-600"></span>
                <span class="text-xs font-mono text-zinc-400 dark:text-zinc-500">2021 — 2025</span>
                <h4 class="text-sm font-semibold text-zinc-900 dark:text-zinc-100 mt-0.5">Sarjana (S1) Teknik Lingkungan</h4>
                <div class="text-xs text-emerald-800 dark:text-emerald-400 font-medium">Universitas Andalas (IPK 3,44 / 4,00)</div>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-2 leading-relaxed">
                  Tugas Akhir: <em>Penyisihan Kandungan Organik Air Limbah Rumah Makan dan Produksi Listrik Secara Anaerob Menggunakan Microbial Fuel Cell (MFC).</em>
                </p>
                <!-- Honors -->
                <div class="mt-3 flex flex-wrap gap-1.5 text-[11px]">
                  <span class="px-2 py-0.5 rounded bg-zinc-100 dark:bg-zinc-800 text-zinc-700 dark:text-zinc-300">Juara 1 LKTI CHEERS Univ Riau</span>
                  <span class="px-2 py-0.5 rounded bg-zinc-100 dark:bg-zinc-800 text-zinc-700 dark:text-zinc-300">Harapan 1 Desain Alat Nasional</span>
                </div>
              </div>

              <!-- Edu 3 -->
              <div class="relative">
                <span class="absolute -left-[26px] top-1.5 w-3 h-3 rounded-full border-2 border-white dark:border-zinc-900 bg-zinc-400 dark:bg-zinc-600"></span>
                <span class="text-xs font-mono text-zinc-400 dark:text-zinc-500">2017 — 2021</span>
                <h4 class="text-sm font-semibold text-zinc-900 dark:text-zinc-100 mt-0.5">D1 Analis Kimia</h4>
                <div class="text-xs text-emerald-800 dark:text-emerald-400 font-medium">SMK SMAK Padang (Nilai: 90,04 / 100)</div>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-2 leading-relaxed">
                  Spesialisasi instrumentasi kimia analitik (Spektrofotometri UV-Vis, AAS, Titrimetri, Gravimetri) yang menjadi pondasi ketepatan analisis parameter limbah cair & tanah.
                </p>
              </div>

            </div>
          </div>

        </div>

      </div>
    </section>
    <!-- ACTIVITIES, TRAININGS & CERTIFICATIONS SECTION -->
<section id="activities" class="py-20 border-t border-zinc-200 dark:border-zinc-800 bg-zinc-50/50 dark:bg-zinc-900/30">
  <div class="max-w-6xl mx-auto px-6 lg:px-8">
    
    <!-- Section Header -->
    <div class="max-w-2xl mb-14">
      <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full text-xs font-semibold tracking-wide uppercase bg-emerald-100 dark:bg-emerald-950/60 text-emerald-800 dark:text-emerald-300 border border-emerald-200 dark:border-emerald-800/50 mb-3">
        Kredensial & Pengembangan Diri
      </div>
      <h2 class="text-3xl font-bold tracking-tight text-zinc-900 dark:text-zinc-100 sm:text-4xl">
        Pelatihan, Sertifikasi & Dokumentasi
      </h2>
      <p class="mt-4 text-base text-zinc-600 dark:text-zinc-400 leading-relaxed">
        Rekam jejak kualifikasi teknis laboratorium lingkungan, penguasaan pemetaan spasial (GIS), rekayasa desain, sertifikasi kompetensi kejuruan, serta dokumentasi kegiatan riset terapan.
      </p>
    </div>

    <!-- 2 Columns Grid: Certifications & Trainings -->
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 mb-16">
      
      <!-- Box 1: Sertifikasi & Kompetensi -->
      <div class="p-8 rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200 dark:border-zinc-800 shadow-sm flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-xl bg-emerald-50 dark:bg-emerald-950/50 text-emerald-700 dark:text-emerald-400 flex items-center justify-center mb-6 border border-emerald-100 dark:border-emerald-800/40">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/>
            </svg>
          </div>
          <h3 class="text-xl font-bold text-zinc-900 dark:text-zinc-100 mb-2">Sertifikasi & Kualifikasi Resmi</h3>
          <p class="text-sm text-zinc-600 dark:text-zinc-400 mb-6">Lisensi keahlian dan kualifikasi kejuruan analitis kimia dan keselamatan kerja.</p>

          <ul class="space-y-4">
            <li class="flex items-start gap-3">
              <span class="mt-1 flex-shrink-0 w-2 h-2 rounded-full bg-emerald-600"></span>
              <div>
                <span class="block font-semibold text-zinc-800 dark:text-zinc-200">Kualifikasi Analis Kimia Terakreditasi</span>
                <span class="text-xs text-zinc-500">SMK SMAK Padang (Skor Akhir: 90,04 / 100)</span>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-0.5">Kompetensi instrumentasi spektrofotometri UV-Vis, AAS, ICP, GC-MS, dan validasi mutu laboratorium.</p>
              </div>
            </li>
            <li class="flex items-start gap-3">
              <span class="mt-1 flex-shrink-0 w-2 h-2 rounded-full bg-emerald-600"></span>
              <div>
                <span class="block font-semibold text-zinc-800 dark:text-zinc-200">Sertifikasi Praktik K3 / HSE Konstruksi</span>
                <span class="text-xs text-zinc-500">PT Harafiel Tri Jaya (Proyek RS Padang Eye Center)</span>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-0.5">Kualifikasi inspeksi bahaya, toolbox meeting harian, simulasi emergency drill, dan audit APD.</p>
              </div>
            </li>
            <li class="flex items-start gap-3">
              <span class="mt-1 flex-shrink-0 w-2 h-2 rounded-full bg-emerald-600"></span>
              <div>
                <span class="block font-semibold text-zinc-800 dark:text-zinc-200">Kualifikasi Pengujian Baku Mutu Air & Sampling</span>
                <span class="text-xs text-zinc-500">Laboratorium Air & Laboratorium Pengujian Lingkungan</span>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-0.5">Pengujian baku mutu air limbah, air minum, serta udara ambien sesuai metode standar SNI/APHA.</p>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <!-- Box 2: Pelatihan & Workshop Teknis -->
      <div class="p-8 rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200 dark:border-zinc-800 shadow-sm flex flex-col justify-between">
        <div>
          <div class="w-12 h-12 rounded-xl bg-emerald-50 dark:bg-emerald-950/50 text-emerald-700 dark:text-emerald-400 flex items-center justify-center mb-6 border border-emerald-100 dark:border-emerald-800/40">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"/>
            </svg>
          </div>
          <h3 class="text-xl font-bold text-zinc-900 dark:text-zinc-100 mb-2">Pelatihan & Bimbingan Teknis</h3>
          <p class="text-sm text-zinc-600 dark:text-zinc-400 mb-6">Program bimbingan teknis tingkat lanjut dalam analisis spasial dan pemodelan rekayasa.</p>

          <ul class="space-y-4">
            <li class="flex items-start gap-3">
              <span class="mt-1 flex-shrink-0 w-2 h-2 rounded-full bg-emerald-600"></span>
              <div>
                <span class="block font-semibold text-zinc-800 dark:text-zinc-200">Spatial Analyst & Multi-Criteria Evaluation (AHP-GIS)</span>
                <span class="text-xs text-zinc-500">ArcGIS Pro & QGIS</span>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-0.5">Analisis kesesuaian lahan TPST/TPA, overlay berbobot (weighted overlay), dan pemetaan zonasi AMDAL.</p>
              </div>
            </li>
            <li class="flex items-start gap-3">
              <span class="mt-1 flex-shrink-0 w-2 h-2 rounded-full bg-emerald-600"></span>
              <div>
                <span class="block font-semibold text-zinc-800 dark:text-zinc-200">CAD Drafting & Pemodelan Rekayasa Lingkungan</span>
                <span class="text-xs text-zinc-500">AutoCAD & SketchUp (2D/3D Drafting)</span>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-0.5">Penyusunan gambar DED IPAL komunal, jaringan pipa SPAM, dan detail arsitektur TPST.</p>
              </div>
            </li>
            <li class="flex items-start gap-3">
              <span class="mt-1 flex-shrink-0 w-2 h-2 rounded-full bg-emerald-600"></span>
              <div>
                <span class="block font-semibold text-zinc-800 dark:text-zinc-200">Inovasi Pengolahan Limbah & Eco-Enzyme</span>
                <span class="text-xs text-zinc-500">Litbang HMTL FT-UNAND</span>
                <p class="text-xs text-zinc-600 dark:text-zinc-400 mt-0.5">Pelatihan formulasi fermentasi organik untuk reduksi beban pencemar pada badan air permukaan.</p>
              </div>
            </li>
          </ul>
        </div>
      </div>

    </div>

    <!-- Gallery / Dokumentasi Kegiatan Lapangan & Laboratorium -->
    <div class="mt-12">
      <div class="flex items-center justify-between mb-8">
        <div>
          <h3 class="text-2xl font-bold text-zinc-900 dark:text-zinc-100">Dokumentasi Aktivitas & Riset</h3>
          <p class="text-sm text-zinc-500 dark:text-zinc-400 mt-1">Dokumentasi kegiatan analisis laboratorium, praktikum GIS, hingga inspeksi lapangan proyek.</p>
        </div>
      </div>

      <!-- Photo Cards Grid -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        
        <!-- Activity Card 1 -->
        <div class="group overflow-hidden rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200 dark:border-zinc-800 transition-all hover:border-emerald-600/40 hover:shadow-md">
          <div class="aspect-video w-full overflow-hidden bg-zinc-100 dark:bg-zinc-800 relative">
            <img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?auto=format&fit=crop&w=700&q=80" 
                 alt="Laboratorium Kualitas Air" 
                 class="h-full w-full object-cover group-hover:scale-105 transition-transform duration-500">
            <span class="absolute top-3 left-3 px-2.5 py-0.5 text-[11px] font-semibold tracking-wide bg-zinc-900/80 backdrop-blur text-white rounded-md">
              Laboratorium Air
            </span>
          </div>
          <div class="p-5">
            <h4 class="font-bold text-zinc-900 dark:text-zinc-100 text-base mb-1">Pengujian Parameter Fisika-Kimia Air</h4>
            <p class="text-xs text-zinc-600 dark:text-zinc-400 leading-relaxed">
              Pengujian parameter COD, BOD, TSS, serta logam berat sampel air limbah dan air minum di Lab Kualitas Air Unand.
            </p>
          </div>
        </div>

        <!-- Activity Card 2 -->
        <div class="group overflow-hidden rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200 dark:border-zinc-800 transition-all hover:border-emerald-600/40 hover:shadow-md">
          <div class="aspect-video w-full overflow-hidden bg-zinc-100 dark:bg-zinc-800 relative">
            <img src="https://images.unsplash.com/photo-1524661135-423995f22d0b?auto=format&fit=crop&w=700&q=80" 
                 alt="Pemetaan GIS & Spasial" 
                 class="h-full w-full object-cover group-hover:scale-105 transition-transform duration-500">
            <span class="absolute top-3 left-3 px-2.5 py-0.5 text-[11px] font-semibold tracking-wide bg-zinc-900/80 backdrop-blur text-white rounded-md">
              Spasial & GIS
            </span>
          </div>
          <div class="p-5">
            <h4 class="font-bold text-zinc-900 dark:text-zinc-100 text-base mb-1">Praktikum & Analisis Pemetaan GIS</h4>
            <p class="text-xs text-zinc-600 dark:text-zinc-400 leading-relaxed">
              Instruksi teknis pemetaan topografi, batas administrasi AMDAL, dan pemodelan kesesuaian tapak TPST.
            </p>
          </div>
        </div>

        <!-- Activity Card 3 -->
        <div class="group overflow-hidden rounded-2xl bg-white dark:bg-zinc-900 border border-zinc-200 dark:border-zinc-800 transition-all hover:border-emerald-600/40 hover:shadow-md">
          <div class="aspect-video w-full overflow-hidden bg-zinc-100 dark:bg-zinc-800 relative">
            <img src="https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=700&q=80" 
                 alt="Inspeksi HSE Konstruksi" 
                 class="h-full w-full object-cover group-hover:scale-105 transition-transform duration-500">
            <span class="absolute top-3 left-3 px-2.5 py-0.5 text-[11px] font-semibold tracking-wide bg-zinc-900/80 backdrop-blur text-white rounded-md">
              HSE & Lapangan
            </span>
          </div>
          <div class="p-5">
            <h4 class="font-bold text-zinc-900 dark:text-zinc-100 text-base mb-1">Inspeksi HSE & Sampling Lapangan</h4>
            <p class="text-xs text-zinc-600 dark:text-zinc-400 leading-relaxed">
              Pengawasan standar keselamatan kerja konstruksi harian dan pengambilan sampel air, udara, dan tanah di lapangan.
            </p>
          </div>
        </div>

      </div>
    </div>

  </div>
</section>

    <!-- Kontak & Konsultasi Section -->
    <section id="contact" class="py-24 px-5 sm:px-8">
      <div class="max-w-6xl mx-auto">
        
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
          
          <!-- Contact Info Left Column -->
          <div class="lg:col-span-5 space-y-6">
            <div>
              <span class="text-xs font-semibold tracking-wider text-emerald-800 dark:text-emerald-400 uppercase font-mono">05 // Kolaborasi & Kontak</span>
              <h2 class="text-2xl sm:text-3xl font-bold tracking-tight text-zinc-950 dark:text-zinc-50 mt-1">
                Diskusikan Kebutuhan Proyek Lingkungan Anda.
              </h2>
            </div>

            <p class="text-sm text-zinc-600 dark:text-zinc-400 leading-relaxed">
              Terbuka untuk penugasan konsultansi dokumen lingkungan (AMDAL/UKL-UPL), kajian persampahan daerah (RIPS/FS TPST), perancangan DED IPAL, maupun kolaborasi penelitian terkait keberlanjutan dan ESG.
            </p>

            <div class="space-y-4 pt-2">
              
              <!-- Email Card -->
              <div class="p-4 rounded-xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900 flex items-center justify-between">
                <div class="flex items-center gap-3">
                  <div class="w-9 h-9 rounded-lg bg-emerald-50 dark:bg-emerald-950 text-emerald-800 dark:text-emerald-400 flex items-center justify-center">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
                  </div>
                  <div>
                    <div class="text-[11px] text-zinc-400 font-mono">EMAIL</div>
                    <a href="mailto:abdullahrsani@email.com" class="text-xs sm:text-sm font-semibold text-zinc-900 dark:text-zinc-100 hover:text-emerald-800">
                      abdullahrsani@email.com
                    </a>
                  </div>
                </div>
                <button onclick="copyToClipboard('abdullahrsani@email.com', 'Email berhasil disalin!')" class="text-xs px-2.5 py-1 rounded bg-zinc-100 dark:bg-zinc-800 hover:bg-zinc-200 text-zinc-600 dark:text-zinc-300">
                  Salin
                </button>
              </div>

              <!-- Phone / WhatsApp Card -->
              <div class="p-4 rounded-xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900 flex items-center justify-between">
                <div class="flex items-center gap-3">
                  <div class="w-9 h-9 rounded-lg bg-emerald-50 dark:bg-emerald-950 text-emerald-800 dark:text-emerald-400 flex items-center justify-center">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                  </div>
                  <div>
                    <div class="text-[11px] text-zinc-400 font-mono">WHATSAPP / TELEPON</div>
                    <div class="text-xs sm:text-sm font-semibold text-zinc-900 dark:text-zinc-100">
                      +62 813 7423 0354
                    </div>
                  </div>
                </div>
                <a href="https://wa.me/6281374230354" target="_blank" rel="noopener noreferrer" class="text-xs px-3 py-1 rounded bg-emerald-800 text-white hover:bg-emerald-900 font-medium">
                  Chat
                </a>
              </div>

              <!-- Location Card -->
              <div class="p-4 rounded-xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900 flex items-center gap-3">
                <div class="w-9 h-9 rounded-lg bg-emerald-50 dark:bg-emerald-950 text-emerald-800 dark:text-emerald-400 flex items-center justify-center">
                  <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                </div>
                <div>
                  <div class="text-[11px] text-zinc-400 font-mono">LOKASI BASIS</div>
                  <div class="text-xs sm:text-sm font-semibold text-zinc-900 dark:text-zinc-100">
                    Padang, Sumatera Barat, Indonesia (Siap survei luar kota)
                  </div>
                </div>
              </div>

            </div>
          </div>
          <!-- Contact Form Right Column -->
          <div class="lg:col-span-7">
            <div class="rounded-2xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900 p-6 sm:p-8 shadow-sm">
              <h3 class="text-lg font-bold text-zinc-900 dark:text-zinc-100 mb-2">Formulir Penjajakan / Konsultasi</h3>
              <p class="text-xs text-zinc-500 mb-6">Silakan tinggalkan detail kebutuhan Anda, tanggapan teknis akan dibalas dalam kurun waktu 1x24 jam.</p>

              <form id="contactForm" onsubmit="handleFormSubmit(event)" class="space-y-4">
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                  <div>
                    <label for="name" class="block text-xs font-medium text-zinc-700 dark:text-zinc-300 mb-1">Nama Lengkap / Instansi</label>
                    <input type="text" id="name" required placeholder="Contoh: PT Sumber Tirta / Dinas LH" class="w-full px-3.5 py-2.5 rounded-lg border border-zinc-300 dark:border-zinc-700 bg-white dark:bg-zinc-800 text-xs sm:text-sm text-zinc-900 dark:text-zinc-100 focus:outline-none focus:border-emerald-700">
                  </div>
                  <div>
                    <label for="email" class="block text-xs font-medium text-zinc-700 dark:text-zinc-300 mb-1">Alamat Email</label>
                    <input type="email" id="email" required placeholder="nama@organisasi.com" class="w-full px-3.5 py-2.5 rounded-lg border border-zinc-300 dark:border-zinc-700 bg-white dark:bg-zinc-800 text-xs sm:text-sm text-zinc-900 dark:text-zinc-100 focus:outline-none focus:border-emerald-700">
                  </div>
                </div>

                <div>
                  <label for="serviceCategory" class="block text-xs font-medium text-zinc-700 dark:text-zinc-300 mb-1">Kategori Layanan / Minat</label>
                  <select id="serviceCategory" class="w-full px-3.5 py-2.5 rounded-lg border border-zinc-300 dark:border-zinc-700 bg-white dark:bg-zinc-800 text-xs sm:text-sm text-zinc-900 dark:text-zinc-100 focus:outline-none focus:border-emerald-700">
                    <option value="RIPS & Sampah">Perencanaan Sistem Pengelolaan Sampah (RIPS / TPST)</option>
                    <option value="DED IPAL & SPAM">Desain Teknis DED IPAL / SPAM</option>
                    <option value="AMDAL & Dokling">Penyusunan AMDAL / UKL-UPL / Pertek</option>
                    <option value="GIS & Pemetaan">Analisis Spasial & Pemetaan ArcGIS</option>
                    <option value="Riset & Konsultasi ESG">Kajian ESG, Riset Laboratorium & Lainnya</option>
                  </select>
                </div>

                <div>
                  <label for="message" class="block text-xs font-medium text-zinc-700 dark:text-zinc-300 mb-1">Uraian Ringkas Kebutuhan</label>
                  <textarea id="message" rows="4" required placeholder="Jelaskan ruang lingkup proyek, target lokasi, atau jadwal yang direncanakan..." class="w-full px-3.5 py-2.5 rounded-lg border border-zinc-300 dark:border-zinc-700 bg-white dark:bg-zinc-800 text-xs sm:text-sm text-zinc-900 dark:text-zinc-100 focus:outline-none focus:border-emerald-700"></textarea>
                </div>

                <div class="flex items-center justify-between pt-2">
                  <span class="text-[11px] text-zinc-400">Data Anda dirahasiakan dan langsung terhubung ke email konsultan.</span>
                  <button type="submit" class="px-6 py-2.5 rounded-lg bg-emerald-800 hover:bg-emerald-900 dark:bg-emerald-700 dark:hover:bg-emerald-600 text-white text-xs sm:text-sm font-semibold transition-all">
                    Kirim Pesan
                  </button>
                </div>
              </form>
            </div>
          </div>

        </div>

      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="border-t border-zinc-200 dark:border-zinc-800 py-12 px-5 sm:px-8 bg-white dark:bg-[#0c0f12]">
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
      
      <div class="flex items-center gap-3">
        <span class="w-7 h-7 rounded bg-emerald-900 text-emerald-100 text-xs font-bold flex items-center justify-center font-mono">
          AR
        </span>
        <div class="text-xs text-zinc-500">
          © 2026 Abdullah Rajab Sani, S.T. All rights reserved.
        </div>
      </div>

      <div class="flex items-center gap-6 text-xs text-zinc-500">
        <a href="#about" class="hover:text-emerald-800">Tentang</a>
        <a href="#portfolio" class="hover:text-emerald-800">Studi Kasus</a>
        <a href="https://www.linkedin.com/in/abdullah-rajab-sani-076699248/" target="_blank" rel="noopener noreferrer" class="hover:text-emerald-800">LinkedIn</a>
        <a href="mailto:abdullahrsani@email.com" class="hover:text-emerald-800">abdullahrsani@email.com</a>
      </div>

    </div>
  </footer>

  <!-- Project Detail Modal -->
  <div id="projectModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-4 sm:p-6 modal-backdrop-blur bg-black/60 transition-opacity">
    <div class="relative w-full max-w-2xl bg-white dark:bg-zinc-900 rounded-2xl border border-zinc-200 dark:border-zinc-800 shadow-2xl overflow-hidden max-h-[90vh] flex flex-col">
      
      <!-- Modal Header -->
      <div class="px-6 py-4 border-b border-zinc-200 dark:border-zinc-800 flex items-center justify-between">
        <div>
          <span id="modalCategory" class="text-[11px] font-mono font-medium text-emerald-800 dark:text-emerald-400 uppercase tracking-wider">Kategori</span>
          <h3 id="modalTitle" class="text-base sm:text-lg font-bold text-zinc-950 dark:text-zinc-50">Judul Proyek</h3>
        </div>
        <button onclick="closeProjectModal()" class="p-2 rounded-lg text-zinc-400 hover:text-zinc-600 dark:hover:text-zinc-200 hover:bg-zinc-100 dark:hover:bg-zinc-800 transition-colors">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>

      <!-- Modal Body (Scrollable) -->
      <div class="p-6 space-y-6 overflow-y-auto text-xs sm:text-sm text-zinc-600 dark:text-zinc-300 leading-relaxed">
        
        <div>
          <h4 class="font-bold text-zinc-900 dark:text-zinc-100 text-xs font-mono uppercase text-emerald-800 dark:text-emerald-400 mb-1">
            01. Latar Belakang & Tujuan
          </h4>
          <p id="modalObjective">Deskripsi tujuan teknis...</p>
        </div>

        <div>
          <h4 class="font-bold text-zinc-900 dark:text-zinc-100 text-xs font-mono uppercase text-emerald-800 dark:text-emerald-400 mb-1">
            02. Metodologi & Instrumen Teknis
          </h4>
          <ul id="modalMethodology" class="list-disc pl-5 space-y-1.5 mt-2">
            <!-- Dynamically injected -->
          </ul>
        </div>

        <div class="p-4 rounded-xl bg-zinc-50 dark:bg-zinc-800/60 border border-zinc-200/70 dark:border-zinc-700/60">
          <h4 class="font-bold text-zinc-900 dark:text-zinc-100 text-xs font-mono uppercase text-emerald-800 dark:text-emerald-400 mb-1">
            03. Hasil & Rekomendasi Rekayasa
          </h4>
          <p id="modalOutcome">Keluaran dan rekomendasi terapan...</p>
        </div>

      </div>

      <!-- Modal Footer -->
      <div class="px-6 py-3.5 border-t border-zinc-200 dark:border-zinc-800 bg-zinc-50/50 dark:bg-zinc-800/30 flex justify-end">
        <button onclick="closeProjectModal()" class="px-4 py-2 text-xs font-medium rounded-lg bg-zinc-200 dark:bg-zinc-700 text-zinc-800 dark:text-zinc-200 hover:bg-zinc-300 dark:hover:bg-zinc-600 transition-colors">
          Tutup
        </button>
      </div>

    </div>
  </div>

  <!-- Notification Toast Container -->
  <div id="toastNotification" class="fixed bottom-6 right-6 z-50 hidden max-w-sm rounded-xl border border-emerald-300 dark:border-emerald-700 bg-white dark:bg-zinc-900 p-4 shadow-xl text-xs flex items-center gap-3">
    <div class="w-8 h-8 rounded-full bg-emerald-100 dark:bg-emerald-950 text-emerald-800 dark:text-emerald-400 flex items-center justify-center shrink-0">
      <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
    </div>
    <div>
      <div class="font-bold text-zinc-900 dark:text-zinc-100" id="toastTitle">Berhasil</div>
      <div class="text-zinc-500 dark:text-zinc-400 mt-0.5" id="toastMessage">Tindakan telah diproses.</div>
    </div>
  </div>

  <script>
    /* Theme Toggle Logic */
    const themeToggleBtn = document.getElementById('themeToggleBtn');
    const sunIcon = document.getElementById('sunIcon');
    const moonIcon = document.getElementById('moonIcon');

    function applyTheme(isDark) {
      if (isDark) {
        document.documentElement.classList.add('dark');
        sunIcon.classList.remove('hidden');
        moonIcon.classList.add('hidden');
        localStorage.setItem('theme', 'dark');
      } else {
        document.documentElement.classList.remove('dark');
        sunIcon.classList.add('hidden');
        moonIcon.classList.remove('hidden');
        localStorage.setItem('theme', 'light');
      }
    }

    // Check system preference or stored setting
    const savedTheme = localStorage.getItem('theme');
    const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
    if (savedTheme === 'dark' || (!savedTheme && prefersDark)) {
      applyTheme(true);
    } else {
      applyTheme(false);
    }

    themeToggleBtn.addEventListener('click', () => {
      const isCurrentlyDark = document.documentElement.classList.contains('dark');
      applyTheme(!isCurrentlyDark);
    });

    /* Mobile Hamburger Menu Logic */
    const mobileMenuBtn = document.getElementById('mobileMenuBtn');
    const mobileMenu = document.getElementById('mobileMenu');
    mobileMenuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });

    // Close mobile menu on anchor click
    mobileMenu.querySelectorAll('a').forEach(link => {
      link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
    });

    /* Project Filtering Logic */
    const filterButtons = document.querySelectorAll('.filter-btn');
    const projectCards = document.querySelectorAll('.project-card');

    filterButtons.forEach(btn => {
      btn.addEventListener('click', () => {
        // Reset classes
        filterButtons.forEach(b => {
          b.classList.remove('bg-emerald-800', 'text-white', 'dark:bg-emerald-700');
          b.classList.add('bg-zinc-100', 'dark:bg-zinc-800', 'text-zinc-600', 'dark:text-zinc-300');
        });

        btn.classList.add('bg-emerald-800', 'text-white', 'dark:bg-emerald-700');
        btn.classList.remove('bg-zinc-100', 'dark:bg-zinc-800', 'text-zinc-600', 'dark:text-zinc-300');

        const filterValue = btn.getAttribute('data-filter');

        projectCards.forEach(card => {
          if (filterValue === 'all' || card.getAttribute('data-category') === filterValue) {
            card.style.display = 'flex';
          } else {
            card.style.display = 'none';
          }
        });
      });
    });

    /* Project Modal Case Studies Data Store */
    const caseStudies = {
      rips: {
        category: "Kajian Persampahan Kota",
        title: "Rencana Induk Sistem Pengelolaan Sampah (RIPS) - Kota Payakumbuh & Bukittinggi",
        objective: "Menyusun peta jalan strategis pengelolaan sampah perkotaan untuk 10 tahun ke depan sesuai amanat UU No. 18/2008 dan target pengurangan Jakstrada.",
        methodology: [
          "Sampling timbulan dan densitas sampah di sumber domestik & non-domestik sesuai SNI 19-3964-1994.",
          "Analisis spasial rute pengangkutan sampah menggunakan Network Analyst di ArcGIS.",
          "Perhitungan neraca massa material 3R serta proyeksi kebutuhan armada dump truck & arm roll."
        ],
        outcome: "Dokumen komprehensif masterplan persampahan, identifikasi reduksi beban TPA sebesar 24.3%, dan rekomendasi jadwal zonasi operasional angkutan yang efisien bahan bakar."
      },
      tpst: {
        category: "Studi Kelayakan / Feasibility Study",
        title: "Studi Kelayakan TPST 3R - Kabupaten Lima Puluh Kota",
        objective: "Menentukan kelayakan teknis, lingkungan, dan finansial pembangunan fasilitas Tempat Pengolahan Sampah Terpadu skala regional.",
        methodology: [
          "Multi-Criteria Decision Analysis (AHP) untuk seleksi tapak berdasarkan kemiringan lereng, jarak ke sungai, dan perumahan.",
          "Desain neraca massa mesin pemilah, rotary screen, dan bioreaktor komposting aktif.",
          "Kalkulasi CAPEX (konstruksi, mekanikal elektrikal) dan OPEX tahunan dengan uji sensitivitas tarif retribusi."
        ],
        outcome: "Rekomendasi tapak optimal dengan skor AHP 84%, skema finansial yang layak (NPV positif, Payback 6,2 tahun), dan desain layout fasilitas 3D sketchup."
      },
      ipal: {
        category: "Rekayasa Pengolahan Air Limbah",
        title: "Perencanaan DED IPAL Industri Tahu Beban Organik Tinggi",
        objective: "Menurunkan konsentrasi COD (mulai dari ~7.000 mg/L) dan BOD menjadi di bawah batas baku mutu Permen LHK No. 68/2016.",
        methodology: [
          "Karakterisasi laboratorium: COD, BOD, TSS, pH, dan rasio C:N:P.",
          "Desain hidrolik bak ekualisasi, Anaerobic Baffled Reactor (ABR) bertingkat, dan kolam aerasi sekunder.",
          "Pembuatan layout CAD lengkap dengan denah, potongan memanjang, profil hidrolis gravitasi, dan spesifikasi blower/pompa submersible."
        ],
        outcome: "Desain sistem dengan estimasi efisiensi penyisihan COD > 85%, tanpa ketergantungan bahan kimia koagulan mahal, serta pemanfaatan potensi biogas sederhana."
      },
      spam: {
        category: "Audit Kualitas & Hidrolika Air",
        title: "Audit Teknis Sistem Penyediaan Air Minum (SPAM) - Universitas Andalas",
        objective: "Menganalisis kontinuitas debit, sisa tekan hidrolik pipa, dan kesesuaian mutu air minum terhadap standar Permenkes No. 2 Tahun 2023.",
        methodology: [
          "Pengukuran tekanan lapangan di simpul kritis jaringan distribusi pipa transmisi.",
          "Pengujian sampel laboratorium berkala: turbidity (kekeruhan), pH, sisa klor, Fe, Mn, serta parameter mikrobiologis Total Coliform / E. coli.",
          "Evaluasi efisiensi pencucian pasir filter dan sistem injeksi desinfektan kaporit."
        ],
        outcome: "Peta titik rawan defisit tekanan air, rekomendasi penggantian katup pengatur tekanan, dan protokol klorinasi berkala untuk memastikan air steril hingga kran gedung fakultas."
      },
      disaster: {
        category: "Kajian Spesifik Tanggap Bencana",
        title: "Kajian Pengelolaan Sampah Tanggap Bencana - Kota Bukittinggi",
        objective: "Merumuskan protokol kontinjensi pembersihan reruntuhan, lumpur, dan sampah darurat pasca bencana alam hidrometeorologi.",
        methodology: [
          "Estimasi volume debris berdasarkan pola permukiman dan topografi kerawanan longsor.",
          "Penetapan lokasi TPS Darurat (Temporary Debris Staging Site) berbasis GIS berjarak aman dari badan air.",
          "Penyusunan Standard Operating Procedure (SOP) integrasi dinas lingkungan hidup, BPBD, dan relawan."
        ],
        outcome: "Dokumen teknis tanggap darurat debris, format checklist inventarisasi alat berat, dan modul edukasi sanitasi darurat pengungsi."
      },
      mfc: {
        category: "Riset Bio-Energi Lingkungan",
        title: "Penyisihan Organik & Bio-Listrik via Microbial Fuel Cell (MFC)",
        objective: "Menyelidiki performa reaktor MFC dalam mengolah air limbah berkadar organik tinggi sekaligus mengonversi energi metabolik mikroba menjadi daya listrik.",
        methodology: [
          "Perakitan reaktor dual-chamber dengan membrane exchange dan elektroda karbon grafit teraktivasi.",
          "Monitoring voltase listrik (multimeter digital) dan laju degradasi COD secara harian selama 14 hari proses anaerob.",
          "Analisis resistansi internal melalui kurva polarisasi kelistrikan sel mikrobiologis."
        ],
        outcome: "Efisiensi degradasi organik hingga 78% diiringi pembuktian panen daya mikro, dipresentasikan pada simposium ilmiah dan memenangkan juara LKTI tingkat nasional."
      }
    };

    const modal = document.getElementById('projectModal');
    const modalCategory = document.getElementById('modalCategory');
    const modalTitle = document.getElementById('modalTitle');
    const modalObjective = document.getElementById('modalObjective');
    const modalMethodology = document.getElementById('modalMethodology');
    const modalOutcome = document.getElementById('modalOutcome');

    function openProjectModal(key) {
      const data = caseStudies[key];
      if (!data) return;

      modalCategory.innerText = data.category;
      modalTitle.innerText = data.title;
      modalObjective.innerText = data.objective;
      modalOutcome.innerText = data.outcome;

      modalMethodology.innerHTML = '';
      data.methodology.forEach(item => {
        const li = document.createElement('li');
        li.innerText = item;
        modalMethodology.appendChild(li);
      });

      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeProjectModal() {
      modal.classList.add('hidden');
      document.body.style.overflow = '';
    }

    // Close modal on click outside box
    modal.addEventListener('click', (e) => {
      if (e.target === modal) closeProjectModal();
    });

    /* Toast Notification Utility */
    function showToast(title, message) {
      const toast = document.getElementById('toastNotification');
      document.getElementById('toastTitle').innerText = title;
      document.getElementById('toastMessage').innerText = message;
      toast.classList.remove('hidden');
      setTimeout(() => {
        toast.classList.add('hidden');
      }, 4000);
    }

    /* Clipboard Helper */
    function copyToClipboard(text, successMsg) {
      const tempInput = document.createElement('input');
      tempInput.value = text;
      document.body.appendChild(tempInput);
      tempInput.select();
      document.execCommand('copy');
      document.body.removeChild(tempInput);
      showToast('Disalin ke Clipboard', successMsg);
    }

    /* Form Submission Handler */
    function handleFormSubmit(e) {
      e.preventDefault();
      const name = document.getElementById('name').value;
      const category = document.getElementById('serviceCategory').value;
      showToast('Pesan Terkirim', `Terima kasih ${name}. Penjajakan terkait "${category}" telah diterima. Kami akan merespons melalui email.`);
      e.target.reset();
    }
  </script>
</body>
</html>
