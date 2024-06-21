
<div style="text-align: center;">
  <h1>Massive Project Group 12 AAI</h1>
</div>
<h3 style="text-align: center;">Pengenalan Massive </h3>
Pelaksanaan Project Massive ini merupakan project terakhir dimana dalam project ini tim project dari program AAI berkolaborasi dengan tim project lintas program yaitu teman-teman tim web dan mobile untuk bersama-sama merancang sebuah aplikasi berserta website dengan implementasi penerapan kecerdasan buatan didalamnya.




### This is a Machine Learning / AI Project

<h4 style="text-align: center;">Team Project AAI</h4>

| Nama           | GitHub Link        |
|----------------|--------------------|
| Adinda Jaida Fauziyah | [adinda jaida fauziyah](https://github.com/adindajaidafauziyah)|
| Masta Angel Valentina  | [Masta Angel Valentina](https://github.com/angelvlntnn)|
| Roes Byandra  | [byandra](https://github.com/byandra)|
| Yumna Ilahi    | [Yumna Ilahi](https://github.com/Yumnailahi04)|


<div style="text-align: center;">
  <h2>Idea Background</h2>
</div>

### 1. Theme 
Tema  : Kesehatan & Tumbuh Kembang Anak
### 2. Problem
Masalah  :  Krisis Stunting dan Terhambatnya Tumbuh Kembang Anak

Indonesia saat ini tengah bergulat dengan krisis kesehatan dan gizi anak yang serius. Stunting, kondisi terhambatnya pertumbuhan fisik dan perkembangan kognitif anak akibat kekurangan gizi kronis, masih menjadi momok bagi bangsa. Data Riskesdas 2023 menunjukkan prevalensi stunting mencapai 21,6%, meskipun mengalami penurunan dari tahun sebelumnya. Angka ini, meskipun menunjukkan sedikit perbaikan, masih tergolong tinggi dan menjadi perhatian utama pemerintah. 

Krisis stunting ini bukan hanya berdampak pada kesehatan dan perkembangan anak saat ini, tetapi juga memiliki konsekuensi jangka panjang yang serius bagi masa depan bangsa. Tidak hanya terpaku pada perawakan pendek, stunting juga membawa konsekuensi serius pada perkembangan kognitif, motorik, dan metabolisme anak. Anak-anak stunting rentan terhadap berbagai penyakit, tertinggal dalam pencapaian belajar, dan memiliki risiko lebih tinggi untuk mengalami obesitas dan penyakit kronis di masa depan. Generasi yang mengalami stunting di masa kecil berisiko memiliki produktivitas yang lebih rendah dan berakibat pada kerugian ekonomi bagi negara. 

Mayoritas orang tua di Indonesia, terutama di daerah pedesaan dan terpencil, masih kurang menyadari bahaya stunting dan dampak jangka panjangnya. Tak jarang banyak dari mereka memiliki akses terbatas terhadap informasi dan edukasi yang tepat tentang gizi anak dan pencegahan stunting. Hal ini menyebabkan minimnya upaya pencegahan dan penanganan stunting di tingkat keluarga. 
### 3. Solution
Solusi  : 

Melihat permasalahan tersebut, kami tergerak untuk menghadirkan solusi inovatif melalui project stuncare chatbot dan sistem prediksi tingkat kesehatan status gizi bayi. Stuncare chatbot ini memanfaatkan teknologi kecerdasan buatan untuk membantu menyediakan akses yang mudah dan luas bagi orangtua terhadap informasi dan edukasi mengenai gizi anak dan pencegahan stunting. Disamping itu ada sistem prediksi yang juga memanfaatkan teknologi kecerdasan buatan untuk membantu orang tua mengidentifikasi tingkat kesehatan status gizi anak dengan mudah dan praktis, sehingga orangtua dapat medeteksi indikasi tumbuh kembang stunting pada anak mereka sejak dini untuk mengambil langkah pencegahan yang efektif.

<div style="text-align: center;">
  <h2>Dataset and Algorithm</h2>
</div>

### 1. Dataset
- Fitur Prediksi

  Kami menggunakan dataset deteksi stunting balita dari Kaggle untuk memprediksi status gizi bayi. Dataset ini terdiri dari 121.000 baris data yang mencakup usia (bulan), jenis kelamin, tinggi badan (cm), dan status gizi (severely stunted, stunted, normal, tinggi). Dataset ini gratis dan mudah diakses di Kaggle.
- Fitur Chatbot

  Kami menggunakan dataset CSV yang diinput manual untuk fitur chatbot. Data berisi pertanyaan dan jawaban terkait stunting dan tumbuh kembang anak dari sumber valid. Dataset ini dikonversi ke format JSON untuk mempermudah pemahaman chatbot.


  
### 2. Framework & Algorithm
- Fitur Prediksi

Kami memilih Scikit-Learn sebagai framework AI untuk membangun model klasifikasi dalam identifikasi status gizi bayi. Scikit-Learn dipilih karena kemudahan penggunaannya dan efisiensinya dalam membangun model pembelajaran mesin. Framework ini menyediakan berbagai algoritma untuk klasifikasi, regresi, dan klasterisasi, yang sangat berguna dalam analisis data gizi dan kesehatan anak. Selain itu, Scikit-Learn memiliki dokumentasi yang baik dan komunitas pengguna yang luas, memudahkan proses pembelajaran dan implementasi. Integrasinya dengan library Python seperti NumPy dan pandas mendukung analisis data kompleks, menjadikannya ideal untuk prediksi status gizi anak

Kami juga menerapkan algoritma klasifikasi untuk membangun model yang memprediksi status gizi berdasarkan usia, jenis kelamin, dan tinggi badan. Algoritma klasifikasi memungkinkan model mempelajari pola dan hubungan antara fitur-fitur ini dengan kategori gizi yang telah ditentukan. Model klasifikasi dilatih menggunakan dataset yang mencakup variasi usia, jenis kelamin, dan tinggi badan bayi, sehingga mampu mengenali pola dan memprediksi status gizi bayi baru berdasarkan data yang diberikan. Algoritma ini dipilih karena kemampuannya dalam menganalisis kombinasi fitur-fitur tersebut untuk memprediksi status gizi dengan akurasi tinggi.
  
- Fitur Chatbot

Kami menggunakan IBM Watson Assistant untuk fitur chatbot. Ada beberapa alasan utama untuk memilihnya:
1. Antarmuka berbasis drag and drop memudahkan pengguna membangun dan mengonfigurasi asisten virtual tanpa memerlukan pengetahuan pemrograman mendalam.
2. Watson Assistant dapat diintegrasikan dengan berbagai platform dan aplikasi, termasuk website, aplikasi mobile, serta saluran komunikasi seperti Slack dan Facebook Messenger.
3. Sebagai bagian dari IBM Cloud, Watson Assistant dapat menangani skala besar dan beban kerja tinggi dengan performa yang konsisten.

Kami menggunakan layanan IBM Watson Assistant untuk membangun fitur chatbot tersebut, sehingga tidak ada algoritma khusus yang kami pakai. Layanan IBM Watson Assistant yang kami gunakan sudah menyediakan kemampuan AI bawaan untuk memahami bahasa alami.
  


<div style="text-align: center;">
  <h2>Prototype</h2>
</div>

### 1. Fitur Prediksi 
![image](https://github.com/Yumnailahi04/Massive_Project_Group12_AAI/assets/154740771/619ee0b0-316a-4f28-a2fc-c2f03c6243b9)

Diagram alir tersebut menggambarkan alur kerja sistem prediksi tingkat kesehatan status gizi yang kami kembangkan. Dalam diagram alir tersebut proses dimulai dengan pengguna yang memasukkan data berupa umur, tinggi badan, dan jenis kelamin bayi. Data ini kemudian diproses dan dipersiapkan untuk dianalisis oleh model pembelajaran mesin. Setelah data diproses, data tersebut dimasukkan ke dalam model Machine Learning untuk diklasifikasikan ke dalam kategori status gizi balita yang sesuai. Model akan menghasilkan distribusi probabilitas yang menunjukkan kemungkinan tingkat kesehatan status gizi balita tersebut. Jika model memiliki keyakinan tinggi terhadap prediksinya, hasil prediksi yang paling mungkin akan ditampilkan kepada pengguna. Namun, jika model tidak yakin dengan prediksinya, model akan memberikan pesan bahwa prediksi tidak dapat ditentukan. Proses ini berakhir ketika pengguna menerima prediksi atau hasil output yang dihasilkan oleh model Machine Learning tersebut. 

### 2. Fitur Chatbot
![image](https://github.com/Yumnailahi04/Massive_Project_Group12_AAI/assets/154740771/4d82221a-313f-4b4c-950a-5d5c18895645)

Diagram alir tersebut menggambarkan alur kerja stuncare chatbot yang kami kembangkan. Dalam diagram alir tersebut, pengguna memulai dengan memasukkan pesan atau pertanyaan ke dalam chatbot. Chatbot kemudian akan memproses input tersebut menggunakan teknik Natural Language Processing (NLP) untuk mengubahnya menjadi query yang dapat dipahami oleh sistem. Berdasarkan query yang telah diproses, chatbot akan memilih respons yang paling sesuai dari database yang tersedia. Hasil pemilihan ini kemudian dikembalikan ke model bahasa besar (Large Language Model) untuk diolah lebih lanjut sehingga menjadi respons yang lebih manusiawi dan natural. Akhirnya, output yang telah dipoles ini dikirim kembali kepada pengguna sebagai jawaban dari chatbot.  


<div style="text-align: center;">
  <h2>Integration</h2>
</div>

### 1. Fitur Prediksi 
Kami memilih untuk mengintegrasikan fitur prediksi ini kedalam aplikasi berbasis website. model prediksi yang kami kembangkan diimplementasikan menggunakan Flask sebagai framework untuk bagian backend dan react.js untuk bagian frontend.  Flask bertanggung jawab mengelola logika dan data dari server, sementara react.js bertanggung jawab mengatur tampilan dan interaksi pengguna di sisi klien.  

Singkatnya sebagai backend server, flask akan menangani permintaan http yang dikirimkan oleh aplikasi frontend yang dibangun dengan react.js. Selanjutnya flask memproses data menggunakan API untuk mengirim data yang diterima dari frontend kepada model dan meminta prediksi. Setelah menerima hasil prediksi dari model tersebut, respons tersebut akan dikirimkan kembali ke react.js untuk ditampilkan kepada pengguna secara dinamis. 

### 2. Fitur Chatbot
Kami memilih untuk mengintegrasikan fitur chatbot ini kedalam aplikasi berbasis mobile. Chatbot yang sudah dibangun dan dikonfigurasi di IBM Watson Asssistant kemudian dipublish ke dalam live environtment untuk mendapatkan embedded code, embedded code adalah kode yang dihasilkan dari proses publish chatbot dalam bentuk snippet code JavaScript atau perintah API. kode ini kemudian diimplementasikan kedalam aplikasi mobile menggunakan Android Studio. Kami juga menggunakan Framework Jetpack Compose dan bahasa pemrograman Kotlin untuk mengembangkan aplikasi ini. 

<div style="text-align: center;">
  <h2>Deployment</h2>
</div>

### 1. Fitur Prediksi 
Untuk proses deployment model KNN yang kami gunakan dalam membangun fitur prediksi ini kami menggunakan layanan IBM Watson studio. Singkatnya model yang sudah selesai ditraining disimpan dalam format PKL untuk diimport kedalam deployment space yang ada di IBM Watson studio. Hasil akhir dari deployment model KNN ini adalah embedded code, perintah API, serta public dan private endpoint.  

### 2. Fitur Chatbot
Untuk fitur chatbot sendiri proses deploymentnya itu berupa proses publishing chatbot yang sudah selesai dibangun dan dikonfigurasi di IBM watson Assistant ke dalam Live Environtment. Hasil akhir dari publishing chatbot ini adalah embedded code dalam bentuk dalam bentuk snippet code JavaScript atau perintah API. 

<div style="text-align: center;">
  <h2>Result</h2>
</div>

### 1. Fitur Prediksi
![image](https://github.com/Yumnailahi04/Massive_Project_Group12_AAI/assets/154740771/83496cd8-7f27-4b0c-8c02-f1a707bdfd14)

### 2. Fitur Chatbot
![image](https://github.com/Yumnailahi04/Massive_Project_Group12_AAI/assets/154740771/aa14b954-2e2e-4695-bd98-96da527354cd)
  ![image](https://github.com/Yumnailahi04/Massive_Project_Group12_AAI/assets/154740771/040c284a-ec75-4d01-a011-225e3c814627)
 ![image](https://github.com/Yumnailahi04/Massive_Project_Group12_AAI/assets/154740771/8e05d7b8-0b5c-444d-b586-53839a29591d)

<div style="text-align: center;">
  <h2>Conclusion</h2>
</div>
Proyek ini mengembangkan solusi digital melalui StunCare Chatbot dan Sistem Prediksi Tingkat Kesehatan Status Gizi Bayi untuk mengatasi masalah stunting di Indonesia. StunCare Chatbot memanfaatkan teknologi AI untuk memberikan informasi dan edukasi tentang gizi anak serta pencegahan stunting kepada orang tua, sementara Sistem Prediksi menggunakan model klasifikasi AI untuk mengidentifikasi tingkat kesehatan status gizi bayi berdasarkan data umur, jenis kelamin, dan tinggi badan. Proyek ini bertujuan untuk menurunkan prevalensi stunting, meningkatkan kesadaran orang tua, memperluas akses informasi gizi, serta meningkatkan deteksi dini dan intervensi terhadap stunting.  
