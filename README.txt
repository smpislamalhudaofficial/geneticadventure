GENETIC ADVENTURE - MPI PEWARISAN SIFAT KELAS IX
Paket aplikasi offline - HTML, CSS, dan JavaScript lokal.
Versi: v3 Biru Interaktif

CARA MENJALANKAN
1. Ekstrak ZIP ke sebuah folder.
2. Buka folder hasil ekstraksi.
3. Klik dua kali index.html.
4. Jalankan di Chrome atau Edge versi terbaru.
5. Aplikasi berjalan secara lokal tanpa backend. Video YouTube pada materi 14 memerlukan internet.

FITUR UTAMA
- Landing page dan navigasi menu.
- Apersepsi interaktif.
- Enam tujuan pembelajaran.
- 14 halaman materi dengan aktivitas interaktif.
- Simulasi pasangan basa DNA dan transkripsi mRNA.
- Aktivitas kromosom, genotipe, fenotipe, ekspresi gen, dan golongan darah ABO.
- Simulasi persilangan monohibrid dan tabel Punnett dihibrid 4 x 4.
- Tiga laboratorium Virtual Biology Lab dengan total delapan stasiun.
- Genetic Puzzle: merakit pengemasan DNA dengan drag-and-drop; mengidentifikasi telomer, sentromer, dan kromatid melalui hotspot bertahap; mengeksplorasi gen dan alel dengan pilihan variabel.
- DNA Challenge: menyusun pasangan basa komplementer dengan drag-and-drop; menjalankan transkripsi DNA menjadi mRNA secara bertahap; mengklasifikasikan ciri DNA/RNA menggunakan dropdown.
- Mendel Master: mengubah genotipe kedua induk monohibrid melalui dropdown dan melihat tabel Punnett otomatis; mengatur jumlah keturunan dihibrid dengan slider untuk membandingkan hasil sampel dan rasio teoretis 9:3:3:1.
- Drag-and-drop mendukung mouse dan layar sentuh melalui Pointer Events. Alternatif tap-to-place tetap tersedia pada perangkat sentuh; slot perakitan juga dapat dioperasikan dengan keyboard.
- Setiap stasiun memiliki pemeriksaan otomatis, umpan balik, progres, dan kesimpulan hasil eksperimen.
- Dua mode praktikum: latihan tanpa batas waktu dan tantangan dengan timer.
- Penilaian praktikum berdasarkan ketepatan aktivitas, ketuntasan stasiun, konsistensi, dan efisiensi.
- Quiz 20 soal LOTS, MOTS, HOTS berbasis cerita, data, dan penalaran dengan timer 20 menit.
- Urutan 20 soal diacak setiap kali peserta memulai sesi baru dan tetap tersimpan selama sesi aktif.
- Area ilustrasi untuk setiap soal; jika gambar belum tersedia, placeholder menampilkan petunjuk dan nama file.
- Navigasi nomor soal dan penyimpanan jawaban selama sesi aktif.
- Hasil quiz, kunci jawaban, pembahasan, dan ekspor Excel XLSX.
- Musik instrumental lokal dengan tombol play/pause dan opsi memilih audio dari perangkat.
- Tema antarmuka biru modern, responsif untuk HP, tablet, laptop, dan komputer.
- Logo brand, favicon browser, dan ikon layar utama menggunakan aset SVG/PNG lokal yang dapat diganti.

TIGA LABORATORIUM DAN DELAPAN STASIUN
1. Genetic Puzzle
   - Stasiun 1: Merakit kemasan DNA - drag-and-drop / tap-to-place.
   - Stasiun 2: Identifikasi bagian kromosom - hotspot dan panduan langkah.
   - Stasiun 3: Gen atau alel - select dan visualisasi lokus.
2. DNA Challenge
   - Stasiun 1: Pasangan basa DNA - drag-and-drop / tap-to-place.
   - Stasiun 2: Transkripsi mRNA - step-by-step, putar otomatis, jeda, lanjut, dan reset.
   - Stasiun 3: Klasifikasi DNA/RNA - dropdown dengan umpan balik langsung.
3. Mendel Master
   - Stasiun 1: Persilangan monohibrid - select genotipe induk dan tabel Punnett otomatis.
   - Stasiun 2: Persilangan dihibrid - slider jumlah keturunan, simulasi acak, dan perbandingan rasio teoretis.

PENGGANTIAN ILUSTRASI SVG LABORATORIUM
Lihat assets/images/lab/README.txt. Delapan file SVG di folder tersebut dapat diganti tanpa mengubah JavaScript selama nama file dipertahankan:
- packaging.svg
- chromosome.svg
- gene-allele.svg
- dna-pairing.svg
- transcription.svg
- dna-rna.svg
- monohybrid.svg
- dihybrid.svg

SVG ilustrasi bersifat statis. Kontrol drag-and-drop, hotspot, dropdown, slider, dan tombol langkah tetap dibuat oleh aplikasi. Gunakan SVG mandiri dengan viewBox, tanpa script, iframe, font eksternal, atau URL internet.

PENGGANTIAN LOGO DAN FAVICON
Lihat assets/images/README.txt.
- assets/images/brand.svg: logo di header aplikasi.
- assets/images/favicon.svg: favicon utama untuk tab browser.
- assets/images/favicon-32.png: fallback favicon PNG 32 x 32.
- assets/images/apple-touch-icon.png: ikon layar utama perangkat Apple.
Pertahankan nama file agar aset pengganti langsung terbaca. Untuk logo/favicons, gunakan bentuk sederhana, kontras tinggi, dan latar yang sesuai.

PENYIMPANAN
Aplikasi memakai sessionStorage untuk menyimpan halaman aktif, jawaban quiz, dan progres sesi pada tab browser yang sama. Data tidak disinkronkan antarkomputer dan akan hilang ketika sesi/tab ditutup sesuai spesifikasi.

EKSPOR EXCEL
Ekspor XLSX dibuat secara lokal oleh aplikasi, tanpa CDN atau koneksi internet. File memiliki dua sheet: Rekap Nilai dan Detail Jawaban.

ILUSTRASI MATERI DAN QUIZ
Lihat assets/images/README.txt untuk nama file, lokasi, dan rekomendasi resolusi ilustrasi. Khusus gambar quiz, ikuti assets/images/quiz/README.txt. Jika gambar belum dimasukkan, aplikasi menampilkan ilustrasi SVG fallback atau placeholder.

CATATAN PENGGUNAAN
- Musik tidak otomatis diputar ketika halaman dibuka karena browser umumnya memerlukan tindakan pengguna. Tekan tombol Musik untuk memulai.
- Gunakan tombol Ganti Musik untuk memilih file audio dari perangkat.
- Timer quiz berjalan selama quiz aktif. Jika waktu habis, jawaban otomatis dikumpulkan.
- Pada mode tantangan, timer game berjalan mundur; mode latihan menggunakan pencatat waktu tanpa batas.
- Progres game dan quiz disimpan selama sesi aktif pada tab browser yang sama.
- Video YouTube di materi 14 membutuhkan koneksi internet.
- Untuk sinkronisasi nilai terpusat antarkomputer, diperlukan pengembangan backend terpisah. Fitur tersebut tidak termasuk versi offline ini.

VIDEO DAN PROFIL PENGEMBANG
- Materi 14: Pewarisan Sifat Manusia dilengkapi pemutar video YouTube di dalam halaman materi.
- Menu Profil Pengembang menampilkan slideshow empat orang, otomatis berganti setiap 7 detik.
- Slideshow memiliki tombol sebelumnya, berikutnya, indikator slide, serta jeda/lanjutkan.
- Petunjuk penggantian foto tersedia di assets/images/profiles/README.txt.
