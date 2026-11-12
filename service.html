<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover" />
    <title>Layanan — SIAP.AI</title>
    <link rel="icon" type="image/png" href="/img/favicon.png" />
    <meta name="description"
        content="Layanan SIAP.AI: setup AI dan pengembangan website, apa yang Anda dapatkan, untuk siapa, dan bagaimana prosesnya." />
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
    <style>
        html {
            scroll-padding-top: 5rem;
        }
    </style>
</head>

<body class="bg-paper text-ink antialiased pb-24 md:pb-0">

    <!-- NAV -->
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
        <!-- HERO -->
        <section class="border-b-4 border-ink">
            <div class="mx-auto max-w-6xl px-5 pb-16 pt-36 md:pb-24 md:pt-44">
                <a href="index.html#layanan"
                    class="font-mono text-sm underline underline-offset-4 hover:bg-signal">&larr; Kembali ke beranda</a>
                <h1 class="rise mt-8 font-display text-[13vw] leading-[0.9] tracking-tighter md:text-[8rem]">
                    LAYANAN
                </h1>
                <p class="rise rise-2 mt-8 max-w-xl text-lg md:text-xl">
                    Dua layanan, satu tujuan: sistem yang benar-benar dipakai tim Anda. Pilih layanan di bawah untuk
                    melihat isinya.
                </p>

                <div class="mt-10 grid border-4 border-ink font-mono font-bold sm:grid-cols-2" role="tablist"
                    aria-label="Pilih layanan">
                    <a href="#setup-ai" data-tab="setup-ai"
                        class="tab-link border-b-4 border-ink px-6 py-5 hover:bg-ink hover:text-paper sm:border-b-0 sm:border-r-4">Setup
                        AI</a>
                    <a href="#website" data-tab="website"
                        class="tab-link px-6 py-5 hover:bg-ink hover:text-paper">Website</a>
                </div>
            </div>
        </section>

        <!-- SETUP AI -->
        <section id="setup-ai" class="border-b-4 border-ink">
            <div class="mx-auto max-w-6xl px-5 py-20">
                <div class="grid gap-10 md:grid-cols-2">
                    <div>
                        <h2 class="font-display text-4xl tracking-tight md:text-6xl">SETUP AI</h2>
                        <p class="mt-6 max-w-lg text-lg">
                            Kami memasang dan mengatur AI di dalam cara kerja bisnis Anda yang sudah ada, bukan
                            sebaliknya. Tim Anda tidak perlu belajar alat baru yang rumit.
                        </p>
                    </div>
                    <div class="border-4 border-ink p-8">
                        <h3 class="font-display text-2xl">Cocok untuk</h3>
                        <ul class="mt-4 space-y-3">
                            <li>— Toko online yang ingin pertanyaan pelanggan terjawab di luar jam kerja</li>
                            <li>— Tim kecil yang menghabiskan waktu untuk pekerjaan berulang</li>
                            <li>— Bisnis jasa yang ingin merapikan balasan dan dokumen</li>
                        </ul>
                    </div>
                </div>

                <h3 class="mt-16 font-display text-2xl md:text-3xl">Yang Anda dapatkan</h3>
                <div class="mt-6 grid border-4 border-ink md:grid-cols-3">
                    <article class="border-b-4 border-ink p-8 md:border-b-0 md:border-r-4">
                        <h4 class="font-display text-xl">Konfigurasi model AI</h4>
                        <p class="mt-3">Pemilihan dan pengaturan model sesuai tugasnya, lengkap dengan instruksi dan
                            batasan
                            jawaban yang kita sepakati.</p>
                    </article>
                    <article class="border-b-4 border-ink p-8 md:border-b-0 md:border-r-4">
                        <h4 class="font-display text-xl">Integrasi sistem</h4>
                        <p class="mt-3">AI disambungkan ke alat yang sudah Anda pakai, misalnya website, pesan
                            pelanggan,
                            atau data internal.</p>
                    </article>
                    <article class="p-8">
                        <h4 class="font-display text-xl">Panduan untuk tim</h4>
                        <p class="mt-3">Cara pakai, cara memeriksa hasil, dan apa yang harus dilakukan kalau jawaban AI
                            kurang tepat.</p>
                    </article>
                </div>

                <h3 class="mt-16 font-display text-2xl md:text-3xl">Contoh yang bisa dikerjakan</h3>
                <ul class="mt-6 grid gap-0 border-4 border-ink md:grid-cols-2">
                    <li class="border-b-4 border-ink p-6 md:border-r-4">Chatbot layanan pelanggan dengan jawaban dari
                        informasi bisnis Anda</li>
                    <li class="border-b-4 border-ink p-6">Asisten internal untuk mencari dan merangkum dokumen</li>
                    <li class="border-b-4 border-ink p-6 md:border-b-0 md:border-r-4">Draf balasan otomatis yang tetap
                        Anda tinjau sebelum dikirim</li>
                    <li class="p-6">Perapian data dan laporan rutin</li>
                </ul>
            </div>
        </section>

        <!-- WEBSITE -->
        <section id="website" class="border-b-4 border-ink bg-ink text-paper">
            <div class="mx-auto max-w-6xl px-5 py-20">
                <div class="grid gap-10 md:grid-cols-2">
                    <div>
                        <h2 class="font-display text-4xl tracking-tight md:text-6xl">WEBSITE</h2>
                        <p class="mt-6 max-w-lg text-lg text-paper/80">
                            Website yang cepat dibuka, rapi di layar ponsel, dan bisa Anda kelola sendiri lewat panel
                            admin tanpa harus menghubungi developer setiap kali ada perubahan.
                        </p>
                    </div>
                    <div class="border-4 border-paper p-8">
                        <h3 class="font-display text-2xl">Pilihan jenis website</h3>
                        <ul class="mt-4 space-y-3">
                            <li><span class="font-bold">Company profile</span> untuk memperkenalkan bisnis dan layanan
                            </li>
                            <li><span class="font-bold">Landing page</span> untuk satu penawaran atau kampanye</li>
                            <li><span class="font-bold">Aplikasi web</span> untuk sistem dengan login dan data</li>
                        </ul>
                    </div>
                </div>

                <h3 class="mt-16 font-display text-2xl md:text-3xl">Yang Anda dapatkan</h3>
                <div class="mt-6 grid border-4 border-paper md:grid-cols-3">
                    <article class="border-b-4 border-paper p-8 md:border-b-0 md:border-r-4">
                        <h4 class="font-display text-xl">Desain UI/UX</h4>
                        <p class="mt-3 text-paper/80">Tata letak dan alur yang membuat pengunjung cepat menemukan yang
                            mereka cari.</p>
                    </article>
                    <article class="border-b-4 border-paper p-8 md:border-b-0 md:border-r-4">
                        <h4 class="font-display text-xl">Frontend dan backend</h4>
                        <p class="mt-3 text-paper/80">Tampilan responsif di semua ukuran layar, ditambah sistem di
                            belakangnya bila diperlukan.</p>
                    </article>
                    <article class="p-8">
                        <h4 class="font-display text-xl">Panel admin</h4>
                        <p class="mt-3 text-paper/80">Ubah teks, gambar, artikel, dan data sendiri lewat tampilan yang
                            sederhana.</p>
                    </article>
                </div>
            </div>
        </section>

        <!-- PROSES -->
        <section id="proses" class="border-b-4 border-ink">
            <div class="mx-auto max-w-6xl px-5 py-20">
                <h2 class="font-display text-4xl tracking-tight md:text-6xl">CARA KERJA</h2>
                <p class="mt-6 max-w-xl text-lg">Alur yang sama untuk kedua layanan, supaya Anda selalu tahu sedang
                    berada di tahap mana.</p>
                <ol class="mt-12 grid gap-8 md:grid-cols-3">
                    <li class="border-t-4 border-signal pt-6">
                        <p class="font-mono text-sm">01</p>
                        <h3 class="mt-2 font-display text-2xl">Diskusi</h3>
                        <p class="mt-3">Kami mendengar kebutuhan Anda, lalu menyepakati ruang lingkup dan jadwal secara
                            tertulis.</p>
                    </li>
                    <li class="border-t-4 border-signal pt-6">
                        <p class="font-mono text-sm">02</p>
                        <h3 class="mt-2 font-display text-2xl">Bangun</h3>
                        <p class="mt-3">Pengerjaan sesuai rencana. Anda bisa melihat dan memberi masukan sebelum lanjut.
                        </p>
                    </li>
                    <li class="border-t-4 border-signal pt-6">
                        <p class="font-mono text-sm">03</p>
                        <h3 class="mt-2 font-display text-2xl">Serah Terima</h3>
                        <p class="mt-3">Sistem diserahkan lengkap dengan panduan penggunaan untuk tim Anda.</p>
                    </li>
                </ol>
            </div>
        </section>

        <!-- FAQ -->
        <section id="faq" class="border-b-4 border-ink">
            <div class="mx-auto grid max-w-6xl gap-10 px-5 py-20 md:grid-cols-[1fr_2fr]">
                <h2 class="font-display text-4xl tracking-tight md:text-6xl">TANYA JAWAB</h2>
                <div class="border-4 border-ink">
                    <div class="faq-item border-b-4 border-ink">
                        <h3>
                            <button type="button" id="faq-btn-0" aria-expanded="false" aria-controls="faq-panel-0"
                                class="faq-btn flex w-full items-center justify-between gap-4 p-6 text-left font-bold hover:bg-ink hover:text-paper">
                                Apakah saya perlu punya tim teknis?
                                <span class="faq-icon font-display text-2xl" aria-hidden="true">+</span>
                            </button>
                        </h3>
                        <div id="faq-panel-0" role="region" aria-labelledby="faq-btn-0" class="faq-panel">
                            <div>
                                <p class="px-6 pb-6 pt-2">Tidak. Kami menjelaskan setiap langkah dengan bahasa yang
                                    mudah dipahami dan menyerahkan panduan di akhir proyek.</p>
                            </div>
                        </div>
                    </div>
                    <div class="faq-item border-b-4 border-ink">
                        <h3>
                            <button type="button" id="faq-btn-1" aria-expanded="false" aria-controls="faq-panel-1"
                                class="faq-btn flex w-full items-center justify-between gap-4 p-6 text-left font-bold hover:bg-ink hover:text-paper">
                                Berapa lama pengerjaannya?
                                <span class="faq-icon font-display text-2xl" aria-hidden="true">+</span>
                            </button>
                        </h3>
                        <div id="faq-panel-1" role="region" aria-labelledby="faq-btn-1" class="faq-panel">
                            <div>
                                <p class="px-6 pb-6 pt-2">Tergantung ruang lingkupnya. Setelah diskusi awal, kami
                                    berikan perkiraan waktu yang jelas sebelum pengerjaan dimulai.</p>
                            </div>
                        </div>
                    </div>
                    <div class="faq-item border-b-4 border-ink">
                        <h3>
                            <button type="button" id="faq-btn-2" aria-expanded="false" aria-controls="faq-panel-2"
                                class="faq-btn flex w-full items-center justify-between gap-4 p-6 text-left font-bold hover:bg-ink hover:text-paper">
                                Bagaimana dengan keamanan data saya?
                                <span class="faq-icon font-display text-2xl" aria-hidden="true">+</span>
                            </button>
                        </h3>
                        <div id="faq-panel-2" role="region" aria-labelledby="faq-btn-2" class="faq-panel">
                            <div>
                                <p class="px-6 pb-6 pt-2">Kami membahas data apa yang boleh dan tidak boleh masuk ke
                                    sistem AI sejak awal, dan mencatatnya dalam kesepakatan proyek.</p>
                            </div>
                        </div>
                    </div>
                    <div class="faq-item">
                        <h3>
                            <button type="button" id="faq-btn-3" aria-expanded="false" aria-controls="faq-panel-3"
                                class="faq-btn flex w-full items-center justify-between gap-4 p-6 text-left font-bold hover:bg-ink hover:text-paper">
                                Bisakah mengambil Setup AI dan Website sekaligus?
                                <span class="faq-icon font-display text-2xl" aria-hidden="true">+</span>
                            </button>
                        </h3>
                        <div id="faq-panel-3" role="region" aria-labelledby="faq-btn-3" class="faq-panel">
                            <div>
                                <p class="px-6 pb-6 pt-2">Bisa. Keduanya dikerjakan dalam satu rencana, misalnya website
                                    dengan chatbot yang sudah terpasang.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- KONTAK -->
        <section id="kontak" class="bg-signal">
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
        // Tandai tab layanan (Setup AI / Website) sesuai bagian yang terlihat
        const tabs = document.querySelectorAll('[data-tab]');
        const setTab = (id) => tabs.forEach((t) => {
            const on = t.dataset.tab === id;
            t.classList.toggle('is-active', on);
            if (on) t.setAttribute('aria-current', 'true'); else t.removeAttribute('aria-current');
        });
        const io = new IntersectionObserver((entries) => {
            entries.forEach((e) => { if (e.isIntersecting) setTab(e.target.id); });
        }, { rootMargin: '-30% 0px -60% 0px' });
        ['setup-ai', 'website'].forEach((id) => {
            const el = document.getElementById(id);
            if (el) io.observe(el);
        });
    </script>

    <script>
        // FAQ: buka-tutup dengan transisi
        document.querySelectorAll('.faq-btn').forEach((btn) => {
            btn.addEventListener('click', () => {
                const item = btn.closest('.faq-item');
                const open = item.classList.toggle('is-open');
                btn.setAttribute('aria-expanded', open);
            });
        });
    </script>

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