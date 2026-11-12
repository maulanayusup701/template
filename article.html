<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover" />
    <title>Artikel — SIAP.AI</title>
    <link rel="icon" type="image/png" href="/img/favicon.png" />
    <meta name="description"
        content="Artikel SIAP.AI tentang setup AI, chatbot, keamanan data, dan website untuk bisnis kecil." />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Space+Mono:wght@400;700&display=swap"
        rel="stylesheet" />
    <script src="https://cdn.tailwindcss.com/3.4.17"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        display: ['"Archivo Black"', 'sans-serif'],
                        mono: ['"Space Mono"', 'monospace'],
                    },
                    maxWidth: { '6xl': '120rem' },
                    // Warna membaca CSS variable (format channel RGB supaya /80, /60 tetap jalan)
                    colors: {
                        paper: 'rgb(var(--color-paper) / <alpha-value>)',
                        ink: 'rgb(var(--color-ink) / <alpha-value>)',
                        signal: 'rgb(var(--color-signal) / <alpha-value>)',
                    },
                    boxShadow: {
                        brutal: '8px 8px 0 0 rgb(var(--color-signal))',
                        'brutal-sm': '4px 4px 0 0 rgb(var(--color-signal))',
                    },
                },
            },
            plugins: [
                function ({ addBase, addComponents }) {
                    // ---------- Variable warna + base ----------
                    addBase({
                        ':root': {
                            '--color-paper': '242 242 236', // #F2F2EC
                            '--color-ink': '10 10 10',      // #0A0A0A
                            '--color-signal': '255 90 31',  // #FF5A1F
                        },
                        html: { scrollBehavior: 'smooth' },
                        body: { fontFamily: '"Space Mono", monospace' },
                        'a:focus-visible, button:focus-visible, input:focus-visible': {
                            outline: '4px solid rgb(var(--color-signal))',
                            outlineOffset: '2px',
                        },
                        mark: {
                            backgroundColor: 'rgb(var(--color-signal))',
                            color: 'rgb(var(--color-ink))',
                            padding: '0 2px',
                        },
                        '@keyframes rise': {
                            from: { opacity: '0', transform: 'translateY(24px)' },
                            to: { opacity: '1', transform: 'none' },
                        },
                        '@media (prefers-reduced-motion: reduce)': {
                            html: { scrollBehavior: 'auto' },
                        },
                    });

                    // ---------- Komponen yang dipakai berulang ----------
                    addComponents({
                        /* Animasi masuk */
                        '.rise': { animation: 'rise 0.7s cubic-bezier(0.2, 0.7, 0.2, 1) both' },
                        '.rise-2': { animationDelay: '0.15s' },
                        '.rise-3': { animationDelay: '0.3s' },
                        '.rise-4': { animationDelay: '0.45s' },

                        /* Kartu: geser + bayangan oranye saat hover
                           (menggantikan: transition duration-200 hover:z-10 hover:-translate-x-1
                            hover:-translate-y-1 hover:bg-ink hover:text-paper hover:shadow-[8px_8px_0_0_#FF5A1F]) */
                        '.card-hover': {
                            position: 'relative',
                            transitionProperty: 'color, background-color, border-color, box-shadow, transform',
                            transitionDuration: '200ms',
                            transitionTimingFunction: 'cubic-bezier(0.4, 0, 0.2, 1)',
                        },
                        '.card-hover:hover': {
                            zIndex: '10',
                            transform: 'translate(-0.25rem, -0.25rem)',
                            backgroundColor: 'rgb(var(--color-ink))',
                            color: 'rgb(var(--color-paper))',
                            boxShadow: '8px 8px 0 0 rgb(var(--color-signal))',
                        },

                        /* Menu desktop */
                        '.desk-link.is-active': {
                            textDecoration: 'underline',
                            textDecorationColor: 'rgb(var(--color-signal))',
                            textDecorationThickness: '4px',
                            textUnderlineOffset: '6px',
                        },

                        /* Bottom bar mobile */
                        '.nav-item': { WebkitTapHighlightColor: 'transparent' },
                        '.nav-item.is-active': {
                            backgroundColor: 'rgb(var(--color-ink))',
                            color: 'rgb(var(--color-paper))',
                        },
                        '.nav-item.is-active .nav-icon': { color: 'rgb(var(--color-signal))' },
                        '.nav-item.is-active + .nav-item': { borderLeftColor: 'transparent' },

                        /* Tab layanan (service.html) */
                        '.tab-link.is-active': {
                            backgroundColor: 'rgb(var(--color-ink))',
                            color: 'rgb(var(--color-paper))',
                        },

                        /* Chip kategori (article.html) */
                        '.chip[aria-pressed="true"]': {
                            backgroundColor: 'rgb(var(--color-ink))',
                            color: 'rgb(var(--color-paper))',
                            boxShadow: '4px 4px 0 0 rgb(var(--color-signal))',
                        },

                        /* FAQ (service.html) */
                        '.faq-panel': {
                            display: 'grid',
                            gridTemplateRows: '0fr',
                            transition: 'grid-template-rows 0.4s cubic-bezier(0.2, 0.7, 0.2, 1)',
                        },
                        '.faq-panel > div': { overflow: 'hidden' },
                        '.faq-panel p': {
                            opacity: '0',
                            transform: 'translateY(-8px)',
                            transition: 'opacity 0.3s ease, transform 0.4s cubic-bezier(0.2, 0.7, 0.2, 1)',
                        },
                        '.faq-item.is-open .faq-panel': { gridTemplateRows: '1fr' },
                        '.faq-item.is-open .faq-panel p': {
                            opacity: '1',
                            transform: 'none',
                            transitionDelay: '0.08s',
                        },
                        '.faq-btn': { transition: 'background-color 0.2s, color 0.2s' },
                        '.faq-item.is-open .faq-btn': {
                            backgroundColor: 'rgb(var(--color-ink))',
                            color: 'rgb(var(--color-paper))',
                        },
                        '.faq-icon': { transition: 'transform 0.35s cubic-bezier(0.2, 0.7, 0.2, 1)' },
                        '.faq-item.is-open .faq-icon': {
                            transform: 'rotate(135deg)',
                            color: 'rgb(var(--color-signal))',
                        },

                        '@media (prefers-reduced-motion: reduce)': {
                            '.rise': { animation: 'none' },
                            '.faq-panel, .faq-panel p, .faq-icon, .faq-btn': { transition: 'none' },
                        },
                    });
                },
            ],
        };
    </script>
</head>

<body class="bg-paper text-ink antialiased pb-24 md:pb-0">

    <header class="absolute inset-x-0 top-0 z-50 transition-transform duration-300">
        <nav class="mx-auto flex max-w-6xl items-center justify-between px-5 py-4">
            <a href="index.html" class="font-display text-2xl tracking-tight">SIAP.AI</a>
            <div class="hidden gap-8 font-mono text-sm md:flex">
                <a href="index.html" data-spy="beranda" class="desk-link hover:underline underline-offset-4">Beranda</a>
                <a href="service.html" data-spy="layanan"
                    class="desk-link hover:underline underline-offset-4">Layanan</a>
                <a href="article.html" data-spy="artikel"
                    class="desk-link hover:underline underline-offset-4">Artikel</a>
                <a href="aboutus.html" data-spy="tentang"
                    class="desk-link hover:underline underline-offset-4">Tentang</a>
            </div>
            <div class="flex items-center gap-2 md:gap-3">
                <a href="login.html"
                    class="border-4 border-ink bg-paper px-3 py-2 font-mono text-sm font-bold text-ink hover:bg-ink hover:text-paper md:px-4">Login</a>
                <a href="index.html#kontak"
                    class="border-4 border-ink bg-ink px-3 py-2 font-mono text-sm font-bold text-paper hover:bg-signal hover:text-ink md:px-4">Hubungi
                    Kami</a>
            </div>
        </nav>
    </header>

    <!-- BOTTOM NAV (MOBILE) -->
    <nav aria-label="Navigasi utama"
        class="fixed inset-x-0 bottom-0 z-50 border-t-4 border-ink bg-paper md:hidden pb-[env(safe-area-inset-bottom)]">
        <div class="grid grid-cols-4 font-mono text-[11px] font-bold">
            <a href="index.html" data-spy="beranda"
                class="nav-item flex min-h-[56px] flex-col items-center justify-center gap-1 py-2 active:bg-ink active:text-paper">
                <svg class="nav-icon h-6 w-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.25"
                    stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                    <path d="M3 10.5 12 3l9 7.5" />
                    <path d="M5 9.5V21h14V9.5" />
                    <path d="M10 21v-6h4v6" />
                </svg>
                <span>Beranda</span>
            </a>
            <a href="service.html" data-spy="layanan"
                class="nav-item flex min-h-[56px] flex-col items-center justify-center gap-1 border-l-4 border-ink py-2 active:bg-ink active:text-paper">
                <svg class="nav-icon h-6 w-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.25"
                    stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                    <rect x="3" y="3" width="7" height="7" />
                    <rect x="14" y="3" width="7" height="7" />
                    <rect x="3" y="14" width="7" height="7" />
                    <rect x="14" y="14" width="7" height="7" />
                </svg>
                <span>Layanan</span>
            </a>
            <a href="article.html" data-spy="artikel"
                class="nav-item flex min-h-[56px] flex-col items-center justify-center gap-1 border-l-4 border-ink py-2 active:bg-ink active:text-paper">
                <svg class="nav-icon h-6 w-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.25"
                    stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                    <rect x="3" y="4" width="18" height="16" />
                    <path d="M7 8h10M7 12h10M7 16h6" />
                </svg>
                <span>Artikel</span>
            </a>
            <a href="aboutus.html" data-spy="tentang"
                class="nav-item flex min-h-[56px] flex-col items-center justify-center gap-1 border-l-4 border-ink py-2 active:bg-ink active:text-paper">
                <svg class="nav-icon h-6 w-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.25"
                    stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                    <circle cx="12" cy="8" r="4" />
                    <path d="M4 21c0-4 3.6-7 8-7s8 3 8 7" />
                </svg>
                <span>Tentang</span>
            </a>
        </div>
    </nav>

    <main>
        <section class="border-b-4 border-ink">
            <div class="mx-auto max-w-6xl px-5 pb-12 pt-36 md:pb-16 md:pt-44">
                <a href="index.html#artikel"
                    class="font-mono text-sm underline underline-offset-4 hover:bg-signal">&larr; Kembali ke beranda</a>
                <h1 class="rise mt-8 font-display text-[15vw] leading-[0.9] tracking-tighter md:text-[8rem]">ARTIKEL
                </h1>
                <p class="rise rise-2 mt-8 max-w-xl text-lg md:text-xl">Panduan singkat soal AI dan website untuk bisnis
                    kecil, ditulis dengan bahasa yang mudah dipahami.</p>

                <div class="mt-10 border-4 border-ink">
                    <div class="border-b-4 border-ink">
                        <label for="cari" class="sr-only">Cari artikel</label>
                        <input id="cari" type="search" autocomplete="off" placeholder="Cari artikel…"
                            class="w-full bg-paper px-6 py-5 font-mono text-base placeholder:text-ink/60 focus:bg-white" />
                    </div>
                    <div id="kategori" role="group" aria-label="Filter kategori" class="flex flex-wrap gap-3 p-4">
                        <button type="button" data-cat="" aria-pressed="true"
                            class="chip border-4 border-ink px-4 py-2 font-mono text-sm font-bold hover:bg-ink hover:text-paper">Semua</button>
                        <button type="button" data-cat="Setup AI" aria-pressed="false"
                            class="chip border-4 border-ink px-4 py-2 font-mono text-sm font-bold hover:bg-ink hover:text-paper">Setup
                            AI</button>
                        <button type="button" data-cat="Chatbot" aria-pressed="false"
                            class="chip border-4 border-ink px-4 py-2 font-mono text-sm font-bold hover:bg-ink hover:text-paper">Chatbot</button>
                        <button type="button" data-cat="Keamanan Data" aria-pressed="false"
                            class="chip border-4 border-ink px-4 py-2 font-mono text-sm font-bold hover:bg-ink hover:text-paper">Keamanan
                            Data</button>
                        <button type="button" data-cat="Website" aria-pressed="false"
                            class="chip border-4 border-ink px-4 py-2 font-mono text-sm font-bold hover:bg-ink hover:text-paper">Website</button>
                    </div>
                </div>
            </div>
        </section>

        <section class="border-b-4 border-ink">
            <div class="mx-auto max-w-6xl px-5 py-12 md:py-16">
                <p id="hasil" class="font-mono text-sm" aria-live="polite"></p>

                <div id="daftar" class="mt-6 grid gap-6 p-1 sm:grid-cols-2 lg:grid-cols-4">
                    <article data-category="Website"
                        class="art-card relative flex flex-col border-4 border-ink bg-paper p-8 card-hover">
                        <div class="flex items-center justify-between gap-3 font-mono text-xs">
                            <span class="border-2 border-current px-2 py-1 font-bold">Website</span>
                            <time datetime="2026-11-12">12 Nov 2026</time>
                        </div>
                        <h2 class="art-title mt-5 font-display text-xl">Memilih Website untuk Bisnis Kecil</h2>
                        <p class="art-excerpt mt-3">Perbandingan company profile, landing page, dan aplikasi web, serta
                            cara memilih yang sesuai kebutuhan.</p>
                        <a href="#"
                            class="mt-auto self-start pt-6 font-mono text-sm font-bold underline underline-offset-4 after:absolute after:inset-0 after:content-['']">Baca
                            selengkapnya</a>
                    </article>
                    <article data-category="Keamanan Data"
                        class="art-card relative flex flex-col border-4 border-ink bg-paper p-8 card-hover">
                        <div class="flex items-center justify-between gap-3 font-mono text-xs">
                            <span class="border-2 border-current px-2 py-1 font-bold">Keamanan Data</span>
                            <time datetime="2026-11-10">10 Nov 2026</time>
                        </div>
                        <h2 class="art-title mt-5 font-display text-xl">Menjaga Data Saat Memakai AI</h2>
                        <p class="art-excerpt mt-3">Hal dasar yang perlu diperiksa sebelum memasukkan data perusahaan ke
                            sistem AI.</p>
                        <a href="#"
                            class="mt-auto self-start pt-6 font-mono text-sm font-bold underline underline-offset-4 after:absolute after:inset-0 after:content-['']">Baca
                            selengkapnya</a>
                    </article>
                    <article data-category="Chatbot"
                        class="art-card relative flex flex-col border-4 border-ink bg-paper p-8 card-hover">
                        <div class="flex items-center justify-between gap-3 font-mono text-xs">
                            <span class="border-2 border-current px-2 py-1 font-bold">Chatbot</span>
                            <time datetime="2026-11-06">06 Nov 2026</time>
                        </div>
                        <h2 class="art-title mt-5 font-display text-xl">Chatbot untuk Layanan Pelanggan: Kapan Cocok?
                        </h2>
                        <p class="art-excerpt mt-3">Cara menilai apakah chatbot cocok untuk layanan Anda, beserta batas
                            yang perlu diperhatikan.</p>
                        <a href="#"
                            class="mt-auto self-start pt-6 font-mono text-sm font-bold underline underline-offset-4 after:absolute after:inset-0 after:content-['']">Baca
                            selengkapnya</a>
                    </article>
                    <article data-category="Setup AI"
                        class="art-card relative flex flex-col border-4 border-ink bg-paper p-8 card-hover">
                        <div class="flex items-center justify-between gap-3 font-mono text-xs">
                            <span class="border-2 border-current px-2 py-1 font-bold">Setup AI</span>
                            <time datetime="2026-11-03">03 Nov 2026</time>
                        </div>
                        <h2 class="art-title mt-5 font-display text-xl">Apa Itu Setup AI untuk Bisnis Kecil?</h2>
                        <p class="art-excerpt mt-3">Langkah awal memasang AI tanpa tim teknis besar, dan hal yang perlu
                            disiapkan lebih dulu.</p>
                        <a href="#"
                            class="mt-auto self-start pt-6 font-mono text-sm font-bold underline underline-offset-4 after:absolute after:inset-0 after:content-['']">Baca
                            selengkapnya</a>
                    </article>
                    <article data-category="Website"
                        class="art-card relative flex flex-col border-4 border-ink bg-paper p-8 card-hover">
                        <div class="flex items-center justify-between gap-3 font-mono text-xs">
                            <span class="border-2 border-current px-2 py-1 font-bold">Website</span>
                            <time datetime="2026-10-31">31 Okt 2026</time>
                        </div>
                        <h2 class="art-title mt-5 font-display text-xl">Panel Admin: Mengelola Website Tanpa Developer
                        </h2>
                        <p class="art-excerpt mt-3">Apa saja yang bisa Anda ubah sendiri, dan apa yang sebaiknya tetap
                            lewat developer.</p>
                        <a href="#"
                            class="mt-auto self-start pt-6 font-mono text-sm font-bold underline underline-offset-4 after:absolute after:inset-0 after:content-['']">Baca
                            selengkapnya</a>
                    </article>
                    <article data-category="Setup AI"
                        class="art-card relative flex flex-col border-4 border-ink bg-paper p-8 card-hover">
                        <div class="flex items-center justify-between gap-3 font-mono text-xs">
                            <span class="border-2 border-current px-2 py-1 font-bold">Setup AI</span>
                            <time datetime="2026-10-28">28 Okt 2026</time>
                        </div>
                        <h2 class="art-title mt-5 font-display text-xl">Alur Kerja Mana yang Layak Dibantu AI?</h2>
                        <p class="art-excerpt mt-3">Cara memilih pekerjaan berulang yang paling pas untuk dibantu AI
                            lebih dulu.</p>
                        <a href="#"
                            class="mt-auto self-start pt-6 font-mono text-sm font-bold underline underline-offset-4 after:absolute after:inset-0 after:content-['']">Baca
                            selengkapnya</a>
                    </article>
                    <article data-category="Chatbot"
                        class="art-card relative flex flex-col border-4 border-ink bg-paper p-8 card-hover">
                        <div class="flex items-center justify-between gap-3 font-mono text-xs">
                            <span class="border-2 border-current px-2 py-1 font-bold">Chatbot</span>
                            <time datetime="2026-10-24">24 Okt 2026</time>
                        </div>
                        <h2 class="art-title mt-5 font-display text-xl">Menyiapkan Jawaban Chatbot dari Informasi Bisnis
                            Anda</h2>
                        <p class="art-excerpt mt-3">Dokumen dan pertanyaan umum apa yang perlu dikumpulkan sebelum
                            chatbot dipasang.</p>
                        <a href="#"
                            class="mt-auto self-start pt-6 font-mono text-sm font-bold underline underline-offset-4 after:absolute after:inset-0 after:content-['']">Baca
                            selengkapnya</a>
                    </article>
                    <article data-category="Keamanan Data"
                        class="art-card relative flex flex-col border-4 border-ink bg-paper p-8 card-hover">
                        <div class="flex items-center justify-between gap-3 font-mono text-xs">
                            <span class="border-2 border-current px-2 py-1 font-bold">Keamanan Data</span>
                            <time datetime="2026-10-20">20 Okt 2026</time>
                        </div>
                        <h2 class="art-title mt-5 font-display text-xl">Siapa Boleh Mengakses AI di Tim Anda?</h2>
                        <p class="art-excerpt mt-3">Pembagian akses sederhana supaya data sensitif tidak sembarangan
                            masuk.</p>
                        <a href="#"
                            class="mt-auto self-start pt-6 font-mono text-sm font-bold underline underline-offset-4 after:absolute after:inset-0 after:content-['']">Baca
                            selengkapnya</a>
                    </article>
                </div>

                <div id="kosong" class="mt-6 hidden border-4 border-ink p-8 md:p-12">
                    <h2 class="font-display text-2xl md:text-3xl">Tidak ada artikel yang cocok</h2>
                    <p class="mt-4 max-w-lg">Coba kata kunci lain atau pilih kategori yang berbeda.</p>
                    <button type="button" id="reset"
                        class="mt-6 border-4 border-ink bg-ink px-6 py-3 font-mono font-bold text-paper hover:bg-signal hover:text-ink">Tampilkan
                        semua artikel</button>
                </div>
            </div>
        </section>

        <section class="bg-signal">
            <div class="mx-auto max-w-6xl px-5 py-20 text-center">
                <h2 class="font-display text-4xl tracking-tight md:text-7xl">SIAP MULAI?</h2>
                <p class="mx-auto mt-6 max-w-xl text-lg">Ceritakan kebutuhan Anda. Kami bantu tentukan langkah
                    pertamanya.</p>
                <div class="mt-10 flex flex-col items-center gap-4 sm:flex-row sm:justify-center">
                    <a href="mailto:halo@contoh.com"
                        class="border-4 border-ink bg-ink px-8 py-4 font-mono font-bold text-paper hover:bg-paper hover:text-ink">halo@contoh.com</a>
                    <a href="https://wa.me/6281234567890"
                        class="border-4 border-ink bg-paper px-8 py-4 font-mono font-bold hover:bg-ink hover:text-paper">WhatsApp:
                        0812-3456-7890</a>
                </div>
            </div>
        </section>
    </main>

    <footer class="border-t-4 border-ink bg-paper">
        <div class="mx-auto grid max-w-6xl gap-10 px-5 py-12 md:grid-cols-3">
            <div>
                <p class="font-display text-3xl tracking-tight">SIAP.AI</p>
                <p class="mt-4 font-mono text-sm">Jasa setup AI dan pengembangan website.</p>
                <p class="mt-3 max-w-xs text-sm">Berbasis di Purwakarta, Jawa Barat. Dari pemasangan AI sampai website
                    yang siap dipakai, setiap langkah kami kerjakan dengan jelas.</p>
            </div>

            <div>
                <p class="font-mono text-sm font-bold">Navigasi</p>
                <ul class="mt-4 space-y-2 font-mono text-sm">
                    <li><a href="#beranda" class="hover:underline underline-offset-4">Beranda</a></li>
                    <li><a href="#layanan" class="hover:underline underline-offset-4">Layanan</a></li>
                    <li><a href="#proses" class="hover:underline underline-offset-4">Proses</a></li>
                    <li><a href="#artikel" class="hover:underline underline-offset-4">Artikel</a></li>
                    <li><a href="#tentang" class="hover:underline underline-offset-4">Tentang</a></li>
                    <li><a href="#kontak" class="hover:underline underline-offset-4">Kontak</a></li>
                </ul>
            </div>

            <div>
                <p class="font-mono text-sm font-bold">Kontak</p>
                <ul class="mt-4 space-y-2 font-mono text-sm">
                    <li><a href="mailto:halo@contoh.com" class="hover:underline underline-offset-4">halo@contoh.com</a>
                    </li>
                    <li><a href="https://wa.me/6281234567890"
                            class="hover:underline underline-offset-4">0812-3456-7890</a></li>
                    <li>Purwakarta, Jawa Barat, Indonesia</li>
                </ul>
                <p class="mt-8 font-mono text-sm font-bold">Sosial Media</p>
                <ul class="mt-4 flex gap-3">
                    <li><a href="https://instagram.com/siap.ai" aria-label="Instagram"
                            class="flex h-11 w-11 items-center justify-center border-4 border-ink hover:bg-ink hover:text-paper"><svg
                                viewBox="0 0 24 24" class="h-5 w-5" fill="none" stroke="currentColor" stroke-width="2">
                                <rect x="2" y="2" width="20" height="20" rx="5" />
                                <circle cx="12" cy="12" r="4.5" />
                                <circle cx="17.5" cy="6.5" r="0.8" fill="currentColor" />
                            </svg></a></li>
                    <li><a href="https://linkedin.com/company/siap-ai" aria-label="LinkedIn"
                            class="flex h-11 w-11 items-center justify-center border-4 border-ink hover:bg-ink hover:text-paper"><svg
                                viewBox="0 0 24 24" class="h-5 w-5" fill="none" stroke="currentColor" stroke-width="2">
                                <rect x="2" y="2" width="20" height="20" rx="2" />
                                <line x1="7" y1="10" x2="7" y2="17" />
                                <circle cx="7" cy="7" r="0.8" fill="currentColor" />
                                <path d="M11 17v-7M11 13c0-2 1-3 3-3s3 1 3 3v4" />
                            </svg></a></li>
                    <li><a href="https://tiktok.com/@siap.ai" aria-label="TikTok"
                            class="flex h-11 w-11 items-center justify-center border-4 border-ink hover:bg-ink hover:text-paper"><svg
                                viewBox="0 0 24 24" class="h-5 w-5" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M9 3v12a3 3 0 1 0 3-3" />
                                <path d="M9 3c0 3 2 5 5 5" />
                            </svg></a></li>
                </ul>
            </div>
        </div>

        <div class="border-t-4 border-ink">
            <div class="mx-auto max-w-6xl px-5 py-6 font-mono text-sm">
                <p>© 2026 SIAP.AI. Hak cipta dilindungi.</p>
            </div>
        </div>
    </footer>

    <script>
        // Header: melayang di atas hero, jadi bar tetap saat di-scroll
        const header = document.querySelector('header');
        const onScroll = () => {
            const scrolled = window.scrollY > 80;
            if (scrolled === header.classList.contains('fixed')) return;
            header.style.transition = 'none';
            if (scrolled) {
                header.classList.remove('absolute');
                header.classList.add('fixed', 'bg-paper', 'border-b-4', 'border-ink', '-translate-y-full');
                header.offsetHeight;
                header.style.transition = '';
                requestAnimationFrame(() => requestAnimationFrame(() => header.classList.remove('-translate-y-full')));
            } else {
                header.classList.remove('fixed', 'bg-paper', 'border-b-4', 'border-ink', '-translate-y-full');
                header.classList.add('absolute');
                header.offsetHeight;
                header.style.transition = '';
            }
        };
        window.addEventListener('scroll', onScroll, { passive: true });
        onScroll();
    </script>
    <script>
        // Pencarian + kategori
        const input = document.getElementById('cari');
        const chips = [...document.querySelectorAll('.chip')];
        const cards = [...document.querySelectorAll('.art-card')];
        const list = document.getElementById('daftar');
        const empty = document.getElementById('kosong');
        const count = document.getElementById('hasil');
        let kategori = '';

        const norm = (t) => t.toLowerCase().normalize('NFD').replace(/[\u0300-\u036f]/g, '');
        // Simpan teks asli untuk menyorot kata yang cocok
        cards.forEach((c) => {
            c.querySelectorAll('.art-title, .art-excerpt').forEach((el) => (el.dataset.raw = el.textContent));
            c.dataset.text = norm(c.dataset.category + ' ' + c.querySelector('.art-title').dataset.raw + ' ' + c.querySelector('.art-excerpt').dataset.raw);
        });

        const highlight = (el, words) => {
            const raw = el.dataset.raw;
            if (!words.length) return (el.textContent = raw);
            const n = norm(raw), marks = [];
            words.forEach((w) => { let i = n.indexOf(w); while (i !== -1) { marks.push([i, i + w.length]); i = n.indexOf(w, i + w.length); } });
            marks.sort((a, b) => a[0] - b[0]);
            const merged = [];
            marks.forEach((m) => { const l = merged[merged.length - 1]; if (l && m[0] <= l[1]) l[1] = Math.max(l[1], m[1]); else merged.push(m); });
            el.textContent = '';
            let pos = 0;
            merged.forEach(([a, b]) => {
                el.append(raw.slice(pos, a));
                const m = document.createElement('mark'); m.textContent = raw.slice(a, b); el.append(m);
                pos = b;
            });
            el.append(raw.slice(pos));
        };

        const render = () => {
            const words = norm(input.value.trim()).split(/\s+/).filter(Boolean);
            let shown = 0;
            cards.forEach((c) => {
                const ok = (!kategori || c.dataset.category === kategori) && words.every((w) => c.dataset.text.includes(w));
                c.hidden = !ok;
                c.classList.toggle('hidden', !ok);
                if (ok) {
                    shown++;
                    c.querySelectorAll('.art-title, .art-excerpt').forEach((el) => highlight(el, words));
                }
            });
            empty.classList.toggle('hidden', shown !== 0);
            list.classList.toggle('hidden', shown === 0);
            count.textContent = shown === 0 ? '' : 'Menampilkan ' + shown + ' dari ' + cards.length + ' artikel';
            chips.forEach((b) => b.setAttribute('aria-pressed', b.dataset.cat === kategori));
            // Simpan di URL supaya bisa dibagikan
            const q = new URLSearchParams();
            if (input.value.trim()) q.set('q', input.value.trim());
            if (kategori) q.set('kategori', kategori);
            history.replaceState(null, '', q.toString() ? '?' + q : location.pathname);
        };

        input.addEventListener('input', render);
        chips.forEach((b) => b.addEventListener('click', () => { kategori = b.dataset.cat; render(); }));
        document.getElementById('reset').addEventListener('click', () => { input.value = ''; kategori = ''; render(); input.focus(); });

        const params = new URLSearchParams(location.search);
        input.value = params.get('q') || '';
        const k = params.get('kategori');
        if (chips.some((b) => b.dataset.cat === k)) kategori = k;
        render();
    </script>

    <!-- Tandai menu navigasi (desktop + mobile) sesuai halaman -->
    <script>
        (function () {
            const path = (location.pathname.split('/').pop() || 'index.html').toLowerCase();
            const map = {
                '': 'beranda',
                'index.html': 'beranda',
                'service.html': 'layanan',
                'article.html': 'artikel',
                'aboutus.html': 'tentang',
            };
            const current = map[path] || 'beranda';

            // Bottom nav (mobile)
            document.querySelectorAll('.nav-item').forEach((el) => {
                const on = el.dataset.spy === current;
                el.classList.toggle('is-active', on);
                if (on) el.setAttribute('aria-current', 'page');
                else el.removeAttribute('aria-current');
            });

            // Desktop nav (sinkron)
            document.querySelectorAll('.desk-link').forEach((a) => {
                const on = a.dataset.spy === current;
                a.classList.toggle('is-active', on);
                if (on) a.setAttribute('aria-current', 'page');
                else a.removeAttribute('aria-current');
            });
        })();
    </script>
</body>

</html>