# Book Recommendation

**Dibuat oleh : Wendi Kardian**

Project kedua membuat sistem rekomendasi untuk memenuhi submission project dari Dicoding, dalam kelas Machine Learning Terapan. Project ini membuat model machine learning yang dapat memberikan rekomendasi berdasarkan preferensi pengguna

![enter image description here](https://api.hub.jhu.edu/factory/sites/default/files/styles/soft_crop_1300/public/2022-12/book_array2.jpg)

## Domain Proyek

### Latar Belakang 

Di tengah perkembangan pesat teknologi informasi dan transformasi digital yang melibatkan penggunaan platform daring dan *e-commerce*, sistem rekomendasi menjadi elemen krusial dalam meningkatkan kualitas pengalaman pengguna. Pembuatan model *machine learning* untuk sistem rekomendasi buku menjadi suatu inisiatif yang strategis. Mengingat kemajuan pesat dalam produksi buku baik dalam format fisik maupun digital, pengguna seringkali dihadapkan pada tantangan besar untuk menavigasi pilihan yang sangat luas. Oleh karena itu, implementasi sistem rekomendasi buku dapat memberikan solusi cerdas dalam membantu pengguna menemukan buku yang sesuai dengan preferensi mereka, memotong hiruk-pikuk katalog yang semakin berkembang.

![enter image description here](https://www.grandviewresearch.com/static/img/research/us-books-market.png)
Gambar 1. Prediksi market industri buku di US 

Dalam industri *e-commerce* buku, organisasi terus berinvestasi dalam pengembangan sistem rekomendasi untuk meningkatkan personalisasi dan pengalaman pengguna. Penelitian menunjukkan bahwa implementasi sistem rekomendasi dapat meningkatkan retensi pelanggan dan penjualan. Terkait dengan pergeseran ke arah format digital, e-book dan audiobook terus mengalami pertumbuhan signifikan. Sistem rekomendasi dapat membantu pengguna menemukan konten yang sesuai dengan preferensi mereka di tengah meluasnya pasar buku digital. Industri buku semakin mengadopsi teknologi *machine learning*, termasuk *neural networks*, untuk meningkatkan akurasi rekomendasi. Hal ini mendorong perusahaan untuk mengintegrasikan solusi inovatif berbasis AI guna memenangkan persaingan pasar.

Pentingnya sistem rekomendasi buku tergambar dalam manfaatnya yang merata bagi berbagai pihak. Bagi pengguna, sistem ini memberikan kemudahan dalam menemukan buku baru yang sesuai dengan minatnya, menciptakan pengalaman yang lebih personal, dan mengoptimalkan waktu untuk pencarian. Di sisi lain, bagi penjual dan penerbit buku, sistem rekomendasi membuka peluang baru untuk meningkatkan penjualan dengan menyuguhkan rekomendasi yang cermat dan relevan. Analisis data dari preferensi pengguna juga dapat menjadi alat strategis dalam merancang pemasaran yang lebih efektif. Dengan begitu, industri buku dan *e-commerce* secara keseluruhan dapat mengalami pertumbuhan yang berkelanjutan melalui penerapan model rekomendasi yang canggih dan responsif terhadap kebutuhan pengguna.

Dari perspektif teknologi, pembuatan *model machine* learning untuk sistem rekomendasi buku menciptakan peluang bagi pengembang untuk memperdalam pemahaman mereka tentang pemrosesan data, pemodelan statistik, dan algoritma machine learning. Ini sekaligus mendorong inovasi dalam pengembangan teknologi AI. Sebagai akibatnya, dapat diharapkan bahwa perkembangan model ini tidak hanya memberikan dampak positif bagi pemangku kepentingan langsung, tetapi juga mendorong pertumbuhan dan evolusi seluruh ekosistem industri buku dan *e-commerce*. Dengan demikian, pembuatan model machine learning untuk sistem rekomendasi buku muncul sebagai langkah progresif yang mendukung efisiensi, inovasi, dan kenyamanan dalam menjelajahi dunia literasi.


## Businesss Understanding

  
Proyek ini bertujuan untuk mendukung perusahaan penerbit buku yang memiliki katalog buku yang luas, dengan fokus utama pada penyediaan sistem rekomendasi buku kepada konsumen. Sebagai perusahaan penerbit, memiliki tantangan dalam mengelola keragaman buku yang terus berkembang, sehingga implementasi sistem rekomendasi menjadi kritis untuk meningkatkan pengalaman pembaca dan memastikan bahwa setiap buku dapat ditemukan oleh pembaca yang potensial.

### Problem Statement : 
- Bagaimana dapat membangun model machine learning yang memahami dengan akurat preferensi pembaca untuk meningkatkan ketepatan rekomendasi buku?
- Apa langkah-langkah konkret untuk mengoptimalkan strategi pemasaran berdasarkan analisis data terkait tren pembacaan dan preferensi konsumen?
- Apa saja variabel dan data historis yang perlu dipertimbangkan dalam model untuk memberikan rekomendasi yang lebih personal dan relevan?


### Goals :
- Membangun model machine learning yang dapat menggambarkan dengan akurat preferensi pembaca berdasarkan data pengguna, ulasan, dan kesamaan jenis buku. Model ini diharapkan dapat meningkatkan ketepatan rekomendasi buku dan memberikan pengalaman personal yang lebih baik kepada pembaca.
- Melakukan analisis mendalam terhadap tren pembacaan dan preferensi konsumen menggunakan data yang ada
- Menciptakan pengalaman pembaca yang lebih personal dengan memanfaatkan data historis untuk merancang rekomendasi yang mempertimbangkan keunikan preferensi dan kesukaan masing-masing pengguna.
- Mengukur *precision* dan *recall* pada tingkat interaksi pengguna dengan rekomendasi. Dengan memberikan wawasan tentang seberapa akurat model dalam meramalkan buku yang benar-benar diminati dan relevan oleh pengguna.
- Mencapai tingkat akurasi yang tinggi pada model rekomendasi. Ini dapat diukur menggunakan metrik evaluasi seperti *Root Mean Squared Error* (RMSE) untuk membandingkan skor peringkat yang diprediksi dengan skor peringkat sebenarnya.

### Solution Statement

- Mengimplementasikan model machine learning yang memanfaatkan teknik pembelajaran mendalam, seperti algoritma *collaborative filtering* dan *content-based filtering*, untuk memproses data pengguna, ulasan buku, dan kesamaan jenis buku. 
- Melakukan analisis mendalam terhadap data historis pembacaan dan perilaku konsumen untuk mengidentifikasi tren signifikan dan pola preferensi. Dengan memanfaatkan teknik analisis statistik dan eksplorasi data, solusi ini akan memberikan wawasan yang mendalam mengenai preferensi konsumen dan membimbing perusahaan dalam merancang strategi pemasaran yang lebih cerdas dan efektif.
- Merancang sistem rekomendasi yang mampu memanfaatkan data historis secara unik untuk setiap pengguna, mempertimbangkan preferensi dan kesukaan masing-masing
- Meningkatkan akurasi model rekomendasi buku dengan fokus pada evaluasi tingkat interaksi pengguna, menggunakan metrik precision dan recall untuk memberikan wawasan mendalam tentang relevansi dan ketertarikan pengguna terhadap rekomendasi buku.
- Mengukur dan meningkatkan tingkat akurasi model dengan memanfaatkan metrik Root Mean Squared Error (RMSE), sehingga model dapat memberikan rekomendasi buku dengan skor peringkat yang lebih mendekati skor sebenarnya, meningkatkan kepuasan pengguna, dan kesuksesan proyek secara keseluruhan.

### Manfaat
Adapun manfaat dari pengembangan proyek *machine learning* ini adalah sebagai berikut : 
1.  **Dari Sudut Pandang Penulis/Penerbit:**
    
    -   Sistem rekomendasi yang lebih akurat dapat meningkatkan visibilitas dan penjualan buku, membantu penulis dan penerbit mengoptimalkan pendapatan dari karya-karya penulis.
    -    Analisis mendalam terhadap tren pembacaan memberikan wawasan tentang preferensi konsumen, memungkinkan penulis dan penerbit untuk lebih memahami tren pasar dan membuat keputusan penerbitan yang lebih cerdas.
2.  **Dari Sudut Pandang Pembaca:**
    
    -    Pembaca akan mendapatkan rekomendasi buku yang lebih sesuai dengan minat dan preferensi pengguna, menciptakan pengalaman membaca yang lebih pribadi dan memuaskan.
    -   Dengan rekomendasi yang lebih akurat, pembaca dapat menemukan buku-buku baru yang mungkin tidak akan pengguna temukan secara manual, memperkaya pilihan bacaan pengguna.
3.  **Dari Sudut Pandang Pemangku Kepentingan Lain (Misalnya, Platform *E-commerce*):**
    
    -    Rekomendasi yang personal dapat meningkatkan keterlibatan pengguna, menghasilkan retensi yang lebih baik, dan membantu platform mempertahankan basis pengguna.
    -    Analisis tren dan preferensi konsumen mendukung strategi pemasaran yang lebih efektif, mempercepat pertumbuhan platform dan penjualan buku.


## Data Understanding 

Dataset yang digunakan berasal dari https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset?select=Users.csv

### Informasi Dataset 
- Berbentuk CSV (*Comma separated values*)
- Terdapat 3 jenis dataset (Users.csv, Ratings.csv, Books.csv)


#### Dataset Books.csv
- Berukuran 271360 rows × 8 columns
- Terdiri dari *column*
1.  **ISBN (International Standard Book Number):** Merupakan kode unik yang digunakan untuk mengidentifikasi secara internasional suatu buku. Setiap buku memiliki ISBN yang berbeda, memudahkan dalam pelacakan dan pemasaran buku.
2.  **Book-Title:** Menyimpan judul dari buku tersebut. Informasi ini membantu dalam pengenalan dan identifikasi buku oleh pengguna atau sistem lainnya.
3.  **Book-Author:** Menyimpan nama atau nama-nama penulis buku. Informasi ini memberikan kredit kepada penulis dan memungkinkan pengguna untuk mencari buku berdasarkan penulis tertentu.
4.  **Year-Of-Publication:** Menyimpan tahun penerbitan buku. Informasi ini membantu dalam mengetahui seberapa baru atau lama suatu buku, yang bisa mempengaruhi preferensi pembaca.
5.  **Publisher:** Menyimpan informasi tentang penerbit buku. Nama penerbit memberikan wawasan tentang sumber dan kualitas penerbitan buku tersebut.
6.  **Image-URL-S, Image-URL-M, Image-URL-L:** Menyimpan URL (*Uniform Resource Locator*) dari gambar sampul buku dalam tiga ukuran berbeda (kecil, sedang, besar). Informasi ini digunakan untuk menampilkan gambar sampul buku dalam aplikasi atau platform online, memperkaya pengalaman visual pengguna. URL ke tiga ukuran memungkinkan penyesuaian tampilan sesuai kebutuhan.

#### Dataset Users.csv
- Berukuran 278858 rows × 3 columns
- Terdiri dari *column*
1.  **User-ID:** Merupakan identifikasi unik untuk setiap pengguna dalam dataset. User-ID digunakan untuk melacak dan membedakan satu pengguna dari pengguna lainnya, memungkinkan analisis dan personalisasi berdasarkan perilaku individu.
2.  **Location:** Menyimpan informasi lokasi atau alamat dari pengguna.
3.  **Age:** Menyimpan informasi usia pengguna

#### Dataset Ratings.csv
- Berukuran 1149780 rows × 3 columns
- Terdiri dari *column*
1.  **User-ID:** Merupakan identifikasi unik untuk setiap pengguna yang memberikan rating pada buku tertentu dalam dataset. User-ID digunakan untuk mengidentifikasi siapa yang memberikan rating dan memungkinkan analisis perilaku rating berdasarkan pengguna tertentu.
2.  **ISBN (International Standard Book Number):**  Kode unik yang digunakan untuk mengidentifikasi suatu buku yang diberi rating oleh pengguna. ISBN memungkinkan pengguna untuk merujuk pada buku tertentu dengan cara yang spesifik dan terstandar.
3.  **Book-Rating:** Menyimpan nilai rating yang diberikan oleh pengguna pada buku tertentu. Informasi ini memberikan wawasan tentang seberapa tinggi atau rendah pengguna menilai suatu buku.

#### Hubungan Antar Data
1. **Hubungan antara "books" dan "ratings":**

-   Kolom kunci yang menghubungkan kedua dataset ini adalah "ISBN". Dataset "ratings" menggunakan "ISBN" untuk merating buku. Oleh karena itu, data dapat menggambarkan hubungan *one-to-many* antara "books" dan "ratings" berdasarkan kolom "ISBN". Sebuah buku dari dataset "books" dapat memiliki beberapa rating di dataset "ratings".
2.  **Hubungan antara "users" dan "ratings":**
    
- Kolom kunci yang menghubungkan kedua dataset ini adalah "User-ID". Dataset "ratings" menggunakan "User-ID" untuk mengetahui siapa yang memberikan rating. dengan menggambarkan hubungan one-to-many antara "users" dan "ratings" berdasarkan kolom "User-ID". Seorang pengguna dari dataset "users" dapat memberikan beberapa rating di dataset "ratings".
3.  **Hubungan antara "books" dan "users":**
 - Tidak ada kolom yang secara langsung menghubungkan dataset "books" dan "users". Namun, melalui dataset "ratings", dengan dapat menghubungkan "books" dan "users" dengan menggunakan kolom "ISBN" dan "User-ID". Oleh karena itu, dengan menggambarkan hubungan one-to-many antara "books" dan "users" melalui dataset "ratings".

###  Exploratory Data Analyst

Sebelum melakukan pemrosesan data, ada baiknya untuk mengeksplor data untuk mengetahui keadaan data seperti mencari  _missing value_, menghapus fitur yang tidak relevan, menghapus duplikat pada kedua dataset,  _merging dataset_  dan menentukan fitur yang akan digunakan.

- *describe*() digunakan untuk menghasilkan ringkasan statistik deskriptif dari dataset ratings ataupun books. Fungsi ini memberikan gambaran cepat tentang distribusi statistik dari kolom-kolom numerik dalam dataset.

Tabel 1. Deskripsi Dataset Ratings

|       |      User-ID |  Book-Rating |
|------:|-------------:|-------------:|
| count | 1.149780e+06 | 1.149780e+06 |
|  mean | 1.403864e+05 | 2.866950e+00 |
|  std  | 8.056228e+04 | 3.854184e+00 |
|  min  | 2.000000e+00 | 0.000000e+00 |
|  25%  | 7.034500e+04 | 0.000000e+00 |
|  50%  | 1.410100e+05 | 0.000000e+00 |
|  75%  | 2.110280e+05 | 7.000000e+00 |
|  max  | 2.788540e+05 | 1.000000e+01 |


Tabel 2. Deskripsi Dataset books 
|        |       ISBN |     Book-Title |     Book-Author | Year-Of-Publication | Publisher |                                       Image-URL-S |                                       Image-URL-M |                                       Image-URL-L |                                       Image-URL-L |
|-------:|-----------:|---------------:|----------------:|--------------------:|----------:|--------------------------------------------------:|--------------------------------------------------:|--------------------------------------------------:|--------------------------------------------------:|
|  count |     271360 |         271360 |          271359 |              271360 |    271358 |                                            271360 |                                            271360 |                                            271357 |                                            271357 |
| unique |     271360 |         242135 |          102023 |                 202 |     16807 |                                            271044 |                                            271044 |                                            271041 |                                            271041 |
|   top  | 0195153448 | Selected Poems | Agatha Christie |                2002 | Harlequin | http://images.amazon.com/images/P/185326119X.0... | http://images.amazon.com/images/P/185326119X.0... | http://images.amazon.com/images/P/225307649X.0... | http://images.amazon.com/images/P/225307649X.0... |
|  freq  |          1 |             27 |             632 |               13903 |      7535 |                                                 2 |                                                 2 |                                                 2 |                                                 2 |

Berdasarkan hasil eksplorasi data pada dataset tersebut, beberapa temuan utama dapat diidentifikasi:

1.  **Books Dataset:**
    
    -   Jumlah total buku (ISBN) dalam dataset "books" adalah 271,360.
    -   Terdapat 242,135 judul buku unik (Book-Title) dalam dataset ini.
    -   Ada 102,023 penulis buku unik (Book-Author) yang terdaftar.
    -   Rentang tahun penerbitan (Year-Of-Publication) buku dalam dataset berkisar dari tahun 0 hingga tahun 202.
    -   Terdapat 16,807 penerbit unik (Publisher) dalam dataset.
2.  **Users Dataset:**
    
    -   Jumlah total pengguna (User-ID) dalam dataset "users" adalah 1,149,780.
    -   Rata-rata peringkat buku (Book-Rating) yang diberikan oleh pengguna adalah sekitar 2.87.
    -   Standar deviasi peringkat menunjukkan variasi yang signifikan dalam peringkat yang diberikan oleh pengguna.
3.  **Ratings Dataset:**
    
    -   Dataset "ratings" memiliki 1,149,780 entri, yang mencerminkan peringkat buku yang diberikan oleh pengguna.
    -   Peringkat buku bervariasi dari 0 hingga 10, dengan rata-rata peringkat sekitar 2.87.
    -   Terdapat beberapa pengguna yang memberikan peringkat 0, yang mungkin menunjukkan bahwa tidak semua pengguna memberikan peringkat untuk setiap buku.

- Check missing value pada dataset
**Missing value form books :**
 ISBN 0
 Book-Title 0 
 Book-Author 1
 Year-Of-Publication 0 
 Publisher 2 
 Image-URL-S 0 
 Image-URL-M 0 
 Image-URL-L 3
  dtype: int64 
  **Missing value form users** 
  User-ID 0
   Location 0 
   Age 110762 
   dtype: int64 
   **Missing value form ratings** 
   User-ID 0 
   ISBN 0 
   Book-Rating 0 
   dtype: int64
   Hapus column 'age' karena tidak dibutuhkan dalam data processing
   
   - Total jumlah unik ISBNs di 'Ratings' dataset: 340556
   -  Total jumlah unik UserIDs di 'Ratings' dataset: 105283

### Data Visualisasi

- Grafik countplot di bawah memvisualisasikan distribusi rating buku dalam dataset 'ratings', memberikan gambaran tentang sebaran frekuensi rating yang diberikan oleh pengguna pada buku-buku.
![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV87gfNlJMmrL-WmlKaD6UoY-KUcyw6W7qMQJoNWgt9WoltcABkemWp-BRYr1gNcW0b3qV60Crw7YpkOXlTAKEYv3g52njfAdC_hrguSbe6tCie2uTuAuA9vy0BT7SovxhrafHN1Fmnqu80sJ61XlLUa1FulBdky7HD9Zh6GBXMXrlx2XCXLDmSmbkzzcLldusxkQV04oPb57f4N6dLu2uE520Ujk_yGarpyRtA6TjmdpDeZWVdVm2g6EHQ3LvVS8nLWJzHlRNO7smnKzIeumURrstNq3JVmuMPii2kQfPeRbW9IJQmB_TsI3bqOe0AVp4rmPNqsABfX2GUS7StblgCAKqzIJ6h6Fb6rH9dMocaNpben4v7TLjgrddH-6xukw6r6juTR86N_JeGqw-kR-FtfgxZLKpBRAZrWgCZtBgh5KxzDG1jl7b32AwdTaHeFzo1-FiBo1u-PHw8z5Z8D8GjUHsJmJ72ne7czyxuaiX6FEfUksqTAONN1IjiBXstmL3nBARJOELAf4OZ2qnsI-7GmReY8I8RwJL4zmu0dZKaKzjOIshmSlnaa_QJaKDjmgCkUWl5sb9xbSRdD5rsRUVxevwslflgaxNo-ZNd6ONSkcpk2RmnnKJkhq0YGjM0uWIc5uin2mwYI6EEQagJlhBkdcC26Ny9Hjd-3A5BMr59oVncCSgqlZ3qNgRFv-sUmksU9rhienTYr61u5xTMIdZPjPxm_ex5uhSUBt61sDtcgU3bRJNJFMzBPbjiGy3xE8mAIG5hfiVzsOJNgcqiaeA1rpxE-Z500r2MK88F5FYAGi2_z0gUPAION_qn09oFrSAD-5uXkcb5reLR4P90SQS0QTaQ9E3DYyxPDw1I1rvB49tOdyYJWHAXVQwySqXJrNrw=w1031-h547-s-no-gm?authuser=0)
Gambar 1. Countplot distribusi rating buku

- Grafik batang di bawah menampilkan sepuluh penerbit teratas dengan jumlah buku terbanyak yang diterbitkan dalam dataset 'books', memberikan gambaran tentang kontribusi relatif masing-masing penerbit terhadap jumlah buku dalam dataset tersebut.

![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV87QkGpNkMM7wp6UaKTF-M1H0x_xZyAWfWIiLoWzVoYHejh1_pgHB3ZGnOx81-0dluUYVohezmRvjNmsfSOThOvNjtxhI-VGKn1VEjdgXCO_AAf9laTSGPu03zmmTwYzIjxLFPoEkAsZuA76v1JDmMqhazmeaKmlUecyu8oHFnMhe2Jn50I6q_LmMqPrf0OMNsuNxEmvYCyeiZhkUM9JeozF6h5Ih5AtjDGXtcMSybiD3zhDCspT5kjJ5N6XC3quGZpzqIWZhLJHa-sC5coCLovZIzx-3AhLGAyC9E2fJ51PanD7mAvAQbBHxB8Eff0C1vo5QBRB7uAiM2K-n0iLdH7lbB1mhxllE1JdjvwBx8cAZst6IN7WFtFby1jHzYJ7GyriplDsV9b8eCaMRbnkmSNmbg_6kofQXIW9toX_SOfFSCnocM3Biy4ob92eKY4BVfnHfz-w3oAjxojcpFsBdznrcHwvqzIZs2-8m1iz4FqJaGroexwujZ9Lu0UsiIixQA4VRQbc2A13wEsll_c6Qg8gq3jYwXR_EORjE-4JIi7O8gZIcJMSiZ_D0R2Crwy4g9QlAUjADNy44_lRxqc9byuaKLfirgwf2v76TwsBtlzU9xf62137hQdiQYIqfcHcgMJuRKYUA-hFYpu4rbsXndQOgoZ1sqY5lOsDFuhDy-eDxp5PcNh9ap5feGvmik3ZyVaH96-dk0pwqDvoMU32mXnNT1kRnT4aT6QMcQX0V8gQ8Rr1LCgXf9gaTtDxxlqz4xQGn051xm0PV1eSYcvP60AcvR1kbzU-EaK-zg_aKy63NZLw2muARxKDtVa68t8b8EdNEToYd1pmm0d8UfrsbxvPG0TBE_TO7l3eHXP8YFQqUZbe2xp8uUErFnOcXJKfXQ=w1153-h547-s-no-gm?authuser=0)
Gambar 2. Grafik batang publisher dengan banyak buku diterbitkan

- Grafik batang di bawah menampilkan sepuluh penulis teratas dengan jumlah buku terbanyak yang diterbitkan dalam dataset 'books', memberikan gambaran tentang kontribusi relatif masing-masing penulis terhadap jumlah buku dalam dataset tersebut.

![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV85ybFBReyuXMn48VuAphbDhJrOraH30CI81gxRoATeO-N9Y9J31BU0yRUXRGJwSMLG8rsUktXY5EMX-nhO5SNa6AkgSLFU0w-86QfXx8mcVEWbRlSZnSXdh89cLWSwTJxbwTNc9zaFt5khOVDAMZBY1cx1GUToDq4jHfecSOOlDAw-bj7H4Zbv3R15GSLZzYGO4PNZsKP3azCDo2eX1xrW2e1DTsNZrH__iPJ3nnMCKGKxCqFQ6wCs0RfH55dwDhN3fJS_PeCy7-Bpzbjq4Zi-RptlQ86nI9ZPkGsZ9T255DTu52iQdrZFUbAaMB4alFcm8LofxseSir2Q5vs6qkCPlRdAsAWiMjFKKkpM4A08BByC0RMfXON5al9tKbpyUCmzDdG65HR6MU_Hw5NSTg0yS0ur-53wvd0T2ItgMTE4A9YvatJoTu7irq5mkztFltfqvtPPU_4BiYFMRK_wtx2BbGLAb3-TjgNgS_t4wUROEhKRKskAcup4MX0HH_Webf9qi6Dw0YTTGlMqVDeb1j04dwBVMZTX1mr7_THmodOpuQdPeq8-PKDRDk7W7jTjjYQE_Rnbqfvf9zaoiVh3Atmb8GpH-WxfTTliBq2PgTuuRdg38R6jy3Yydr9lMVi1Ayzo2WMzzzt8eJbWt5s6fswVKDbEx_vTzoYIkwwKPOZ-yjac9FIIkxMtZcoW4SXjwzPuRWjiiUj_BztG61yKNk9YK0WxdTRvcm7o0xPF4vDlSoJbTbq9PoeOjjJKdNrdHRFnT3MWo9fElqs7lu3Lc9-L2pNLe5QmtVJHEPYKvQXUcVnZL1wPYFSEEy96UaNpxtX9MICmwCMMSv1Meft723q8yR5F4RpsmLNxW1JBLaBV1lO0pvpn7LdRZcTrKbifgmw=w1124-h547-s-no-gm?authuser=0)
Gambar 3. Grafik batang penulis dengan buku terbanyak

- Grafik batang di bawah menampilkan sepuluh pengguna teratas dengan jumlah rating terbanyak yang diberikan dalam dataset 'ratings', memberikan gambaran tentang kontribusi relatif masing-masing pengguna terhadap jumlah rating dalam dataset tersebut.
![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV86yXOu3OKAEW4H-teMPH6H6gqq3DIjEli7GQpDlx7waIOKyJ5uKjI9vNZsHa4CO_wzWko2AqvxCzvth-2OHyH1a8AhAJokceIsNWGaPpFcvn906YYZsBZkPDfkWbLslsGXgJF2KJu6Dn_7d3O3Mt1Z_JPkTzOJO4cVWN5bBzX-4Cf_Tv4RZlmtQDh-U6AULiXEqO1o6bXHwqZASUpUpoHaKiG5t4jPijlQR2L5V3EP1LABGAE23l-jgOlV0zpatmbfJpYK64JWM9uOGHqG6IgBOo_H01ovz2pgHFs4LhNod2TTSSQUhd96Bi52Bwah-m0Yt-C9iA5UGYsT5xfSgjTBRnuZeakw62_xxbict6Zg7mFCym1r-u3_CFOISg_6GjkaBmCp5yUJp4uao7LLRLoA2pIsS5hmPRUoZfJZ46tb08mHtI0_4GdFU9YA98UxrErC_XWbQG6LTg5_h1l61xLJoTXSPtkCsPRdpGUIjwXncF9XlK7-ZIbAjCyVOij7kIrdz6Sn7VUm0KrzOfZxYsfgCgcvrCqaO5DapSHxMR3J7afzZgQy6qXcugyueEdlXR9RMUnm_9Vvha-YJTSLDyDkpMQNIRXyWNkYwp36TWerlpHmtIIstWjEsca4G2jzFMKiLRPFjMDuPot6Dym4RVTziv14U4RoITjhk8yIDwMMrWUPEsLRxn9fBRvOUo2svChztz-mwyXAiTFs7xJ1sGPHDd59G4CFJ617AlbBPPquOrlog5sUCNEg6K6sSuVpAlE9Vpe1h_UaJCjf7XKeyIqqSyG6j-e6JtPQt19WzcUc8l4nb3DE9CGMplxRpsw1ybQyH7lhAhWAywx5JIatbAa_BNhpUE4HsJMfK4n0BEjSp6Lte_Thpwpn-h_Ht-Lm2Xw=w1023-h547-s-no-gm?authuser=0)
Gambar 4. sepuluh pengguna teratas dengan jumlah rating terbanyak

- Grafik batang di bawah menampilkan sepuluh buku teratas dengan jumlah rating terbanyak dalam dataset, memberikan gambaran tentang popularitas relatif masing-masing buku berdasarkan jumlah rating yang diberikan oleh pengguna.
![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV85P4JuyWrwrvLuIMEKbUkPf_9ufbAo8tTUXQk4IweBziC7yuhbf9lTYuTM5SxT_fvOGjSoBwWpgdHHbkimYo7dcXt-oMK8fblAhiC-kC4mgoghVvXcF3LHIwG4f2YsxDORUpINXRCyaHL4ne9sdv6QwY0HNlW-iITEc_Ybf5Tf9qSj1Fo_p1h51S8vMP2_CjdaH2_tBKCvEoeLBgxCUZ43GzGOm54CIWS5PBYOTQ7J04jjWmbW45fh5YaAxEAErOeWdgZslZm7n2MDyfuloNz_ry8eRXWjE1RklpdT3f8dRzrqIjSFTr6zKTP5HT7mVfH3HOYxnpOcgnYh-LOyhJsch1SX5OtsJuwpmqXmQ2bXn-R_uAsQRdUqU3kh4EakJwPEQGb_szgzIW5x9dAkJoQFJsPALWYVOsIy22jOLcZuCSSwnqJbmFVHUVlhoLuJdIy38QXU4UZTjvPiM2ebe74Iap6IKXIlDGvkIU82PN6Ea_EPVOGHlCy404XJm2jEA1UbaGeHWGVQAMnEefMwh-QSCzIuyD2feB20ZEyLQbcF4_X7VyMdBLjapvhQByf9jKFMqU-05OqQw3UvtvH64TH-BOhNdHXu76JihCJnuAT0Baq8jsKQZNhOVWdyMkdNdfRoN9VDX0xBaaa4uH3z4s5OR5KjGP3RbmAVsLdZ0hqD6IywpSHkOEc4bIqTfpt_fAdCCzqrxe3XijkjoqbE4ni6caIdNysB_9zqbV_6-EXWOPI2LuNUVMIuaHk08B8ptKsT-cCeKDqQt90lmC2vd_Tez_eyKMikaD9IRzvwJqSqumTAhwC1omB_3XwwWKFP2a5l7ywW3Zj1RETjXt08VlyaxlVrYXc9NPCYJtXV2xC6v-2JZMVZli6eGiIw1Z09a_A=w1341-h547-s-no-gm?authuser=0)
Gambar 5. Sepuluh buku teratas dengan jumlah rating terbanyak 

## Data Preparation

### Untuk *Content Based Filtering*

- **Merge Dataset**
penggabungan (merge) antara dataset ratings dan books berdasarkan kolom ISBN, dan menampilkan dimensi (shape) dari kedua dataset sebelum dan setelah penggabungan.
Dengan hasil : 
**before merged**
ratings shape: (1149780, 3)
Books shape: (271360, 8)
**after merged:** 
(1031136, 10)
Dengan bentuk dataset

Tabel 3. Dataset hasil penggabungan
|   | User-ID |       ISBN | Book-Rating |           Book-Title | Book-Author | Year-Of-Publication |        Publisher |                                       Image-URL-S |                                       Image-URL-M |                                       Image-URL-L |
|--:|--------:|-----------:|------------:|---------------------:|------------:|--------------------:|-----------------:|--------------------------------------------------:|--------------------------------------------------:|--------------------------------------------------:|
| 0 |  276725 | 034545104X |           0 | Flesh Tones: A Novel |  M. J. Rose |                2002 | Ballantine Books | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... |
| 1 |    2313 | 034545104X |           5 | Flesh Tones: A Novel |  M. J. Rose |                2002 | Ballantine Books | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... |
| 2 |    6543 | 034545104X |           0 | Flesh Tones: A Novel |  M. J. Rose |                2002 | Ballantine Books | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... |
| 3 |    8680 | 034545104X |           5 | Flesh Tones: A Novel |  M. J. Rose |                2002 | Ballantine Books | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... |
| 4 |   10314 | 034545104X |           9 | Flesh Tones: A Novel |  M. J. Rose |                2002 | Ballantine Books | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... | http://images.amazon.com/images/P/034545104X.0... |

- ***Grouping* dataset berdasarkan ISBN dan User-ID**
Data telah dikelompokkan berdasarkan ISBN dan User-ID dalam dataset 'books_ratings_collab', dan nilai rata-rata dari kolom 'Book-Rating' dihitung untuk setiap kelompok.

Tabel 4. Hasil *grouping* dataset
|   |       ISBN | User-ID | Book-Rating |
|--:|-----------:|--------:|------------:|
| 0 | 0000913154 |  171118 |         8.0 |
| 1 | 0001010565 |   86123 |         0.0 |
| 2 | 0001010565 |  209516 |         0.0 |
| 3 | 0001046438 |   23902 |         9.0 |
| 4 | 0001046713 |  196149 |         0.0 |

- Dataset 'books_ratings_clean' dibuat dengan menghapus baris yang mengandung nilai kosong (NaN) dalam dataset 'books_ratings_collab', sehingga menghasilkan dataset yang lebih bersih dan tidak mengandung missing values.

- Menghilangkan data duplikat berdasarkan ISBN
Dataset 'preparation' dibuat dengan menghilangkan duplikat buku berdasarkan nilai ISBN dalam dataset 'books_fix', sehingga setiap buku hanya muncul sekali dalam dataset persiapan tersebut.

- DataFrame 'book_new' dibuat dengan menggunakan list 'book_ISBN', 'book_title', 'book_author', dan 'book_publisher'. DataFrame tersebut kemudian diurutkan berdasarkan kolom 'author' secara menaik dan hanya menyertakan 50,000 baris pertama.
Dengan bentuk dataset menjadi : 
Tabel 5. Dataset final untuk *content based filtering*

|        |       isbn |                                             title |                           author |              publisher |
|-------:|-----------:|--------------------------------------------------:|---------------------------------:|-----------------------:|
|  36236 | 0312956762 |              Die Hard: With a Vengeance - A Novel |                         D. Chiel |          St Martins Pr |
|  45889 | 034545006X |                                        The Taking |                     J. D. Landis |       Ballantine Books |
| 232474 | 1579651372 |              Ruskin's Rose: A Venetian Love Story |                      Mimma Balia |     Artisan Publishers |
|  88069 | 0440416361 |                         Nsync : The Official Book |                          'N Sync |        Delacorte Press |
| 216006 | 0972066713 | The Mom-to-Mom Guide to the Baby Years: Review... | 142 moms from all over the world | Sound Bite Press, Inc. |

### Untuk *Collaborative Filtering*

- membuat pemetaan unik antara User-ID dalam dataset ke representasi numerik, baik dari User-ID ke indeks (encoded) maupun sebaliknya, menggunakan dictionary dalam Python.
- membuat pemetaan unik antara ISBN buku dalam dataset ke representasi numerik, baik dari ISBN ke indeks (encoded) maupun sebaliknya, menggunakan dictionary dalam Python.
- Menambahkan dua kolom baru, 'user' dan 'book', ke dalam DataFrame 'df', yang merupakan representasi numerik dari User-ID dan ISBN berdasarkan pemetaan yang telah dibuat sebelumnya (user_to_user_encoded dan book_to_book_encoded).
Tabel 6. Hasil pemetaan data

|       | User-ID |       ISBN | Book-Rating | user |  book | rating |
|------:|--------:|-----------:|------------:|-----:|------:|-------:|
| 33553 |    7930 | 0679751521 |           8 | 3745 |  1730 |    8.0 |
|  9427 |  278798 | 0345460359 |           0 |  825 |  8864 |    0.0 |
|  199  |  276847 | 347354034X |           7 |   48 |   198 |    7.0 |
| 12447 |    1211 | 0723206015 |           0 | 1265 | 11278 |    0.0 |
| 39489 |    9660 | 0440193613 |           5 | 4354 |  1599 |    5.0 |

- Membagi data untuk pelatihan model *neural network*
Mempersiapkan data untuk pelatihan model rekomendasi, dengan mengubah nilai rating ke dalam rentang [0, 1] menggunakan normalisasi dan membagi dataset menjadi data pelatihan (x_train, y_train) dan data validasi (x_val, y_val)


## Modeling

### Pendekatan Content Based Filtering 

Content-based filtering merupakan salah satu metode dalam sistem rekomendasi yang menggunakan informasi terkait konten atau karakteristik item untuk membuat rekomendasi kepada pengguna. Content-based filtering dengan TF-IDF, TF-IDF (Term Frequency-Inverse Document Frequency) digunakan untuk mengukur pentingnya sebuah kata atau istilah dalam suatu dokumen atau konten.

1.  **TF-IDF (Term Frequency-Inverse Document Frequency):**
    
    -   **Term Frequency (TF):** Mengukur seberapa sering sebuah kata muncul dalam suatu dokumen. Ini memberikan bobot yang lebih tinggi pada kata-kata yang muncul lebih sering dalam dokumen tersebut.
    -   **Inverse Document Frequency (IDF):** Mengukur seberapa unik sebuah kata dalam seluruh koleksi dokumen. Kata-kata yang umum, seperti kata hubung, diberi bobot yang lebih rendah, sementara kata-kata yang lebih spesifik menerima bobot yang lebih tinggi.

3.  **Keunggulan:**
    
    -   Content-based filtering memungkinkan pemberian rekomendasi yang lebih personal karena mempertimbangkan preferensi pengguna yang telah terbentuk dari sejarah rating atau interaksi sebelumnya.
    -   Tidak bergantung pada data pengguna lain atau kolaborasi, sehingga cocok untuk kasus-kasus ketika data pengguna bersifat terbatas atau tidak tersedia.
4.  **Keterbatasan:**
    
    -   Bergantung pada kualitas deskripsi atau atribut konten yang digunakan untuk membuat vektor TF-IDF. Jika deskripsi tidak cukup informatif, kualitas rekomendasi dapat menurun.
    -   Tidak dapat memberikan rekomendasi untuk item yang tidak memiliki konten yang diukur oleh model.

Content-based filtering dengan TF-IDF dapat diimplementasikan menggunakan berbagai teknologi, termasuk pemrograman Python dengan menggunakan library seperti scikit-learn untuk perhitungan TF-IDF dan pengembangan model.

Dalam content-based filtering dengan menggunakan metode Term Frequency-Inverse Document Frequency (TF-IDF), setiap item dan pengguna direpresentasikan sebagai vektor TF-IDF. Vektor ini mencerminkan bobot kata-kata atau istilah yang signifikan dalam setiap dokumen atau preferensi pengguna. Selanjutnya, untuk menilai kesamaan antara pengguna dan setiap item, digunakan metode cosine similarity.

![sik](https://miro.medium.com/v2/resize:fit:1400/1*LfW66-WsYkFqWc4XYJbEJg.png)
Gambar 7. Formula *cosine similarity*

 Proses perhitungan cosine similarity memungkinkan pengukuran sejauh mana dua vektor mirip, di mana nilai 1 menunjukkan kesamaan yang sempurna dan nilai -1 menunjukkan ketidaksamaan yang sempurna. Dengan menghitung cosine similarity antara vektor representasi pengguna dan vektor representasi setiap item, sistem rekomendasi dapat merangkum item yang paling sesuai dengan preferensi pengguna. Item kemudian diurutkan berdasarkan nilai cosine similarity, dan yang memiliki nilai tertinggi direkomendasikan kepada pengguna sebagai pilihan yang paling relevan. Melalui pendekatan ini, content-based filtering dengan TF-IDF dan cosine similarity memberikan solusi rekomendasi yang lebih personal dan dapat disesuaikan berdasarkan karakteristik konten dan sejarah preferensi pengguna.

Cosine similarity dengan metode TF-IDF memiliki keunggulan dalam memberikan pengukuran kesamaan yang robust, skalabilitas tinggi untuk data dengan dimensi tinggi, serta integrasi yang baik dengan relevansi kesamaan antara vektor. Kelebihan lainnya mencakup kemampuan untuk memperhitungkan hubungan antara atribut, fleksibilitas dalam menangani data bervariasi, dan ketidakpengaruhannya oleh panjang vektor. Dengan demikian, cosine similarity meningkatkan akurasi dan relevansi rekomendasi, menjadikannya pilihan yang efektif dalam menyajikan item yang paling sesuai dengan preferensi pengguna.

### Contoh hasil rekomendasi 

Dalam pengujian sistem rekomendasi buku menggunakan contoh input buku **"Delta Blood" karya Barbara Ferry Johnson**, sistem menganalisis kesamaan karakteristik kontennya, khususnya pada atribut judul dan penulis. Setelah menganalisis, sistem memberikan rekomendasi berdasarkan kemiripan konten dengan buku input. Sebagai contoh, hasil rekomendasi mencakup buku-buku seperti "Homeward Winds the River," "Tara's Song," "The Heirs of Love," "Christian Acts of Kindness," dan "Living Somewhere Between Estrogen and Death," yang semuanya merupakan karya dari penulis yang sama, Barbara Ferry Johnson. Rekomendasi ini didasarkan pada kesamaan karakteristik konten, termasuk judul dan penulis, yang dianggap relevan dan dapat menarik bagi pengguna yang menyukai buku "Delta Blood." Dengan demikian, sistem dapat memberikan rekomendasi yang personal dan sesuai dengan preferensi pengguna berdasarkan analisis konten buku yang diinputkan.

Berikut adalah tabel hasil rekomendasi : 
Tabel 7. Contoh hasil rekomendasi 
|   |                                       title | author                |
|--:|--------------------------------------------:|-----------------------|
| 0 |                    Homeward Winds the River | Barbara Ferry Johnson |
| 1 |                                 Tara's Song | Barbara Ferry Johnson |
| 2 |                           The Heirs of Love | Barbara Ferry Johnson |
| 3 |                  Christian Acts of Kindness |       Barbara Johnson |
| 4 | Living Somewhere Between Estrogen and Death |       Barbara Johnson |

### Collaborative Filtering

Dalam *collaborative filtering*, model berusaha memahami pola preferensi pengguna dan karakteristik item berdasarkan data historis interaksi pengguna dengan item. Pada model ini, representasi vektor embedding digunakan untuk mewakili pengguna dan item, dan interaksi direpresentasikan melalui fungsi aktivasi sigmoid.

Model ini memiliki dua jenis embedding: embedding untuk pengguna (`user_embedding`) dan embedding untuk buku (`book_embedding`). Embedding ini digunakan untuk merepresentasikan pengguna dan buku dalam ruang vektor dengan dimensi `embedding_size`. Proses pembelajaran dari model ini terjadi melalui pembobotan dari embedding dengan menerapkan lapisan `Embedding` dari TensorFlow. Pembobotan ini memungkinkan model untuk menggambarkan preferensi pengguna dan karakteristik item secara lebih abstrak dan relevan.

Selain embedding, model juga memasukkan informasi bias untuk pengguna (`user_bias`) dan buku (`book_bias`). Ini membantu model untuk mengkoreksi perbedaan inherent dalam preferensi pengguna dan popularitas item. Fungsi aktivasi sigmoid diterapkan pada hasil dari produk dot (tensordot) antara embedding pengguna dan buku, serta ditambah dengan bias pengguna dan buku. Hal ini menghasilkan output yang berada dalam rentang 0 hingga 1, yang dapat diinterpretasikan sebagai probabilitas bahwa pengguna akan menyukai buku tersebut.

Model *collaborative filtering* ini memanfaatkan representasi vektor yang dipelajari untuk merekomendasikan buku baru kepada pengguna berdasarkan kesamaan preferensi dengan pengguna lain. Proses pembelajaran model ini melibatkan optimisasi parameter embedding dan bias untuk meningkatkan akurasi rekomendasi. Dengan demikian, model ini memberikan pendekatan yang kuat untuk merepresentasikan dan memahami hubungan antara pengguna dan item.

#### Contoh Pengujian hasil rekomendasi dengan teknik Collaborative Filtering


Showing recommendations for users : 51655
book with high ratings from user
A Sudden Change of Heart : Barbara Taylor Bradford
 -------------------------------- Top 10 book recommendation ----------------------------
 Tears of the Giraffe (No.1 Ladies Detective Agency) : Alexander McCall Smith 
 Queen of the Darkness (Black Jewels Trilogy) : Anne Bishop 
 The Poisonwood Bible : Barbara Kingsolver 
 Small Wonder: Essays : Barbara Kingsolver 
 Prodigal Summer : Barbara Kingsolver 
 Notes From a Small Planet : Bill Bryson 
 The Watsons Go to Birmingham - 1963 (Yearling Newbery) : CHRISTOPHER PAUL CURTIS 
 The Alienist : Caleb Carr Sister of My Heart : Chitra Banerjee Divakaruni 
 Dragonfly in Amber : DIANA GABALDON

Hasil rekomendasi di atas menunjukkan buku dengan judul **"A Sudden Change of Heart" oleh Barbara Taylor Bradford** yang memiliki rating tinggi dari pengguna dengan ID 51655. Selanjutnya, ditampilkan sepuluh buku rekomendasi teratas untuk pengguna tersebut berdasarkan teknik *collaborative filtering*.

Rekomendasi tersebut dihasilkan dari pemodelan dan analisis pola preferensi pengguna dengan menggunakan *collaborative filtering*. Teknik ini memanfaatkan informasi dari interaksi pengguna dengan buku-buku lain untuk menyaring dan mengidentifikasi item-item yang kemungkinan besar akan disukai oleh pengguna yang bersangkutan. Pemilihan buku rekomendasi dilakukan berdasarkan kesamaan preferensi dengan pengguna lain yang memiliki skor peringkat tinggi untuk buku yang sama atau serupa.

Evaluasi *Collaborative Filtering* (CF) dilakukan dengan menggunakan metrik precision, recall, dan F1 Score. Precision mengukur seberapa banyak dari buku yang direkomendasikan oleh sistem yang benar-benar sesuai dengan preferensi pengguna. Recall mengukur sejauh mana sistem dapat mengidentifikasi dan merekomendasikan buku yang benar-benar diminati oleh pengguna dari total buku yang seharusnya direkomendasikan.

## Evaluation

### Content Based Filtering 
1. **Precision**
Precision mengukur proporsi item yang direkomendasikan yang benar-benar disukai oleh pengguna. Dalam konteks content-based filtering, precision dapat dihitung sebagai jumlah item yang benar-benar relevan (direkomendasikan dan disukai) dibagi dengan jumlah total item yang direkomendasikan.

*Precision=Jumlah Total Buku yang Direkomendasikan / Jumlah Buku Relevan yang Direkomendasikan​*

2. **Recall**
-   Recall mengukur sejauh mana sistem dapat mengidentifikasi semua item yang benar-benar relevan dari semua item yang seharusnya direkomendasikan.
-   Recall dapat dihitung sebagai jumlah buku relevan yang direkomendasikan dibagi dengan total jumlah buku yang seharusnya direkomendasikan (termasuk yang sesuai dengan "Delta Blood").

*Recall=Jumlah Total Buku yang Seharusnya Direkomendasikan / Jumlah Buku Relevan yang Direkomendasikan​*

-   **Skenario Pengujian:**
    
    -   **Input:** Buku "Delta Blood" karya Barbara Ferry Johnson.
    -   **Output:** Daftar rekomendasi buku.
    -   **Expected Relevant Books:** Buku-buku yang seharusnya relevan dengan "Delta Blood" berdasarkan karakteristik kontennya (penulis).
-   **Perhitungan Precision dan Recall:**
    
    -   Dengan menggunakan daftar rekomendasi dan buku-buku yang seharusnya relevan, dapat menghitung precision dan recall dengan rumus di atas.
-   **Interpretasi Hasil:**
    
    -   Precision dan recall yang tinggi menunjukkan kinerja yang baik dalam merekomendasikan buku yang sesuai dengan preferensi pengguna.
    - Dengan hasil sebagai berikut :
	    - Average Precision: 0.8
	    -  Average Recall: 0.8

Dengan cara ini,  dapat mengevaluasi sistem rekomendasi buku berbasis konten untuk memastikan bahwa rekomendasi yang diberikan memiliki tingkat akurasi (precision) yang tinggi dan kemampuan untuk mencakup sebagian besar buku yang seharusnya relevan (recall).


### Collaborative Filtering

![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV84wj64U5JTYlmEq_5PxPb2YFjf8z6XIpIyRmuZxv95jIS8Lk3v_o0PQKmAxzSF3wt3sYKWD3vDfv8fq40x9IVA57ilKYvZdT0R4Ihehp5ZP_YSP5jsYmmIPbrO4jbph1sy3viNQq1zt4OwHqU3_L3lV8qAb5ELcJRK8KuaxKMmfTlglF1gWSijM3-Tg1ohKlhHPodH6K2YlOy6myTbJS6ZiAR1pWL0FgaD9h2V36JVJrPTkTPMRoNoVZKsfmvidfeizSYgGnjy3-ZJHeR_HhC8-xxOXTRLJnbTVm2NmgjgY6DPZ-nXBhu5mrDmxCzIiguX39vDP-GJX1xCeii_RhwJ9X6SbIQvgvpB49N-GyA4IOpKhHBmDrfPbO-oJ-LactQCpHSPacFMArAG4ln05EFxktw42s9z_7bqYtSugR255XE_PEIFawc_6-JmwcJIy2nOPtdF3yvAgOYq5G1vf6E4RbuglXljY3kCSskO1XoVc5Q_oM13CIh6jFjXZ7XRqnyhJerln6LaUEiAkMrbCj8alTiim8KZCSa01JgqqpjXvp8JN0Cyd4Ba38exOI2nMHfHPoSZIlFc7f49veksQJU7Q84K4WHe3G9Jo1cEW7_gn141oTS_kdMeLODkN1EGxRYfZpSq2kssUKowFOELDpnAtWhyYRnGMo9Cvi86FIZB4GjEHNLkMavhUZlRDzg366oASOPN-0MaUPYGY2_fJktp2kWbTVOr_VXSG0N3DE3HOo1UJOY4v_xGcNGYUUpsJmRqSxQFIxP6dOb45R6dXfq4I_XLQ10ElyLCFrCzoPsuwWGYqWoeLcC8wF6hmOS0CUqfTkIInk7RzITKDZMxvJqpwv8HWlfuhtL29dmH9UgJ4wMcaJP29T_RvO4O6gMrI-A=w576-h455-s-no-gm?authuser=0)
Gambar 8. Hasil evaluasi model *neural network*

Grafik evaluasi model neural network untuk *collaborative filtering* menunjukkan perbandingan antara kinerja model pada data pelatihan dan data validasi sepanjang proses pelatihan. Metrik `root_mean_squared_error` digunakan sebagai penilaian, dengan tujuan mengukur sejauh mana model mampu mereplikasi skor peringkat yang sebenarnya dari interaksi pengguna dengan item dalam dataset. Melalui grafik tersebut, dengan mengamati tren penurunan nilai metrik pada kedua kurva, mengindikasikan upaya model untuk meminimalkan kesalahan prediksi dan meningkatkan akurasi rekomendasi.

Grafik yang ideal mencerminkan konvergensi antara kurva train dan test, menandakan bahwa model dapat menggeneralisasi dengan baik ke data baru. Peningkatan performa pada kurva validasi menunjukkan bahwa model dapat secara efektif memperkirakan skor peringkat yang mendekati nilai sebenarnya. Evaluasi ini memberikan pemahaman yang lebih baik tentang kemampuan model *collaborative filtering* dalam memberikan rekomendasi yang relevan dan akurat, dengan harapan dapat meningkatkan pengalaman pengguna dalam menemukan buku yang sesuai dengan preferensinya.

-----
  #### Hasil pengujian F1 Score, Precision, dan Recall Collaborative Filtering
Precision: 0.3283318623124448
Recall: 0.484375
F1 Score: 0.39137296159915835

  
Dalam pengujian model rekomendasi menggunakan collaborative filtering, hasil metrik evaluasi seperti Precision, Recall, dan F1 Score memberikan gambaran tentang seberapa baik model dapat merekomendasikan buku dengan mempertimbangkan relevansi dan kelengkapan rekomendasinya. Dalam kasus spesifik ini, nilai Precision sekitar 0.33 menunjukkan bahwa sekitar 33% dari rekomendasi yang diberikan oleh model benar-benar relevan. Sementara itu, nilai Recall sekitar 0.48 menunjukkan bahwa model dapat mengidentifikasi sekitar 48% dari keseluruhan buku yang seharusnya direkomendasikan. F1 Score, yang merupakan gabungan harmonis dari Precision dan Recall, menyediakan metrik terpadu sebesar 0.39.

#### Hasil Perbandingan 

Dalam perbandingan kinerja antara Content Based Filtering (CBF) dan Collaborative Filtering (CF), dapat diamati bahwa CBF memiliki hasil evaluasi yang lebih baik. Average Precision dan Average Recall pada CBF masing-masing mencapai 0.8, menunjukkan tingkat ketepatan dan kelengkapan yang tinggi dalam merekomendasikan buku berdasarkan konten dan fitur buku yang serupa. Dalam konteks ini, CBF berhasil memberikan rekomendasi yang sangat sesuai dengan preferensi pengguna.

Di sisi lain, Collaborative Filtering (CF) memberikan nilai Precision sekitar 0.33, Recall sekitar 0.48, dan F1 Score sekitar 0.39. Meskipun CF dapat memberikan rekomendasi yang relevan, kinerjanya tidak sebaik CBF dalam hal ketepatan dan kelengkapan. Dalam hal ini, CF mungkin mengalami kendala karena ketergantungan pada kemiripan antarpengguna atau antaritem yang mungkin sulit diukur atau terbatas oleh data pengguna yang tersedia.

Berikut adalah tabel perbandingan metrik evaluasi antara CBF dan CF:

Tabel 8. Perbandingan Hasil
| Metrik               | Content Based Filtering (CBF) | Collaborative Filtering (CF) |
|----------------------|--------------------------------|-------------------------------|
| Precision            | 0.8                            | 0.33                          |
| Recall               | 0.8                            | 0.48                          |
| F1 Score             | -                              | 0.39                          |

Dengan melihat perbandingan ini, dapat disimpulkan bahwa CBF lebih unggul dalam memberikan rekomendasi buku yang sesuai dengan preferensi pengguna dibandingkan dengan CF dalam kasus ini.

## Kesimpulan


Sistem rekomendasi ini berhasil mengimplementasikan dua pendekatan utama, yaitu *collaborative filtering* dan *content-based filtering*, untuk meningkatkan kualitas rekomendasi buku. Dengan memanfaatkan model *machine learning* berbasis *neural network*, metode *collaborative filtering* dapat mereplikasi pola interaksi pengguna dengan item, sementara *content-based filtering* menggunakan representasi vektor *TF-IDF* untuk menggambarkan karakteristik unik dari setiap buku.

Analisis mendalam terhadap data historis pembacaan dan perilaku konsumen memberikan wawasan yang signifikan terkait tren dan pola preferensi. Dengan menerapkan teknik analisis statistik dan eksplorasi data, solusi ini dapat memberikan pemahaman yang mendalam mengenai preferensi konsumen, membimbing perusahaan dalam merancang strategi pemasaran yang lebih cerdas dan efektif.

Sistem rekomendasi ini dirancang untuk memberikan rekomendasi yang lebih personal, mempertimbangkan preferensi dan kesukaan unik dari setiap pengguna. Penerapan model *machine learning* yang adaptif dan dapat mengenali pola-pola yang kompleks dari data historis membantu meningkatkan akurasi dan relevansi rekomendasi. Dengan demikian, solusi ini membawa dampak positif bagi perusahaan dalam meningkatkan pengalaman pengguna, memperluas jangkauan pasar, dan mendukung pengambilan keputusan yang lebih cerdas.

## Daftar Pustaka

- Ahmed, E., Letta, A. (2023). Book Recommendation Using Collaborative Filtering Algorithm. Applied Computational Intelligence and Soft Computing :1-12 DOI:10.1155/2023/1514801
- Alkaff, M., Khatimi, H., & Eriady, A. (2020). Sistem Rekomendasi Buku Menggunakan Weighted Tree Similarity dan Content Based Filtering. Jurnal Manajemen, Teknik Informatika dan Rekayasa Komputer, 193-202.
- Bachhav, A., et al. (2022). Book Recommendation System using Machine learning and Collaborative Filtering. International Journal of Advanced Research in Science, Communication and Technology (IJARSCT).  279 - 283
- Kaddam, N., & Kumar, S. (2016). A review of Content and Collaborative filtering approaches on Movielens Data. International Research Journal of Engineering and Technology (IRJET), 273-278.
- Mishra, H., & Asthana, A. (2022). Book Recommendation System. International Research Journal of Engineering and Technology. 2953 - 2961 
- Shao, B., Li, X., & Bian, G. (2020). A survey of research hotspots and frontier trends of recommendation systems from the perspective of knowledge graph. Expert Systems with Applications, 1-20.

