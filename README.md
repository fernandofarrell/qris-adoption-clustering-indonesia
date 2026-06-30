# Evaluating Regional Disparities in Indonesia: A Clustering Analysis of Digital Readiness and MSEs QRIS Adoption

This repository contains the dataset and computational code used in the research paper: **"Evaluating Regional Disparities in Indonesia: A Clustering Analysis of Digital Readiness and MSEs QRIS Adoption"**.

## Files in this Repository
* `qris_regional_dataset_2024.csv`: The pre-processed dataset containing the IP-TIK Score, standardized User Ratio, and standardized Merchant Ratio for 34 provinces in Indonesia.

## Data Sources (Raw Data)
To maintain reproducibility, the raw data used to construct the dataset in this repository was collected from the following official public reports:

1. **Information and Communication Technology Development Index (IP-TIK):**
   * **Source:** Statistics Indonesia (Badan Pusat Statistik / BPS)
   * **Publication:** *Indeks Pembangunan Teknologi Informasi dan Komunikasi 2024*
   * [Access the official BPS report here](https://www.bps.go.id/id/publication/2025/09/30/12567c4a325929839ae63740/indeks-pembangunan-teknologi-informasi-dan-komunikasi-2024.html)

2. **Regional Demographic Data (Total Population):**
   * **Source:** Statistics Indonesia (Badan Pusat Statistik / BPS)
   * **Publication:** *Jumlah Penduduk Menurut Provinsi 2024*
   * [Access the official BPS data table here](https://sulut.bps.go.id/id/statistics-table/2/OTU4IzI=/jumlah-penduduk-menurut-provinsi-di-indonesia.html)

3. **Micro and Small Enterprises (MSEs / UMKM) Data:**
   * **Source:** Statistics Indonesia (Badan Pusat Statistik / BPS)
   * **Publication:** *Jumlah Perusahaan Industri Skala Mikro dan Kecil Menurut Provinsi*
   * [Access the official BPS data table here](https://www.bps.go.id/id/statistics-table/2/NDQwIzI=/jumlah-perusahaan-industri-skala-mikro-dan-kecil-menurut-provinsi.html)
  
4. **Integrated QRIS Merchants Data:**
   * **Source:** Indonesian Payment System Association (Asosiasi Sistem Pembayaran Indonesia / ASPI)
   * **Publication:** *Laporan Tahunan ASPI & Buletin Statistik ASPI Triwulan IV 2024*
   * [Access the ASPI Annual Report here](https://aspi-indonesia.or.id/berita-info/laporan-tahunan/) | [Access the Q4 2024 Statistics here](https://aspi-indonesia.or.id/buletin-statistik-aspi-triwulan-iv-2024/)
  
4. **QRIS Users Data:**
   * **Source:** Bank Indonesia (BI) Provincial Economic Reports, supplemented by manually aggregated data from official provincial government (Pemprov) publications and validated regional economic news.
   * **Note on Data Collection:** Due to the absence of a single centralized public database for provincial-level QRIS consumer adoption, the data for registered QRIS users was meticulously compiled by cross-referencing regional Bank Indonesia press releases, local government open datasets, and verified economic news reports.

## Authors
* **Fernando Farrell** - Data Science Program, Bina Nusantara University
* **Dr. Ir. Alexander Agung Santoso Gunawan** - Computer Science Department, Bina Nusantara University
* **Rilo Chandra Pradana** - Computer Science Department, Bina Nusantara University
