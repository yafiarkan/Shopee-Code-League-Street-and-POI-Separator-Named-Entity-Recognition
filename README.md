# Shopee-Code-League-Street-and-POI-Separator-Named-Entity-Recognition
Program ini digunakan untuk lomba yang dilaksanakan oleh Shopee pada Tahun 2021 dan mendapatkan top 250 dari 1000 lebih tim di seluruh Asia Tenggara dan Tiongkok. Projek ini adalah pemisah antara nama jalan dan nama tempat dengan kekompleksan dataset, dimana dataset memiliki format yang tidak tentu dan spesial karakter yang tidak diperlukan. Model yang dibuat mendapatkan akurasi sebesar 50% untuk data uji.

# Latar Belakang
At Shopee, we strive to ensure our customers' highest satisfaction for their shopping and delivery experience - fast and accurate delivery of goods. This can be better achieved if we have key address elements for each user address which allows us to accurately geocode it to obtain geographic coordinates to ship the parcel to our customers. These key address elements include Point of Interest (POI) Names and Street Names. However, most addresses that Shopee receives are unstructured and in free text format, not following a certain pattern. Thus it is important for us to develop a model to precisely extract the key address elements from it.

# Metodologi
Kami membuat dua model yang berbeda yaitu untuk membedakan khusus nama jalan dan khusus nama tempat. Model untuk khusus nama jalan memiliki kelas yaitu nama jalan dan bukan nama jalan, model kedua memiliki kelas yaitu nama tempat dan bukan nama tempat. Kedua model ini menggunakan dataset yang sama namun konfigurasi yang berbeda. Hasil kedua model yang dikombinasi dan menghasilkan hasil yang utuh.

# Hasil
Hasil yang didapatkan adalah dapat digunakan untuk memprediksi spesial karakter sebagai nama jalan dan nama tempat dengan akurasi 50%
