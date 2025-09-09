# VISUALISASI DATA MENGGUNAKAN BOXPLOT
## Pendahuluan
Tugas kali ini memvisualisasikan data menggunakan boxplot pada dataset titanic (bawaan dari library seaborn).
sebelum menentukan variable yang akan divisualisasikan, langkah pertama adalah mencari **hubungan** yang kuat antar variable.

## langkah awal
setelah dilakukan visualisasi terhadap hubungan antar variable menggunakan heatmap, 
terlihat bahwa ada 3 diantara 6 variable yang memiliki hubungan yang cukup kuat.

- 3 variable, 1 sebagai variable independen dan 2 sebagai variable dependen.
  - pclass (independen): karena berdasarkan hipotesis, mempengaruhi survived atau tidaknya dan juga umur yang mendudukinya (makin tua makin kecil pclassnya)
  - age (dependen): dikatakan dependen karena secara logis, penumpang kelas 1 mayoritas adalah orang dengan usia yang rata-ratanya lebih tinggi daripada kelas lain
  - survive (dependen): sangat dipengaruhi oleh kelas dari kapal, semakin kecil kelasnya, semakin mungkin ia selamat

penempatan itu dapat terlihat dari gambar grafik ini:
<img width="695" height="547" alt="image" src="https://github.com/user-attachments/assets/f883d170-fd97-45d4-8a9e-eb76b835e4a9" />
<img width="686" height="547" alt="image" src="https://github.com/user-attachments/assets/1fa518ef-e397-455f-a401-3a226f69dac8" />



## langkah akhir
setelah mengetahuinya, maka berikutnya menentukan dimana posisi dari setiap variable terhadap tiap sumbu.
disini, karena yang paling mudah untuk dikelompokan adalah survived dan pclass, maka mereka berada pada sumbu x.
sedangkan, age berada pada sumbu y karena bersifat numerikal.

hasil akhir dari visualisasi seperti ini:
<img width="996" height="701" alt="image" src="https://github.com/user-attachments/assets/acb6fb86-2f3b-4d68-a80f-09a4107bb1c9" />


