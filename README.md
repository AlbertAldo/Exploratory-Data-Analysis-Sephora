# Exploratory-Data-Analysis-Sephora

### DEFINE PROBLEMS :
- Meningkatkan Penjualan SEPHORA E-Commerce melalui Brand SEPHORA COLLECTION yang berfokus pada Online Store.

### EDA GOALS :
- Mencari tahu apakah Penjualan SEPHORA pada Brand SEPHORA COLLECTION sudah berfokus pada Online Store atau belum.
- Mencari tahu category apa saja yang paling diminati, cukup diminati, dan kurang diminati pada Brand SEPHORA COLLECTION.
- Mencari tahu cara meningkatkan penjualan Brand SEPHORA COLLECTION untuk setiap category, dan mempertahankan category-category yang sudah cukup baik.
- Mencari tahu cara meningkatkan rating untuk category yang masih dibawah rata-rata.

#### Keterangan
- id : ID Produk
- brand : Brand dari Produk SEPHORA
- category : Kategori dari Produk SEPHORA
- name : Nama dari Produk
- size : Ukuran dari Produk
- rating : Nilai yang diberikan oleh Customers
- number_of_reviews : Total Review yang diberikan oleh Customers tiap Barang
- love : Berapa banyak orang yang suka dengan produk ini
- value_price : Harga barang sebelum diskon
- price : Harga barang yang terjual
- MarketingFlags : Iklan Marketing dengan Bendera/Baliho
- MarketingFlags_content : Jenis Iklan Baliho
- options : Pilihan
- details : Detail dari Produk
- how_to_use : Cara penggunaan Produk
- ingredients : Bahan-bahan/Isi dari Produk
- online_only : Ada di Online Store atau tidak
- exclusive : Barang Eksklusif atau tidak
- limited_edition : Barang yang Limited Edition atau tidak
- limited_time_offer : Barang yang Limited Time Offer atau tidak

#### Klasifikasi
Saya membagi 4 klasifikasi berdasarkan sebagai berikut :
- Klasifikasi 1 (Perfect) = Nilai Rating diatas rata-rata Rating & Nilai number_of_reviews diatas rata-rata number_of_reviews
- Klasifikasi 2 (Top) = Nilai Rating dibawah rata-rata Rating & Nilai number_of_reviews diatas rata-rata number_of_reviews
- Klasifikasi 3 (Great) = Nilai Rating diatas rata-rata Rating & Nilai number_of_reviews dibawah rata-rata number_of_reviews
- Klasifikasi 4 (Fair) = Nilai Rating dibawah rata-rata Rating & Nilai number_of_reviews dibawah rata-rata number_of_reviews

#### Asumsi
- Per barang memiliki profit margin sebesar 30% setiap barang.
- Biaya Operasional (Sewa gedung, Listrik, Gaji Karyawan, dll) \$1500 per bulan.
- Hire Digital Marketing Specialist dengan biaya \$500 per bulan.
- Membuat Apps \$25.000.
- Setelah menggunakan Apps Online Store penjualan naik menjadi 20% per bulan.

### Insight
- Berdasarkan data yang diperoleh, Penjualan Online SEPHORA pada Brand SEPHORA COLLECTION hanya ada 7,26% dan masih didominasi oleh penjualan Store Offline.
- Berdasarkan data yang diperoleh, Category yang Limited Edition pada Brand SEPHORA COLLECTION hanya ada 15,12% dan mayoritas masih penjualan yang ready stock.
- Belum ada Category yang Limited Time Offer pada Brand SEPHORA COLLECTION.
- Category yang paling diminati oleh Customers berdasarkan total number_of_reviews pada Brand SEPHORA COLLECTION ada 21 category dari 92 category, namun dari 21 category tersebut, ada 4 category yang memiliki rating dibawah rata-rata yaitu Lipstick, Facial Cleansing, Mascara, dan Face Primer. Namun, walaupun Lipstick memiliki rating dibawah rata-rata tetapi memiliki tingkat kesukaan (love) paling tinggi diantara seluruh Category pada Brand SEPHORA COLLECTION.
- Ada 42 category yang rating diatas rata-rata namun memiliki number_of_reviews yang dibawah rata-rata.
- Ada 29 category yang rating dibawah rata-rata dan memiliki number_of_reviews dibawah rata-rata.

### Conclusion & Recommendation
- Penjualan SEPHORA dapat ditingkatkan melalui penjualan Online dengan cara membuat Apps Online Store SEPHORA, selain meningkatkan penjualan SEPHORA juga dapat bersaing dengan kompetitor lain melalui kelebihan Apps Online Store yang dimiliki dan mempermudah bagi para pelanggan untuk berbelanja melalui Apps Online Store.
- Penjualan beberapa Category yang kurang diminati atau masih dibawah rata-rata number_of_reviews dapat ditingkatkan melalui Apps Online Store SEPHORA, berlaku juga untuk produk yang sudah diminati oleh para Customers, sehingga meningkatkan probability Customers untuk berbelanja. 
- Penjualan melalui Apps Online Store SEPHORA, jika dengan anggapan kalau total penjualan meningkat 20%, dapat meningkatkan pendapatan bersih sebesar 3.73% (sudah dikurangi oleh biaya operasional, dan lain lain).
- Apabila penjualan melalui Store dan Online Store SEPHORA pada Brand SEPHORA COLLECTION stabil setiap bulannya dan tidak ada faktor lain yang menurunkan penjualan, maka untuk Investasi Apps Online Store SEPHORA dapat balik modal selama 20 bulan.
- Untuk meningkatkan rating yang masih dibawah rata-rata maka dilakukan riset terhadap Customers dengan memberikan kuesioner setelah pembelian barang, agar pihak SEPHORA dapat mengetahui kelebihan produk dan kekurangan produk serta kritik dan saran dari Customers, supaya pihak SEPHORA dapat mengembangkan bagian yang masih perlu diperbaiki. Agar terjadi komunikasi yang sehat antara Customers dan pihak SEPHORA.
- Produk/Category yang lovenya cukup tinggi contohnya seperti Lipstick dapat dibuatkan Produk yang Limited Time Offer & Limited Edition, sehingga Customers yang suka dengan Category tersebut dapat mempertimbangkan untuk melakukan pembelian pada barang tersebut, dikarenakan barang yang ia sukai sedang Limited Time Offer & Limited Edition. Hal ini bisa dikolaborasi dengan Selebgram (Limited Edition by Selebgram).
- Dengan Asumsi agar Selebgram mengiklankan supaya followersnya berbelanja melalui Apps Online Store SEPHORA sehingga total penjualan meningkat menjadi 40%, dapat meningkatkan pendapatan bersih sebesar 15.6% (Selama Event Limited Time Offer & Limited Edition berjalan selama sebulan).
