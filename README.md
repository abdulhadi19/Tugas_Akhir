# STUDI BATAS SIKLUS OSILASI GROUND RESONANCE HELIKOPTER AS565 MBe PANTHER MELALUI PENDEKATAN MATEMATIS DAN SIMULASI PADA GROUND VIBRATION TEST

[![latest version](https://img.shields.io/github/v/release/b201lab/template-buku-ta-its)](https://github.com/b201lab/template-buku-ta-its/releases/)
[![commits since latest version](https://img.shields.io/github/commits-since/b201lab/template-buku-ta-its/latest)](https://github.com/b201lab/template-buku-ta-its/commits/master)
[![repo size](https://img.shields.io/github/repo-size/b201lab/template-buku-ta-its)](https://github.com/b201lab/template-buku-ta-its)
[![license](https://img.shields.io/github/license/b201lab/template-buku-ta-its)](./LICENSE)
[![build status](https://img.shields.io/github/actions/workflow/status/b201lab/template-buku-ta-its/build.yml?branch=main)](https://github.com/b201lab/template-buku-ta-its/actions)
[![deploy status](https://img.shields.io/github/actions/workflow/status/b201lab/template-buku-ta-its/deploy.yml?branch=main&label=deploy)](https://github.com/abdulhadi19/Tugas_Akhir/blob/master/02311940000082-Undergraduate_Thesis_compressed.pdf)

Dokumen ini berisikan tugas akhir yang saya kerjakan di Laboratorium Vibrasi dan Akustik Teknik Fisika ITS. Pekerjaan tugas akhir ini merupakan kelanjutan kerja praktik saya di PT Dirgantara Indonesia. Github ini merupakan bagian dari pembelajaran dan bentuk latihan saya dalam mempelajari tata kelola dokumen dalam bidang pemrograman yang saya pelajari dari [Mekatronik Achmadi](https://github.com/mekatronik-achmadi). Adapun format ini telah menyesuaikan buku tugas akhir yang diberlakukan oleh [Institut Teknologi Sepuluh Nopember](https://www.its.ac.id/) (ITS). Template yang ada pada repositori ini bersifat universal dan bisa digunakan oleh setiap departemen yang ada di ITS karena sudah mengikuti aturan resmi yang berdasarkan pada [SK Rektor ITS No. 280 Tahun 2022](https://www.its.ac.id/pendidikan/wp-content/uploads/sites/112/2022/03/280-SK-Rektor-ttg-Pedoman-Penyusunan-Laporan-Tugas-Akhir-Sarjana-Sarjana-Terapan.pdf) tentang pedoman penyusunan laporan tugas/proyek akhir program sarjana dan sarjana terapan.

> Tugas akhir saya dapat anda lihat [disini](https://github.com/abdulhadi19/Tugas_Akhir/blob/master/02311940000082-Undergraduate_Thesis_compressed.pdf).

## Abstrak

Helikopter dalam gerakannya memiliki komponen yang kompleks dan rumit. Kerusakan dapat terjadi sewaktu-waktu pada bagian helikopter. Salah satu kerusakan tersebut yang terjadi pada helikopter adalah ground resonance. Pengujian terhadap helikopter AS565 MBe Panther yang dilakukan oleh PTDI hanya menggunakan 6 sensor pada 3 titik pengujian, sedangkan pada umumnya ground vibration test menggunakan sebanyak 300 hingga 500 sensor. Sehingga diperlukan suatu studi untuk menganalisis menggunakan pendekatan matematis dan simulasi yang divalidasi menggunakan data pengukuran. Pengukuran dilakukan menggunakan FTIS (Flight Test Instrumentation System) dan sensor akselerometer dengan variasi kondisi tekanan pada landing gear. Selanjutnya data pengukuran diolah menggunakan analisis dengan bantuan komputasi Matlab dan simulasi pada software Femap (Finite Element Modeling And Postprocessing). Dari penggunaan 6 sensor didapatkan error dominan frekuensi untuk matematis dan simulasi berturut-turut sebesar 2.63% dan 42.5%, kemudian dari root mean square error (RMSE) nya berturut-turut sebesar 1.7% dan 3.40%. Hasil pengolahan data hasil FTIS didapatkan kuantifikasi damping ratio sebesar 0.0542, 0.0479, 0.0433, dan 0.0505 masing-masing pada rate of roll, rate of pitch, rate of yaw dan percepatan arah sumbu-y. Setelah batas siklus osilasi didapatkan, ditemukan persentase respon frekuensi terhadap batas siklus osilasi tersebut untuk f1 (5.92-6.08Hz) sebesar 0%, f2 (23.68-24.32Hz) sebesar 15.88%, f3 (47.36-48.64Hz) sebesar 4.27% dan f4 (71.04-72.96Hz) sebesar 0.62%. Pada hasil modifikasi, secara matematis didapatkan persentase tambahan sebanyak 2% terhadap respon frekuensi helikopter tanpa modifikasi. Kemudian pada pemodelan simulasi menggunakan bentuk stik model didapatkan frekuensi pada mode ke-6 yang berkorelasi terhadap fenomena ground resonance yaitu 4.31Hz dengan persentase respon sebanyak 3.40%. Sehingga setelah serangkaian hasil pendekatan matematis dan simulasi kondisi normal serta modifikasinya dilakukan, tidak ditemukan potensi ground resonance pada helikopter AS565 MBe Panther.

## Aplikasi Penunjang

Dalam mengerjakan tugas akhir ini saya menggunakan beberapa aplikasi bantuan seperti:
- [Matlab](https://www.mathworks.com/products/matlab.html)
- [LaTeX](https://www.latex-project.org/)
- [Femap](https://plm.sw.siemens.com/en-US/simcenter/mechanical-simulation/femap/)


- **[`abstrak`](./abstrak)**, berisi file `*.tex` untuk abstrak dalam Bahasa Indonesia dan Bahasa Inggris.
- **[`bab`](./bab)**, berisi file `*.tex` dari setiap bab yang akan dimasukkan pada buku tugas akhir.
- **[`gambar`](./gambar)**, berisi file `*.jpg`, `*.png`, maupun format gambar lain yang akan dimasukkan pada buku tugas akhir.
- **[`lainnya`](./lainnya)**, berisi file `*.tex` dari halaman lain seperti lembar pengesahan, kata pengantar, biografi penulis, dsb. yang akan dimasukkan pada buku tugas akhir.
- **[`program`](./program)**, berisi file kode program yang akan dimasukkan pada dokumen.
- **[`pustaka/pustaka.bib`](./pustaka/pustaka.bib)**, berisi daftar pustaka yang akan dimasukkan pada dokumen.
- **[`pustaka/variables.tex`](./pustaka/variables.tex)**, berisi variabel-variabel yang memuat nama, nrp, dan hal-hal lain yang dapat disesuaikan dengan kebutuhan penulis.
- **[`sampul`](./sampul)**, berisi file `*.tex` dari sampul luar dan dalam untuk buku tugas akhir.

> Penjelasan lebih lanjut mengenai penggunaan template ini akan dijelaskan dengan comment yang tersedia pada setiap file yang ada.

## Contoh Penggunaan Template

Berikut adalah daftar repositori lain yang menggunakan template yang berasal dari repositori ini:

- [threeal/buku-ta-simulasi-robot](https://github.com/threeal/buku-ta-simulasi-robot).
- [chillytaka/last_boss](https://github.com/chillytaka/last_boss).

## Lisensi

Kode sumber yang ada pada repositori ini dilisensikan di bawah [lisensi MIT](./LICENSE).
