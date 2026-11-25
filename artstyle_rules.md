\# Art Style Rules — Dragon Warrior: Super



\*\*Panduan personal project, diperbarui 25 November 2026.\*\* Satu dokumen mandiri untuk diberikan kepada AI/developer sebelum membuat aset, map, karakter, animasi, atau memperbaiki visual.



Dokumen ini merangkum arah yang sudah diminta pengguna. Instruksi terbaru pengguna mengungguli catatan lama. Angka ukuran di bawah adalah patokan implementasi saat ini, bukan standar universal untuk semua aset. Jangan menganggap membaca panduan ini sebagai perintah merombak game yang sudah ada.



\## 1. Identitas visual yang dipilih



\- Game desktop browser \*\*2D side-scroller\*\* bertema \*\*Dragon Ball Z klasik colorful\*\*.

\- Tampilan ilustrasi anime klasik: tinta jelas, warna cerah hangat, bayangan cel tegas, bentuk mudah dibaca, dan kedalaman berlayer.

\- Pertahankan konsistensi antara pemain, NPC, monster, bangunan, terrain, prop, proyektil, dan efek.

\- Jangan beralih ke gaya 3D/Xenoverse, material fotorealistis, pixel art, atau chibi berlebihan tanpa permintaan eksplisit pengguna.

\- Kedalaman dan volume boleh terasa kaya, tetapi bahasa visual tetap ilustrasi 2D klasik.

\- Perbaikan satu detail tidak boleh mengubah desain lain yang sudah diterima.



\## 2. Sumber aset: AI-generated dan reuse



1\. Artwork utama karakter, monster, terrain, background, prop, bangunan, dan efek menggunakan aset AI-generated yang cocok dengan gaya project.

2\. \*\*Utamakan aset AI lama yang sudah cocok.\*\* Map baru bukan alasan mengganti seluruh kit.

3\. Pohon, semak, batu, langit, dan tanah Bumi sudah tersedia; gunakan kembali kit Bumi yang dipakai area latihan dan Outer Red Ribbon.

4\. Jangan mengganti artwork utama dengan SVG, primitive Canvas, atau pola prosedural yang tampil berbeda dari ilustrasi game.

5\. Crop, resize, perbaikan alpha, stitching, recolor terkontrol, penempatan, bayangan kontak, parallax, dan transform animasi diperbolehkan untuk mengintegrasikan artwork.

6\. UI boleh memakai sistem kode yang sudah ada; aturan aset lingkungan bukan kewajiban membuat semua teks/tombol sebagai gambar.

7\. Simpan asal aset dan proses edit agar perbaikannya bisa diulang.

8\. \*\*Generated bukan jaminan bagus atau konsisten.\*\* Aset harus diperiksa sebelum dan sesudah masuk game.



\## 3. Referensi harmoni



| Keperluan | Acuan project |

| --- | --- |

| Harmoni warna, detail, dan kedalaman | Lembah Curam |

| Kit alam Bumi dan hubungan objek dengan tanah | Area latihan dan Outer Red Ribbon |

| Bangunan markas besar | Markas Outer Red Ribbon pada skala besar yang diterima |

| Interior militer | Lobby, gudang, aula, dan laboratorium RR yang sudah diterima, dengan koreksi skala terbaru |

| Kota | Tiga distrik Capsule City terbaru |

| Desain karakter tertentu | Referensi gambar pengguna dan aset terakhir yang diterima |



Contoh tersebut menjadi acuan konsep, bukan layout untuk ditiru 1:1. Cocokkan karya baru dengan kamera main dan aset tetangganya, bukan hanya berdasarkan nama gaya pada prompt.



\## 4. Palet, garis, dan pencahayaan



\- Langit: turquoise, cyan lembut, mint.

\- Dedaunan: jade, hijau lime hangat; bentuk rumpun membulat dan tinta terbaca.

\- Tanah: ochre hangat; batu: sandstone/warna tanah keemasan.

\- Bangunan: ivory, cream, teal/turquoise, terracotta, dengan aksen yang sesuai fungsi bangunan.

\- Bayangan: teal gelap atau cokelat hangat, terutama dalam satu–dua bidang cel utama.

\- Arah cahaya mengikuti scene/kit yang ada, umumnya dari kiri atas.

\- Latar jauh lebih pucat dan kurang kontras; karakter serta objek dekat lebih tegas.

\- Hindari tekstur foto, pori, serat kayu realistis, metal seperti render produk, bloom berlebihan, dan hitam pekat yang mendominasi lingkungan.

\- Seragam navy atau mesin gelap tetap boleh, dengan bentuk dan bayangan yang terbaca.

\- Identitas bioma boleh berbeda, tetapi teknik gambar, skala detail, dan pencahayaan harus tetap satu keluarga.



\## 5. Background wajib berlayer



Susun lapisan sesuai ruang dan fungsi map, misalnya:



```text

Langit → siluet/bukit jauh → kota/hutan jauh → layer tengah

→ bangunan dan prop → bidang karakter → foreground rendah

```



\- Jangan menyelesaikan sebuah map hanya dengan satu gambar background utuh.

\- Gambar utuh boleh menjadi bahan satu layer, lalu dilengkapi komposisi layer lain.

\- Parallax mengikuti kedalaman. Bangunan yang sejalur dengan pemain tidak boleh bergeser seperti latar jauh.

\- Periksa sambungan, pengulangan, tepi kosong, dan objek melayang sepanjang kamera bergerak.

\- Hutan harus cukup rapat, tetapi tidak menutup pemain, proyektil, pintu, atau trigger.

\- Background bambu tidak boleh terlalu jarang atau menggantung tanpa dasar yang masuk akal.

\- Kepadatan prop bukan tujuan sendiri: setiap objek harus membantu ruang terasa menyatu.



\### Urutan Capsule City yang berlaku sekarang



```text

Langit dan skyline jauh

→ trotoar sisi jauh + bangunan besar + pemain

→ boulevard di bawah jalur pemain + mobil terbang + zebra cross

→ trotoar dekat + sedikit pucuk pohon di tepi bawah layar

```



Ini \*\*menggantikan\*\* layout lama yang menaruh boulevard di belakang bangunan utama. Jangan mengambil aturan lama tersebut dari catatan historis.



\## 6. Skala: pemain menjadi pembanding tetap



\- Pemain remaja tetap sekitar 110 unit tinggi visual di semua map/state.

\- Jangan mengecilkan karakter saat lompat, terkena hit, memasuki interior, atau berpindah map.

\- Tentara dewasa/kekar harus jelas lebih besar daripada pemain, tidak semuanya diseragamkan setinggi pemain.

\- Patokan tentara lobby: sekitar 132 untuk varian bertopi dan 142 untuk varian berotot; Gohan sekitar 105 dengan anatomi kakek dewasa pendek, bukan bayi chibi.

\- Ukuran pintu, jendela, konsol, peti, ubin dan tangga membantu menilai skala manusia.

\- Interior luas tidak boleh terasa seperti semua karakter berubah menjadi mini. Perbaiki ukuran prop, bukan menyamarkan masalah dengan perubahan skala hero.

\- Rumah biasa, institusi kota, dan markas pusat punya kelas ukuran berbeda.

\- Bangunan besar yang sudah diminta boleh melampaui batas atas kamera, seperti markas RR dan institusi kota terbaru.

\- Untuk ruangan, kapsul penelitian, pilar, atau langit-langit tertentu boleh besar bila fungsinya masuk akal; pintu orang dan konsol tetap perlu pembanding manusia.



\## 7. Grounding dan terrain



\- Bangunan harus tertanam sedikit, tidak mengambang dan tidak tenggelam.

\- Nilai pijakan nyata dari alpha gambar, bukan hanya dimensi file atau titik pusat sprite.

\- Periksa alas kiri, tengah, kanan; pintu dan tangga harus terhubung dengan bidang pijakan.

\- Jangan memakai semak sebagai penutup kesalahan grounding.

\- Akar pohon, pondasi rumah, kaki menara, dan prop harus punya hubungan yang masuk akal dengan terrain.

\- Terrain memakai skala tekstur yang konsisten, sambungan rapi, dan permukaan berjalan yang terbaca.

\- Jangan memakai tekstur sisi tebing sebagai permukaan jalan.

\- Pijakan visual, hitbox terrain, dan posisi kaki karakter harus selaras.

\- Shadow kontak boleh membantu, tetapi tidak menggantikan koreksi posisi.



\## 8. Aturan map terbaru



\### Outer Red Ribbon



\- Markas mempertahankan desain AI yang ada dan skala besar yang diterima: tinggi 1120, sekitar dua kali versi sebelumnya.

\- Atap boleh melampaui layar; alas tetap tertanam.

\- Patokan pusat/pintu luar 1994, checkpoint 1100 di kiri fasad; bila layout berubah, pintu visual dan trigger harus tetap sejajar.

\- Bendera di atap berkibar, tidak berdiri terpisah di tanah.

\- Lobby mempunyai penanda keluar menuju Outer Red Ribbon dan robot dekoratif ber-LED EXIT yang menunjuk ke bawah.



\### Persimpangan



\- Map damai penghubung, dengan kota jauh terlihat di balik pohon.

\- Jalan cabang berupa tanah hutan yang menyatu dengan kit Bumi.

\- Jalan tampak lurus turun ke bawah terrain dari high ground menuju low ground; jangan membentang naik ke langit.

\- Rambu kiri/kanan/atas tetap terbaca. Kontrol akses kota mengikuti sistem yang sudah ada.



\### Hutan Karin



\- Kaki Menara Karin tertanam di tanah; menara menjulang melewati atas layar sehingga puncaknya tidak terlihat.

\- Hutan, rumah suku Karinga, dan prop memakai bahasa visual Bumi yang sama.

\- Dua varian penjaga bertombak tetap mempertahankan identitas dan skala pada semua state.



\### Tiga distrik Capsule City



| Map | Bangunan utama | Patokan tinggi visual saat ini |

| --- | --- | --- |

| Center Capsule City | Capsule Corp; kantor polisi | 820; 620 |

| Capsule City Barat | Spaceport; pesawat mendarat | 560; 260 |

| Capsule City Timur | Rumah Mr. Satan; restoran | 820; 520 |



\- Budokai sudah dihapus dari kota; jangan muncul kembali tanpa permintaan baru.

\- Pertahankan desain bangunan yang diterima; perubahan skala/relokasi tidak berarti menggambar ulang semuanya.

\- Pemain berjalan di trotoar sisi jauh boulevard. Bidang pijakan kota saat ini y430, sementara skala pemain tetap.

\- Skyline membentang sepanjang rute, bukan kota kecil sebagai satu prop.

\- Pucuk pohon Bumi hanya sedikit masuk dari bawah layar dan sisanya tenggelam keluar frame.

\- Zebra cross di Center menandai akses kembali ke Persimpangan; penanda trigger di atas tetap ada.

\- Spaceport memakai pintu kaca ganda, bukan lubang pintu hitam kosong.

\- Mobil adalah mobil terbang tanpa roda. Patokan tinggi dekat 96 dan jauh 82 terhadap pemain 110; jangan kembali ke ukuran mini 51/43.

\- Mobil melesat cepat; maksimal satu per arah, dua total per map, dengan jeda sebelum berikutnya.

\- Jalur jauh bergerak ke kiri pada sisi jauh jalan dan lebih tinggi daripada jalur dekat.



\## 9. Identitas karakter dan monster



\### Pemain



\- Rambut, kepala, warna pakaian, proporsi dan skala stabil antar-state.

\- Pose terkena hit: kedua lutut tertekuk seperti melompat, kedua lengan menyilang melindungi wajah.

\- Memperbaiki rambut tidak boleh mengganti pose seluruh tubuh.

\- Tidak boleh ada double head atau kepala yang terlepas, termasuk pada bentuk hantu saat mati.



\### Kakek Gohan



\- Kakek dewasa pendek kekar, topi hijau dengan pompom putih, kumis putih lebar.

\- Rompi oranye bermotif cincin kuning, lengan gelap, manset putih; \*\*tanpa halo\*\*.

\- Hindari proporsi kepala bayi/chibi.

\- Idle tenang dan stabil; hadap mengikuti posisi pemain kiri/kanan.



\### Rabbit Gang



\- Manusia berseragam, bukan kelinci antropomorfik bergaya Warner Bros.

\- Helm taupe dengan telinga kain hitam, kacamata biru, mantel navy, epaulet merah, emblem kelinci, ban lengan, alas kaki putih.

\- Ada varian gemuk dan kurus; keduanya tetap menyatu dengan proporsi karakter game.



\### Manusia Red Ribbon



\- Wajah dewasa bervariasi: rahang, hidung, usia, rambut/topi, lebar bahu, dan cara memakai seragam.

\- Jangan semua berwajah generik seperti Krillin kecil.

\- Variasi infanteri dan awak tank tetap dibedakan; awak tank botak sesuai arah yang diminta.

\- Otot dibaca lewat anatomi/siluet dan cel shadow, bukan tekstur kulit realistis.

\- General Blue dan Cyborg Tao mempertahankan ciri lore/referensi serta desain terakhir yang diterima; pose bela diri mengikuti aturan serangan dan guard yang sudah diminta.



\### Penjaga Karin



\- Hit biasa harus recoil tegak, bukan salto atau pose terbalik.

\- Pada atlas saat ini digunakan frame 3 dengan pivot kaki broad 228/scout 277. Angka ini hanya berlaku untuk atlas tersebut; inspeksi ulang bila sumber atlas berubah.



\## 10. Animasi dan efek



\- Ukuran, pivot, titik kaki, arah hadap, hitbox dan muzzle harus mengikuti transform yang sama.

\- Kecepatan animasi berjalan mengikuti laju perpindahan sebenarnya, terutama tentara yang berjalan lambat.

\- Jangan memperlihatkan dua hit saat mekanisme serangannya hanya satu kontak tanpa alasan animasi yang jelas.

\- Seluruh monster saat mati: terpental, memantul tiga kali, berkedip, lalu hilang; berlaku juga untuk robot dan tank.

\- Pose recoil dapat dikunci selama gerak pantulan. Hit biasa tidak boleh memakai pose salto kematian.

\- Proyektil keluar dari ujung senjata/tangan yang benar. Robot mengangkat satu tangan saat menembakkan rudal.

\- Bendera berkibar dari tiang/atap; pangkal kain tetap melekat.

\- Baling-baling helikopter berputar; roda/rantai tank, getaran mesin, dan asap bergerak sesuai fungsi.

\- Ledakan granat, rudal, listrik, ki, trace pukulan, dan debu mengikuti DBZ colorful klasik, bukan efek stok realistis.

\- Ledakan harus terbaca sesuai area serangan; jangan membuatnya sangat kecil dibanding hitbox.

\- Transparansi bersih: tanpa kotak samar, halo, pinggiran warna latar, atau bagian subjek yang hilang.

\- Kepulan debu/asap berkurang dengan opacity dan hilang; jangan berhenti sebagai tempelan statis.

\- VFX tidak boleh menutupi informasi penting seperti posisi pemain, musuh, jalur menghindar dan penanda serangan.



\## 11. Penanda map dan UI visual



\- \*\*Nama tujuan dan penanda trigger map di atas wajib dipertahankan\*\* ketika pemain dekat akses.

\- Rambu fisik tidak menggantikan penanda trigger UI.

\- Tulisan info kecil yang diminta dihapus tidak sama dengan penanda tujuan map.

\- Center City memakai arah kiri/kanan/bawah; Persimpangan kiri/kanan/atas. Jangan memberi arah yang tidak punya akses.

\- Robot EXIT tetap prop dekoratif, tidak mengubah sistem combat.

\- UI mengikuti gaya existing dan tidak mengganggu jalur permainan.

\- Cover menggunakan cuplikan nyata game sebagai acuan bila diminta, lalu boleh dipoles AI; jangan menganggap cover sebagai perubahan layar judul atau gameplay.



\## 12. Workflow sebelum dan setelah generate



1\. Baca permintaan terbaru, panduan ini, dan kode/aset yang terkait.

2\. Tentukan map pembanding yang sudah diterima dan inventaris aset yang bisa dipakai ulang.

3\. Pisahkan kebutuhan artwork baru dari masalah integrasi seperti crop, skala, urutan layer, dan pivot.

4\. Tentukan tujuan aset, arah kamera, sudut pandang, ukuran relatif, titik pijakan, serta kebutuhan transparansi sebelum membuat prompt.

5\. Gunakan referensi visual nyata jika alat mendukungnya; jangan mengklaim gambar menjadi input apabila hanya dideskripsikan lewat teks.

6\. Periksa hasil gambar: identitas, garis, palet, cahaya, anatomi, detail, alpha dan footprint.

7\. Masukkan ke game dan bandingkan dengan pemain serta tetangganya dalam kamera main.

8\. Periksa pintu/alas, sisi kiri–kanan objek, titik masuk, tengah, dan ujung map yang terdampak.

9\. Untuk animasi, amati beberapa frame dan transisi state dengan input nyata; screenshot diam tidak cukup.

10\. Perbaiki sumber masalah yang terbukti, lalu periksa kembali area terdampak.

11\. Catat perubahan dan batas pemeriksaan. Hasil generate/build bukan persetujuan kualitas visual.



\## 13. Template prompt gaya



Gunakan sebagai kerangka; isi bagian objek dan komposisi secara spesifik. Template bukan pengganti referensi atau inspeksi.



```text

STYLE:

Classic colorful Dragon Ball Z 1990s hand-painted cel anime art,

clean dark ink outlines, crisp one or two main cel-shadow levels,

warm ivory, turquoise/teal, terracotta and ochre palette,

consistent daylight from upper left, readable shapes,

flat 2D side-scrolling game illustration.



SUBJECT:

\[Objek/karakter yang diperlukan, identitas dan ciri referensinya.]



COMPOSITION:

\[Sudut kamera yang cocok dengan game, arah hadap, ruang gerak,

ukuran relatif terhadap pemain, footprint/pijakan, layer tujuan.]



INTEGRATION:

\[Subjek utuh dengan margin; cutout bila perlu;

untuk bangunan semua dasar berada pada bidang yang sesuai;

untuk background jelaskan hanya layer yang sedang dibuat.]



AVOID:

Photorealism, glossy 3D render, excessive chibi proportions,

inconsistent character anatomy, disconnected foundations,

baked scenery on an isolated prop, opaque background boxes,

unrelated props, unintended text, excessive tiny detail.

```



Untuk animasi, tambahkan identitas yang harus tetap, pose awal/aksi/akhir, kaki/pivot, senjata/muzzle dan kontak serang. Gunakan spesifikasi atlas sebenarnya dari hasil alat; jangan menebak grid atau jumlah frame.



\## 14. Checklist penerimaan visual



\- \[ ] Gaya DBZ klasik colorful konsisten dengan aset sekitar.

\- \[ ] Kit lama digunakan kembali bila sudah sesuai.

\- \[ ] Warna, garis, detail dan cahaya cocok di kamera main.

\- \[ ] Skala pemain stabil dan ukuran objek masuk akal terhadapnya.

\- \[ ] Bangunan, pohon, menara dan prop menapak pada terrain.

\- \[ ] Background berlayer, parallax rapi, tidak ada sambungan kosong/melayang.

\- \[ ] Urutan jalan/bangunan kota memakai keputusan terbaru.

\- \[ ] Rambut, wajah, kepala, pakaian dan tubuh konsisten antar-state.

\- \[ ] Pose hit benar; kematian memakai pantulan dan kedip yang diminta.

\- \[ ] Kecepatan animasi sesuai gerak aktual.

\- \[ ] Muzzle, proyektil, hitbox dan area efek selaras secara visual.

\- \[ ] Alpha bersih tanpa kotak/halo atau potongan subjek hilang.

\- \[ ] Portal, pintu dan penanda tujuan tetap terbaca.

\- \[ ] Pengujian mencakup map/state yang diubah, bukan hanya loading.

\- \[ ] Hal yang belum diamati dilaporkan sebagai belum diuji.



\## 15. Instruksi siap salin untuk developer/AI



> Pertahankan Dragon Warrior: Super sebagai game 2D side-scroller dengan art style Dragon Ball Z klasik colorful. Gunakan artwork AI yang harmonis; utamakan kit/aset lama yang sudah cocok. Jangan mengganti artwork utama dengan SVG/primitive. Lembah Curam adalah acuan harmoni, area latihan dan Outer RR acuan kit Bumi. Jaga skala pemain, grounding, layer, identitas karakter dan pose animasi. Ikuti tata letak tiga distrik Capsule City terbaru: bangunan serta pemain di trotoar jauh, boulevard di bawah, pucuk pohon di tepi bawah. Penanda trigger map tetap wajib. Periksa hasil generate, lalu inspeksi dalam kamera permainan dan uji gerak yang terkait. Jangan menganggap hasil alat otomatis berkualitas, jangan mengubah sistem lain di luar permintaan, dan laporkan keterbatasan verifikasi dengan jujur.



