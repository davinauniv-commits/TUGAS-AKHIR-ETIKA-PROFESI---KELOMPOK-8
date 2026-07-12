# Laporan Etika Profesi Teknologi Informasi
## Analisis Kasus Tesla Autopilot & Full Self-Driving (FSD)

---

# HEADER PEMETAAN 

## Informasi Kelompok

| Keterangan        | Isi |
|-------------------|-----|
| **Nama Kelompok** | Kelompok 8 |
| **Kasus** | Analisis Etika Profesi pada Kasus Tesla Autopilot & Full Self-Driving (FSD) |
| **Fokus Analisis** | Sejumlah kecelakaan terkait Autopilot. Fokus: batas tanggung jawab engineer vs user, overclaiming kapabilitas, safety-critical software ethics |

---

## Anggota Kelompok

| No | Nama | NPM | Tugas |
|----|------|-----|--------|
| 1 | Nailah AlyaCalista Salsabill | 4524210075 | Pembagian Tugas |
| 2 | Okta Yudha Ramadhan | 45242210079 | Pembagian Tugas|
| 3 | Raudha Hafsha Aqila | 4524210123 |Pembagian Tugas |
| 4 | Davina Arthamevia Azahra | 4524210127 | Pembagian Tugas |
| 5 | Refani Usman | 4524210144 | Pembagian Tugas |

---

## Header Pemetaan Sub-CPMK

| Sub-CPMK | Capaian Pembelajaran | Bagian Laporan |
|-----------|----------------------|----------------|
| **Sub-CPMK 1** | Analisis dilema etika dengan teori filsafat moral dan kode etik profesi | BAB IV (Analisis Empat Teori Etika), BAB VI (ACM Code of Ethics & IEEE Code of Ethics) |
| **Sub-CPMK 2** | Evaluasi kepatuhan terhadap regulasi hukum, HKI, dan standar industri | BAB VII (Analisis Regulasi dan Hukum), BAB VI (Standar ACM & IEEE), BAB IX (ISO 31000) |
| **Sub-CPMK 3** | Analisis dampak sosial dan lingkungan dengan kerangka keberlanjutan | BAB X (Dampak terhadap Masyarakat dan Industri), BAB III (Analisis Stakeholder) |
| **Sub-CPMK 4** | Evaluasi risiko etis menggunakan kerangka analisis risiko ISO 31000 | BAB IX (Manajemen Risiko ISO 31000 dan Opsi 4T) |
| **Sub-CPMK 5** | Analisis potensi penyalahgunaan kewenangan, integritas, dan tindak pidana korupsi | BAB VIII (Checkpoint Integritas dan Anti Korupsi) |
| **Sub-CPMK 7** | Perumusan strategi mitigasi risiko etika dan kontrol preventif | BAB IX (Opsi 4T), BAB X (Kontrol Preventif dan Rekomendasi) |
| **Sub-CPMK 8** | Demonstrasi hasil investigasi dalam forum profesional | Video Presentasi YouTube (Unlisted) dan Slide Presentasi |
| **Sub-CPMK 9** | Refleksi prinsip etika ke dalam rencana integritas karier (individu) | BAB XI (Pelajaran Utama, Refleksi, dan Kesimpulan) |

---

## Video Presentasi



---

#  Deskripsi

Repository ini berisi laporan analisis mengenai kasus **Tesla Autopilot dan Full Self-Driving (FSD)** berdasarkan perspektif Etika Profesi Teknologi Informasi.
Analisis dilakukan menggunakan teori etika, kode etik profesi ACM dan IEEE, nilai-nilai Pancasila, regulasi hukum, serta manajemen risiko ISO 31000.

---

# Daftar Isi

- BAB I Kronologi dan Konteks
- BAB II Fakta Kunci dan Catatan Transparansi
- BAB III Pemetaan Pemangku Kepentingan
- BAB IV Analisis Empat Teori Etika
- BAB V Lensa Pancasila
- BAB VI Kode Etik Profesi
- BAB VII Analisis Regulasi dan Hukum
- BAB VIII Checkpoint Integritas dan Anti Korupsi
- BAB IX Manajemen Risiko dan Opsi 4T
- BAB X Dampak dan Kontrol Preventif
- BAB XI Pelajaran Utama
- Daftar Pustaka

---

# Tujuan

- Menganalisis kasus Tesla Autopilot berdasarkan etika profesi.
- Mengidentifikasi stakeholder yang terlibat.
- Mengkaji kasus menggunakan teori etika.
- Menganalisis penerapan nilai Pancasila.
- Mengevaluasi kepatuhan terhadap ACM dan IEEE Code of Ethics.
- Mengkaji aspek hukum dan regulasi.
- Menyusun analisis risiko menggunakan ISO 31000.
- Memberikan rekomendasi teknis dan etis.

---

# BAB I — Kronologi dan Konteks

## 1.1 Latar Belakang

Tesla, Inc. adalah perusahaan kendaraan asal Amerika Serikat yang didirikan pada tahun 2003 oleh Martin Eberhard dan Marc Tarpenning. Tesla dikenal sebagai salah satu pelopor inovasi mobil listrik serta penerapan teknologi kecerdasan buatan di sektor otomotif.

Salah satu inovasi Tesla adalah **Autopilot** dan **Full Self-Driving (FSD)**, yaitu sistem Bantuan Pengemudi Canggih yang dirancang untuk membantu pengemudi melalui berbagai fitur seperti **Traffic-Aware Cruise Control**, **Autosteer**, **Automatic Emergency Braking**, berpindah jalur otomatis, mengenali tanda lalu lintas, serta membantu proses parkir. Meskipun memiliki berbagai fitur canggih, menurut **Society of Automotive Engineers (SAE)** sistem ini masih berada pada **Level 2 Automasi Berkendara**, sehingga pengemudi tetap bertanggung jawab penuh terhadap pengendalian kendaraan.

Kasus Tesla Autopilot menjadi contoh penting dalam pembahasan rekayasa perangkat lunak dan etika profesi karena berbagai insiden yang melibatkan kendaraan Tesla menimbulkan pertanyaan mengenai keamanan sistem, tanggung jawab perusahaan, serta perilaku pengguna. Kasus ini juga menunjukkan bahwa pengembangan perangkat lunak tidak hanya berfokus pada inovasi, tetapi juga harus mengutamakan keselamatan pengguna, keterbukaan informasi, serta tanggung jawab profesional. Oleh karena itu, setiap proses pengembangan, pengujian, hingga penerapan sistem harus dilakukan secara teliti agar risiko terhadap keselamatan pengguna dapat diminimalkan.

### 1.2 Kronologi Kejadian

Penyelidikan mengenai Tesla Autopilot dimulai setelah serangkaian kecelakaan yang terjadi di berbagai wilayah Amerika Serikat. Salah satu peristiwa yang paling mendapat perhatian terjadi pada tahun 2021 ketika kendaraan Tesla dengan fitur Autopilot menabrak kendaraan darurat yang sedang berhenti di tepi jalan. Insiden serupa juga terjadi di beberapa negara bagian lainnya, seperti Florida, California, Michigan, dan Utah.

Pada **Agustus 2021**, **National Highway Traffic Safety Administration (NHTSA)** secara resmi memulai penyelidikan terhadap sistem Autopilot Tesla dengan mengevaluasi laporan kecelakaan, data kendaraan, serta cara kerja sistem untuk mengetahui apakah terdapat kelemahan dalam mendeteksi kendaraan yang berhenti dan apakah sistem pemantauan pengemudi telah bekerja secara efektif.

Hasil penyelidikan menunjukkan bahwa pada beberapa kasus pengemudi terlalu mengandalkan sistem Autopilot, sementara mekanisme pemantauan pengemudi dinilai belum cukup efektif. Sebagai tindak lanjut, pada **Desember 2023** Tesla melakukan pembaruan perangkat lunak terhadap lebih dari dua juta kendaraan untuk meningkatkan sistem pemantauan pengemudi dan membatasi penggunaan Autopilot pada kondisi tertentu. Hingga tahun **2025**, penyelidikan masih berlanjut dengan fokus pada kemampuan sistem **Full Self-Driving (FSD)** dalam menghadapi berbagai kondisi jalan, cuaca, dan visibilitas.

### 1.3 Konteks Teknis

Autopilot dan **Full Self-Driving (FSD)** bekerja dengan memanfaatkan kamera, sensor kendaraan, GPS, serta kecerdasan buatan. Data dari kamera diproses menggunakan algoritma *Machine Learning* untuk mengenali kendaraan lain, pejalan kaki, marka jalan, lampu lalu lintas, dan berbagai objek di sekitar kendaraan. Berdasarkan data tersebut, sistem dapat membantu mengendalikan arah kendaraan, mengatur kecepatan, melakukan pengereman otomatis, serta menjaga kendaraan tetap berada di jalur yang benar.

Pada versi terbaru, Tesla menggunakan pendekatan **Tesla Vision** yang lebih mengandalkan kamera dibandingkan radar. Meskipun menggunakan teknologi modern, Autopilot dan FSD masih termasuk dalam **SAE Level 2 Driving Automation**, sehingga pengemudi tetap harus memperhatikan kondisi jalan dan siap mengambil alih kendali kapan saja.

Menurut hasil penyelidikan **NHTSA**, terdapat beberapa faktor yang diduga menjadi penyebab kecelakaan, seperti keterbatasan sistem dalam mengenali kendaraan darurat pada kondisi tertentu, kurang optimalnya sistem pemantauan perhatian pengemudi, serta kecenderungan sebagian pengguna yang terlalu bergantung pada Autopilot. Perpaduan antara keterbatasan teknologi dan faktor manusia menjadi fokus utama dalam penyelidikan.

---

# BAB II — Fakta Kunci dan Transparansi

## 2.1 Fakta Terverifikasi

Tesla mengembangkan sistem bantuan mengemudi **Autopilot** dan **Full Self-Driving (FSD)** untuk meningkatkan kenyamanan dan keamanan berkendara. Meskipun memiliki kemampuan yang cukup maju, kedua sistem tersebut masih termasuk dalam **Level 2 Driving Automation**, sehingga pengemudi tetap harus memantau kendaraan dan siap mengambil alih kendali kapan pun diperlukan.

Pada **Agustus 2021**, **National Highway Traffic Safety Administration (NHTSA)** resmi memulai investigasi terhadap sistem Autopilot setelah menerima laporan mengenai beberapa kecelakaan yang melibatkan kendaraan Tesla, terutama tabrakan dengan kendaraan darurat yang berhenti di tepi jalan. Penyelidikan dilakukan untuk menilai kemampuan sistem dalam mengenali objek di jalan serta mengevaluasi efektivitas pemantauan perhatian pengemudi.

Pada **Desember 2023**, Tesla melakukan pembaruan perangkat lunak terhadap lebih dari dua juta kendaraan untuk meningkatkan sistem pemantauan pengemudi, memperkuat peringatan saat perhatian pengemudi menurun, serta membatasi penggunaan Autopilot pada kondisi tertentu. Hingga tahun **2025**, NHTSA masih melanjutkan penyelidikan guna mengevaluasi efektivitas pembaruan tersebut.

## 2.2 Informasi yang Masih Dalam Investigasi

Meskipun beberapa informasi telah dikonfirmasi, masih terdapat beberapa hal yang belum memperoleh keputusan akhir dari pihak regulator. Salah satunya adalah apakah seluruh kecelakaan yang melibatkan Tesla Autopilot disebabkan oleh masalah pada sistem atau dipengaruhi oleh faktor lain, seperti kondisi jalan, cuaca, maupun perilaku pengemudi.

NHTSA juga masih mengevaluasi efektivitas pembaruan perangkat lunak yang dirilis Tesla pada akhir tahun 2023 karena masih ditemukan laporan kecelakaan setelah pembaruan tersebut diterapkan. Selain itu, proses penyelidikan juga menilai apakah desain antarmuka dan sistem peringatan Tesla sudah cukup efektif untuk memastikan pengemudi tetap memperhatikan kondisi jalan saat menggunakan fitur bantuan mengemudi.

Hingga saat ini, belum ada keputusan akhir yang menyatakan adanya kesalahan teknis tertentu sebagai penyebab utama dari seluruh kecelakaan yang terjadi.

## 2.3 Catatan Transparansi

| Jenis Informasi | Pernyataan | Status |
|-----------------|------------|--------|
| **Fakta** | NHTSA memulai penyelidikan resmi terhadap Autopilot Tesla pada Agustus 2021 setelah serangkaian kecelakaan yang melibatkan kendaraan darurat. | Telah dikonfirmasi melalui laporan resmi NHTSA. |
| **Fakta** | Tesla melakukan pembaruan perangkat lunak pada Desember 2023 terhadap lebih dari dua juta kendaraan untuk meningkatkan sistem pemantauan pengemudi. | Didukung oleh pengumuman resmi Tesla dan NHTSA. |
| **Fakta** | Hingga tahun 2025, NHTSA masih mengevaluasi efektivitas pembaruan perangkat lunak Tesla. | Berdasarkan dokumen investigasi resmi NHTSA. |
| **Dugaan** | Keterbatasan Autopilot dalam mengenali objek pada kondisi tertentu diduga berkontribusi terhadap kecelakaan. | Masih dalam proses investigasi. |
| **Dugaan** | Efektivitas pembaruan perangkat lunak Tesla masih terus dievaluasi. | Masih menjadi bagian dari penyelidikan NHTSA. |
| **Opini** | Penyebutan **"Full Self-Driving"** dinilai dapat menimbulkan persepsi bahwa kendaraan mampu beroperasi secara mandiri. | Merupakan pendapat berbagai pihak, bukan keputusan resmi regulator. |
| **Opini** | Strategi komunikasi Tesla mengenai kemampuan Autopilot dinilai perlu dibuat lebih jelas agar pengguna memahami batasan sistem. | Merupakan pandangan yang belum ditetapkan sebagai fakta oleh regulator. |

---

# BAB III — Pemetaan Stakeholder

## 3.1 Indentifikasi Stakeholder
  Dalam kasus kecelakaan yang melibatkan sistem Autopilot/FSD, teridentifikasi enam stakeholder utama yang memiliki keterkaitan langsung maupun tidak langsung terhadap isu ini:
|No |	Stakeholder	| Kategori	| Peran |
|---|-------------|-----------|-------|
|1	|Tesla	| Internal | Produsen kendaraan dan pengembang sistem Autopilot/FSD |
|2	|Software Engineer	| Internal | Perancang dan pengembang algoritma sistem otonom |
|3	|Pengguna (konsumen)	| Eksternal |	Pembeli dan pengoperasi kendaraan berfitur Autopilot/FSD |
|4	|Korban	| Eksternal	| Pihak yang mengalami kerugian akibat insiden yang menyangkut penggunaan kendaraan dengan fitur Autopilot/FSD
|5	|NHTSA	| Eksternal	| Regulator keselamatan kendaraan bermotor di Amerika Serikat |
|6	|Investor	| Eksternal	| Pemegang saham dan penyandang dana perusahaan |

Kategori internal digunakan untuk pihak yang terdampak langsung oleh keputusan dan operasional sistem, sedangkan eksternal mengarah kepada pihak yang memiliki kepentingan pengawasan atau finansial terhadap keberlangsungan perusahaan.

## 3.2 Hubungan Kepentingan
### Tesla
Sebagai produsen, Tesla memiliki kepentingan komersial untuk mempercepat komersialisasi FSD sekaligus menjaga reputasi keselamatan. Tesla berhubungan langsung dengan seluruh stakeholder lain, seperti mempekerjakan software engineer, menjual produk kepada pengguna, bertanggung jawab atas dampak terhadap korban, diawasi oleh NHTSA, dan melapor kepada investor.

### Software Engineer
Engineer bertanggung jawab merancang sistem deteksi objek, algoritma pengambilan keputusan, dan mekanisme peringatan kepada pengemudi. Kepentingan mereka mencakup tekanan untuk memenuhi target rilis produk sekaligus tanggung jawab etis-teknis atas keselamatan sistem yang mereka bangun. 

### Pengguna 
Pengguna berkepentingan atas kenyamanan, efisiensi berkendara, serta jaminan keselamatan. NHTSA mencatat bahwa FSD dan Autopilot masih dikategorikan sebagai sistem SAE Level 2, yang tetap mensyaratkan pengemudi mengawasi penuh dan bertanggung jawab atas jalannya kendaraan, sehingga tanggung jawab hukum utama tetap berada pada pengemudi meskipun sistem otomatis sedang aktif. 

### Korban 
Korban meliputi pengemudi, penumpang, maupun pihak ketiga (pejalan kaki, pengendara lain) yang mengalami cedera atau kematian akibat insiden. Basis data independen mencatat sedikitnya 65 kematian yang melibatkan sistem Autopilot atau FSD Tesla sejak 2013 hingga 2025. Kepentingan mereka adalah kompensasi, keadilan hukum, dan pencegahan insiden serupa di masa depan. 

### NHTSA
NHTSA berkepentingan menegakkan standar keselamatan kendaraan bermotor di ranah publik. Lembaga ini telah membuka lebih dari tiga puluh investigasi kecelakaan khusus terhadap sistem bantuan pengemudi Tesla sejak 2016, dan pada Oktober 2024 membuka investigasi baru terhadap sekitar 2,4 juta unit Tesla model tahun 2016–2024 terkait performa FSD, yang kemudian ditingkatkan statusnya menjadi Engineering Analysis pada Maret 2026, mencakup sekitar 3,2 juta kendaraan model 2016–2026. 

### Investor
Investor berkepentingan pada nilai saham, tata kelola perusahaan, dan keberlanjutan strategi bisnis jangka panjang. Ketidakpastian terkait klaim kemampuan otonom Tesla sempat memicu gugatan class action yang diajukan oleh pemegang saham terhadap Musk dan Tesla terkait risiko keselamatan robotaxi dan kendaraan otonom. Sebagian pemegang saham institusional juga menyatakan keprihatinan atas terpecahnya fokus kepemimpinan Musk di berbagai perusahaan lain, yang dinilai melemahkan kemampuan Tesla mengelola bisnis intinya. 

## 3.3 Dampak bagi masing-masing stakeholder
|No | Stakeholder	| Dampak Positif |	Dampak negatif |
|---|-------------|----------------|-----------------|
| 1	| Tesla	| Diferensiasi produk, potensi pendapatan dari fitur FSD berbayar	| Risiko reputasi, tuntutan hukum, biaya recall unit, tekanan regulasi |
|2	| Software Engineer	| Peran strategis dalam inovasi teknologi	| Beban tanggung jawab etis, tekanan tenggat produk yang berisiko terhadap kualitas keselamatan |
|3	| Pengguna (konsumen)	| Kemudahan dan pengurangan beban mengemudi	| Risiko kesalahpahaman batas kemampuan sistem, potensi kecelakaan |
|4	| Korban	| -	| Cedera, kematian, kerugian finansial dan psikologis, proses hukum yang panjang |
|5	| NHTSA	| Penguatan mandat pengawasan keselamatan publik	| Beban investigasi besar, tantangan regulasi teknologi yang berkembang cepat |
|6	| Investor	| Potensi pertumbuhan nilai saham dari narasi AI/otonom	| Volatilitas saham, risiko litigasi, ketidakpastian tata kelola perusahaan |



# BAB IV — Analisis Empat Teori Etika

## Utilitarianisme
### a.	Prinsip teori
Utilitarianisme merupakan cara menilai benar atau salahnya suatu tindakan berdasarkan konsekuensinya. Tindakan dianggap etis jika menghasilkan manfaat (kebahagiaan, kesejahteraan) terbesar bagi jumlah orang terbanyak, dan tidak etis jika menimbulkan kerugiaan yang lebih besar dari manfaatnya. Perhitungan dilakukan secara agregat, membandingkan total utilitas seluruh pihak yang berdampak, bukan hanya sepihak.

### b.	Analisis kasus
Tesla secara konsisten membela pengembangan Autopilot/FSD dengan argumen agregat: jika secara statistik sistem ini menurunkan angka kecelakaan dibanding rata-rata pengemudi manusia, maka penyebarannya dapat dibenarkan meski menimbulkan korban individual. Namun, analisis NHTSA menemukan bahwa desain sistem keterlibatan pengemudi pada Autopilot tergolong lemah dibanding sistem Level 2 pesaing Autosteer justru nonaktif ketika pengemudi mencoba melakukan koreksi kemudi manual, sebuah desain yang berpotensi mendorong kelalaian alih-alih mencegahnya. Artinya, klaim manfaat agregat Tesla dibangun di atas desain yang belum tentu optimal secara keselamatan, sehingga perhitungan utilitasnya patut dipertanyakan validitasnya. Selain itu, tekanan investor untuk mempercepat rilis fitur demi pertumbuhan nilai saham menciptakan potensi trade-off antara utilitas jangka pendek (nilai saham, pangsa pasar) dan utilitas jangka panjang (keselamatan publik, kepercayaan pasar)  sesuatu yang jarang dihitung penuh dalam kalkulasi utilitas versi perusahaan. 

### c.	Kesimpulan 
Dari sudut pandang utilitarianisme murni, pengembangan FSD/Autopilot berpotensi dibenarkan hanya jika klaim manfaat agregatnya benar-benar teruji secara independen dan transparan bukan sekadar klaim internal perusahaan. Selama data keselamatan belum divalidasi pihak ketiga yang independen dan desain sistem masih memiliki kelemahan yang diketahui, klaim "manfaat terbesar bagi jumlah terbesar" belum dapat dipertanggungjawabkan secara etis, karena berpotensi mengorbankan korban individual demi kepentingan agregat yang belum terbukti solid. 

## Deontologi
### a.	Prinsip teori
Deontologi, terutama dalam kerangka Immanuel Kant, menilai tindakan berdasarkan kesesuaiannya dengan kewajiban moral dan prinsip universal (categorical imperative), terlepas dari konsekuensi yang dihasilkan. Prinsip kuncinya: manusia tidak boleh diperlakukan semata sebagai sarana (means) untuk mencapai tujuan pihak lain, melainkan selalu harus diperlakukan sebagai tujuan (ends) itu sendiri. Kejujuran dan transparansi menjadi kewajiban mutlak, tidak bisa dikompromikan meski demi hasil yang dianggap baik. 

### b.	Analisis kasus
Terdapat kewajiban mutlak bagi Tesla untuk tidak menyesatkan konsumen mengenai kemampuan sebenarnya dari sistem yang dijual. Fakta bahwa pengadilan dan DMV California menemukan adanya praktik periklanan yang menyesatkan terkait batas kemampuan sistem hingga memaksa Tesla mengubah nama pemasaran dari "Autopilot" merupakan pelanggaran langsung terhadap prinsip kejujuran deontologis. Pengguna dan pihak ketiga di jalan (calon korban) tidak pernah diperlakukan sepenuhnya sebagai ends, melainkan turut berfungsi sebagai means dalam proses pengumpulan data pengujian dunia nyata untuk mematangkan sistem, tanpa selalu disertai transparansi penuh atas keterbatasan teknologi tersebut. Dari sisi internal, software engineer yang mengetahui adanya keterbatasan sistem namun tetap merilisnya karena tekanan tenggat waktu turut melanggar kewajiban profesional untuk jujur dan berhati-hati (duty of care). 

### c.	Kesimpulan 
Dari sudut pandang deontologi, tindakan Tesla dalam memasarkan kemampuan sistem tidak dapat dibenarkan meski hasil akhirnya (jika benar) menurunkan angka kecelakaan secara agregat, karena deontologi menolak logika "tujuan menghalalkan cara". Kewajiban untuk berkata jujur kepada pengguna dan tidak menjadikan pihak ketiga sebagai objek uji coba bersifat mutlak dan berlaku universal, sehingga pelanggaran terhadap kewajiban ini tetap tidak etis terlepas dari manfaat statistik yang diklaim.

## Etika Kebajikan
### a.	Prinsip teori
Etika kebajikan (virtue ethics), berakar pada pemikiran Aristoteles, tidak berfokus pada aturan (deontologi) atau konsekuensi (utilitarianisme), melainkan pada karakter moral pelaku. Suatu tindakan dinilai etis jika mencerminkan kebajikan (virtues) seperti kejujuran, kehati-hatian (prudence), tanggung jawab, dan keberanian moral dan sebaliknya, tindakan dinilai tidak etis jika mencerminkan sifat buruk (vices) seperti keserakahan, kecerobohan, atau kesombongan. Fokusnya adalah "tindakan seperti apa yang akan dilakukan oleh orang/organisasi yang berkarakter baik?" 

### b.	Analisis kasus
Sejumlah pemegang saham institusional secara terbuka mengkritik kepemimpinan Musk karena dianggap terlalu terbagi perhatiannya di berbagai perusahaan lain (SpaceX, X, xAI, Neuralink), sementara Dewan Direksi Tesla dinilai pasif dan tidak memberikan pengawasan yang memadai. Kritik ini pada dasarnya mempersoalkan kebajikan kepemimpinan apakah pemimpin perusahaan menunjukkan tanggung jawab dan kehati-hatian yang sepatutnya terhadap keselamatan produk yang berisiko tinggi terhadap nyawa manusia. Pola keterlambatan pelaporan insiden kepada NHTSA sebagaimana disyaratkan oleh Standing General Order juga dapat dibaca sebagai kegagalan organisasi menunjukkan kebajikan transparansi. Di sisi lain, etika kebajikan juga menuntut keberanian moral dari software engineer untuk menyuarakan keberatan internal ketika suatu sistem dianggap belum layak dirilis sebuah kebajikan yang sulit dinilai dari luar, namun menjadi elemen penting dalam budaya organisasi yang etis. 

### c.	Kesimpulan 
Dari sudut pandang etika kebajikan, pola kepemimpinan yang terpecah fokus, minimnya pengawasan dewan direksi, dan keterlambatan transparansi pelaporan insiden mencerminkan defisit karakter organisasi khususnya pada kebajikan tanggung jawab dan kehati-hatian yang seharusnya menjadi prioritas utama bagi perusahaan yang mengembangkan teknologi berisiko keselamatan tinggi. Perbaikan tata kelola dan budaya keberanian menyuarakan risiko secara internal menjadi kebutuhan mendasar agar organisasi dapat dikatakan bertindak sebagaimana organisasi yang berkarakter baik seharusnya bertindak. 

## Etika Hak/Kontraktarian
### a.	Prinsip teori
Etika hak menekankan bahwa setiap individu memiliki hak dasar yang tidak boleh dilanggar pihak lain termasuk hak atas keselamatan, hak atas informasi yang jujur, dan hak atas ganti rugi. Kontraktarianisme, berakar pada pemikiran John Locke dan dikembangkan lebih lanjut oleh John Rawls, memandang moralitas sebagai hasil kesepakatan sosial yang adil, di mana aturan main yang berlaku harus dapat diterima oleh semua pihak yang terlibat termasuk pihak yang paling rentan dan tidak memiliki kekuatan tawar. Konsep Rawlsian veil of ignorance mengajukan uji etis: apakah suatu kebijakan akan tetap dianggap adil jika perancangnya tidak tahu posisi mana yang akan mereka tempati dalam sistem tersebut? 

### b.	Analisis kasus
Pengguna memiliki hak atas informasi akurat mengenai batas kemampuan sistem sebelum memutuskan mengaktifkan fitur FSD hak yang berpotensi dilanggar melalui praktik pemasaran yang pernah dinyatakan menyesatkan oleh otoritas California. Lebih krusial lagi, korban pihak ketiga seperti pejalan kaki atau pengendara lain tidak pernah menyetujui kontrak apapun dengan Tesla, namun tetap menanggung risiko dari teknologi yang tidak mereka pilih sendiri pelanggaran nyata terhadap prinsip persetujuan (informed consent) yang menjadi inti etika kontraktarian. Uji veil of ignorance juga relevan: seandainya pengambil keputusan pengujian robotaxi di jalan publik tidak tahu apakah kelak mereka akan menjadi pengemudi, penumpang, atau pejalan kaki yang terdampak, desain pengujian kemungkinan besar akan jauh lebih konservatif sebagaimana ditunjukkan oleh kritik kelompok advokasi keselamatan terhadap uji jalan publik robotaxi. NHTSA di sini berperan sebagai representasi negara yang menjaga kontrak sosial, memastikan risiko yang ditanggung publik sebanding dengan hak mereka atas keselamatan. 

### c.	Kesimpulan 
Dari sudut pandang etika hak/kontraktarian, terdapat ketimpangan mendasar antara pihak yang menanggung risiko (pengguna dan pihak ketiga di jalan) dan pihak yang mengambil keputusan (perusahaan serta jajaran direksinya). Selama pihak ketiga yang tidak pernah menyetujui kontrak apa pun tetap menanggung risiko tanpa kompensasi atau perlindungan yang memadai, praktik pengembangan dan pengujian sistem otonom ini tidak memenuhi standar keadilan kontraktarian, dan memerlukan mekanisme persetujuan serta perlindungan hak yang lebih kuat sebelum dapat dianggap etis secara penuh. 

# BAB V — Analisis Berdasarkan Pancasila

## 5.1 Analisis Sila 1 – Ketuhanan Yang Maha Esa
  Penghormatan terhadap kehidupan manusia yang tidak boleh dikorbankan demi keuntungan bisnis menunjukkan nilai sila ini. Penamaan "Autopilot" dan "Full Self-Driving" membuat pengguna percaya bahwa kendaraan dapat berkendara sendiri, meskipun kendaraan masih berada di Level 2 dan membutuhkan pengawasan penuh, yang merupakan bentuk ketidakjujuran yang menjaga kepercayaan pengguna.
  Engineer memiliki tanggung jawab untuk merancang sistem sejujur mungkin tanpa melebih-lebihkan kemampuannya sistem harus digunakan sesuai batasan. Semangat sila pertama menganggap nyawa manusia penting untuk dilindungi daripada diuji coba oleh karena itu, kelalaiannya menyebabkan korban jiwa.
  
## 5.2 Analisis Sila 2 – Kemanusiaan yang Adil dan Beradab
  Sila ini paling terasa kaitannya dengan kasus Autopilot, prinsip ini sangat relevan untuk kasus Autopilot karena berkaitan dengan perlakuan adil dan bermartabat terhadap manusia.
  Tidak ada korelasi yang jelas antara Tesla dan individu yang terlibat dalam insiden. Sementara pengguna hanya bergantung pada klaim pemasaran dan nama fitur yang terdengar meyakinkan, Tesla memiliki akses penuh ke data teknis dan hasil pengujian internal. Ketidakseimbangan informasi ini mengganggu pengguna saat memutuskan untuk mempercayai sistem. Keadilan di sini bersifat timbal balik: perusahaan harus jujur tentang batasan produk mereka, dan konsumen harus mematuhinya.
  
## 5.3 Analisis Sila 3 – Persatuan Indonesia
  Dalam kasus Tesla, ada perbedaan yang jelas antara kepentingan masyarakat luas terkait keselamatan jalan raya dan keinginan bisnis Tesla untuk tetap menjadi pemimpin dalam teknologi self-driving. Fitur yang dirilis dengan cepat untuk bersaing di pasar tanpa mempertimbangkan bahayanya bagi keselamatan bersama, menunjukkan bahwa kepentingan pribadi lebih penting daripada kepentingan bersama, bertentangan dengan sila ketiga.
  
## 5.4 Analisis Sila 4 – Kerakyatan yang Dipimpin oleh Hikmat Kebijaksanaan dalam Permusyawaratan/Perwakilan
  Sila ini menekankan bahwa pengambilan keputusan melibatkan banyak pihak, bukan satu pihak. Dari urutan peristiwa saat ini, tampak bahwa Tesla lebih banyak memilih sendiri desain, nama, dan tanggal perilisan Autopilot, tanpa berkonsultasi dengan regulator (NHTSA) atau perwakilan pengguna. Pengawasan eksternal sangat reaktif dan tidak termasuk dalam proses pengambilan keputusan sejak awal, menurut investigasi NHTSA yang baru dilakukan setelah kecelakaan terjadi.
  Semangat musyawarah dan kebijaksanaan bersama yang menjadi inti sila keempat bertentangan dengan keputusan yang dibuat secara sepihak tanpa melibatkan regulator, ahli keselamatan, atau calon pengguna sejak awal.
  
## 5.5 Analisis Sila 5 – Keadilan Sosial bagi Seluruh Rakyat Indonesia
  Sila ini tidak berbicara tentang siapa yang menang, tetapi tentang pemerataan manfaat dan risiko. Pejalan kaki dan pengendara kendaraan darurat yang sama sekali tidak terlibat dalam pengambilan keputusan membeli fitur tersebut adalah pihak yang lebih rentan, yang Tesla dan investornya menikmati keuntungan besar dari kenaikan saham dan dominasi pasar kendaraan listrik.
 Menurut prinsip keadilan sosial, keuntungan dari inovasi harus sebanding dengan tanggung jawab atas risiko yang ditimbulkannya, bukan dibebankan ke masyarakat luas tanpa kompensasi yang memadai.

## 5.6 Nilai Universitas Pancasila
  Selain lima sila, kasus ini juga dapat dibaca melalui lima nilai yang dijunjung Universitas Pancasila. Hal ini karena nilai-nilai ini sebenarnya berasal dari semangat Pancasila sendiri.
### - Integritas
  Dalam hal integritas, Tesla tampak tidak selaras dengan nama fitur yang digunakan dibandingkan dengan kemampuan sebenarnya sistem. Meskipun masih di Level 2, menyebut fitur "Full Self-Driving" merupakan bentuk ketidakjujuran yang merusak integritas perusahaan dan engineer yang terlibat dalam pengembangannya.
### - Kepedulian
  Dari sisi kepedulian, sebelum fitur dirilis ke pasar keselamatan pengguna harus menjadi prioritas utama daripada perbaikan belakangan setelah muncul korban. Sejak awal, respons Tesla terhadap tekanan dari NHTSA menunjukkan kepedulian yang sifatnya reaktif, bukan proaktif.
### - Harmonis
  Dari sisi harmonis, ada ketegangan yang tidak terkontrol antara kepentingan bisnis Tesla dan keselamatan pengguna jalan; proses pengembangan yang lebih hati-hati seharusnya memperbaikinya.
### - Kolaboratif
  Dalam hal kolaboratif, keputusan penting tentang desain dan perilisan fitur dibuat secara internal tanpa melibatkan regulator atau ahli keselamatan sejak tahap awal. Namun, kolaborasi semacam itu penting untuk sistem yang membutuhkan kehidupan manusia.
### - Profesionalisme
  Dari sisi Profesionalisme, seorang software engineer yang bekerja di sistem keselamatan kritis seperti ini harus berani menyuarakan keberatan jika ada tekanan bisnis yang mengancam keselamatan, daripada hanya mengikuti target rilis tanpa mempertimbangkan risikonya terhadap pengguna dari perspektif profesional.

---

# BAB VI — Kode Etik Profesi

## 6.1 ACM Code of Ethics
  Untuk membaca kasus Tesla ini, ada kode etik yang dibuat oleh ACM (Association for Computing Machinery). Salah satu prinsip terpenting ialah bahwa seorang praktisi IT memiliki kewajiban untuk menjaga kesejahteraan manusia dan menghindari  bahaya. Prinsip ini sangat berkaitan dengan tugas engineer untuk memastikan bahwa sistem Autopilot tidak menimbulkan risiko bagi pengguna, terutama bagi orang lain di jalan raya yang tidak terlibat dalam pengambilan keputusan untuk menggunakan fitur tersebut.
  Kejujuran dan kepercayaan juga penting. Karena nama "Full Self-Driving" memberi kesan kemampuan yang lebih tinggi daripada kenyataan teknisnya, penamaan sistem yang secara teknis masih berada pada Level 2 cukup sulit dibenarkan berdasarkan prinsip ini.
ACM juga menekankan pentingnya memahami dan mengevaluasi dampak sosial dari suatu pekerjaan. Dampak sosial ini harus mencakup semua orang yang mungkin mengalami kerugian. Dalam kasus Tesla, ini berarti bahwa engineer tidak hanya perlu mempertimbangkan aspek teknis sistem, tetapi juga mempertimbangkan bagaimana produk tersebut digunakan atau bahkan disalahgunakan oleh pengguna di lapangan.

## 6.2 IEEE Code of Ethics
  Sebagai asosiasi profesional yang memberikan dukungan kepada banyak insinyur perangkat lunak, keselamatan, kesehatan, dan kesejahteraan publik adalah hal yang paling penting. Prinsip ini sangat penting untuk Autopilot karena sistem tersebut sangat berkaitan dengan keselamatan jiwa dan tidak boleh dikorbankan oleh tekanan pasar atau kecepatan produk baru.
IEEE juga mengatakan bahwa setiap klaim atau perkiraan yang dibuat harus didasarkan pada data yang tersedia secara akurat dan bebas dari unsur-unsur penipuan. Ketentuan ini bersinggungan langsung dengan masalah overclaiming pada branding Autopilot dan FSD kesan publik lebih meyakinkan daripada kemampuan sistem sebenarnya.
  Bagian dari kode etik ini menekankan betapa pentingnya untuk tetap terbuka untuk kritik teknis dan mengakui kekeliruan. Dalam hal respons Tesla terhadap penyelidikan NHTSA, perbaikan sistem yang baru dilakukan setelah tekanan regulator menunjukkan bahwa proses evaluasi diri belum sepenuhnya berjalan sejak awal dan lebih banyak dipengaruhi oleh faktor eksternal.

## 6.3 Pasal yang relevan
  Beberapa poin dari kedua kode etik ini dapat diterapkan dalam situasi ini. Hal-hal seperti penghindaran bahaya dan kejujuran dalam menyampaikan klaim kemampuan sistem menjadi rujukan utama untuk menilai masalah penamaan fitur dan potensi risiko yang muncul darinya, menurut ACM.
  IEEE mengatakan bahwa pilihan untuk pengembangan dan pemasaran Autopilot didasarkan pada hal-hal seperti mengutamakan keselamatan publik daripada hal-hal lain. Kedua kode etik ini berasal dari organisasi yang berbeda, tetapi prinsip dasar yang sama menempatkan keselamatan dan kejujuran di atas kepentingan bisnis, terutama untuk sistem keselamatan seperti ini.

## 6.4 Analisis pelanggaran/kepatuhan
  Dari perspektif kepatuhan, Tesla telah mengikuti prinsip kode etik dengan menyempurnakan sistem Tesla Vision dan melakukan penarikan kembali melalui pembaruan perangkat lunak pada akhir 2023. Tindakan ini dapat dianggap sebagai bukti kesediaan Tesla untuk menilai dan memperbaiki kesalahan yang ada.
  Sebaliknya, beberapa tindakan cukup jelas menyimpang dari prinsip yang sudah disebutkan sebelumnya. Menurut ACM dan IEEE, prinsip kejujuran dan larangan klaim palsu dapat bertentangan dengan penggunaan nama "Full Self-Driving" untuk sistem yang masih dianggap sebagai Level 2. Fakta bahwa perbaikan besar terjadi hanya karena tekanan investigasi NHTSA, bukan karena tindakan pencegahan, menunjukkan bahwa prinsip keselamatan publik belum sepenuhnya dimasukkan ke dalam proses pengembangan sejak awal.
  Dengan kata lain, pola menunjukkan bahwa kepatuhan terhadap kode etik lebih sering muncul sebagai hasil dari dorongan dari luar daripada telah menjadi budaya kerja sejak awal pengembangan.


---

# BAB VII — Regulasi dan Hukum

- Regulasi NHTSA
- Regulasi Kendaraan Otonom
- Product Liability
- Tanggung Jawab Hukum
- Perbedaan Hukum dan Moral

---

# BAB VIII — Integritas dan Anti Korupsi

- Penyalahgunaan Kepercayaan
- Overclaim Sistem
- Konflik Kepentingan
- Integritas Engineer
- Analisis Anti Korupsi

---

# BAB IX — Manajemen Risiko

Menggunakan **ISO 31000:2018**

Tahapan:

- Identifikasi Risiko
- Analisis Risiko
- Evaluasi Risiko
- Opsi 4T

---

# BAB X — Dampak dan Kontrol Preventif

- Dampak terhadap masyarakat
- Dampak terhadap industri
- Rekomendasi teknis
- Rekomendasi regulasi
- Kontrol preventif

---

# BAB XI — Pelajaran Utama

## Bagi Software Engineer

...

## Bagi Perusahaan

...

## Bagi Regulator

...

## Kesimpulan

...

---

# Lampiran

- Laporan Lengkap (PDF)
- Slide Presentasi
- Gambar Pendukung

---

# Daftar Pustaka

Gunakan format IEEE sesuai laporan.


## 📄 Lisensi

Repository ini dibuat untuk keperluan akademik pada Mata Kuliah **Etika Profesi** Program Studi Teknik Informatika Universitas Pancasila.
