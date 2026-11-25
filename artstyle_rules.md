---
name: dragon-warrior-art-direction
description: Jaga konsistensi visual Dragon Warrior Super saat merancang, mencari, menghasilkan, menganimasikan, mengganti, mengintegrasikan, atau menilai karakter, NPC, monster, boss, robot, map, terrain, props, UI dan VFX. Gunakan juga untuk keluhan ukuran, arah hadap, siluet kurus, idle, chibi, dan percampuran gaya. Tidak diperlukan untuk perubahan logika yang tidak memengaruhi visual.
---

# Art direction Dragon Warrior

Pertahankan satu fingerprint colorful cartoon DBZ berdasarkan aset Earth yang dirujuk pengguna. Perlakukan keselarasan sebagai syarat penerimaan, bukan pemolesan opsional setelah pemasangan.

## Mulai dari bukti

1. Baca `AGENTS.md`, `docs/spec.md`, dan `docs/artstyle_rules.md` dari akar proyek. Ikuti koreksi pengguna terbaru jika berbeda dengan aturan lama. Jangan menganggap lore DBZ sebagai spesifikasi visual yang cukup.
2. Baca [DNA visual](references/visual-dna.md). Buka gambar acuan asli dan lihat implementasi saat ini; jangan menilai dari nama berkas atau prompt. Bedakan acuan pengguna, variasi yang ditoleransi, kandidat, dan aset yang dikritik.
3. Gunakan skill rendering/media/UI/playtest yang sesuai untuk pelaksanaan teknis. Skill ini menentukan standar artistik; jangan menggantikan aturan alat, izin, atau pemeriksaan runtime.

## Kerjakan satu keluarga visual

1. Salin [brief aset](assets/asset-brief.md) ke dokumen kerja di `reports/`. Isi peran, referensi positif/negatif, ukuran terlihat, massa tubuh, pose, kamera, dan fingerprint yang harus tetap sama. Jangan meminta pengguna menetapkan angka rutin; ukur acuan dan buat keputusan yang beralasan.
2. Buat atau pilih satu pose netral representatif sebelum produksi banyak animasi/varian. Sertakan gambar acuan yang benar pada alat yang mendukungnya. Gunakan nama karakter untuk identitas, lalu instruksi visual konkret untuk gaya.
3. Jalankan [pemeriksaan penerimaan](references/acceptance.md) pada sumber dan komposit dengan lingkungan asli sebelum menghubungkan kandidat ke jalur permainan aktif. Simpan hasil pada [catatan review](assets/asset-review.md).
4. Jika gagal, bedakan masalah gambar sumber dari pemotongan atlas, skala runtime, pivot, flip, atau pencahayaan. Perbaiki penyebabnya. Jangan menutupi desain kurus dengan stretch horizontal atau kesalahan gaya dengan filter warna.
5. Setelah pose netral selaras, buat animasi/varian dengan identitas, volume, kostum, dan rendering terkunci. Periksa seluruh frame serta gerakan nyata; jangan menyimpulkan gerakan bagus dari satu screenshot.
6. Integrasikan kandidat yang lolos pemeriksaan visual awal, lalu nilai pada kamera permainan sebenarnya. Jika pemeriksaan runtime belum tersedia, tandai belum terverifikasi dan jangan menyebutnya selesai atau acuan baru. Pertahankan aset lama yang valid sampai pengganti layak.

## Putuskan dan simpan

- Nilai setiap dimensi secara terpisah: cocok, gagal, atau belum terverifikasi. Jangan menjumlahkan skor untuk meloloskan kegagalan besar.
- Ambil keputusan artistik rutin sendiri berdasarkan arahan yang sudah ada. Skill ini tidak mewajibkan persetujuan pengguna untuk setiap aset. Tanyakan hanya keputusan arah baru yang benar-benar belum terjawab.
- Catat bukti dan keterbatasan secara jujur. Kelulusan teknis, keberhasilan generasi, dan penilaian agen bukan persetujuan artistik pengguna.
- Jangan ubah referensi utama menjadi hasil generasi terbaru hanya karena terlihat lebih detail. Perubahan fingerprint memerlukan arahan restyle pengguna yang eksplisit.
- Gunakan [pelajaran profesional](references/research.md) untuk alasan desain, bukan sebagai alasan mengadopsi estetika game lain.
