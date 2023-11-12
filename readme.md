# Kumpulan kode kode readme.md untuk github

## 1. Kode untuk menampilkan tingkat header atau judul 

``````
# Ini adalah Header 1
``````
- Maka menampilkan:
# Ini adalah Header 1

``````
## Ini adalah Header 2
``````
- Maka menampilkan:
## Ini adalah Header 2

``````
### Ini adalah Header 3
``````
- Maka menampilkan:
### Ini adalah Header 1

- Jadi makin banyak '#' Maka makin kecil tulisanya

## 2. Kode untuk menampilan gambar dan link 
```
![Nama Gambar](gambar/namagambar.png)
```
- Ganti gambar/namagambar.png menjadi lokasi file gambar anda
- Contoh saya menruh file gambar saya di gambar/alvin.png maka kodenya : 
```
![Nama Gambar](gambar/alvin.png)
```
### maka hasilnya 
![Nama gambar](gambar/alvin.png)

## Dan jika gambar kalian jika di klik ingin redirect makan kodenya 

``````
[![Nama gambar ](gambar/namagambar.png)](https://linkanda.com)
``````
- Ganti gambar/namagambar.png menjadi lokasi file gambar anda
- ganti https://linkanda.com menjadi link anda
- Contoh saya menruh file gambar saya di gambar/alvin2.jpg dan jika gambar di klik akan meredirect ke https://github.com/alvinalfandy maka kodenya : 

``````
[![Nama gambar ](gambar/alvin2.png)](https://github.com/alvinalfandy)
``````
## maka akan menampilkan

<a href="https://github.com/alvinalfandy">
  <img src="gambar/alvin2.png" alt="Deskripsi Gambar" width="200"/>
</a>



## 3. Kode untuk membuat tabel

```
| Nama           | NIM       | Kelas       |
| -------------- | --------- | ----------- |
| ALVIN BIDEN      | 123456    | IT-101    |
| ALFANDY ZUCKERBERG   | 789012    | CS-202|

```
- contoh diatas saya ingin membuat tabel untuk profil saya , maka tamppilanya menjadi :

| Nama           | NIM       | Kelas       |
| -------------- | --------- | ----------- |
| ALVIN BIDEN      | 123456    | IT-101      |
| ALFANDY ZUCKERBERG   | 789012    | CS-202      |

## 4. Kode untuk Teks Tebal dan Miring
``````
**Alvin alfandy** 
*Alvin alfandy*  
``````
- untuk ** teks **  akan menampilkan teks tebal dan miring ( dua tanda *)
-  untuk * teks *  akan menampilkan teks miring saja  ( satu tanda *)

## maka hasilnya

**Alvin alfandy** 

*Alvin alfandy*  

## 5.Kode untuk Teks Tautan

```
[Teksnya ](https://www.example.com)
```

- Ganti https://www.example.com menjadi link anda
- ganti Teksnya menjadi teks anda
- ini bisa di variasikan dengan emotikon keyboard/dari sumberlainya seperti 🚀
- bisa di tambah dengan ## untuk memperbesar teks
- contoh saya akan membuat teks " 🚀 Ini adalah Rocket " Dan redirect ke link https://github.com/alvinalfandy dengan ##
### maka kodenya
``````
## [🚀 Ini adalah Rocket ](https://github.com/alvinalfandy)
``````
### maka akan menampilkan 
## [🚀 Ini adalah Rocket ](https://github.com/alvinalfandy)

## 6.Kode untuk menampilkan garis horizontal
``````
---
``````
- Anda bisa memvariasikan dengan ada teks dibawah dan diatasnya dengan #
- contoh kodenya:

```
## Alvin alfandy

---

Alvin alfandy adalah orang
```
- maka menampilkan

## Alvin alfandy

---

Alvin alfandy adalah orang

## 7.Kode untuk membuat markdown blok kode/Teksnya bisa di salin
-  Ini digunakan untuk menandai bagian teks yang merupakan kode sumber, dan sering digunakan untuk menyertakan contoh kode atau fragmen kode dalam dokumen Markdown. Contoh penggunaan:

kodenya adalah
```````
```
isi
```
```````
- ganti "isi" menjadi kode anda 
- bisa di variasikan menjadi warna dengan menambahkan teks "python" di akhir garis atas  "`"
contoh:

``````
```python
print("Haloo, saya Alvin)
```
``````
### maka akan menampilkan
```python
print("Haloo, saya Alvin)
```

## 8.Kode untuk menampilkan Jumlah pengujung Github
```
![Profile views](https://komarev.com/ghpvc/?username=alvinalfandy&color=brightgreen)
```
- Ganti "alvinalfandy" menjadi username github anda
- Ganti Brightgreen jika ingin mengubah warna tombolnya
- Contoh saya akan menggunakan kode diatas dan menampilkan

![Profile views](https://komarev.com/ghpvc/?username=alvinalfandy&color=brightgreen)

## 9.Kode untuk menampilkan statistik github  kamu
```
| <a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api?username=alvinalfandy&show_icons=true&include_all_commits=true&theme=radical&hide_border=true" alt="Isallkun github stats" /></a> | <a href=""><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alvinalfandy&layout=compact&theme=radical&hide_border=true" /></a> |
| ------------- | ------------- |
```
- Cukup ganti usernamenya dengan username anda
- Contoh kode diatas akan menampilkan statistik github saya

| <a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api?username=alvinalfandy&show_icons=true&include_all_commits=true&theme=radical&hide_border=true" alt="Isallkun github stats" /></a> | <a href=""><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alvinalfandy&layout=compact&theme=radical&hide_border=true" /></a> |
| ------------- | ------------- |

## 10.Kode untuk Kontak saya
```
### Kontak saya :

[![website](./img/youtube-light.svg)](https://www.youtube.com/@Alvinviclates#gh-light-mode-only)
[![website](./img/youtube-dark.svg)](https://www.youtube.com/@Alvinviclates#gh-dark-mode-only)
&nbsp;&nbsp;
[![website](./img/twitter-light.svg)](https://twitter.com/alfandy_alvin#gh-light-mode-only)
[![website](./img/twitter-dark.svg)](https://twitter.com/alfandy_alvin#gh-dark-mode-only)
&nbsp;&nbsp;
[![website](./img/linkedin-light.svg)](https://www.linkedin.com/in/alvin-alfandy-69893b1a8/#gh-light-mode-only)
[![website](./img/linkedin-dark.svg)](https://www.linkedin.com/in/alvin-alfandy-69893b1a8/#gh-dark-mode-only)
&nbsp;&nbsp;
[![website](./img/instagram-light.svg)](https://instagram.com/alvinalfandyy#gh-light-mode-only)
[![website](./img/instagram-dark.svg)](https://instagram.com/alvinalfandyy#gh-dark-mode-only)
```
- Ganti setiap username menjadi username akun anda
- Contoh kode diatas akan menampilkan kontak saya

### Kontak saya :

[![website](https://raw.githubusercontent.com/alvinalfandy/alvinalfandy/1a7b462add9a7d0a93d504c98d94193542733c73/img/youtube-light.svg)](https://www.youtube.com/@Alvinviclates#gh-light-mode-only)
[![website](https://raw.githubusercontent.com/alvinalfandy/alvinalfandy/1a7b462add9a7d0a93d504c98d94193542733c73/img/youtube-dark.svg)](https://www.youtube.com/@Alvinviclates#gh-dark-mode-only)
&nbsp;&nbsp;
[![website](https://raw.githubusercontent.com/alvinalfandy/alvinalfandy/1a7b462add9a7d0a93d504c98d94193542733c73/img/twitter-light.svg)](https://twitter.com/alfandy_alvin#gh-light-mode-only)
[![website](https://raw.githubusercontent.com/alvinalfandy/alvinalfandy/1a7b462add9a7d0a93d504c98d94193542733c73/img/twitter-dark.svg)](https://twitter.com/alfandy_alvin#gh-dark-mode-only)
&nbsp;&nbsp;
[![website](https://raw.githubusercontent.com/alvinalfandy/alvinalfandy/1a7b462add9a7d0a93d504c98d94193542733c73/img/linkedin-light.svg)](https://www.linkedin.com/in/alvin-alfandy-69893b1a8/#gh-light-mode-only)
[![website](https://raw.githubusercontent.com/alvinalfandy/alvinalfandy/1a7b462add9a7d0a93d504c98d94193542733c73/img/linkedin-dark.svg)](https://www.linkedin.com/in/alvin-alfandy-69893b1a8/#gh-dark-mode-only)
&nbsp;&nbsp;
[![website](https://raw.githubusercontent.com/alvinalfandy/alvinalfandy/1a7b462add9a7d0a93d504c98d94193542733c73/img/instagram-light.svg)](https://instagram.com/alvinalfandyy#gh-light-mode-only)
[![website](https://raw.githubusercontent.com/alvinalfandy/alvinalfandy/1a7b462add9a7d0a93d504c98d94193542733c73/img/linkedin-dark.svg)](https://instagram.com/alvinalfandyy#gh-dark-mode-only)
