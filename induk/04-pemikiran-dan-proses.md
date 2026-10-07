# 04 — Pemikiran & proses

[Kembali ke indeks](../README.md)

## Maksud induk

Induk ini menjelaskan bagaimana kamu bergerak dari masalah menuju solusi. Pembaca melihat kemampuan memahami keadaan, menggunakan informasi, menimbang pilihan, mengambil keputusan, dan memperbaiki hasil. Proses yang ditampilkan harus berasal dari pekerjaan aktual, bukan urutan ideal yang ditempel setelah pekerjaan selesai.

Pemikiran adalah alasan di balik tindakan. Proses adalah rangkaian tindakan dan pemeriksaannya. Menyebut “riset → desain → implementasi → testing” belum menjelaskan pemikiran jika tidak ada temuan, pilihan, dan konsekuensi yang nyata.

Case study merupakan wadah utama untuk induk ini, tetapi juga memuat konteks karya, hasil, serta bukti. Tidak semua proyek memerlukan case study panjang.

## Isi yang tercakup

1. **Masalah awal:** keadaan yang perlu diperbaiki; siapa yang mengalaminya dan dari mana masalah diketahui.
2. **Tujuan dan kriteria keberhasilan:** perubahan yang dituju dan cara menilai tercapainya.
3. **Konteks dan constraint:** waktu, biaya, perangkat, bahan, tim, dependensi, batas teknis, atau kebutuhan akses yang relevan.
4. **Peran dan kewenangan:** keputusan yang boleh diambil sendiri dan yang memerlukan kesepakatan pihak lain.
5. **Informasi awal:** data, observasi, brief, sumber, atau asumsi yang digunakan.
6. **Pilihan solusi:** alternatif yang sungguh dipertimbangkan; tidak perlu mengarang alternatif agar cerita terlihat matang.
7. **Keputusan penting:** pilihan yang mengubah arah atau mutu pekerjaan beserta alasannya.
8. **Pelaksanaan:** bagaimana keputusan diwujudkan menjadi karya.
9. **Pemeriksaan dan iterasi:** apa yang diuji, ditemukan, lalu diubah.
10. **Pembelajaran dan pekerjaan tersisa:** apa yang diketahui sekarang, apa yang belum pasti, dan perubahan berikutnya yang beralasan.

## Menjelaskan keputusan

Gunakan hubungan: keadaan → pilihan → alasan → konsekuensi → pemeriksaan. Alasan sebaiknya spesifik pada proyek. “Lebih modern” tidak cukup jika tidak menjelaskan manfaat terhadap kebutuhan.

Contoh hipotetis: informasi produk pada daftar terlalu padat. Dua pilihan yang dipertimbangkan adalah menampilkan semua spesifikasi atau menampilkan ringkasan dan menyediakan halaman detail. Ringkasan dipilih agar daftar lebih mudah dipindai. Konsekuensinya, sebagian informasi membutuhkan satu langkah tambahan. Pemeriksaan berikutnya melihat apakah pengguna masih bisa menemukan spesifikasi penting.

Ini menjelaskan tradeoff: manfaat yang diperoleh bersama biaya atau keterbatasannya. Keputusan yang baik tidak harus menghilangkan semua kompromi.

## Status pengetahuan dalam cerita

| Jenis | Cara menuliskan |
| --- | --- |
| Fakta | Sebut sumber atau artefak yang mendukungnya. |
| Observasi | Jelaskan apa yang diamati dan pada konteks apa. |
| Asumsi | Nyatakan sebagai dugaan kerja yang belum diperiksa. |
| Keputusan | Sebut pilihan dan alasan saat keputusan diambil. |
| Interpretasi | Pisahkan kesimpulanmu dari data yang tersedia. |
| Pembelajaran setelah proyek | Jelaskan sebagai refleksi, bukan alasan yang seolah sudah diketahui sejak awal. |

Jika tidak ada riset pengguna, tulis demikian dan jelaskan dasar lain yang digunakan. Jika pemeriksaan hanya dilakukan sendiri, jangan menyebutnya validasi pengguna. Ketiadaan pengujian tertentu dapat menjadi batas, bukan alasan mengarang tahap yang tidak pernah terjadi.

## Memilih kedalaman

Pada preview proyek, cukup tampilkan satu masalah dan satu keputusan utama. Pada case study, jelaskan beberapa keputusan yang paling menentukan, artefak pendukung, dan hasil pemeriksaan. Catatan detail dapat menjadi lampiran bila dibutuhkan.

Jangan memasukkan semua screenshot proses. Setiap artefak harus membantu pembaca memahami keputusan atau perubahan. Diagram tanpa penjelasan hubungan terhadap masalah tidak otomatis menjadi bukti kedalaman.

Untuk kerja tim, jelaskan siapa mengambil keputusan, bagaimana kontribusimu memengaruhinya, dan bagian yang bukan kewenanganmu. Untuk proyek kecil, proses sederhana yang dijelaskan jujur sudah memadai.

## Contoh ringkas hipotetis

“Tujuan prototipe adalah memudahkan pemeriksaan informasi produk. Saya mengelompokkan spesifikasi berdasarkan kegunaan karena daftar awal tidak memiliki hierarki. Setelah pemeriksaan mandiri, label kategori diperjelas agar tidak memakai istilah internal. Belum ada pengujian pengguna, sehingga klaim kemudahan penggunaan masih perlu diperiksa.”

## Kesalahan umum

- Menulis proses sebagai ritual yang sama untuk semua proyek.
- Menampilkan hanya hasil akhir tanpa keputusan yang menjelaskan kualitasnya.
- Mengarang wawancara, iterasi, atau alternatif yang tidak pernah dilakukan.
- Menyembunyikan constraint sehingga solusi terlihat lebih bebas daripada keadaan sebenarnya.
- Menggunakan refleksi setelah proyek sebagai alasan awal secara retrospektif.

## Cukup kuat ketika

Pembaca memahami alasan di balik keputusan penting dan dapat melihat hubungan antara masalah, tindakan, pemeriksaan, dan hasil. Ada batas yang jelas antara fakta, asumsi, dan pembelajaran.

Gunakan [template case study](../templates/case-study.md), lalu hubungkan dengan [karya](03-karya-dan-kontribusi.md), [hasil](05-hasil-dan-dampak.md), dan [bukti](08-kredibilitas-dan-bukti.md).
