# Market8

Spesifikasi Kebutuhan Perangkat Lunak

untuk

Market8 : Kumpulan Website Marketplace

Disusun oleh:

1. ADAM ZUHRUF ANANDA FARENDRA (22091397055)
2. ALLAN JULI SANJAYA (22091397052)
3. RACHMADAN NAUVAL HIDAYAT AKBAR (220913970B72

Program Studi D4 Manajemen Informatika
Fakultas Vokasi
Universitas Negeri Surabaya
2023



Datar Isi

BAB 1
PENDAHULUAN

1.1 Latar Belakang

1.2 Tujuan

1.3 Konvesi Dokumen

1.4 Audiens yang Dituju dan Saran Bacaan

1.5 Cakupan Produk

1.6 Referensi

BAB 2
DESKRIPSI KESELURUHAN

BAB 3
PERSYARATAN ANTARMUKA EKSTERNAL

BAB 4
FITUR SISTEM DAN KERANGKA DESAIN FITUR

BAB 5
PERSYARATAN NONFUNGSIONAL LAINNYA

5.1 Persyaratan Kinerja

5.2 Persyaratan Keselamatan 

5.3 Persyaratan Keamanan

5.4 Atribut Kualitas Perangkat Lunak

5.5 Aturan Bisnis

BAB 6
PERSYARATAN LAINNYA

6.1 Lampiran A: Glosarium

6.2 Lampiran B: Model Analisis

6.3 Lampiran C: Penjelasan Source Code

BAB 1
PENDAHULUAN

1.1 Latar Belakang

Didalam era digital dan globalisasi didalam bidang tekologi yang semakin maju dan efisiensi waktu, website telah menjadi bagian tidak terpisahkan dalam kehidupan sehari-hari, Website-website tersebut tidak hanya memberikan kenyamanan, tetapi juga membuka peluang baru dalam berbagai sektor, termasukindustri ritel. Salah satu bentuk website yang semakin populer adalah website Market 8. Website Market 8 hadir sebagai solusi yang inovatif untuk mempermudah akses cepat kesebuah toko online seperti shoope, lazada, blibli, tokopedia dan sebagainya. Dengan bantuan website ini, kami selaku pemilik website e-comerce dapat memperluas jangkauan pelanggan kepada anak muda dan juga cara cepat untuk mengakses aplikasi e-comerce tanpa mengunduh aplikasinya, dan meningkatkan efisiensi operasional secara keseluruhan. Selain itu, website ini juga memberikan kemudahan bagi pelanggan dalam mecari suatu e-comerce tanpa mengunduh aplikasinya.

Kesimpulannya website Marker 8 memberikan solusi modern untuk mengoptimalkan pengalaman belanja dan akses cepat di website Market 8. Dengan fitur-fitur yg inovatif seperti akses cepat keberbagai e-comerce, website ini memudahkan pelanggan dalam akses cepat tanpa mengunduh aplikasi dan juga website ini dapat lebih ringan dari pada mengunduh aplikasi yg dapat memungkinkan lebih lambat dan berat, serta membantu pemilik e-comerce untuk mendapatkan pelanggan lebih banyak apalagi kalangan muda yg menginginkan kemudahan dan akes cepat dan ringan dalam pengoprasionalkan.

1.2 Tujuan

Platform website market 8 yang menawarkan akses cepat menuju e-comerce kepada pengguna yang lebih luas, dengan kemudahan hanya satu klik lalu masuk pada tampilan e-comercenya dengan mudah dan terjangkau. Tujuan dari website ini untuk menawarkan akses cepat menuju kedalam beberapa e-comerce yang diminati dari shoope hingga blibli dan tokopedia untuk keperluan berbelanja atau hal lainnya didalam e-comerce sesuai apa yang ingin dicari pengguna.
pasarnya yaitu individu yang mencari suatu e-comerce yang juga menginginkan akses cepat dan mudah tanpa download aplikasinya sehingga ringan ketika digunakan.

1.3 Konvensi Dokumen

Konvensi tipografi yang umum digunakan dalam SRS meliputi penggunaan  ukuran font yang harus berada diukuran 12 untuk teks normal dan ukuran 10 untuk teks kecil. Lalu didalam Jenis font yang digunakan adalah Times New Roman atau Arial, lalu Warna font yang digunakan adalah hitam, lalu Jarak antar baris adalah 1,5 spasi, lalu Jarak antar paragraf adalah 2 spasi, lalu teks: Teks ditulis dengan huruf kecil kecuali untuk awal kalimat, nama, dan istilah khusus, huruf tebal atau italic untuk menyoroti kata-kata atau frasa yang penting, serta penggunaan nomor atau huruf untuk menyusun hierarki persyaratan. Selain itu, ada juga standar tertentu yang dapat diikuti, seperti IEEE 830 yang menetapkan format dan struktur umum untuk SRS.

1.4 Audiens yang Dituju dan Saran Bacaan

Saran membaca dokumen ini ditujukan untuk beberapa jenis pembaca yang mungkin memiliki peran yang berbeda dalam proyek
pengembangan perangkat lunak, termasuk:

1. Pengembang: orang yang bertanggung jawab untuk merancang, mengembangkan, dan mengimplementasikan perangkat lunak. Mereka akan membutuhkan informasi detail tentang persyaratan fungsional dan nonfungsional, antarmuka, dan ketergantungan yang diperlukan oleh perangkat lunak.

2. Manajer Proyek: orang yang bertanggung jawab untuk merencanakan, mengarahkan, dan mengawasi pengembangan perangkat lunak. Mereka akan membutuhkan informasi tentang jadwal, sumber daya, tanggung jawab, risiko, dan kendala proyek.

3. Pengguna: orang yang akan menggunakan perangkat lunak. Mereka akan membutuhkan informasi tentang fitur dan fungsi yang tersedia dalam perangkat lunak, serta persyaratan yang harus dipenuhi untuk menggunakannya.

4. Penguji: orang yang bertugas untuk merencanakan, mengorganisir, memimpin, dan mengendalikan proyek agar perangkat lunak dapat memenuhi persyaratan. Mereka akan membutuhkan informasi tentang persyaratan fungsional dan nonfungsional, dan bagaimana perangkat lunak harus beroperasi.

5. Penulis Dokumentasi: orang yang bertanggung jawab untuk menulis dokumen-dokumen yang menjelaskan bagaimana cara menggunakan atau memelihara perangkat lunak. Mereka akan membutuhkan informasi tentang fitur dan fungsi perangkat lunak, serta bagaimana menggunakannya. Dalam pengembangan perangkat lunak, Dokumentasi yang baik dapat membantu berbagai pihak yang terlibat dalam pengembangan perangkat lunak, mulai dari pengembang, tester, pengguna, hingga manajer proyek.

1.5 Cakupan Produk

Dokumen ini menjelaskan tentang perangkat lunak website Market 8. Tujuan dari perangkat lunak ini adalah untuk memfasilitasi operasi dari sebuah toko dan e-comerce atau yang sering disebut toko online. Website ini dirancang untuk memungkinkan pengguna untuk melakukan akses cepat dalam pencarian toko online yang ingin di kunjungi,  pelaporan secara efektif Dengan website ini, pemilik toko dapat atau pemilik e-comerce dapat melakukan kerjasama dengan website kami dan dpaat juga melakukan pelacakan berapa kali toko online tersebut di cari oleh pengguna mengelola.

1.6 Referensi

1. https://media.neliti.com/media/publications/55496-ID-none.pdf
2. https://media.neliti.com/media/publications/496548-implementasi-progressive-web-application-f6b0aaf9.pdf
3. http://e-journal.uajy.ac.id/6722/1/JURNAL.pdf
4. https://ejournal.gunadarma.ac.id/index.php/infokom/article/view/1743/1502
5. https://ejournal.undiksha.ac.id/index.php/insert/article/download/50467/23020
6. https://jurnal.umj.ac.id/index.php/semnaskat/article/download/10666/6015
7. https://ejournal.uinib.ac.id/jurnal/index.php/tathwir/article/download/2767/pdf
8. https://ejournal.jak-stik.ac.id/index.php/komputasi/article/view/170/362
9. https://jurnal.ibik.ac.id/index.php/jikes/article/download/403/705/
10. https://www.researchgate.net/publication/327543746_RANCANG_BANGUN_WEBSITE_TOKO_ONLINE_MENGGUNAKAN_METODE_WATERFALL

BAB 2
DESKRIPSI KESELURUHAN

2.1 Perspektif Produk

Produk yang dijelaskan dalam SRS ini adalah webiste Market 8. yang merupakan website yang bertujuan untuk menyediakan platform bagi pengguna untuk mengakses cepat ke dalam sebuah e-comerce untuk membeli barang-barang dan mengecek barang secara online.

2.2 Fungsi Produk

1. Dirancang Khusus untuk membantu pengolahan dan operasional e-comerce didalam website Market 8.
2. Memebantu dalam akses cepat ke sebuah e-comerce yang ingin di kunjungi
3. Website Market 8 memungkinkan pengguna untuk melakukan akses cepat tanpa mendownload aplikasi dan memberatkan perangkat yang ada hanya dengan membuka website Market 8 saja.

2.3 Kelas Pengguna dan Karakteristik

Berdasarkan tujuan dan fungsi utama dari produk website Market 8, beberapa kelas pengguna yang diantisipasi
akan menggunakan produk ini meliputi:

1. Admin : Akan memiliki hak akses penuh ke sistem dan bertanggung jawab untuk mengelola pengguna, produk, transaksi, dan laporan. Admin harus memiliki keahlian teknis yang tinggi dalam mengelola website, termasuk pengaturan dan konfigurasi server.

2. Pemilik e-comerce: Akan memiliki hak untuk dapat memberikan penjelasan dan akses secara instan kedalam aplikasinya dengan bekerja sama kepada website Market 8.
Mereka dapat mengakses laporan kunjungan pengguna yang mengunjungi ke dalam e-comerce tersebut.

3. Tamu/pengguna: Akan memiliki hak mengunjungi aplikasi dengan cara akses cepat dengan tautan yang sudah tertera didalam website Market 8 tersebutyang belum mendaftar sebagai pengguna. Mereka dapat  dan dapat menjelajahi beberapa e-comerce lainnya yang sudah ada didalam Market 8.

2.4 Lingkup Operasi

  > Lingkup operasi Website Market 8:
    1. Pendaftaran dan pengolahan e-comerce yang sebelum dicantumkan didalam website market 9 harus mengisi berkas berkas persyarat kerja sama
    2. Akan ada grafik yang dapat dilihat oleh setiap e-comerce untuk melihat e-comerce mana yang sering dikunjungi
    3. Lebih mudah dan ringan ketika digunakan karena tidak memerlukan mengunduh aplikasi e-comerce tersebut

  >  Lingkup operasi managemen website Market 8:
    1. Managemen kontak dan informasi pelangan, partner bisnis, dan rekan kerja
    2. Pelaporan dan analisis kinerja e-comerce
    3. Managemen proyek, pengaturan tugas, jadwal, dan pengalokasian sumber daya

2.5 Kendala Desain dan Implementasi

Beberapa hal yang membatasi pilihan yang tersedia untuk para pengembang dalam pengembangan perangkat lunak termasuk:

  > Kebijakan perusahaan atau regulasi: Perusahaan dapat memiliki kebijakan atau aturan tertentu yang harus diikuti oleh pengembang dalam pengembangan perangkat lunak. Selain itu, adanya regulasi pemerintah dapat membatasi pilihan pengembang dalam pengembangan perangkat lunak dan adanya regulasi dari pemilik e-comerce yang mengharuskan target kunjungan yang harus terpenuhi

  > Keterbatasan perangkat keras: Persyaratan memori pada perangkat keras dapat membatasi pilihan pengembang
dalam pengembangan perangkat lunak. Dan pada pengembangan perangkat lunak pada website market 8 ini mengutamakan kepraktisan dan keefesiensi dari website tersebut untuk digunakan pengguna secara luas tanpa harus memikirkan dan khawatir dengan batasan memori yang tersedia pada perangkat keras. Dengan adanya hal tersebut kami ketika mengembangkan perangkat lunak selalu mempertimbangkan dari segi kompatibilitas ukuran dan kompleksitas program agar sesuai dengan kapasitas perangkat keras. 

  > Antarmuka ke aplikasi lain: Jika perangkat lunak harus berinteraksi dengan aplikasi lain, maka pengembang harus mempertimbangkan antarmuka aplikasi tersebut. Pengembang harus memastikan bahwa perangkat lunak dapat berfungsi dengan baik dengan aplikasi lain.

  > Teknologi khusus, alat, dan database: Jika pemilik e-comerce pelanggan menggunakan teknologi khusus, alat, atau database tertentu, pengembang harus mempertimbangkan teknologi tersebut agar perangkat lunak dapat berfungsi dengan baik

  > Operasi paralel: Jika perangkat lunak akan beroperasi secara paralel, pengembang harus mempertimbangkan teknik pemrograman paralel dan memastikan bahwa perangkat lunak dapat beroperasi dengan baik di lingkungan tersebut.

  > Persyaratan Bahasa: Jika pengguna dari berbagai negara akan menggunakan perangkat lunak, pengembang harus mempertimbangkan persyaratan bahasa dan memastikan bahwa perangkat lunak dapat berfungsi dengan baik di berbagai bahasa.

  > Pertimbangan Keamanan: Pengembang harus memeprtimbangkan dari segi keamanan yang harus menjaga kerahasiaan dari setiap e-comerce dan juga pengunjung

2.6 Dokumentasi Pengguna

Dalam SRS ini, akan disampaikan beberapa komponen dokumentasi pengguna yang akan disertakan bersama perangkat lunak, yaitu:

1. Panduan Pengguna: dokumen ini akan memberikan petunjuk yang jelas tentang cara menggunakan perangkat lunak, mulai dari akses memasuki website hingga penggunaan fitur-fitur utama.

2. Bantuan Online: dokumen ini akan disediakan dalam bentuk online dan akan memberikan panduan lengkap tentang cara menggunakan website, fitur-fiturnya, serta solusi untuk masalah yang mungkin timbul saat penggunaan.

3. Tutorial: dokumen ini akan memberikan panduan step-by-step tentang cara menggunakan fitur-fitur kunci dalam perangkat lunak.

2.7 Asumsi dan Ketergantungan

Komponen pihak ketiga atau komersial: Penggunaan komponen pihak ketiga atau komersial dalam pengembangan perangkat lunak dapat mempengaruhi persyaratan yang tercantum dalam SRS, terutama jika ada pembatasan lisensi atau fitur-fitur yang tersedia dalam komponen tersebut.

1.  Lingkungan pengembangan atau operasi : Lingkungan pengembangan atau operasi yang berbeda dapat mempengaruhi persyaratan yang tercantum dalam SRS, seperti persyaratan kinerja dan keamanan. Misalnya, jika lingkungan operasi yang
diinginkan adalah lingkungan yang sangat terdistribusi atau berada di lingkungan cloud, maka persyaratan kinerja dan
keamanan harus diperhitungkan dengan cermat.

2. Kendala : Kendala seperti anggaran dan waktu dapat mempengaruhi persyaratan yang tercantum dalam SRS. Jika anggaran atau waktu terbatas, maka beberapa persyaratan mungkin harus dikurangi atau dihilangkan.

3. Faktor eksternal: Faktor eksternal seperti komponen perangkat lunak yang digunakan kembali dari proyek lain dapat mempengaruhi persyaratan dalam SRS. Jika komponen tersebut tidak tersedia atau tidak sesuai dengan kebutuhan proyek saat ini, maka persyaratan mungkin harus diubah.

BAB 3

PERSYARATAN ANTARMUKA EKSTERNAL

3.1 Antarmuka Pengguna

Antarmuka pengguna adalah suatu elemen penting dalam sebuah perangkat lunak karena merupakan tempat interaksi antara pengguna dan sistem. Beberapa karakteristik dari antarmuka pengguna yang perlu diperhatikan dalam SRS adalah sebagai berikut:

1. Tampilan : antarmuka pengguna harus memiliki tampilan yang mudah dipahami dan menarik. Tampilan tersebut dapat berupa gambar yang menunjukkan bagaimana tampilan antarmuka pengguna akan terlihat.

2. GUI: antarmuka pengguna harus mengikuti standar GUI (Graphical User Interface) atau panduan gaya keluarga produk yang telah ditentukan. Hal ini penting agar antarmuka pengguna mudah dipahami oleh pengguna.

3. Tata letak: tata letak antarmuka pengguna harus dirancang sedemikian rupa sehingga mudah dipahami.

4. Pesan permasalahan/eror : Tampilan pesan yang menunjukkan ketika ada suatu masalah atau eror ketika diakses yang di informasikan kepada pengguna dan pesan itu harus mudah di mengerti oleh pengguna yang diharuskan dan ditentukan masuk kedalam SRS.

Beberapa komponen perangkat lunak yang memerlukan antarmuka pengguna adalah menu, tombol, teks atau deskripsi, ,
tampilan data, link akses cepat dan juga informasi e-comerce yang ada. Desain antarmuka pengguna yang lebih detail harus didokumentasikan dalam spesifikasi antarmuka pengguna yang terpisah. Spesifikasi tersebut harus mencakup deskripsi tentang semua elemen antarmuka pengguna, termasuk tata letak, tombol, menu, dan pintasan keyboard, serta bagaimana pengguna mengakses dan berinteraksi di dalam website.

3.2 Antarmuka Perangkat Keras

Antarmuka perangkat keras adalah titik pertemuan antara dua perangkat keras yang berbeda. Antarmuka ini memungkinkan perangkat keras untuk berkomunikasi dan bertukar data satu sama lain.

Antarmuka perangkat keras dapat diklasifikasikan menjadi dua jenis, yaitu:

1. Antarmuka fisik adalah antarmuka yang menggunakan media fisik untuk menghubungkan dua perangkat keras. Contoh antarmuka fisik adalah konektor USB, konektor HDMI, dan konektor SATA.

2. Antarmuka logis adalah antarmuka yang menggunakan protokol komunikasi untuk menghubungkan dua perangkat keras. Contoh antarmuka logis adalah Universal Serial Bus (USB), Serial Peripheral Interface (SPI), dan Inter-Integrated Circuit (I²C).
Antarmuka perangkat keras memiliki peran yang penting dalam sistem komputer. Antarmuka ini memungkinkan berbagai perangkat keras untuk bekerja sama dan membentuk sistem yang kohesif.

3.3 Antarmuka Perangkat Lunak

Antarmuka perangkat lunak (software interface) adalah titik pertemuan antara pengguna dan perangkat lunak. Antarmuka ini memungkinkan pengguna untuk berinteraksi dengan perangkat lunak dan memberikan input ke perangkat lunak.

Antarmuka perangkat lunak dapat diklasifikasikan menjadi dua jenis, yaitu:

1. Antarmuka pengguna (user interface) adalah antarmuka yang digunakan oleh pengguna untuk berinteraksi dengan perangkat lunak. Antarmuka pengguna dapat berupa antarmuka berbasis teks atau antarmuka berbasis grafis.

2. Antarmuka antarkomponen (component interface) adalah antarmuka yang digunakan oleh komponen perangkat lunak untuk berkomunikasi satu sama lain. Antarmuka antarkomponen biasanya berupa antarmuka abstrak yang didefinisikan dalam kode.

Antarmuka perangkat lunak memiliki peran yang penting dalam perangkat lunak. Antarmuka ini menentukan bagaimana pengguna berinteraksi dengan perangkat lunak dan bagaimana komponen perangkat lunak berkomunikasi satu sama lain. Antarmuka perangkat lunak terus berkembang seiring dengan perkembangan teknologi. Antarmuka baru yang lebih intuitif dan efisien terus dikembangkan untuk meningkatkan pengalaman pengguna.

Berikut adalah beberapa faktor yang penting dalam desain antarmuka perangkat lunak:

1. Kesederhanaan Antarmuka perangkat lunak harus sederhana dan mudah digunakan.

2. Intuisi Antarmuka perangkat lunak harus intuitif dan mudah dipahami.

3. Efisien Antarmuka perangkat lunak harus efisien dan mudah dipelajari.

4. Fleksibilitas Antarmuka perangkat lunak harus fleksibel dan dapat disesuaikan dengan kebutuhan pengguna.

5. Estetika Antarmuka perangkat lunak harus estetis dan menarik.
Desain antarmuka perangkat lunak yang baik akan membuat perangkat lunak lebih mudah digunakan dan meningkatkan kepuasan pengguna.

3.4 Antarmuka Komunikasi

1. Notifikasi Akses
   > Pengguna akan mendapatkan notifikasi ketika sedang dan dalam mengakses akses cepat ke sebuah salah satu e-comerce
   > notifikasi akan di kirim via notifikasi cepat pada panel notifikasi pop-up
2. Ulasan
   > Pengguna dapat memberikan ulasan kepada website kami apakah nyaman untuk digunakan atau tidaknya
   > pengguna dapat melaporkan ketika terjadinya eror atau masalah pada website kami

BAB 4
FITUR SISTEM DAN KERANGKA DESAIN FITUR

Menjelaskan mengenai proses yang akan dilakukan oleh sistem yang ada didalam website Market 8 ini developmen akan mengajak sebuah berbagai e-comerce untuk kerja sama yang dapat menguntung e-comerce karena website ini dapat memunculkan dan memberikan akses cepat dan ringan ke dalam e-comerce mereka

4.1 Halaman e-comerce pada tampilan pertama

![alt text](https://github.com/Rachmadan210/Market8/blob/main/Tampilan%201%20Website%20Market%208.png.jpg?raw=true)

4.2 Halaman e-comerce pada tampilan kedua

![alt text](https://github.com/Rachmadan210/Market8/blob/main/Tampilan%202%20Website%20Market%208.png.jpg?raw=true)

4.3 Halaman e-comerce pada tampilan ketiga

![alt text](https://github.com/Rachmadan210/Market8/blob/main/Tampilan%203%20Website%20Market%208.png.jpg?raw=true)

4.4 Halaman e-comerce pada tampilan ke empat

![alt text](https://github.com/Rachmadan210/Market8/blob/main/Tampilan%204%20Website%20Market%208.png.jpg?raw=true)

4.5 Halaman e-comerce pada tampilan ke lima

![alt text](https://github.com/Rachmadan210/Market8/blob/main/Tampilan%205%20Website%20Market%208.png.jpg?raw=true)

4.6 Halaman e-comerce pada tampilan ke enam

![alt text](https://github.com/Rachmadan210/Market8/blob/main/Tampilan%206%20Website%20Market%208.png.jpg?raw=true)

BAB 5
PERSYARATAN NON-FUNGSIONAL LAINNYA

5.1 Persyaratan Kinerja

Persyaratan keselamatan sangat penting untuk memastikan produk aman digunakan oleh pengguna. Berikut adalah beberapa contoh persyaratanh keselamatan yang mungkin diperlukan:

1. Produk harus memenuhi standar keselamatan yang relevan, seperti standar keselamatan elektronik, keamanan produk, dan
persyaratan lingkungan.

2. Produk harus dirancang sedemikian rupa sehingga tidak ada risiko kebakaran atau ledakan ketika digunakan dengan benar.
Produk juga harus dilengkapi dengan tindakan pengamanan seperti sensor panas dan alat pemadam api otomatis.

3. Produk harus menghindari potensi kecelakaan saat digunakan, seperti cedera fisik atau trauma pada pengguna. Produk harus mempertimbangkan faktor ergonomic, seperti tinggi dan lebar kursi, untuk memastikan kenyamanan dan keselamatan pengguna.

4. Produk harus memiliki label peringatan dan petunjuk penggunaan yang jelas dan mudah dipahami oleh pengguna. Label harus
mencakup informasi tentang bahaya dan peringatan penting yang berkaitan dengan penggunaan produk.

5. Produk harus memiliki fitur keamanan yang membatasi akses pengguna yang tidak sah. Ini dapat mencakup perlindungan password atau perangkat lunak enkripsi yang terenkripsi untuk melindungi informasi pribadi dan data penting.

6. Produk harus memiliki fitur cadangan atau pemulihan darurat yang memungkinkan pengguna untuk mengembalikan data dan informasi setelah kehilangan atau kegagalan sistem.

7. Produk harus dirancang untuk memenuhi persyaratan keselamatan yang diperlukan oleh badan pengatur atau sertifikasi. Ini mungkin mencakup persyaratan UL atau sertifikasi CE

Dalam mengembangkan produk, sangat penting untuk mempertimbangkan keamanan dan keselamatan pengguna sebagai prioritas utama. Tim pengembang harus berkolaborasi dengan ahli keselamatan dan badan pengatur untuk memastikan produk aman dan memenuhi standar keselamatan yang relevan.

5.2 Persyaratan Keselamatan

Berikut adalah beberapa persyaratan keamanan dan privasi yang dapat terkait dengan penggunaan produk:

1. Persyaratan autentikasi pengguna: Produk harus menyediakan mekanisme autentikasi pengguna yang aman dan dapat diandalkan untuk mengakses fitur atau layanan yang sensitif. Mekanisme autentikasi harus memenuhi standar keamanan dan privasi yang berlaku.

2. Persyaratan otorisasi pengguna: Produk harus memiliki mekanisme otorisasi yang tepat untuk mengontrol akses pengguna ke fitur atau layanan yang berbeda dalam sistem. Akses pengguna harus diatur berdasarkan peran, tanggung jawab, atau kebutuhan bisnis.

3. Persyaratan enkripsi data: Produk harus dapat mengenkripsi data yang sensitif pada saat penyimpanan atau pengiriman data melalui jaringan untuk melindungi kerahasiaan dan integritas data.

4. Persyaratan proteksi data: Produk harus dapat melindungi data sensitif dari kehilangan, penggunaan yang tidak sah, atau akse tidak sah. Data sensitif harus diidentifikasi dan dikelola secara khusus untuk meminimalkan risiko pelanggaran keamanan data

5. Persyaratan pelaporan keamanan: Produk harus memiliki mekanisme pelaporan yang tepat untuk melaporkan pelanggaran keamanan atau aktivitas mencurigakan yang terkait dengan produk. Pelaporan harus dilakukan sesuai dengan standar industri atau peraturan yang berlaku.

6. Persyaratan pemantauan keamanan: Produk harus memiliki kemampuan untuk memantau aktivitas pengguna dan sistem secara real-time untuk mendeteksi dan merespons ancaman keamanan. Pemantauan harus meliputi audit log, alarm keamanan, dan tindakan pencegahan atau mitigasi risiko.

7. Persyaratan privasi data: Produk harus mematuhi standar privasi yang berlaku dan memproteksi data pribadi pengguna dengan tepat. Data pribadi harus diidentifikasi dan dikelola secara khusus untuk meminimalkan risiko pelanggaran privasi data.

8. Persyaratan sertifikasi keamanan atau privasi: Produk harus memenuhi sertifikasi keamanan atau privasi yang berlaku untuk industri atau wilayah tertentu, seperti PCI DSS, HIPAA, atau GDPR. Produk harus memenuhi persyaratan sertifikasi untuk memastikan keamanan dan privasi yang tepat bagi pengguna produk.

5.3 Persyaratan Keamanan

Berikut adalah beberapa persyaratan keamanan dan privasi yang dapat terkait dengan penggunaan produk:

1. Persyaratan autentikasi pengguna: Produk harus menyediakan mekanisme autentikasi pengguna yang aman dan dapat diandalkan untuk mengakses fitur atau layanan yang sensitif. Mekanisme autentikasi harus memenuhi standar keamanan dan privasi vana berlaku.

2. Persyaratan otorisasi pengguna: Produk harus memiliki mekanisme otorisasi yang tepat untuk mengontrol akses pengguna ke fitur atau layanan yang berbeda dalam sistem. Akses pengguna harus diatur berdasarkan peran, tanggung jawab, atau kebutuhan bisnis.

3. Persyaratan enkripsi data: Produk harus dapat mengenkripsi data yang sensitif pada saat penyimpanan atau pengiriman data melalui jaringan untuk melindungi kerahasiaan dan integritas data.

4. Persyaratan proteksi data: Produk harus dapat melindungi data sensitif dari kehilangan, penggunaan yang tidak sah, atau akses
tidak sah. Data sensitif harus diidentifikasi dan dikelola secara khusus untuk meminimalkan risiko pelanggaran keamanan data.

5. Persyaratan pelaporan keamanan: Produk harus memiliki mekanisme pelaporan yang tepat untuk melaporkan pelanggaran keamanan atau aktivitas mencurigakan yang terkait dengan produk Pelaporan harus dilakukan sesuai dengan standar industri atau peraturan yang berlaku.

6. Persyaratan pemantauan keamanan: Produk harus memiliki kemampuan untuk memantau aktivitas pengguna dan sistem secara real-time untuk mendeteksi dan merespons ancaman keamanan. Pemantauan harus meliputi audit log, alarm keamanan, dan tindakan pencegahan atau mitigasi risiko.

5.4 Atribut Kualitas Perangkat Lunak

1. Keandalan : Produk harus dapat diandalkan dan bekerja secara konsisten tanpa kesalahan atau gangguan yang signifikan.

2. Penggunaan Kembali : Produk harus dirancang agar dapat digunakan kembali dalam berbagai lingkungan atau website, dengan memaksimalkan penggunaan kembali kode dan fungsi.

3. Ketersediaan : Produk harus tersedia secara konsisten dan dapat diakses oleh pengguna kapan saja, di mana saja.

4. Kegunaan: Produk harus mudah digunakan dan intuitif bagi pengguna, dengan navigasi yang jelas dan fitur-fitur yang mudah dipahami.

5. Interoperabilitas : Produk harus kompatibel dengan perangkat lunak dan perangkat keras yang berbeda dan dapat berintegrasi dengan mudah dengan sistem yang ada.

6. Pemeliharaan : Produk harus mudah dikelola dan dipelihara dengan biaya yang wajar dan waktu yang terbatas.

7. Fleksibilitas : Produk harus dapat diadaptasi dan disesuaikan dengan kebutuhan pengguna dan perusahaan dengan cepat dan mudah.

5.5 Atruran Bisnis

Prinsip operasi produk mencakup:

1. Hak akses dan peran pengguna: Prinsip ini menetapkan hak akses dan peran pengguna yang berbeda dalam sistem, seperti administrator, pengguna terdaftar, atau pengunjung anonim. Hal ini dapat memengaruhi persyaratan fungsional terkait dengan otorisasi, autentikasi, dan manajemen hak akses.

2. Urutan operasi : Prinsip ini menentukan urutan operasi yang diperlukan untuk menjalankan fungsi atau mengakses fitur tertentu. Hal ini dapat memengaruhi persyaratan fungsional terkait dengan tata letak antarmuka pengguna, navigasi, dan perubahan status sistem.

3. Konteks penggunaan: Prinsip ini menentukan kondisi atau konteks penggunaan yang memengaruhi cara produk dioperasikan, seperti penggunaan pada perangkat seluler, di lingkungan dengan koneksi internet yang tidak stabil, atau di lingkungan dengan keadaan darurat. Hal ini dapat memengaruhi persyaratan fungsional terkait dengan kecepatan, keandalan, dan tata letak antarmuka pengguna yang responsif.

4. Aturan bisnis: Prinsip ini menentukan aturan bisnis dan kebijakan yang harus diterapkan pada produk, seperti aturan privasi atau kebijakan pengembalian. Hal ini dapat memengaruhi persyaratan fungsional terkait dengan manajemen data.

BAB 6
PERSYARATAN LAINNYA

6.1 Lampiran A: Glosarium

Berikut adalah daftar istilah dan akronim yang digunakan dalam SRS ini:

1. Software: Serangkaian intruksi dan data yang diatur dalam bentuk program komputer yang dapat dijalankan pada perangkat keras computer. Software memberikan kerangka kerja bagi perangkat keras untuk menjalankan tugas-tugas tertentu dan menyediakan fungsionalitas yang diperlukan oleh penggunaan komputer.

2. Website: Kumpulan halaman web tertaut yang dapat diakses melalui Internet. Setiap halaman web biasanya berisi teks, gambar, audio, video, atau elemen lain yang dirancang untuk memberikan informasi atau interaksi kepada pengguna.

3. Server: Merupakan sistem yang memiliki layanan khusus berupa penyimpanan data server. Dimana server data tersebut akan menyimpan berbagai jenis dokumen dan menyediakan informasi untuk penggunanya atau pengunjung.

4. DB: Database atau basis data merupakan kumpulan data yang akan dikelola sedemikian rupa dengan berdasarkan ketentuan tertentu dimana yang saling berhubungan sehingga mudah dalam pengelolaannya. Dengan melalui pengolahan tersebut pengguna dapat memperoleh kemudahan dalam mencari informasi, menyimpan informasi dan membuang informasi.

5. CSS: bahasa Cascading Style Sheet dan biasanya digunakan untuk mengatur tampilan elemen yang tertulis dalam bahasa
markup, seperti HTML CSS berfungsi untuk memisahkan konten dari tampilan visualnya di situs

6. Javascript: JavaScript adalah bahasa skrip yang digunakan untuk membuat konten halaman web dinamis, berfungsi untuk membuat elemen yang mampu meningkatkan interaksi pengunjung seperti menu drop-down, animasi, dan warna background dinamis

7. HTML: bahasa markah standar untuk dokumen yang dirancang untuk ditampilkan di peramban internet.

6.2 Lampiran B: Model Analisis

1. Use Case

![alt text](https://github.com/Rachmadan210/Market8/blob/main/Use%20Case.png.jpg?raw=true)
 

2. Flowcart Diagram

![alt text](https://github.com/Rachmadan210/Market8/blob/main/Flowrcart%20Diagram.png.jpg?raw=true)

6.3 Lampiran C Penjelasan Source Code

1. Penjelasan source code HTML
![alt text](https://github.com/Rachmadan210/Market8/blob/main/SS%20html%201.jpg?raw=true)


  1. Tag <HEAD> tugasnya adalah memberikan informasi tentang dokumen, maksudnya didalam tag <head> kita bisa menambahkan tag- tag yang biasanya digunakan untuk memberikan informasi berupa penulis, judul dokumen, kata kunci pada dokumen dan masih banyak lagi informasi yang bisa di tambahkan pada tag ini.
  2. I DOCTYPE untuk mendeklarasikan sebuah instruksi yang mengaitkan dokumen XML atau SGML tertentu dengan definisi tipe dokumen.
  3. deklarasi <html lang="en">memberi tahu browser bahwa semua konten di halaman tresebut adalah bahasa Inggris. subtag langjuga memiliki skrip atau penunjuk wilayah, yang memungkinkan Anda menentukan sistem penulisan bahasa atau wilayah geografis.
  4. UTF-8 adalah sebuah pengkodean karakter dengan lebar variabel tertentu yang mewakili setiap karakter komputer dalam himpunan karakter Unicode.
  5. menggunakan tag <meta name='viewport'>, kita bisa mengatur viewport sesuai kebutuhan. untuk bisa membuat web menjadi responsive.. kita membutuhkan bantuan dari tag <meta name='viewport'> untuk mengatur viewport.
  6. Tag <link>mendefinisikan hubungan antara dokumen saat ini dan sumber daya eksternal. Lalu ketika link rel maka, Diperlukan untuk Menentukan hubungan antara dokumen saat ini dan dokumen tertaut 
  7. Title bar adalah batang judul yang berfungsi untuk menampilkan nama dari jendela program tersebut.
  8. <body> sebagai bagian isi/konten yang ingin ditampilkan dalam sebuah halaman web
  9. Tag <div> digunakan sebagai wadah elemen HTML - yang kemudian ditata dengan CSS atau dimanipulasi dengan JavaScript.  Tag <div> mudah ditata dengan menggunakan atribut class atau id.  Segala jenis konten dapat dimasukkan ke dalam tag <div>
  10. Tag <img>digunakan untuk menyematkan gambar di halaman HTML. Gambar secara teknis tidak dimasukkan ke dalam halaman web; gambar ditautkan ke halaman web. Tag <img>menciptakan ruang penahan untuk gambar yang direferensikan.
  11. <h2> Tag HTML yang digunakan untuk menunjukkan bagian penting pada halaman website
  12. <p> untuk membuat paragraf
  13. Tag HTML <a> untuk Menunjukkan bahwa target dari link tersebut akan didownload ketika user mengkliknya lalu "href" menentukan untuk alamat URL atau nama ID halaman atau element yang akan dituju.

  
![alt text](https://github.com/Rachmadan210/Market8/blob/main/SS%20html%201.jpg?raw=true)


  1. Tag <div> digunakan sebagai wadah elemen HTML - yang kemudian ditata dengan CSS atau dimanipulasi dengan JavaScript.  Tag <div> mudah ditata dengan menggunakan atribut class atau id.  Segala jenis konten dapat dimasukkan ke dalam tag <div>
  2. <br> untuk membuat baris baru
  3. Tag <img>digunakan untuk menyematkan gambar di halaman HTML. Gambar secara teknis tidak dimasukkan ke dalam halaman web; gambar ditautkan ke halaman web. Tag <img>menciptakan ruang penahan untuk gambar yang direferensikan.
  4. <h2> Tag HTML yang digunakan untuk menunjukkan bagian penting pada halaman website
  5. <p> untuk membuat paragraf
  6. Tag HTML <a> untuk Menunjukkan bahwa target dari link tersebut akan didownload ketika user mengkliknya lalu "href" menentukan untuk alamat URL atau nama ID halaman atau element yang akan dituju.
  7. <nav> pada HTML yang dibuat untuk mempresentasikan link navigasi.
  8. <ul> digunakan untuk menampilkan daftar item yang sejajar, tanpa prioritas atau urutan tertentu. Dalam praktiknya, kamu bisa menggunakan tag < ul > untuk mendefinisikan list dan tag < li > untuk setiap item dalam list.
  9. <li> Untuk membuat nested list di HTML, list tambahan harus diletakkan di dalam tag <li>. Fungsi li pada html adalah untuk menampilkan item pada unordered dan ordered list. Sedangkan pada description list tidak menggunakan tag <li>.
  10. <Footer> seringkali berisi informasi seperti: Tautan ke halaman penting seperti "Tentang Kami," "Kontak," "Kebijakan Privasi," dan lain-lain. Informasi kontak seperti alamat, nomor telepon, dan alamat email.



![alt text](https://github.com/Rachmadan210/Market8/blob/main/SS%20html%203.jpg?raw=true)


  1. <p> untuk membuat paragraf
  2. Tag HTML <a> untuk Menunjukkan bahwa target dari link tersebut akan didownload ketika user mengkliknya lalu "href" menentukan untuk alamat URL atau nama ID halaman atau element yang akan dituju.
  3. Tag <div> digunakan sebagai wadah elemen HTML - yang kemudian ditata dengan CSS atau dimanipulasi dengan JavaScript.  Tag <div> mudah ditata dengan menggunakan atribut class atau id.  Segala jenis konten dapat dimasukkan ke dalam tag <div>
  4. <nav> pada HTML yang dibuat untuk mempresentasikan link navigasi.
  5. <ul> digunakan untuk menampilkan daftar item yang sejajar, tanpa prioritas atau urutan tertentu. Dalam praktiknya, kamu bisa menggunakan tag < ul > untuk mendefinisikan list dan tag < li > untuk setiap item dalam list.
  6. <li> Untuk membuat nested list di HTML, list tambahan harus diletakkan di dalam tag <li>. Fungsi li pada html adalah untuk menampilkan item pada unordered dan ordered list. Sedangkan pada description list tidak menggunakan tag <li>.
  7. <Footer> seringkali berisi informasi seperti: Tautan ke halaman penting seperti "Tentang Kami," "Kontak," "Kebijakan Privasi," dan lain-lain. Informasi kontak seperti alamat, nomor telepon, dan alamat email.
  8. <body> sebagai bagian isi/konten yang ingin ditampilkan dalam sebuah halaman web
  9. deklarasi <html lang="en">memberi tahu browser bahwa semua konten di halaman tresebut adalah bahasa Inggris. subtag langjuga memiliki skrip atau penunjuk wilayah, yang memungkinkan Anda menentukan sistem penulisan bahasa atau wilayah geografis.

3. Penjelasan source code CSS
![alt text](https://github.com/Rachmadan210/Market8/blob/main/SS%20css%201.jpg?raw=true)


1. Margin berfungsi sebagai “penyangga” yang untuk mengatur layout dan penataan elemen atau memisahkan satu elemen dari elemen lainnya.
2. Padding adalah ruang kosong atau space antara satu konten dengan konten yang lainnya. Dengan padding, tampilan website akan lebih teratur dan lebih menarik.
3. Untuk mendeklarasikan aturan gaya pada isi halaman web, Anda perlu membuat aturan CSS untuk bodytag pemilih. Dan untuk menambahkan gambar latar belakang kesitus anda
4. Untuk memberikan warna latar pada suatu elemen, menggunakan tag background-color.
5. Deklarasi ini font-family: "Arial", Sans-Serif;mengatur jenis font (Arial) dan jenis font generik (Sans-Serif) untuk semua teks di halaman web.
6. Color untuk mengatur warna dari elemen-elemen tertentu seperti teks dan latar belakang (background).
7. Header memberikan identitas dan navigasi yang jelas bagi sebuah website.
8. Tag text-align untuk menyelaraskan konten sebaris (yaitu: teks) dari elemen di dalam elemen blok induknya.
9. Hanya gunakan satu elemen H1 pada halaman. elemen heading H1 sampai H6 memperkenalkan konten yang mengikutinya. heading tag H1 paling penting dari semua heading tag HTML lainnya. Semakin meningkat tingkat heading tag (H2, H3, H4, H5, dan H6), kepentingan kontennya dianggap semakin berkurang oleh mesin pencari.
10. Font size digunakan untuk menentukan keterbacaan, aksesibilitas, dan juga estetika dari sebuah website. Melalui penggunaan properti font-size dalam CSS, kamu diberi kebebasan dan fleksibilitas untuk menyesuaikan tampilan teks, memastikan informasi disajikan dengan tampilan yang nyaman untuk pembaca.
11. Container berfungsi untuk membungkus blok di dalamnya, sehingga terlihat rapi terhadap ukuran layar.



![alt text](https://github.com/Rachmadan210/Market8/blob/main/SS%20css%202.jpg?raw=true)


1. Container berfungsi untuk membungkus blok di dalamnya, sehingga terlihat rapi terhadap ukuran layar
2. Margin berfungsi sebagai “penyangga” yang untuk mengatur layout dan penataan elemen atau memisahkan satu elemen dari elemen lainnya.
3. Padding adalah ruang kosong atau space antara satu konten dengan konten yang lainnya. Dengan padding, tampilan website akan lebih teratur dan lebih menarik.
4. Onlineshop untuk mendeklarasikan bagian yang disebut "onlineshop"
5. Untuk memberikan warna latar pada suatu elemen, menggunakan tag background-color.
6. box-shadow digunakan untuk membuat bayangan untuk kotak atau elemen kontainer.
7. Onlineshop untuk mendeklarasikan bagian yang disebut "onlineshop" dalam bentuk gambar menjadi "onlineshop img" yang didalamnya terdapat deklarasi tambahan yaitu "img"
8. width yang berarti lebar Dengan begitu Anda bisa menyesuaikan ukuran lebar sesuai dengan kebutuhan Anda. Secara default ukuran width dan tergantung pada konten didalamnya. Lalu jika, Max-width yang berarti lebar maksimal
9. menggunakan properti border, Anda tidak lagi menulis kode yang panjang seperti menggunakan border individu.
10. Properti border-radius digunakan untuk membuat border atau perbatasan yang bulat. Agar Anda bisa melihat effek visual border-radius, sangat disarankan agar memberikan background-color atau border pada elemennya, ini tidak wajib, ini supaya Anda bisa melihat effek perbatasan yang bulat.
11. tag H2 pada CSS untuk membuat heading atau sub-judul pada sebuah halaman web. Tag H2 memiliki ukuran dan tingkat kepentingan yang lebih rendah dari pada tag H1 tetapi lebih tinggi daripada tag H3, jadi pada onlineshop h2 maka akan mendeklarasikan sebuah onlineshop pada heading atau sub judul pada sebuah halaman web
12. Font size digunakan untuk menentukan keterbacaan, aksesibilitas, dan juga estetika dari sebuah website. Melalui penggunaan properti font-size dalam CSS, kamu diberi kebebasan dan fleksibilitas untuk menyesuaikan tampilan teks, memastikan informasi disajikan dengan tampilan yang nyaman untuk pembaca.
13. Color untuk mengatur warna dari elemen-elemen tertentu seperti teks dan latar belakang (background).

![alt text](https://github.com/Rachmadan210/Market8/blob/main/SS%20css%203.jpg?raw=true)


1. Tag <p> untuk sebuah Paragraf, ialah kumpulan dari beberapa kalimat.
2. Line height untuk mengatur jarak tulisan pada situs
3. elemen Nav dibuat untuk integritas link navigasi.
4. Properti text-decoration adalah properti untuk memberikan dekorasi garis pada teks. Contohnya seperti garis bawah, garis atas, dan garis di tengah (teks tercoret).
5. Color untuk mengatur warna dari elemen-elemen tertentu seperti teks dan latar belakang (background).
6. font-weight, dapat mengubah ketebalan sebuah teks.
7. <nav>: Elemen Bagian Navigasi, untuk menyediakan link navigasi, baik dalam dokumen saat ini atau ke dokumen lain. Jadi <nav> dan <ul> Keduanya dapat digunakan bersama untuk menu navigasi. Ul membuat daftar secara tidak berurutan. Tidak berurutan berarti item dalam daftar tidak akan berada dalam urutan tertentu. Anda dapat meletakkan "ul" elemen di dalamnya "nav" untuk menempatkan tautan Anda.
8. list-style tag singkat untuk menentukan atau mengatur list dengan css dalam satu deklarasi
9. Display berguna untuk mengatur tampilnya suatu elemen.
10. justify-content digunakan untuk mensejajarkan item-item diantara flexbox agar container dari flexbox tersebut bisa mendistribusikan ruang kosong yang tersisa ketika item flex dalam satu baris tersebut tidak flexsibel atau meskipun flexsibel tapi sudah mencapai batas ukuran maksimum.
11.  Untuk memberikan warna latar pada suatu elemen, menggunakan tag background-color.
12.  Padding adalah ruang kosong atau space antara satu konten dengan konten yang lainnya. Dengan padding, tampilan website akan lebih teratur dan lebih menarik.
13.  elemen Nav dibuat untuk integritas link navigasi. Lalu elemen li untuk menampilkan item pada unordered dan ordered list.
14.  Margin berfungsi sebagai “penyangga” yang untuk mengatur layout dan penataan elemen atau memisahkan satu elemen dari elemen lainnya.

![alt text](https://github.com/Rachmadan210/Market8/blob/main/SS%20css%204.jpg?raw=true)


1. Color untuk mengatur warna dari elemen-elemen tertentu seperti teks dan latar belakang (background).
2. Padding adalah ruang kosong atau space antara satu konten dengan konten yang lainnya. Dengan padding, tampilan website akan lebih teratur dan lebih menarik.
3. elemen Nav dibuat untuk integritas link navigasi. Lalu elemen li untuk menampilkan item pada unordered dan ordered list.
4. elemen Nav dibuat untuk integritas link navigasi. elemen Nav dibuat untuk integritas link navigasi.
5. Properti text-decoration adalah properti untuk memberikan dekorasi garis pada teks. Contohnya seperti garis bawah, garis atas, dan garis di tengah (teks tercoret).
6. Color untuk mengatur warna dari elemen-elemen tertentu seperti teks dan latar belakang (background).
7. font-weight, dapat mengubah ketebalan sebuah teks.
8. Footer adalah bagian bawah dokumen. Letaknya di bawah badan utama atau body. Tag <footer> mendefinisikan footer untuk dokumen atau bagian.
9. text-align berfungsi untuk mengatur posisi teks
10. Tag footer untuk mendefinisikan dokumen atau bagian jadi ketik <p> untuk membuat paragraf, maka footer p untuk mendefinisikan dokumen pada suatu paragraf
