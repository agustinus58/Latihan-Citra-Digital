# Latihan-Citra-Digital
Latihan ini untuk mahasiswa yang mengambil kelas Pengolahan citra digital
Histogram
Histogram sebagai grafik atau plot, yang memberi gambaran keseluruhan tentang distribusi intensitas gambar. Plot bernilai pixel (mulai dari 0 hingga 255, tidak selalu) dalam sumbu X dan jumlah piksel yang sesuai pada gambar pada sumbu Y.

alt text

PLOTING HISTOGRAM DENGAN MATPLOTLIB
plt.hist(img_vec, bins = 256, color, alpha)
img_vec: vektor image yang akan di buat grafik, img.ravel() perintah memberi vektor berisi semua piksel gambar yang tersusun

color: Ini adalah warna yang ingin gunakan untuk merencanakan histogram. Secara default, ini berwarna biru tua. Anda dapat menentukannya sebagai Merah, Biru, Hijau, Kuning, agenta, atau warna standar lainnya.

bins: Ini adalah jumlah batang yang ingin kami tampilkan pada sumbu X. Kita tahu bahwa intensitas piksel berkisar dari 0 hingga 255, dan jika kita ingin memvisualisasikan secara terpisah jumlah piksel untuk setiap intensitas yang mungkin, kita memerlukan grafik yang menunjukkan interval 0-255 sebagai 256 batang terpisah. Oleh karena itu, kita akan menyimpan bins = 256. Jika Anda tidak menentukan bins, Python akan memperlakukannya sebagai 10 secara default (dalam contoh berikut, kita akan melihat artinya).

alpha: Ini adalah tingkat transparansi yang ingin Anda gambar histogram.
