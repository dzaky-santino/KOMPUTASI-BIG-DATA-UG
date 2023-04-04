# Praktikum KOMPUTASI BIG DATA (KBD)

GUNADARMA UNIVERSITY - 2023
KOMPUTASI BIG DATA

- [x] [GOOGLE COLAB](https://colab.research.google.com/)
- [x] [JUPYTER NOTEBOOK](https://jupyter.org/try)

## Analisis Data Set "Data Komponen Beton"

## Overview Dataset

"Data Komponen Beton".

Data set ini berisikan beberapa kategori sebagai berikut

1. **cement (kg)**: Jumlah semen dalam satu meter kubik campuran beton.
2. **slag (blast furnace slag, kg)**: Jumlah campuran slag dalam satu meter kubik campuran beton.
3. **ash (fly ash, kg)**: Jumlah abu terbang dalam satu meter kubik campuran beton.
4. **water (kg)**: Jumlah air dalam satu meter kubik campuran beton.
5. **superplastic (superplasticizer, kg)**: Jumlah superplastikizer dalam satu meter kubik campuran beton.
6. **coarseagg (coarse aggregate, kg)**: Jumlah agregat kasar dalam satu meter kubik campuran beton.
7. **fineagg (fine aggregate, kg)**: Jumlah agregat halus dalam satu meter kubik campuran beton.
8. **age (days, 1-365)**: Usia dalam hari pada waktu uji kekuatan beton.
9. **strength (Concrete compressive strength, MPa)**: Kekuatan tekan beton dalam satuan Megapascal.

## Univariate and Bivariate Analysis

### Univariate Analysis

1. Kolom **cement** memiliki rata-rata sebesar 281.17 dan standar deviasi sebesar 104.51.
2. Kolom **slag** memiliki rata-rata sebesar 73.89 dan standar deviasi sebesar 86.30.
3. Kolom **ash** memiliki rata-rata sebesar 54.19 dan standar deviasi sebesar 63.99.
4. Kolom **water** memiliki rata-rata sebesar 181.57 dan standar deviasi sebesar 21.35.
5. Kolom **superplastic** memiliki rata-rata sebesar 6.20 dan standar deviasi sebesar 5.97.
6. Kolom **coarseagg** memiliki rata-rata sebesar 972.92 dan standar deviasi sebesar 77.75.
7. Kolom **fineagg** memiliki rata-rata sebesar 773.58 dan standar deviasi sebesar 80.18.
8. Kolom **age** memiliki rata-rata sebesar 45.66 dan standar deviasi sebesar 63.17.
9. Kolom **strength** memiliki rata-rata sebesar 35.82 dan standar deviasi sebesar 16.71.

### Bivariate Analysis

#### Hubungan antara kolom cement dan strength

Dari scatter plot yang dihasilkan, terlihat bahwa semakin tinggi nilai kolom **cement**, semakin tinggi pula nilai kolom **strength**. Hal ini menunjukkan kekuatan beton sangat dipengaruhi oleh jumlah semen yang digunakan pada campuran beton.

#### Hubungan antara kolom water dan strength

Dari scatter plot yang dihasilkan, terlihat bahwa semakin rendah nilai kolom **water**, semakin tinggi pula nilai kolom **strength**. Hal ini menunjukkan kekuatan beton sangat dipengaruhi oleh jumlah air yang digunakan pada campuran beton.

#### Hubungan antara kolom age dan strength

Dari scatter plot yang dihasilkan, terlihat bahwa semakin tinggi nilai kolom **age**, semakin tinggi pula nilai kolom **strength**. Hal ini menunjukkan beton akan semakin mengeras, dan akhirnya mencapai kekuatan maksimal setelah beberapa minggu.

# Lisensi MIT

Hak Cipta (c) [2023] [Ahmad Dzaky Santino]

Dengan ini diberikan izin, secara gratis, kepada siapa pun yang mendapatkan salinan
perangkat lunak ini dan file dokumentasi terkait ("Perangkat Lunak"), untuk bertransaksi
dalam Perangkat Lunak tanpa batasan, termasuk namun tidak terbatas pada hak
untuk menggunakan, menyalin, memodifikasi, menggabungkan, mempublikasikan, mendistribusikan, mensublisensikan, dan/atau menjual
salinan Perangkat Lunak, dan untuk mengizinkan orang yang menerima Perangkat Lunak
yang diberikan Perangkat Lunak untuk melakukan hal tersebut, dengan tunduk pada ketentuan-ketentuan berikut:

Pemberitahuan hak cipta di atas dan pemberitahuan izin ini harus disertakan dalam semua
salinan atau bagian penting dari Perangkat Lunak.

PERANGKAT LUNAK INI DISEDIAKAN "SEBAGAIMANA ADANYA", TANPA JAMINAN APA PUN, TERSURAT MAUPUN
TERSURAT MAUPUN TERSIRAT, TERMASUK NAMUN TIDAK TERBATAS PADA JAMINAN DAPAT DIPERJUALBELIKAN,
KESESUAIAN UNTUK TUJUAN TERTENTU DAN NON-PELANGGARAN. DALAM HAL APA PUN
PENULIS ATAU PEMEGANG HAK CIPTA TIDAK BERTANGGUNG JAWAB ATAS KLAIM, KERUSAKAN, ATAU
TANGGUNG JAWAB, BAIK DALAM TINDAKAN KONTRAK, KESALAHAN ATAU LAINNYA, YANG TIMBUL DARI,
DARI ATAU SEHUBUNGAN DENGAN PERANGKAT LUNAK ATAU PENGGUNAAN ATAU TRANSAKSI LAIN DALAM
PERANGKAT LUNAK.

# Practicum of BIG DATA COMPUTATION (KBD)

GUNADARMA UNIVERSITY - 2023
BIG DATA COMPUTING

- [x] [GOOGLE COLAB](https://colab.research.google.com/)
- [x] [JUPYTER NOTEBOOK](https://jupyter.org/try)

## Analysis of "Concrete Component Data" Dataset

## Dataset Overview

"Concrete Component Data".

This dataset contains the following categories

1. **cement (kg)**: The amount of cement in one cubic meter of concrete mix.
2. **slag (blast furnace slag, kg)**: Amount of slag admixture in one cubic meter of concrete mix.
3. **ash (fly ash, kg)**: Amount of fly ash in one cubic meter of concrete mix.
4. **water (kg)**: Amount of water in one cubic meter of concrete mix.
5. **superplastic (superplasticizer, kg)**: Amount of superplasticizer in one cubic meter of concrete mix.
6. **coarseagg (coarse aggregate, kg)**: Amount of coarse aggregate in one cubic meter of concrete mix.
7. **fineagg (fine aggregate, kg)**: Amount of fine aggregate in one cubic meter of concrete mix.
8. **age (days, 1-365)**: Age in days at the time of the concrete strength test.
9. **strength (Concrete compressive strength, MPa)**: Concrete compressive strength in Megapascals.

## Univariate and Bivariate Analysis

### Univariate Analysis

1. The **cement** column has a mean of 281.17 and a standard deviation of 104.51.
2. The **slag** column has a mean of 73.89 and a standard deviation of 86.30.
3. Column **ash** has a mean of 54.19 and a standard deviation of 63.99.
4. The **water** column has a mean of 181.57 and a standard deviation of 21.35.
5. The **superplastic** column has a mean of 6.20 and a standard deviation of 5.97.
6. The **coarseagg** column has a mean of 972.92 and a standard deviation of 77.75.
7. The **fineagg** column has a mean of 773.58 and a standard deviation of 80.18.
8. The **age** column has a mean of 45.66 and a standard deviation of 63.17.
9. The **strength** column has a mean of 35.82 and a standard deviation of 16.71.

### Bivariate Analysis

#### Relationship between cement and strength columns

From the resulting scatter plot, it can be seen that the higher the **cement** column value, the higher the **strength** column value. This shows that the strength of concrete is strongly influenced by the amount of cement used in the concrete mix.

#### Relationship between water and strength columns

From the resulting scatter plot, it can be seen that the lower the **water** column value, the higher the **strength** column value. This shows that the strength of concrete is strongly influenced by the amount of water used in the concrete mix.

#### Relationship between age and strength columns

From the resulting scatter plot, it can be seen that the higher the **age** column value, the higher the **strength** column value. This shows that the concrete will harden further, and finally reach maximum strength after a few weeks.

Translated with www.DeepL.com/Translator (free version)

# MIT License

Copyright (c) [2023] [Ahmad Dzaky Santino]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
