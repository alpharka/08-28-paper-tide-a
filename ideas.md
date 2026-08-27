# Arah Desain Undangan Digital

## Tiga Pendekatan Visual

### Theme Name: Paper & Tide
**Very Brief Intro:** Editorial coastal modern dengan kertas gading, biru laut yang tenang, dan aksen koral matahari terbenam. Terasa intim, lapang, dan dewasa.

**Probability:** 0.07

### Theme Name: Midnight Vellum
**Very Brief Intro:** Dark romantic yang dibangun dari hitam tinta, plum, dan kilau emas tipis. Dramatis tetapi tetap hening dan elegan.

**Probability:** 0.03

### Theme Name: Kyoto After Rain
**Very Brief Intro:** Japanese wabi-sabi dengan warna tanah liat, hijau lumut, dan ruang kosong yang terukur. Hangat, kontemplatif, dan sangat personal.

**Probability:** 0.08

## Pendekatan Terpilih: Paper & Tide

### Design Movement
Editorial coastal modern, terinspirasi dari majalah perjalanan pesisir, stationery letterpress, dan fotografi analog dengan cahaya pagi.

### Core Principles
1. **Lapang tetapi berkarakter:** whitespace menjadi bagian dari komposisi, bukan ruang kosong yang tidak disengaja.
2. **Editorial asimetris:** konten disusun dengan offset, garis margin, nomor bab, dan kolom yang tidak terlalu seragam.
3. **Material yang terasa:** tekstur kertas, garis cetak halus, border hairline, serta aksen stempel matahari.
4. **Romantis yang tenang:** interaksi lembut dan copy spesifik, tanpa ornamen berlebihan.

### Color Philosophy
Dasar **shell ivory** memberi rasa kertas undangan yang tak lekang waktu. **Deep marine** menjaga kedalaman dan keterbacaan seperti tinta biru tua. **Terracotta coral** menjadi aksen milik pasangan: hangat, optimistis, dan terasa seperti cahaya sore di tepi laut. Warna tidak digunakan sebagai gradient dekoratif, melainkan sebagai blok editorial dan penanda navigasi.

### Layout Paradigm
Alur vertikal seperti membaca surat panjang: cover penuh layar, lalu hero dengan kolom teks yang bergeser, cerita dalam dua jalur, detail acara sebagai timeline editorial, galeri masonry, dan penutup yang kembali lapang. Elemen penting memakai garis kiri dan nomor kecil, bukan kumpulan kartu yang seragam.

### Signature Elements
1. **Sun stamp:** emblem matahari bergaris yang muncul di cover, header, detail acara, dan footer.
2. **Tide rule:** garis horizontal tipis dengan label bab kecil untuk menandai perpindahan cerita.
3. **Coral tab:** aksen terracotta pada tombol utama, angka countdown, dan affordance galeri.

### Interaction Philosophy
Interaksi terasa seperti membuka surat pribadi: cover naik perlahan, anchor navigation meluncur halus, gambar dibuka sebagai lembar foto, dan setiap aksi memberi feedback singkat yang jelas. Tidak ada animasi yang mengganggu pembacaan.

### Animation
Cover slide-up 720ms dengan cubic-bezier yang lembut. Header muncul dari atas setelah cover selesai; konten reveal menggunakan opacity dan translateY kecil melalui IntersectionObserver. Galeri memakai scale sangat ringan saat hover/focus. Lightbox fade cepat dan memusatkan perhatian pada foto. Semua motion non-esensial dinonaktifkan pada `prefers-reduced-motion: reduce`.

### Typography System
Display memakai **Cormorant Garamond** untuk nama pasangan, judul bab, dan angka besar; bentuknya editorial dan romantis tanpa menjadi dekorasi berlebihan. Body memakai **DM Sans** dengan tracking sedikit lega untuk keterbacaan digital. Eyebrow dan metadata memakai DM Sans uppercase berukuran kecil dengan letter-spacing yang tegas.

### Brand Essence
Undangan digital untuk pasangan yang ingin mengundang orang terdekat dengan kehangatan surat pribadi, dibedakan oleh bahasa editorial pesisir dan ritme visual yang tenang.

**Personality:** intimate, sunlit, composed.

### Brand Voice
Headline, CTA, dan microcopy terdengar hangat, spesifik, dan tidak menjual. Hindari filler; gunakan kalimat yang terasa ditulis oleh pasangan.

Contoh:
- “Satu sore, dua arah pulang — dan kami memilih berjalan bersama.”
- “Mari duduk lebih lama, berbagi cerita, lalu merayakan kami.”

### Wordmark & Logo
Logo berupa emblem matahari setengah terbit di atas satu garis horizon, terdiri dari lingkaran terbuka, tiga sinar pendek, dan garis ombak tipis. Simbol dibuat tanpa teks sehingga dapat dipakai sebagai favicon, cap, dan penanda section.

### Signature Brand Color
**Terracotta Coral `#C96E58`** — aksen hangat yang menjadi tanda visual khas pasangan di atas shell ivory dan deep marine.
