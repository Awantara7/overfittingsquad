# Prediksi Kelayakan Air Sumur Area Jakarta Berdasarkan Parameter Kimia-Fisika dengan Random Forest: Upaya Mitigasi Risiko Kesehatan Masyarakat

## :bookmark_tabs: ToC

- [Abstract](#Abstract)
- [Latar Belakang](#Latar-Belakang)
- [Tujuan](#Tujuan)
- [Data dan Metode](#Data-dan-Metode)
- [Hasil dan Diskusi](#Hasil-dan-Diskusi)
- [Kesimpulan](#Kesimpulan)
- [Rekomendasi](#Rekomendasi)

  
## Abstract

Air bersih merupakan kebutuhan dasar yang sangat vital bagi kesehatan masyarakat, terutama di wilayah padat seperti Jakarta. Penelitian ini bertujuan untuk memprediksi kelayakan air sumur rumah tangga berdasarkan parameter kimia-fisika menggunakan algoritma Random Forest. Data yang digunakan merupakan hasil pengujian kualitas air sumur dari berbagai kecamatan di Jakarta tahun 2023, dengan parameter seperti pH, zat besi (Fe), E. coli, nitrat, dan lainnya. Hasil model menunjukkan performa klasifikasi yang baik dan berhasil mengidentifikasi parameter paling kritis terhadap ketidaklayakan air. Informasi ini diharapkan dapat menjadi dasar mitigasi risiko kesehatan masyarakat melalui intervensi wilayah dan edukasi.

## Latar Belakang

Kualitas air sumur rumah tangga di Jakarta menjadi perhatian serius mengingat tingginya kepadatan penduduk dan ancaman pencemaran lingkungan. Air yang tidak memenuhi baku mutu dapat menimbulkan berbagai penyakit, seperti diare, keracunan logam berat, dan gangguan kulit. Oleh karena itu, diperlukan upaya prediktif berbasis data untuk mengidentifikasi daerah berisiko dan variabel penyebab utama.

## Tujuan

Adapun tujuan dari project ini:

1. Memprediksi kelayakan air sumur rumah tangga di Jakarta berdasarkan parameter kimia-fisika.
2. Mengidentifikasi parameter pencemar utama yang paling berkontribusi terhadap ketidaklayakan air.
3. Memberikan rekomendasi mitigasi risiko kesehatan masyarakat berdasarkan hasil analisis model.

## Data dan Metode

### Data

Dataset ini merekam kualitas air sumur dari berbagai lokasi di DKI Jakarta pada tahun 2023, yang tersebar di berbagai kecamatan dan wilayah administratif (Jakarta Pusat, Jakarta Barat, Jakarta Timur, Jakarta Utara, dan Jakarta Selatan). Data ini penting karena kualitas air sumur berkaitan langsung dengan kesehatan masyarakat, terutama bagi masyarakat yang masih mengandalkan air tanah sebagai sumber air utama.

| Kolom                  | Deskripsi                  | 
|:---------------------------|:-----------------------|
| lintang_selatan                    | Koordinat geografis lintang (latitude) dari lokasi sumur  | 
| bujur_timur                | Koordinat geografis bujur (longitude) dari lokasi sumur | 
| wilayah                 | Nama wilayah administratif	| 	
| kecamatan                | Nama kecamatan di mana sumur berada  | 
| nama_lokasi	               | Nama atau penanda lokasi sumur  | 
| Besi		    	             | Kadar kandungan besi (Fe) dalam air (mg/L)  | 
| E_Coli	    	     | Jumlah bakteri Escherichia coli dalam air (jumlah koloni per 100 ml)  | 
| IP		        	     | Indeks pencemaran  | 
| Krom_heks		    	           | character varying(50)Kandungan kromium heksavalen (Cr⁶⁺) dalam air (mg/L)  | 
| Mangan	    	   | Kandungan mangan (Mn) dalam air (mg/L)                | 
| Nitrat		    	         |            Kadar nitrat (NO₃⁻) dalam air (mg/L)        | 
| 	  Nitrit  	         | Kadar nitrit (NO₂⁻) dalam air (mg/L)                   | 
| Organik	    	           | Zat organik yang terlarut dalam air (mg/L)                   | 
| Surfaktan | Kadar surfaktan (detergen) dalam air (mg/L) |
| Total_colif | Jumlah total \textit{coliform} per 100 m |
| Warna | Tingkat pewarnaan air (dalam satuan warna - mg/L PtCo) |


### Metode

Langkah-langkah metode penelitian ini dapat dilihat pada flowchart di bawah ini.

<p align="center">
  <img width="900" height="500" src="Flowchart">
</p>

## Hasil dan Diskusi

## Kesimpulan

## Rekomendasi

### Rekomendasi untuk Praktisi Keilmuan

### Rekomendasi untuk Pemangku Kebijakan
