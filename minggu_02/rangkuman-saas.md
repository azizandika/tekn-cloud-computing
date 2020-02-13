#b 1.ntara IaaS, SaaS, dan PasS 
IaaS (Infrastruktur sebagai layanan)
Perangkat keras, perangkat lunak, dan kode aplikasi Anda harus dikelola. Anda memilih server untuk diaktifkan (baik fisik atau virtual), menginstal OS dan tumpukan perangkat lunak, lalu akhirnya menyebarkan aplikasi Anda. Beberapa penyedia menawarkan kontrol tingkat sangat rendah sehingga Anda dapat membangun pusat data Anda sendiri di cloud.

SaaS (Perangkat Lunak sebagai layanan)
Ini adalah level abstraksi tertinggi dan berarti Anda hanya menggunakan aplikasi web dan tidak pernah melihat tumpukan perangkat keras dan lunak yang membuatnya berjalan. Anda memasukkan data Anda sendiri ke dalam aplikasi yang disediakan namun beberapa aplikasi yang lebih besar memungkinkan untuk membangun aplikasi khusus di atas (mis. Facebook).

PaaS (Platform sebagai layanan)
Jenis layanan ini memisahkan semua keputusan perangkat keras. Hanya tumpukan perangkat lunak dan kode aplikasi Anda yang harus dikelola. Pilih penyedia yang sesuai tergantung pada tumpukan perangkat lunak yang Anda inginkan kemudian gunakan aplikasi Anda. Server, jaringan, dan penyimpanan yang sebenarnya semuanya diurus secara otomatis oleh platform.

## 2. Arsitektur Platform SAAS (Perangkat Lunak sebagai Layanan)
Perangkat lunak sebagai layanan adalah model lisensi dan pengiriman perangkat lunak di mana perangkat lunak dilisensikan berdasarkan berlangganan dan di-host secara terpusat. Pengguna dapat mengaksesnya dengan bantuan browser web.

SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan pesan, perangkat lunak manajemen, virtualisasi dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS).

**Arsitektur SAAS:**
Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. Aplikasi ini diinstal pada banyak mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). Dalam beberapa kasus, versi kedua aplikasi diatur untuk menawarkan kelompok pelanggan tertentu dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian. Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode unik. Meskipun pengecualian, beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola secara efektif sejumlah besar pelanggan di tempat. Apakah multitenancy merupakan komponen yang diperlukan untuk perangkat lunak-sebagai-layanan adalah topik kontroversi.

Ada dua varietas utama SaaS:
1. SaaS Vertikal
2. Perangkat Lunak yang menjawab kebutuhan industri tertentu (mis. Perangkat lunak untuk kesehatan, pertanian, real estat, industri keuangan)
3. SaaS Horisontal
4. Produk-produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.

**Manfaat SaaS:**
Ini menawarkan peluang besar bagi organisasi dari semua ukuran untuk mengalihkan risiko akuisisi perangkat lunak, dan untuk memindahkan TI dari pusat biaya reaktif menjadi bagian perusahaan yang proaktif dan bernilai tambah. Secara tradisional, menyebarkan sistem perangkat lunak skala besar telah menjadi tugas utama. Menyebarkan sistem ini di perusahaan besar membutuhkan biaya lebih besar. Waktu, staf, dan persyaratan anggaran untuk penyebaran sebesar ini mewakili risiko yang signifikan bagi organisasi dalam ukuran berapa pun, dan sering kali menempatkan perangkat lunak seperti itu di luar jangkauan organisasi yang lebih kecil yang jika tidak dapat diturunkan darinya banyak utilitas. Model pengiriman berdasarkan permintaan mengubah beberapa hal ini.

**Kesimpulan**
Perusahaan sebaiknya mempertimbangkan fleksibilitas dan implikasi manajemen risiko dalam menambahkan SaaS ke portofolio layanan TI mereka. Integrasi dan komposisi adalah komponen penting dalam strategi arsitektur Anda untuk menggabungkan SaaS dengan sukses sebagai anggota yang berpartisipasi penuh dari infrastruktur TI Anda yang berfokus pada layanan. Kami percaya bahwa masa depan komputasi perusahaan tidak akan murni di tempat. Sebaliknya, mereka akan ada dalam harmoni simbiosis.

##Arsitektur Platform SAAS (Perangkat Lunak sebagai Layanan)
**Apa itu Platform SaaS?**
Sebelum kita masuk ke beberapa poin yang lebih terlibat, ada baiknya menyebutkan apa itu platform SaaS. SaaS adalah cara untuk mengirimkan perangkat lunak, penyedia perangkat lunak ini secara sentral menampung satu atau lebih aplikasi dan membuatnya tersedia bagi pelanggan melalui internet.

SaaS juga merupakan salah satu pilar utama komputasi awan. Sebuah ledakan dalam komputasi Cloud, didorong oleh penyedia cloud seperti Microsoft dengan Azure atau Amazon dengan AWS, telah melihat pertumbuhan produk dan layanan lain yang disampaikan melalui internet seperti:
1. Infrastruktur sebagai Layanan
2. Platform sebagai Layanan
3. Pembelajaran Mesin sebagai Layanan

Setiap pembaruan atau tambalan untuk aplikasi SaaS semuanya ditangani oleh penyedia. Pelanggan tidak perlu mengunduh pemutakhiran atau menginstal ulang versi baru suatu produk saat perangkat lunak dikirimkan melalui internet.Dengan penjelasan tentang SaaS, mari kita lihat mengapa Anda mungkin ingin menggunakan produk perangkat lunak yang dirancang seperti ini.

##Cara membangun aplikasi SaaS berbasis cloud
Bisnis SaaS adalah industri yang tumbuh sangat cepat yang menarik lebih banyak orang dan perusahaan. Organisasi-organisasi ini semakin banyak aplikasi mengambang di cloud. Penskalaan di cloud memiliki beberapa manfaat dan risiko penting juga. Dalam artikel ini kami akan menunjukkan kepada Anda bagaimana mulai membangun arsitektur SaaS berbasis cloud, berurusan dengan masalah skalabilitas dan apa artinya ini untuk aplikasi SaaS Anda.

**Bangun untuk cloud**
Saat membangun aplikasi SaaS (global), kemungkinan besar Anda membangunnya di cloud. The awan memiliki banyak keuntungan - memikirkan skalabilitas - kontras dengan lingkungan server lokal. Karena itu pos ini, dan yang akan mengikuti fokus pada perangkat lunak yang dibangun dan direkayasa di cloud. Inilah cara membangun arsitektur SaaS berbasis cloud.

**Bagaimana cara memulai?**
Yang pemrograman bahasa , yang database, yang perangkat lunak alat yang harus Anda pilih? Ada banyak pertanyaan yang perlu dijawab. Karena itu saya berusaha fokus pada hal-hal terpenting.

**Bahasa pemrograman mana?**
Membangun produk untuk cloud berarti membangun produk dengan bahasa pemrograman modern. Selain kemampuan dan keterampilan pribadi, pilihan bahasa pemrograman Anda akan dipengaruhi oleh kemungkinan masing-masing bahasa. Ada berbagai bahasa pemrograman (modern) di luar sana sehingga sulit untuk memilih yang benar.

Perbedaan antara IaaS, SaaS, dan PasS 
IaaS (Infrastruktur sebagai layanan)
Perangkat keras, perangkat lunak, dan kode aplikasi Anda harus dikelola. Anda memilih server untuk diaktifkan (baik fisik atau virtual), menginstal OS dan tumpukan perangkat lunak, lalu akhirnya menyebarkan aplikasi Anda. Beberapa penyedia menawarkan kontrol tingkat sangat rendah sehingga Anda dapat membangun pusat data Anda sendiri di cloud.

SaaS (Perangkat Lunak sebagai layanan)
Ini adalah level abstraksi tertinggi dan berarti Anda hanya menggunakan aplikasi web dan tidak pernah melihat tumpukan perangkat keras dan lunak yang membuatnya berjalan. Anda memasukkan data Anda sendiri ke dalam aplikasi yang disediakan namun beberapa aplikasi yang lebih besar memungkinkan untuk membangun aplikasi khusus di atas (mis. Facebook).

PaaS (Platform sebagai layanan)
Jenis layanan ini memisahkan semua keputusan perangkat keras. Hanya tumpukan perangkat lunak dan kode aplikasi Anda yang harus dikelola. Pilih penyedia yang sesuai tergantung pada tumpukan perangkat lunak yang Anda inginkan kemudian gunakan aplikasi Anda. Server, jaringan, dan penyimpanan yang sebenarnya semuanya diurus secara otomatis oleh platform.

## 2. Arsitektur Platform SAAS (Perangkat Lunak sebagai Layanan)
Perangkat lunak sebagai layanan adalah model lisensi dan pengiriman perangkat lunak di mana perangkat lunak dilisensikan berdasarkan berlangganan dan di-host secara terpusat. Pengguna dapat mengaksesnya dengan bantuan browser web.

SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan pesan, perangkat lunak manajemen, virtualisasi dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS).

**Arsitektur SAAS:**
Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. Aplikasi ini diinstal pada banyak mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). Dalam beberapa kasus, versi kedua aplikasi diatur untuk menawarkan kelompok pelanggan tertentu dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian. Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode unik. Meskipun pengecualian, beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola secara efektif sejumlah besar pelanggan di tempat. Apakah multitenancy merupakan komponen yang diperlukan untuk perangkat lunak-sebagai-layanan adalah topik kontroversi.

Ada dua varietas utama SaaS:
1. SaaS Vertikal
2. Perangkat Lunak yang menjawab kebutuhan industri tertentu (mis. Perangkat lunak untuk kesehatan, pertanian, real estat, industri keuangan)
3. SaaS Horisontal
4. Produk-produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.

**Manfaat SaaS:**
Ini menawarkan peluang besar bagi organisasi dari semua ukuran untuk mengalihkan risiko akuisisi perangkat lunak, dan untuk memindahkan TI dari pusat biaya reaktif menjadi bagian perusahaan yang proaktif dan bernilai tambah. Secara tradisional, menyebarkan sistem perangkat lunak skala besar telah menjadi tugas utama. Menyebarkan sistem ini di perusahaan besar membutuhkan biaya lebih besar. Waktu, staf, dan persyaratan anggaran untuk penyebaran sebesar ini mewakili risiko yang signifikan bagi organisasi dalam ukuran berapa pun, dan sering kali menempatkan perangkat lunak seperti itu di luar jangkauan organisasi yang lebih kecil yang jika tidak dapat diturunkan darinya banyak utilitas. Model pengiriman berdasarkan permintaan mengubah beberapa hal ini.

**Kesimpulan**
Perusahaan sebaiknya mempertimbangkan fleksibilitas dan implikasi manajemen risiko dalam menambahkan SaaS ke portofolio layanan TI mereka. Integrasi dan komposisi adalah komponen penting dalam strategi arsitektur Anda untuk menggabungkan SaaS dengan sukses sebagai anggota yang berpartisipasi penuh dari infrastruktur TI Anda yang berfokus pada layanan. Kami percaya bahwa masa depan komputasi perusahaan tidak akan murni di tempat. Sebaliknya, mereka akan ada dalam harmoni simbiosis.

##Arsitektur Platform SAAS (Perangkat Lunak sebagai Layanan)
**Apa itu Platform SaaS?**
Sebelum kita masuk ke beberapa poin yang lebih terlibat, ada baiknya menyebutkan apa itu platform SaaS. SaaS adalah cara untuk mengirimkan perangkat lunak, penyedia perangkat lunak ini secara sentral menampung satu atau lebih aplikasi dan membuatnya tersedia bagi pelanggan melalui internet.

SaaS juga merupakan salah satu pilar utama komputasi awan. Sebuah ledakan dalam komputasi Cloud, didorong oleh penyedia cloud seperti Microsoft dengan Azure atau Amazon dengan AWS, telah melihat pertumbuhan produk dan layanan lain yang disampaikan melalui internet seperti:
1. Infrastruktur sebagai Layanan
2. Platform sebagai Layanan
3. Pembelajaran Mesin sebagai Layanan

Setiap pembaruan atau tambalan untuk aplikasi SaaS semuanya ditangani oleh penyedia. Pelanggan tidak perlu mengunduh pemutakhiran atau menginstal ulang versi baru suatu produk saat perangkat lunak dikirimkan melalui internet.Dengan penjelasan tentang SaaS, mari kita lihat mengapa Anda mungkin ingin menggunakan produk perangkat lunak yang dirancang seperti ini.

##Cara membangun aplikasi SaaS berbasis cloud
Bisnis SaaS adalah industri yang tumbuh sangat cepat yang menarik lebih banyak orang dan perusahaan. Organisasi-organisasi ini semakin banyak aplikasi mengambang di cloud. Penskalaan di cloud memiliki beberapa manfaat dan risiko penting juga. Dalam artikel ini kami akan menunjukkan kepada Anda bagaimana mulai membangun arsitektur SaaS berbasis cloud, berurusan dengan masalah skalabilitas dan apa artinya ini untuk aplikasi SaaS Anda.

**Bangun untuk cloud**
Saat membangun aplikasi SaaS (global), kemungkinan besar Anda membangunnya di cloud. The awan memiliki banyak keuntungan - memikirkan skalabilitas - kontras dengan lingkungan server lokal. Karena itu pos ini, dan yang akan mengikuti fokus pada perangkat lunak yang dibangun dan direkayasa di cloud. Inilah cara membangun arsitektur SaaS berbasis cloud.

**Bagaimana cara memulai?**
Yang pemrograman bahasa , yang database, yang perangkat lunak alat yang harus Anda pilih? Ada banyak pertanyaan yang perlu dijawab. Karena itu saya berusaha fokus pada hal-hal terpenting.

**Bahasa pemrograman mana?**
Membangun produk untuk cloud berarti membangun produk dengan bahasa pemrograman modern. Selain kemampuan dan keterampilan pribadi, pilihan bahasa pemrograman Anda akan dipengaruhi oleh kemungkinan masing-masing bahasa. Ada berbagai bahasa pemrograman (modern) di luar sana sehingga sulit untuk memilih yang benar.


