# **✨ Marketing Campaign - by Datalicious ✨**

<img src="https://raw.githubusercontent.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/main/assets/banner.png">

**✅ Members of Datalicious ✅**

1. Nur Imam Masri
2. Astuti Rahmawati
3. Prasidya Bagaskara
4. Moh. Harwin Prayoga
5. Riskiyatul Hasanah
6. M Rayhan Azzindani
7. Siti Hajjah Mardiah
8. Christine
9. M. Ifzal Asril

## **⚙ Work Environment ⚙**

- **Tools**

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/blob/main/Response%20Prediction%20Classification%20Marketing%20Campaign.ipynb)

- **Programming Language**

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

- **Libraries**

[Requirements Text](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/blob/main/requirements.txt)

- **Dataset**

[Marketing campaign](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign "Marketing campaign dataset from Kaggle")

## **💻 Script 💻**

**Open in Colab**

- [Response Prediction Classification Marketing Campaign.ipynb](https://colab.research.google.com/github/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/blob/main/Response%20Prediction%20Classification%20Marketing%20Campaign.ipynb)

## **📍 Table of Content 📍**
<!--ts-->
* **Business Understanding**
    * [Problem Statement](#-business-understanding-)
    * [Roles](#-roles)
    * [Goals](#-goals)
    * [Objectives](#-objectives)
    * [Business Metrics](#-business-metrics)
* **Data Preparation**
    * [Data Description](#-data-description-)
    * Libraries & Datasets
* **Data Understanding**
    * [Exploring Datasets](#-data-understanding-)
    * [Data Types Information](#-data-types-information)
    * [Statistical Summary](#-statistical-summary)
    * [EDA (Exploratory Data Analysis)](#-exploratory-data-analysis-eda)
    * [Feature Engineering / Extraction (Business Insight)](#-feature-engineering--extraction)
    * [Business Insight](#-business-insight)
* **Data Cleansing/Preprocessing**
    * [Handling Missing Values]()
    * [Handling Duplicated Rows]()
    * [Handling Invalid Values]()
    * [Handling Outliers]()
    * [Feature Engineering / Extraction]()
    * [Feature Transformation (Numeric)]()
    * [Feature Encoding (Categoric)]()
    * [Feature Selection]()
    * [Handling Imbalanced Data]()
<!--te-->

## **⛳ Business Understanding ⛳**

### **📌 Problem Statement**

**Lotto Mart** adalah sebuah supermarket yang bergerak dibidang retail,  menjual berbagai jenis produk seperti Fish, Meat, Fruits, Sweet Products, Wines, dan Gold Products. Selama 6 bulan terakhir,  Marketing Team melakukan campaign berupa pemberian discount vouchers kepada semua customer melalui  Broadcast Message. Namun, setelah campaign  dilakukan, justru Lotto Mart menghadapi beberapa permasalahan sebagai berikut :
- **Response rate** dari marketing campaign yang dilakukan rendah yaitu sekitar 14.91%
- **Inefficient Cost** dalam melakukan marketing campaign
- **Profit tidak sebanding** dengan cost yang dikeluarkan

Berdasarkan hal tersebut,  Marketing Team meminta tim data untuk menganalisis permasalahan yang terjadi.  Selanjutnya perusahaan ingin membuat marketing campaign yang tepat sasaran  sesuai dengan **karakteristik customer**. Strategi ini diharapkan  mampu **meningkatkan response rate**,  **meminimalisasi cost**, dan kemudian **meningkatkan profit**

### **📌 Roles**

Sebagai **tim data** di Supermarket Lotto Mart, untuk menganalisis keberhasilan marketing campaign selanjutnya. Berikut adalah beberapa roles beserta PIC yang berkontribusi dalam menyelesaikan permasalahan di Lotto Mart:

- **Lead Data Science**

    Sebagai koordinator project

    PIC: `Nur Imam Masri`

- **Machine Learning Engineer**

    Membuat model dan evaluasi Machine Learning
    
    PIC: `Prasidya Bagaskara` dan `Moh. Harwin Prayoga`
    
- **Data Engineer**

    Melakukan Data Preparation, Cleaning, dan    
    Exploratory Data Analysis (EDA)

    PIC: `M Rayhan Azzindani` dan `M. Ifzal Asril`

- **Business Analyst**

    Membuat insight business

    PIC: `Riskiyatul Hasanah` dan `Christine`

- **Data Analyst**

    Membuat dashboard

    PIC: `Siti Hajjah Mardiah` dan `Astuti Rahmawati`


### **📌 Goals**

Perusahaan ingin meningkatkan **response rate** dan  meminimalisasi **marketing campaign cost** sehingga dapat memaksimalkan **profit**. 


### **📌 Objectives**

Membuat classification model untuk **memprediksi kelompok customer yang akan merespon campaign** agar dapat **meminimalisasi biaya pemasaran dan memaksimalkan keuntungan** pada campaign marketing berikutnya.


### **📌 Business Metrics**

- **Response Rate/RR**
    
    Persentase total customer response  terhadap  total delivered campaign
    
    _**Indicator  RR :**_ 30% is good ( Efti 2018).
    
    - **Net Profit Margin /NPM**
    
        Mengukur net profit dibanding penjualannya. Semakin besar NPM, maka kinerja marketing campaign semakin efektif dan efisien (Handayani,  Winarningsih  2020).  

        _**Indicator NPM :**_ 5% is low, 10-19% is average, 20% is good (Jayathilaka 2020).
    
    - **Return of Investment /ROI**
    
        CLV (customer lifetime value)) dibagi CAC((customer acquisition cost).  Sebagai indikator kinerja perusahaan dan pembuatan keputusan  para investor. 

        _**Indicator ROI :**_ 3:1 to 5:1 is good (Manzer  2017).  
        
**📝 References :**

- Efti S.  2018. Sales Benchmarks: The 30/50 rule for cold emailing & cold calling. diakses 20 Mei 2023. https://blog.close.com/sales-benchmarks/ 

- Handayani N,  Winarningsih S. 2020. The Effect of Net Profit Margin and Return on Equity Toward Profit Growth. Moneter-Jurnal Akuntansi Dan Keuangan 7(2): 198-204. https://doi.org/10.31294/moneter.v7i2.8701.

- Jayathilaka AK. 2020. Operating Profit and Net Profit: Measurements of Profitability. Open Access Library Journal 7(12): 1-11. https://doi.org/10.4236/oalib.1107011.

- Manzer D. 2017. Five insights into measuring marketing ROI. diakses 20 Mei 2023. https://growswyft.com/five-insights-to-measure-your-roi/.


## **🕹 Data Description 🕹**

**Marketing Campaign ([link datasets](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign))**

_Boost the profit of a marketing campaign_

A response model can provide a significant boost to the efficiency of a marketing campaign by increasing responses or reducing expenses. 

The objective is to predict who will respond to an offer for a product or service

**Dataset Description:**

The training dataset contains `2240 samples`. Contains `28 features` and `1 target boolean` variable `"Response"` :

**Accepted/Responses Campaign**

- `AcceptedCmp1` - 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- `AcceptedCmp2` - 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- `AcceptedCmp3` - 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- `AcceptedCmp4` - 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- `AcceptedCmp5` - 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- `Response (target)` - 1 if customer accepted the offer in the last campaign, 0 otherwise
- `Complain` - 1 if customer complained in the previous 2 years

**Customer Information**

- `ID` - Customer's id
- `Year_Birth` - Customer's year of birth
- `Education` - customer’s level of education
- `Marital` - customer’s marital status
- `Kidhome` - number of small children in customer’s household
- `Teenhome` - number of teenagers in customer’s household
- `Income` - customer’s yearly household income
- `DtCustomer` - date of customer’s enrolment with the company
- `Recency` - number of days since the last purchase

**Sales Product Type**

- `MntFishProducts` - amount spent on fish products in the last 2 years
- `MntMeatProducts` - amount spent on meat products in the last 2 years
- `MntFruits` - amount spent on fruits products in the last 2 years
- `MntSweetProducts` - amount spent on sweet products in the last 2 years
- `MntWines` - amount spent on wine products in the last 2 years
- `MntGoldProds` - amount spent on gold products in the last 2 years

**Number of Purchases per Type**

- `NumDealsPurchases` - number of purchases made with discount
- `NumCatalogPurchases` - number of purchases made using catalogue
- `NumStorePurchases` - number of purchases made directly in stores
- `NumWebPurchases` - number of purchases made through company’s web site
- `NumWebVisitsMonth` - number of visits to company’s web site in the last month

**Cost and Revenue**

- `Z_CostContact = 3` (Cost to contact a customer)
- `Z_Revenue = 11` (Revenue after client accepting campaign)


# **💡 Data Understanding 💡**

## **📌 Explore Datasets**

### **Basic Datasets Information**

- Dataset memiliki `29 columns` dan `2240 rows` data
- Terdapat 3 jenis tipe data yaitu : `int64, object, float64`
- Kolom `Income` memiliki 2216 nilai non-null, dan `24 nilai null / missing values`


**Hal yang harus dilakukan saat Data Pre-Processing adalah:**

- Karena data yang dimiliki tidak terlalu banyak, sehingga untuk `Missing Values` pada `Income` akan dilakukan `Imputation` pada tahap Data Preprocessingnya :
    - Imputation (Median), karena Highly Positively Skewed
    - Multivariate Approach (MICE Imputation, KNN Imputer, dll)

### **Checking Duplicate Rows**

Data yang kita miliki tidak memiliki duplikat

### **Checking Missing Values**

- Kolom `Income` memiliki `24 nilai null / missing values`, persentase sebesar 1.07% dari jumlah data 

**Hal yang harus dilakukan saat Data Pre-Processing adalah:**

- Karena data yang dimiliki tidak terlalu banyak, sehingga untuk `Missing Values` pada `Income` akan dilakukan `Imputation` pada tahap Data Preprocessingnya :
    - Imputation (Median), karena Highly Positively Skewed
    - Multivariate Approach (MICE Imputation, KNN Imputer, dll)

## **📌 Data Types Information**

**List of Column Types:**

- **Date**

    `Dt_Customer`

- **Categorical** (10 Columns) : 
    - `ID` - Nominal
    - `Education` - Ordinal (Levels : Basic - Graduation - 2n Cycle - Master - PhD)
    - `Marital_Status` - Nominal
    - `AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5, Complain, Response` - Nominal (Binary 0 & 1)

- **Continuous** (18 Columns):

    `Year_Birth, Income, Kidhome, Teenhome, 
    Recency, MntWines, MntFruits, MntMeatProducts, 
    MntFishProducts, MntSweetProducts, MntGoldProds, 
    NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, 
    NumStorePurchases, NumWebVisitsMonth, Z_CostContact, Z_Revenue`

**Change the Some column data type**

- Kita mengubah tipe data categorical ke `category`, agar dalam melakukan explorasi dan insight tidak di anggap sebagai data numerical
- Untuk memudahkan dalam proses extraction `Dt_Customer` maupun part of, maka kolom date `object` diubah menjadi `datetime64`

## **📌 Statistical Summary**

### **Numerical + Date Features**

- **Dt_customer** 
    - Sebelumnya masih berbentuk `string/object`, untuk tipe datanya kurang sesuai sehingga di ubah menjadi `Datetime`
    - `Dt_Customer` tetap dipertahankan untuk Business Insight, namun kemungkinan dihapus karena tanggal customer mulai bergabung tidak mempengaruhi model prediksi

- **Year_Birth:**

    - Tahun kelahiran tertua (min) yaitu `1893`, hal ini yang kemungkinan adanya `salah input data`sehingga data harus diproses lebih lanjut pada `Outlier`
    - Kemungkinan akan dilakukan `Feature extraction` untuk mengambil `data Umur/Age` pada range tahun saat ini 2014 (sesuai pada data)

- **Household Income:**

    - `Mean` nya adalah `52247.25` dan `Median` nya adalah `51381.5` dari data tersebut dapat disimpulkan bahwa rata-rata lebih besar dari pada median maka menggambarkan sedikit `Right-skewed Distribution`
    - Selanjutnya mempunyai `Range 1730.0 (minimal) ke 666666.0 (maximal) yang sangat jauh`, menandakan adanya `outliers` sehingga perlu dilakukan `Log Transformation/Normalisasi atau Segmentasi` pada data income sebelum melanjutkan ke tahap pemodelan

- **Recency, Kidhome, Teenhome**

    - Rata Rata (mean) dan median memiliki `kesamaan` yang artinya `kemungkinan` memiliki distribusi normal-skewed distribution / bimodial `(akan dicek pada univariate analysis)` 
    - Untuk `Kidhome` dan `Teenhome` berpotensi untuk membuat feature baru 'Dependents' untuk lebih menggambarkan berapa jumlah anggota keluarga yg dependent

- **Mount of Type Products :**

    Pada beberapa kolom terdapat summary nilai yang memiliki nilai `Mean dan Median` memiliki rentang nilai terlalu jauh seperti pada kolom:

    1. `MntWines`, mean = 303.9, median = 173.5
    2. `MntFruits`, mean = 26.3, median = 8
    3. `MntMeatProducts`, mean = 166.9, median = 67
    4. `MntFishProducts`, mean = 37.5, median = 12
    5. `MntSweetProducts`, mean = 27.06, median = 8
    6. `MntGoldProds`, mean = 44.02, median = 24

    Jika dilihat dari beberapa nilai `mean dan median` yang memiliki jarak agak aneh, kemungkinan memiliki jumlah `outlier yang tinggi` dan distribusi yang `skewed`, maka untuk Data Preprocessing perlu dilakukan `Log Transformation`, digunakan untuk mengubah data skewed mendekati / sesuai dengan normalitas.

- **Moderately Positively Skewed (Sedikit skew ke kanan) pada kolom :**

    `NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumWebVisitsMonth`
    
    Jika dilihat pada data ini nilai `mean dan median` yang memiliki jarak yang tidak lumayan jauh, namun kemungkinan memiliki distribusi yang `skewed` ke kanan, maka perlu di visualisasi lebih lanjut, kemudian untuk Data Preprocessing perlu dilakukan `Log Transformation`, digunakan untuk mengubah data skewed mendekati / sesuai dengan normalitas.
    
- **Z_CostContact, Z_Revenue**

    Dapat diketahui bahwa nilai `cost (3)` dan `revenue (11)` ini hanya memiliki satu nilai, sehingga akan di `Drop pada step modelling nantinya` karena tidak memberikan informasi yang signifikan terhadap model prediksi


### **Categorical Features**

- Terlalu banyak kategori pada kolom `ID`, `Year_Birth`
- Pada data `ID` semuanya hanya muncul sekali, sehingga dapat dikatakan tidak ada duplicate ID pada data
- Customer banyak yang lahir (`Year Birth`) pada tahun `1976 (age = 38 years)` sebanyak 89 orang
- Kategori `Education`, "2n Cycle" dan "Master" memliki arti yang sama.
- Kategori `Education`: customer mayoritas memiliki kategori pendidikan `Graduation` sebanyak 1127 orang, namun nilainya sangat besar di banding yang lain
- Dalam kategori `Marital Status`,: customer mayoritas sudah menikan (Married) 864 orang
- Dalam kategori `Marital Status`, "Single" dan "Alone" memiliki arti yang sama.
- Dalam kategori `Marital Status`, "Together" dan "Married" memiliki arti yang sama.
- Dalam kategori `Marital Status`, ada beberapa data yang tidak jelas apa yang dimaksud yaitu "Absurd" dan "YOLO", maka disarankan digabung dan diganti "Others".
- Pada kategori `AcceptedCmp(1-5)`, customer mayoritas tidak merespon / accept dari campaign yang dilakukan
- Pada kategori `Complain`, customer mayoritas tidak pernh complain dari campaign yang dilakukan
- Target yang kita miliki ada pada kolom `Respon`, yang mana memiliki ketimpangan yang sangat tinggu (Imbalanced Data), 
    - Tidak merespon = 1906
    - Merespon = 334
    
**Hal yang harus dilakukan saat Data Pre-Processing adalah:**

- Akan dilakukan `replace data / menyatukan yang memiliki arti yang sama` agar mengurangi jumlah dimensi maupun `redudansi pada data`
- Pada kolom `Response`,  Sebaran kategori yang timpang pada target. Pada target, menyebabkan proses Machine Learning gagal. Oleh karena itu, perlu dilakukan `Sampling Data (Undersampling/Oversampling/Combinded/SMOTE/dll)`
- Akan dilakukan `Feature Encoding` pada kolom `Education` dan `Marital_Status` untuk proses modelling, karena masih belum memiliki representasi nilai numerical

## **📌 Exploratory Data Analysis (EDA)**

### **Uni-variate Analysis**

#### **Individual Boxplot and Violinplot**

**Observations:**

Terdapat outlier pada kolom Year_Birth, Income, MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds, NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, dan NumWebVisitMonth.

- Pada kolom `Year_Birth`, outlier terjauh adalah di bawah 1900
- Pada kolom `Income`, outlier terjauh adalah di atas $600,000.
- Pada kolom `MntWines`, outlier berada pada angka 1200 keatas.
- Pada kolom `MntFruits`, outlier berada di sekitar angka 80 sampai 200.
- Pada kolom `MntMeatProducts`, outlier terjauh ada di sekitar angka 1,750.
- Pada kolom `MntFishProducts`, outlier berada di sekitar angka 125 sampai diatas 250.
- Pada kolom `MntSweetProducts`, outlier terjauh berada di sekitar angka 250.
- Pada kolom `MntGoldProds`, outlier terjauh berada di sekitar angka 350.
- Pada kolom `NumDealsPurchases`, outlier terjauh berada di angka 15.
- Pada kolom `NumWebPurchases`, outlier berada di sekitar angka 25.
- Pada kolom `NumCatalogPurchases`, outlier terjauh berada di atas angka 25.
- Pada kolom `NumWebVisitsMonth`, outlier terjauh berada di angka 20.

**Hal yang harus dilakukan saat Data Pre-Processing adalah:**
- Mengaplikasikan `Log Transformation` untuk `Feature Scaling` dan `Handling Outlier` yang mana transformasi ini de-emphasizes / minimize `outliers` dan dapat membantu untuk potentially obtain a `bell-shaped / normal distribution`. Hal ini juga dikarenakan jumlah data yang terbatas hanya sebanyak 2240 baris data saja, menjadi pilihan terbaik karena tanpa menghapus baris data.
- Alternatif lainnya, Membersihkan data dengan cara menghapus `outliers` berdasarkan `IQR atau Z-score` namun akan mengurangi data yang dimiliki


#### **Individual Histogram / Distplot**

Berdasarkan chart **Boxplot, Distribusi, dan Violin** diatas, dapat diketahui bahwa ada beberapa variabel yang memiliki **outlier** didalamnya dan beberapa memiliki **Skewed Distribution**. Berikut adalah beberapa variabel tersebut:

1. ***Normal distribution***
    - `Recency` Normal Distribution (Symmetric)
    - `Year_Birth` Moderately Normal Distribution (Symmetric)
    - `NumWebVisitsMonth` Moderately Normal Distribution (Symmetric)
    
2. ***Uniform distribution***  
    - `Z_CostContact` Uniform Distribution - Memiliki satu nilai saja
    - `Z_Revenue` Uniform Distribution - Memiliki satu nilai saja

3. ***Positive skewed distribution***
    - Income `Income`
    - Amount of Wines Products `MntWines`
    - Amount of Fruits Products `MntFruits`
    - Amount of Meats Products `MntMeatProducts`
    - Amount of Fish Products `MntMeatProducts`
    - Amount of Sweet Products `MntSweetProducts`
    - Amount of Golds Products `MntGoldProds`
    - Number Deals Purchases `NumDealsPurchases`
    - Number Web Purchases `NumWebPurchases`
    - Number Catalog Purchases `NumCatalogPurchases`
    - Number Store Purchases `NumStorePurchases`

4. ***Bimodal distribution***
    - Number of small children  in customer's household `Kidhome`
    - Number of teenagers in customer's household `Teenhome`

**Rekomendasi pada data pre-processing:**

Data yang mengalami `Positive Skewed Distribution` dilakukan `Log Transformation` sehingga data bisa menjadi normal distribution


#### **Individual Countplot**

**Observations:**
- Terlalu banyak kategori pada kolom `ID`, `Year_Birth`
- Kolom `Education` dan `Marital_Status` memiliki beberapa kategori yang valuenya sama dan ambigu.
    - Kategori `Education`, "2n Cycle" dan "Master" memliki arti yang sama.
    - Kategori `Education`: customer mayoritas memiliki kategori pendidikan `Graduation` sebanyak 1127 orang, namun nilainya sangat besar di banding yang lain
    - Dalam kategori `Marital Status`, customer mayoritas sudah menikah (Married) 864 orang
    - Dalam kategori `Marital Status`, "Single" dan "Alone" memiliki arti yang sama.
    - Dalam kategori `Marital Status`, "Together" dan "Married" memiliki arti yang sama.
    - Dalam kategori `Marital Status`, ada beberapa data yang tidak jelas apa yang dimaksud yaitu "Absurd" dan "YOLO", maka disarankan digabung dan diganti "Others".
- Kolom `Kidhome` dan `Teenhome` mayoritas customer tidak memiliki anak dan remaja (value 0)
- Kolom `AcceptedCmp1, AcceptedCmp2, AcceptedCmp3 ,AcceptedCmp4, AcceptedCmp5, Complain, dan Response` value didominasi dengan value 0 (Tidak Response / Complain)
- Target yang kita miliki ada pada kolom `Respon`, yang mana memiliki ketimpangan yang sangat tinggu (Imbalanced Data), 
    - Tidak merespon = 1906
    - Merespon = 334

**Hal yang harus dilakukan saat Data Pre-Processing adalah:**

- Kolom `ID` di drop untuk proses modelling
- Dari kolom `Year_Birth` dibuat kolom baru yaitu kolom `Age` yang menunjukkan umur seorang customer.
- Akan dilakukan `replace data / menyatukan yang memiliki arti yang sama` agar mengurangi jumlah dimensi maupun `redudansi pada data`
    - Kategori `Education`, "2n Cycle" dan "Master" memliki arti yang sama.
    - Dalam kategori `Marital Status`, Customer mayoritas sudah menikan (Married) 864 orang
    - Dalam kategori `Marital Status`, "Single" dan "Alone" memiliki arti yang sama.
    - Dalam kategori `Marital Status`, "Together" dan "Married" memiliki arti yang sama.
    - Dalam kategori `Marital Status`, ada beberapa data yang tidak jelas apa yang dimaksud yaitu "Absurd" dan "YOLO", maka disarankan digabung dan diganti "Others".
- Melakukan `Label Encoding` pada kolom `Education`.
- Melakukan `One Hot Encoding (OHE)` pada kolom `Marital_Status`.
- Pada kolom `Response`,  Sebaran kategori yang timpang pada feature mengindikasikan ketidakgunaan feature. Pada target, menyebabkan proses Machine Learning gagal. Oleh karena itu, perlu dilakukan `Sampling Data (Undersampling/Oversampling/Combinded/SMOTE/dll)`


### **Multivariate Analysis**

#### **Heatmap Correlation**

- **Korelasi ke Target (Response)**
    - `Top 10 Yang berkolerasi tinggi ke target` sebagai berikut, Kemungkinan besar top ini bisa menjadi feature yang paling relevan dan harus dipertahankan:
        - `AcceptedCmp5` - 0.32 - Positif
        - `AcceptedCmp1` - 0.29 - Positif
        - `AcceptedCmp3` - 0.25 - Positif
        - `MntWines` - 0.24 - Positif
        - `MntMeatProducts` - 0.23 - Positif
        - `NumCatalogPurchases` - 0.22 - Positif
        - `Recency` - 0.19 - Negatif
        - `AcceptedCmp4` - 0.17 - Positif
        - `AcceptedCmp2` - 0.16 - Positif
        - `Teenhome` - 0.15 - Negatif

    - Korelasi Kolom **Response** dengan kolom lainnya cenderung rendah. Dari seluruh korelasi antara feature-target berada di `range 0.00 sampai 0.33`. Oleh karena itu, kami memutuskan untuk membuat nilai `threshold di angka 0.15`. Feature-feature di atas yang kemungkinan kami pertahankan adalah feature yang memiliki nilai korelasi `>0.15`.
    - Korelasi kolom **Response** dengan kolom **AcceptedCmp5** adalah yang paling tinggi dibandingkan kolom campaign sebelumnya.
    - Produk yang ditawarkan di campaign terakhir (kolom **Response**) agak mirip dengan campaign ke 5 (**AcceptedCmp5**)
    - Customer cenderung lebih tertarik dengan Wines dan Meat yang ditunjukan dengan korelasi kolom **Response** dengan kolom **MntWines** dan **MntMeatProducts**
    - Customer juga lebih menyukai pembelian dengan cara Katalog (kolom **NumCatalogPurchases**) dibandingkan yang lain.
    
    
- **Complain, Z_CostContact dan Z_Revenue** berpotensi untuk dihapus, karena tidak memiliki korelasi dibanding kolom lainnya

- **Korelasi Antar Feature**

    - **MntMeatProduct** berkorelasi positif cukup besar dengan **NumCatalogPurchases**, bisa dikatakan sebagian besar pembelian meat product dilakukan melalui catalog (korelasinya 0.72) sehingga kemungkinan ada redudansi pada data, sehingga yang di drop adalah **NumCatalogPurchases** karena lebih rendah korelasi ke target (response)

    Selain itu, Pada korelasi antar-feature, terdapat pola yang menarik sebagai berikut :

    - **Year Birth**
        - **Year_Birth** berkolerasi positif dengan **Kidhome**, bisa dikatakan semakin muda maka semakin banyak pula anak kecilnya sedangkan untuk kolom **Teenhome** berkolerasi negatif atau semakin tua customer maka jumlah anak remaja semakin banyak
    - **Kidhome & Teenhome**
        - Customer yang (**Kidhome**) memiliki anak kecil **Income** nya cenderung rendah
        - Customer yang (**Kidhome**) memiliki anak kecil cenderung lebih sering mengunjungi web dan melakukan pembelian ketika sedang diskon
        - Customer yang (**Teenhome**) memiliki anak remaja cenderung lebih banyak melakukan pembelian ketika sedang diskon
    - **Income**
        - Customer yang memiliki **Income** yang tinggi cenderung banyak melakukan pembelian
        - Kolom **Income** berkorelasi positif cukup besar dengan **MnWines, MntFruits, MntMeatProduct, MntFishProduct, MntSweetProduct dan MntGoldProduct**
        - Kolom **Income** berkorelasi positif cukup besar dengan **NumWebPurchases, NumCatalogPurchases, dan NumStorePurchases** sedangkan dengan kolom **NumWebVisitsPurchases** berkorelasi negative cukup besar, bisa dikatakan bahwa semakin besar income customer maka mayoritas tempat yang dipilih untuk melakukan pembelian adalah Web, Catalog dan Store, sedangankan customer yang memiliki income rendah cenderung lebih banyak melakukan pembelian melauli web atau lebih sering mengunjungi web
    - **Product**
        - Kolom **MntWines** berkorelasi positif cukup besar dengan **MntMeatProduct**, kemungkinan customer membeli wine juga membeli meat
        - Kolom **MntFruits** berkorelasi positif cukup besar dengan **MntMeatProduct, MntFishProduct dan MntSweetProduct**, kemungkinan ketika customer membeli product tersebut bersamaan
        - **MntMeatProduct** berkorelasi positif cukup besar dengan **NumCatalogPurchases**, bisa dikatakan sebagian besar pembelian meat product dilakukan melalui catalog
        - **MntWines** paling banyak dibeli melalui katalog dari pada metode pembelian lainya
    - **Purchases**
        - Kolom **NumDealsPurchases** berkorelasi positif dengan NumWebVisitMonth, ketika sedang diskon customer yang mengunjungi web meningkat
        - Kolom **NumWebVisitMonth** berkorelasi negatif cukup besar dengan **NumCatalogPurchases dan NumStorePurchases**, ketika customer lebih sering mengunjungi web maka pembelian melalui catalog dan store menurun
    - **Additional**
        - Customer yang membeli Wines (**MntWines**) cenderung akan membeli Meat (**MntMeatProducts**) dan lebih suka membeli langsung di **Store**, **Catalog** dan **Website**.
        - Beberapa kombinasi **Fruits** yang sangat disukai customer antara lain **Fruits** dan **Meat**, **Fruits** dan **Fish**, atau **Fruits** dan **Sweet**. Customer juga lebih nyaman membeli langsung di **Store** atau melalui **Catalog** dibandingkan dengan menggunakan Website.
        - Kombinasi 5 Kolom product cukup tinggi nilai korelasinya. Oleh karena itu, customer cenderung suka membeli lebih dari 1 product dalam sekali berbelanja.
        - Produk **Wines** dan **Gold** lebih banyak dibeli menggunakan **ebsite**. Sedangkan **Fruits**, **Meat**, **Fish** dan **Sweet** dibeli melalui **Store** maupun **Catalog**.
        - Produk yang ditawarkan menggunakan **Deals** (potongan harga) belum terlalu menarik minta customer karena korelasi dengan kolom produk apapun sangat rendah.
        - Customer yang menggunakan **Deals** lebih banyak customer yang menggunakan **Website** untuk membeli barang/produk.
        
    Berdasarkan analisa awal antar fitur yang kami lakukan terhadap fitur yang memiliki korelasi lebih tinggi dengan target, didapatkan hasil sebagai berikut:

    - `Recency` : Nilai korelasi Recency dengan feature lainnya memiliki range 0.00 sampai 0.05

    - `MntWines` : Feature yang berkorelasi dengan MntWines: 
    
        Income = 0.58, NumCatalogPurchases = 0.64, NumStorePurchases = 0.64

    - `MntMeatProducts` : Feature yang berkorelasi dengan MntMeatProducts:
    
        NumCatalogPurchases = 0.72, Income = 0.58, MntWines = 0.56

    - `NumCatalogPurchases` : Feature yang berkorelasi dengan NumCatalogPurchases: 
    
        MntMeatProducts = 0.72, MntWines = 0.64,Income = 0.59

    - `AcceptedCmp3` : Feature yang berkorelasi dengan AcceptedCmp3: 
    
        MntGoldProducts = 0.12

    - `AcceptedCmp5` : Feature yang berkorelasi dengan AcceptedCmp5: 
    
        MntWines = 0.47, MntMeatProducts = 0.37, Income = 0.34

    - `AcceptedCmp1` : Feature yang berkorelasi dengan AcceptedCmp1: 
    
        AcceptedCmp5 = 0.40, MntWines = 0.35, MntMeatProducts = 0.31, NumCatalogPurchases = 0.31

    Dari hasil tersebut, kemungkinan digunakan sebagai fitur prioritas penentuan feature untuk klasifikasi response customer
    

#### **Box Plot based on Response**

Berdasarkan analisis Boxplot diatas dengan menambahkan feature `Response` sebagai variabel pembanding, maka dapat ditemukan beberapa *insights* sebagai berikut: 

Terdapat beberapa variabel yang memiliki perbedaan yang cukup signifikan dilihat dari jarak antar median antara customer yang respon dan tidak respon sepert : `Income`, `Recency`, `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProducts`, `NumberWebPurchases`, `NumberCatalogPurchases` dan `NumberStorePurchases`.
Berikut adalah penjelasannya:

- Pada variabel `Income`, Customer yang *merespon campaign* cenderung memiliki income yang lebih tinggi dengan rata-rata income yang dimiliki customer sekitar 65000, dibanding customer yang *tidak merespon campaign* memiliki income rata-rata hanya sekitar 50000.
- Pada variabel `Recency`, Customer yang *merespon campaign* cenderung lebih aktif untuk berbelanja dengan rata-rata hari terakhir pembelian produk sekitar 30 hari, dibanding customer yang *tidak merespon campaign* memiliki rata-rata hari terakhir pembelian produk sekitar lebih dari 50 hari
- Pada variabel `MntWines`, Customer yang *merespon campaign* cenderung lebih banyak membeli produk Wines dengan rata-rata pembelian produk Wines sekitar \\$450 selama 2 tahun, dibanding customer yang *tidak merespon campaign* dengan rata-rata pembelian produk Wines kurang dari \\$200 selama 2 tahun
- Pada variabel `MntFruits`, Customer yang *merespon campaign* cenderung lebih banyak membeli produk Fruits dengan rata-rata pembelian produk Fruits lebih dari \\$20 selama 2 tahun, dibanding customer yang *tidak merespon campaign* dengan rata-rata pembelian produk Fruits kurang dari \\$5 selama 2 tahun
- Pada variabel `MntMeatProducts`, Customer yang *merespon campaign* cenderung lebih banyak membeli produk Meat dengan rata-rata pembelian produk Meat lebih dari \\$190 selama 2 tahun, dibanding customer yang *tidak merespon campaign* dengan rata-rata pembelian produk Meat kurang dari \\$50 selama 2 tahun
- Pada variabel `MntFishProducts`, Customer yang *merespon campaign* cenderung lebih banyak membeli produk Fish dengan rata-rata pembelian produk Fish sekitar \\$25 selama 2 tahun, dibanding customer yang *tidak merespon campaign* dengan rata-rata pembelian produk Fish kurang dari \\$5 selama 2 tahun
- Pada variabel `MntSweetProducts`, Customer yang *merespon campaign* cenderung lebih banyak membeli produk Sweet dengan rata-rata pembelian produk Sweet sekitar \\$20 selama 2 tahun, dibanding customer yang *tidak merespon campaign* dengan rata-rata pembelian produk Sweet kurang dari \\$5 selama 2 tahun
- Pada variabel `MntGoldProducts`, Customer yang *merespon campaign* cenderung lebih banyak membeli produk Gold dengan rata-rata pembelian produk Gold sekitar \\$40 selama 2 tahun, dibanding customer yang *tidak merespon campaign* dengan rata-rata pembelian produk Gold kurang dari \\$20 selama 2 tahun
- Pada variabel `NumberWebPurchases`, Customer yang *merespon campaign* cenderung lebih banyak membeli produk melalui Web dengan rata-rata 5 kali pembelian produk, dibanding customer yang *tidak merespon campaign* membeli produk melalui Web dengan rata-rata 3 kali pembelian produk
- Pada variabel `NumberCatalogPurchases`, Customer yang *merespon campaign* cenderung lebih banyak membeli produk melalui Catalog dengan rata-rata 4 kali pembelian produk, dibanding customer yang *tidak merespon campaign* membeli produk melalui Catalog dengan rata-rata 1 kali pembelian produk
- Pada variabel `NumberStorePurchases`, Customer yang *merespon campaign* cenderung lebih banyak membeli produk melalui Toko dengan rata-rata 6 kali pembelian produk, dibanding customer yang *tidak merespon campaign* membeli produk melalui Toko dengan rata-rata 5 kali pembelian produk


**Simplified based on Mount Product**

Pada `Response yang menerima (values 1)`, memiliki nilai `Mount` (Jumlah Pembelian) di tiap product `lebih tinggi` daripada yang tidak merespon (values 0)

**Simplified based on Type Purchases**

- Untuk pembelian melalui `Web`, `Catalog`, `Web`, Pada `Response yang menerima (values 1)`, memiliki nilai `Purchases` (Jumlah Pembelian) lumayan sedikit `lebih tinggi` daripada yang tidak merespon (values 0)
- Sedangkan pada pembelian melalui `Deals / Discount` dan `Store` memiliki nilai yang `tidak terlalu berbeda`


#### **Count Plot based on Response**

**Simplified based on Status Customer**

- Education
    - `Graduation,PhD dan Master` memiliki jumlah respon yang tinggi, masing-masing ada pada ratio perbandingan respon > 13.4% (maks 20%)
- Marital_Status
    - `Single, Married, Together, dan Divorced` memiliki jumlah respon yang tinggi, namun ratio perbandingan respon vs no responnya < 22.4% (maks 50%)
- Kidhome & Teenhome
    - Semakin tinggi jumlah anak/remaja yang dimiliki customer, maka semakin kecil kemungkinan customer menerima Response (marketing campaign terakhir), sehingga lebih baik perusahaan menargetkan campaign kepada customer yang tidak memiliki anak/remaja. Begitupun pada ratio perbandingan respon vs no responnya menurun.
    
    
**Simplified based on Campaign/Complain**

- AcceptedCmp columns
    - Dari segi Response tertinggi cenderung pada yang tidak accept campaign.
    - Dari yang Accept Campaign, hanya pada 1, 3, 4, 5 yang memiliki nilai yang kebih besar. Bisa juga dilihat pada ratio perbandingan respon vs no responnya 33-56%, berarti tidak berbeda signifikan dan perbandingannya lumayan sama.
    - Pada Acccept Campaign 2 Jumlahnya sangat sedikit, namun ratio perbandingan respon vs no responnya yang paling tinggu 66%.

- Complain
    - Dari segi Response tertinggi cenderung pada yang tidak ada complain pada campaign

    
## **📌 Feature Engineering / Extraction**

New Calculation, Extraction, and Binning features for business insight :
- Age Customer
- Age Group
- Has Child
- Dependents
- Month Customer
- Spending
- Total Accepted/Responses
- Education and Marital Simplify
- Income Segment
- Convertion Rate
- Total of days/years joined


## **📌 Business Insight**

### **Response Ratio**

- Jumlah yang `Response` signifikan lebih kecil dibandingkan yang Tidak Merespon `No Respon`, dengan ratio 14.9%
- Ini berarti adanya `data imbalance` pada campaign terakhir (ke-6) perusahaan
- Sehingga bisa dilakukan upaya peningkatan proses marketing campaign agar lebih banyak customer yang merespon campaign

### **Acceptance Rate for each Campaign (1-5)**

Dari Campaign Rate yang telah kita lakukan, terdapat perubahan drastis yang terjadi dari Campaign 1 ke campaign 2 (menurun drastis) dan 3 (naik signifikan). Adapun dari Campaign 3-5 Semuanya memiliki rate yang kurang lebih sama disekitar ~7%. Sehingga dari perusahaan dan tim perlu melakukan identifikasi lanjutan untuk mengetahui apakah ada pola dari pembelian customer

### **Total Accept Campaign (1-5)**

Paling banyak pada Lima Campaign kita adalah 0 (tidak pernah merespon), namun ada yang sedikit berpotensi pada, hanya sekali (1) atau dua kali (2) merespon masing-masing 325 dan 83 Customers

### **Income vs. Campaign**

Customer dengan income diatas > \\$120.000 tidak ada yang menerima/respon campaign perusahaan. Jadi sebaiknya perusahaan fokus melakukan campaign kepada customer dengan income dibawah < \\$120000.

### **Birth Year / Age vs. Response**

Kategori customer yang menerima Response (marketing campaign terakhir) terbanyak berasal dari tahun lahir 1970-1975 (39-44 years old), dan 1980-1990 (24-34 years old). 

Jika perusahaan harus memprioritaskan beberapa customer saja, maka perusahaan dapat memilih customer yang lahir pada tahun tersebut untuk menawarkan sebuah campaign. 

Namun tetap memperhatikan juga No Response (Tidak Menerima) karena pada area tahun lahir 1970-1975 juga sangat tinggi.

### **Age Group vs. Response**

Berdasarkan chart diatas dapat dilihat bahwa kelompok umur yang paling banyak merespon campaign adalah `Adult dan Senior Adult` dan yang paling rendah adalah `Young Adult`. 

`Artinya semakin Tua seseorang maka jumlah response juga meningkat`

### **Education vs. Response**

Dari visualisasi piechart Education, dapat dilihat bahwa customer yang merespon terbanyak berasal dari customer yang memiliki edukasi Graduation dan PhD, sehingga marketing team dapat memfokuskan campaign ke customer yang beredukasi Graduation.

### **Marital Status vs Response**

Jumlah customer paling banyak menerima respon berdasarkan status penikahan yaitu Married dan orang yang masih single, sehingga pada campaign selanjutnya perusahaan sebaiknya memfokuskan kepada customer yang telah menikah (Married)

Sedangkan untuk "Absurd" dan "Yolo" pada data "Others" sangat sedikit

### **Kids and Teens (Dependents) vs. Response**

Semakin tinggi jumlah anak/remaja yang dimiliki customer, maka semakin kecil kemungkinan customer menerima Response (marketing campaign terakhir), sehingga lebih baik perusahaan menargetkan campaign kepada customer yang tidak memiliki anak/remaja.

Dari visualisasi kidhome dan teenhome, dapat dilihat bahwa customer yang merespon terbanyak berasal dari customer yang tidak mempunyai anak dan tidak mempunyai remaja (0.265403), sehingga marketing team dapat memfokuskan campaign ke customer yang tidak mempunyai anak dan tidak mempunyai remaja.

### **Recency vs. Response**

Berdasarkan recency (kapan terakhir kali customer melakukan pembayaran), semakin rendah recency maka semakin besar kemungkinan customer tersebut menerima marketing campaign perusahaan yang terakhir (Response). Sehingga marketing campaign selanjutnya dapat difokuskan kepada customer dengan recency yang rendah.


* Recency rendah : waktu purchase terakhir pelanggan dengan produk.belum terlalu lama


### **Income vs Response**

Jumlah customer paling banyak menerima respon berdasarkan pendapatan yaitu orang-orang yang memilik pendapatan sebesar 80000, sehingga pada campaign selanjutnya perusahaan sebaiknya lebih memfokuskan kepada orang dengan pendapatan 80000 


### **Purchase type vs. Response**

Semakin sedikit pembelian yang dilakukan (baik yang menggunakan diskon ataupun yang melalui web, catalog, store), maka semakin besar kemungkinan customer untuk menerima Response (marketing campaign terakhir). Sehingga perusahaan dapat menargetkan campaign kepada customer dengan jumlah pembelian yang masih sedikit.

### **Purchase type vs. Complain**

- Customer dengan Purchase lebih rendah -> Memiliki Jumlah Complain Tinggi, tapi Response Tinggi

    Perusahaan sebaiknya meningkatkan kualitas pelayanan, agar respone sejalan dengan tingkat kepuasan pelanggan untuk mengurangi complain customer

- Customer dengan Purchase lebih tinggi -> Memiliki Jumlah Complain Rendah, tapi Response Rendah

    Bisa dilakukan penelaah kembali hal-hal yang membuat customer dengan purchase lebih tinggi, cenderung rendah pada tingkat response
    
    
### **Income x Spending for Response**

Income dan Spending memiliki korelasi positif pada response, dimana semakin tinggi nilai income dan spending semakin besar tingkat respon sehingga fitur income dan spending perlu dipertahankan

### **Income Segment vs. Response**

Higher the income, more likely to give response for campaign

Customer yang merespon campaign cenderung memiliki income yang lebih tinggi, terbukti dari customer yang memiliki income “High” level  merespon campaign lebih banyak.

### **Income Segment vs Product**

Customer dengan income High dan Medium lebih suka dengan produk Gold dan Fish. Oleh karena itu, jika ingin membuat campaign disarankan untuk memberikan campaign produk Gold dan Fish untuk cutomer dengan income tersebut.

### **Income Segment vs Purchase Type**

Kemudian pada pembuatan campaign, disarankan berbentuk Catalog atau Diskon dan lebih banyak diarahkan ke customer dengan income High / Medium. untuk opsi kedua, bisa langsung dibuat banner/booth pada Store.

### **Product vs. Response**

Customer yang merespon campaign cenderung lebih banyak membeli Wines dan Meat products. Sehingga untuk campaign selanjutnya produk Wines dan Meat menjadi rekomendasi produk utama untuk customer yang merespon.

### **Total Campaign vs Num Values**

Berikut adalah insights yang diperoleh berdasarkan Total Campaign vs Variable:

- `Income`:
    Customer yang menerima total 4 campaign cenderung memiliki income yang lebih tinggi.
- `Kidhome:` 
    Customer yang tidak menerima campaign sama sekali memiliki kidhome lebih banyak.
- `Teenhome`:
    Customer yang tidak menerima campaign sama sekali memiliki Teenhome lebih banyak.
- `Recency`:
    Customer yang menerima total 3 campaign cenderung memiliki recency (total hari terakhir berbelanja) yang lebih lama.
- `MntWines`:
    Customer yang menerima total 4 campaign cenderung membeli produk Wines lebih banyak.
- `MntFruits`:
    Customer yang menerima total 3 campaign cenderung membeli produk Fruits lebih banyak.
- `MntMeatProducts`:
    Customer yang menerima total 3 campaign cenderung membeli produk Meat lebih banyak.
- `MntFishProducts`:
    Customer yang menerima total 3 campaign cenderung membeli produk Fish lebih banyak.
- `MntSweetProducts`:
    Customer yang menerima total 3 campaign cenderung membeli produk Sweet lebih banyak.
- `MntGoldProducts:` 
    Customer yang menerima total 3 campaign cenderung membeli produk Gold lebih banyak.
- `NumDealsPurchases`:
    Customer yang tidak menerima campaign sama sekali lebih sering membeli produk menggunakan diskon.
- `NumWebPurchases`:
    Customer yang menerima total 2 dan 3 campaign cenderung lebih sering membeli produk melalui web.

- `NumCatalogPurchases`:
    Customer yang menerima total 4 campaign cenderung lebih sering membeli produk melalui katalog.
- `NumStorePurchases`:
    Customer yang menerima total 4 campaign cenderung lebih sering membeli produk melalui toko.
- `NumWebVisitsMonths`:
    Customer yang tidak menerima campaign sama sekali lebih sering melakukan web visit pada bulan terakhir.



# **🏝 Data Cleansing/Preprocessing 🏝**

## **📌 Handling Missing Value**

```html
Missing values status: True
                     Total Null Values  Percentage Data Type
Income                              24    1.071429     int64
ID                                   0    0.000000     int64
Z_CostContact                        0    0.000000     int64
Complain                             0    0.000000    object
AcceptedCmp2                         0    0.000000    object
AcceptedCmp1                         0    0.000000   float64
AcceptedCmp5                         0    0.000000     int64
AcceptedCmp4                         0    0.000000     int64
AcceptedCmp3                         0    0.000000    object
NumWebVisitsMonth                    0    0.000000     int64
NumStorePurchases                    0    0.000000     int64
NumCatalogPurchases                  0    0.000000     int64
NumWebPurchases                      0    0.000000     int64
NumDealsPurchases                    0    0.000000     int64
Z_Revenue                            0    0.000000     int64
MntGoldProds                         0    0.000000     int64
MntFishProducts                      0    0.000000     int64
MntMeatProducts                      0    0.000000     int64
MntFruits                            0    0.000000     int64
MntWines                             0    0.000000     int64
Recency                              0    0.000000     int64
Dt_Customer                          0    0.000000     int64
Teenhome                             0    0.000000     int64
Kidhome                              0    0.000000     int64
Marital_Status                       0    0.000000     int64
Education                            0    0.000000     int64
Year_Birth                           0    0.000000     int64
MntSweetProducts                     0    0.000000     int64
Response                             0    0.000000     int64
```

Berdasarkan hasil analisa awal, dapat diketahui bahwa terdapat data kosong pada kolom income sebanyak 24 baris dengan persentase sebesar 1,07% dari keseluruhan data.

Pada proses handling missing values untuk kolom `Income` ada beberapa metode yang dapat di lakukan :
- **Drop Rows Missing Values**
- **Imputation Median**
    - `Fillna` or `SimpleImputer`
- **Multivariate Approach**
    - Perlu dipastikan untuk data yang dimiliki semaunya dalam bentuk tipe numerical (categorical encoding)
        - `Label Encoding` : `Education`
            - `LabelEncoder` or `Mapping`
        - `One Hot Encoding` : `Marital Status`
            - `get_dummies` or `OneHotEncoder`
    - Kita juga drop kolom yang tidak penting seperti data tanggal `Dt_Customer`
    - Metode :
        - `KNNImputer` or K-Nearest Neighbor
        - `MICE` or Multiple Imputation by Chained Equation      
            - Imputation using MICE with `IterativeImputer`
            - Imputation using MICE with `LightGBM`
            
**Choice Determination:**

- Pada proses handling missing values ini kita menggunakan `Imputation using MICE with LightGBM`

**Imputation using `MICE` with `LightGBM`**

```
import miceforest as mf

# Create kernel. 
kds = mf.ImputationKernel(
  df_ma,
  save_all_iterations=True,
  random_state=100
)

# Run the MICE algorithm
kds.mice(iterations=5, n_estimators=50)

# Return the completed dataset.
df_imputed = kds.complete_data()
df["Income"] = df_imputed["Income"].copy()
df.head()
```

**Kesimpulan**

Berdasarkan hasil pengecekan, Untuk kolom `Income` terdapat missing values 24 rows (1,07%). Dikarenakan data kita terbatas, sehingga untuk prosesnya kita tidak akan melakukan penghapusan baris (Drop Rows), melainkan dilakukan proses Imputation. 

Pada proses handling missing values ini kita menggunakan `Imputation using MICE with LightGBM`. Imputasi MICE dapat lebih efisien menggunakan `miceforest` karena diharapkan kinerjanya jauh lebih baik karena mengimplementasikan algortima `lightgbm` di backend untuk melakukan imputasi. `LightGBM` dikenal dengan akurasi prediksi yang tinggi. Menggabungkannya dengan algortima `mice` menjadikannya algortima yang kuat untuk imputasi.


## **📌 Handling Duplicate Rows**

```html
df[df.duplicated(keep=False)].sort_values(by=list(df.columns.values))

df.duplicated().sum()

df.duplicated(subset=["ID"]).sum()

-----------------------------------------
0
```
**Kesimpulan**

- Berdasarkan hasil pengecekan, tidak ditemui baris data yang memiliki duplikat. Sehingga kami tidak perlu melakukan handling duplicated data
- Pada pengecekan duplikat subset untuk ID tidak ditemukan ada nya ID customer yang sama


## **📌 Handling Invalid Values**

```html
===== ID =====
[5524, 2174, 4141, 6182, 5324, 7446, 965, 6177, 4855, 5899, .....]

===== Year_Birth =====
[1957, 1954, 1965, 1984, 1981, 1967, 1971, 1985, 1974, 1950, .....]

===== Education =====
['Graduation', 'PhD', 'Master', 'Basic', '2n Cycle']

===== Marital_Status =====
['Single', 'Together', 'Married', 'Divorced', 'Widow', 'Alone', 'Absurd', 'YOLO']

===== Income =====
[58138.0, 46344.0, 71613.0, 26646.0, 58293.0, 62513.0, 55635.0, 33454.0, 30351.0, 5648.0, .....]

===== Kidhome =====
[0, 1, 2]

===== Teenhome =====
[0, 1, 2]

===== Dt_Customer =====
['2012-09-04', '2014-03-08', '2013-08-21', '2014-02-10', '2014-01-19', '2013-09-09', '2012-11-13', '2013-05-08', '2013-06-06', '2014-03-13', .....]

===== Recency =====
[58, 38, 26, 94, 16, 34, 32, 19, 68, 11, .....]

===== MntWines =====
[635, 11, 426, 173, 520, 235, 76, 14, 28, 5, .....]

===== MntFruits =====
[88, 1, 49, 4, 43, 42, 65, 10, 0, 5, .....]

===== MntMeatProducts =====
[546, 6, 127, 20, 118, 98, 164, 56, 24, 11, .....]

===== MntFishProducts =====
[172, 2, 111, 10, 46, 0, 50, 3, 1, 11, .....]

===== MntSweetProducts =====
[88, 1, 21, 3, 27, 42, 49, 2, 112, 5, .....]

===== MntGoldProds =====
[88, 6, 42, 5, 15, 14, 27, 23, 2, 13, .....]

===== NumDealsPurchases =====
[3, 2, 1, 5, 4, 15, 7, 0, 6, 9, .....]

===== NumWebPurchases =====
[8, 1, 2, 5, 6, 7, 4, 3, 11, 0, .....]

===== NumCatalogPurchases =====
[10, 1, 2, 0, 3, 4, 6, 28, 9, 5, .....]

===== NumStorePurchases =====
[4, 2, 10, 6, 7, 0, 3, 8, 5, 12, .....]

===== NumWebVisitsMonth =====
[7, 5, 4, 6, 8, 9, 20, 2, 3, 1, .....]

===== AcceptedCmp3 =====
[0, 1]

===== AcceptedCmp4 =====
[0, 1]

===== AcceptedCmp5 =====
[0, 1]

===== AcceptedCmp1 =====
[0, 1]

===== AcceptedCmp2 =====
[0, 1]

===== Complain =====
[0, 1]

===== Z_CostContact =====
[3]

===== Z_Revenue =====
[11]

===== Response =====
[1, 0]
```

### **1. Melakukan konversi data `Date`**

Untuk mempermudah dalam proses feature extraction/engineering maka untuk data yang mengandung datetime akan dilakukan konversi ke format datetime pandas

`df["Dt_Customer"] = pd.to_datetime(df["Dt_Customer"])`

### **2. Melakukan penyederhanaan `Marital_Status`**

Akan dilakukan replace data / menyatukan yang memiliki arti yang sama agar mengurangi jumlah dimensi maupun redudansi pada data

- Mengganti kategori `Widow`, `Alone`, `Absurd`, `YOLO` menjadi `Single`
- Mengganti kategori `Together` menjadi `Married`
- Mempertahankan kategori `Divorced`

```html
# Mengganti kategori 'Widow', 'Alone', 'Absurd', 'YOLO' menjadi 'Single'
df['Marital_Status'] = df['Marital_Status'].replace(['Widow', 'Alone', 'Absurd', 'YOLO'],'Single')
# Mengganti kategori 'Together' menjadi 'Married'
df['Marital_Status'] = df['Marital_Status'].replace(['Together'],'Married')
```

`df['Marital_Status'].unique()`

'Single', 'Married', 'Divorced'

### **3. Melakukan penyederhanaan `Education_Simple`**

Untuk kategori `2n Cycle` dan `Master` juga kurang lebih sama. Maka dari itu, baris yang memiliki kategori `2n Cycle` akan dihapus dan digantikan dengan kategori `Master`.

`df['Education'] = df['Education'].replace(['2n Cycle'],'Master')`

**Kesimpulan**

Berdasarkan hasil pengecekan, Untuk kolom `Dt_Customer` sebelumnya masih berbentuk string/object, untuk tipe datanya kurang sesuai sehingga di ubah menjadi Datetime untuk diolah pada tahap Feature Engineering. Kemudian pada `Marital_Status` dan `Education` replace data / menyatukan yang memiliki arti yang sama agar mengurangi jumlah dimensi maupun redudansi pada data.


## **📌 Handling Outliers**

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/82cb2648-4896-4e7f-ba2b-1616f1a9d3e5)

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/4510b7f1-cc69-4513-ab42-258f2f7b5f60)
![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/140f65ab-c55b-41b5-a929-4f35c3b8a5bd)
![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/ae73a9b9-a8be-4bcd-8cb5-a9336b619ba5)

Karena pada kolom `Year_Birth` memiliki nilai min yang sangat jauh di tahun `1893-1900`

dan `Income` memiliki nilai max yang sangat tinggi sebesar `$666.666`

Maka akan dilakukan Penghapusan rows pada nilai ini agar tidak ada ketimpangan nilai. Ada beberapa metode yang dapat kita lakukan :
- **Handling Oulier**
    - IQR (Interquartile Range)
    - Z-Score
- **Manually Trimmed**

**Choice Determination:**

- Untuk kasus saat ini, akan digunakan metode `Manually Trimmed`, agar menghindari penghapusan data yang terlalu banyak jika menggunakan Handling Outlier
- Adapaun pada kolom lainnya `selain Year_Birth dan Income` yang terdapat outlier tidak kita handle karena akan melalui proses `Normal Distribution Transformation` nantinya yang akan `mereduksi outliernya.`

**Manually Trimmed**

- Kolom `Year_Birth`, menghapus nilai yang sangat jauh di tahun `1893-1900`
- Kolom `Income` menghapus nilai yang sangat tinggi sebesar `$666.666`

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/504e3f4a-97bc-4da6-b8c9-536bb6fc0e49)

**Kesimpulan**
Berdasarkan hasil perhitungan menggunakan `Z-score` dan juga `IQR`, dapat diketahui bahwa jumlah baris yang dihapus dari `Year_Birth` dan `Income` berdasarkan `IQR` untuk kolom  tidak jauh berbeda dibandingkan dengan `Z-score`, yaitu :
- IQR :
    - Jumlah data sebelum handling outliers : 2240
    - Jumlah data setelah handling outliers (Year_Birth) : 2237
    - Jumlah data setelah handling outliers (Income) : 2229

- Z_Score :
    - Jumlah data sebelum handling outliers : 2240
    - Jumlah data setelah handling outliers (Year_Birth) : 2237
    - Jumlah data setelah handling outliers (Income) : 2229

Namun, karena kita ingin meminimalisasi penghapusan data maka untuk proses ini kita memiliki `Manually Trimmed` agar tidak terlalu banyak data yang dihapus, jadi hanya berfokus pada data yang memiliki jauh yang sangat tinggi

- Jumlah data sebelum handling outliers : 2240
- Jumlah data setelah handling outliers (Year_Birth) : 2237
- Jumlah data setelah handling outliers (Income) : 2236

## **📌 Feature Engineering / Extraction**

Kita akan melakukan Calculation, Extraction, dan Binning features :
- Age Customer
- Age Group
- Has Child
- Dependents
- Month Customer (Lifetime)
- Spending
- Primer and Tersier product
- Total of Purchases
- Total_Cmp (Accepted Campaign 1-5)
- Ever_Accept (Accepted Campaign 1-5)
- Total Revenue
- Income Segment
- Conversion Rate Web
- Month Joined
- Recency Segment

**Membuat Kolom `Umur / Age`**

Berdasarkan data diketahui basis tahunnya : SAS Institute, 2014

**Membuat Kolom `Age Group`** 

[source age group](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FHuman-Age-Group-Classification-Using-Facial-Bhat-V.K.Patil%2F19ddb412336ce633c1fe21544605c7bd65ff8d66&psig=AOvVaw3Sm17zYYJRrkisQVRyg4rf&ust=1684919686463000&source=images&cd=vfe&ved=0CBMQjhxqFwoTCJDXlY2Ni_8CFQAAAAAdAAAAABAI)

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/7f19ab5e-b8db-4728-b83c-d68e14ddf5d7)

Akan disederhanakan lagi :
- Young Adult < 30
- Adult 30-45 Tahun
- Senior Adult > 45 tahun

**Membuat Kolom `Has_child`**

Menggabungkan Kidhome dan Teenhome menjadi feature Has_child, yang mana hasil penjumlahannya yang memiliki anak minimal 1

**Membuat Kolom `Dependents`**

Jumlah tanggungan dari customer, dari penjumlahan Kidhome dan Teenhome

**Membuat Kolom `Lifetime`**

Sudah berapa bulan customer sejak pembelian pertama di supermarket

**Membuat Kolom `Spending`**

Jumlah pembelian tiap customer pada keseluruhan product

**Membuat Kolom `Primer and Tersier product`**

Jumlah pembelian tiap customer pada kelompok primer dan tersier product

**Membuat Kolom `Total of Purchases`**

Jumlah pembelian tiap customer pada keseluruhan metode pembelian. 

**Membuat Kolom `Total_Cmp`**

Berapa kali tiap customer merespon ke 5 campign yang dilaksanakan (AcceptedCmp 1 - 5)

**Membuat Kolom `Ever_Accept`**

Apakah Customer pernah minimal sekali menerima campign atau tidak pernah sama sekali

**Membuat Kolom `Total Revenue`**

Jumlah Campaign yang diresponse/accept (Campaign 1-5) dikali dengan revenue = 11

**Membuat Kolom `Income Segmentation`**

- None -> Missing values
- High -> >= q3(68468)
- Medium -> q1(35335) - q3(68468)
- Low -> < q1(35335)

**Membuat Kolom `Conversion Rate Web`**

Perbandingan Total Purchases dengan Jumlah Pengunjung Website

**Membuat Kolom `Month Joined`**

Membuat kolom extraction month dari tanggal Customer pertama kali berbelanja

Note : Untuk nilai tahun tidak digunakan karena berpotensi bias karena dari nilai nya akan increasing tiap waktu, sedangkan month akan repeat pada tiap periode

**Membuat Kolom `Recency_sgmt`**

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/67179e33-ba86-402d-948a-be1bcc795c79)

Perkiraan pembagian dengan rentang 19 Hari:
- 4 score -> setengah bulan
- 3 score -> 1 bulan
- 2 score -> 1 setengah bulan
- 1 score -> 2 bulan
- 0 score -> 3 bulan

#### **Mengecek nilai Extraction**

**Categorical (String)**

- Education - Basic, Graduation, Master, PhD
- Marital_Status - Single, Married, Divorced
- Age_group - Young Adult, Adult, Senior Adult
- Income_sgmt - High, Medium, Low

**Categorical (Int)**

- ID
- Kidhome - 0, 1, 2
- Teenhome - 0, 1, 2
- AcceptedCmp1 - 0, 1
- AcceptedCmp2 - 0, 1
- AcceptedCmp3 - 0, 1
- AcceptedCmp4 - 0, 1
- AcceptedCmp5 - 0, 1
- Ever_Accept - 0, 1
- Complain - 0, 1
- Response - 0, 1
- Has_child - 0, 1
- Recency_sgmt - 0, 1, 2, 3, 4

**Numericals**

- Year_Birth = 1940 - 1996
- Income = 1730.0 - 162397.0
- Kidhome = 0 - 2
- Teenhome = 0 - 2
- Recency = 0 - 99
- Age = 18 - 74
- Dependents = 0 - 3
- Lifetime = 1 - 36
- Spending = 5 - 2525
- Primer_purchase = 1 - 1727
- Tersier_purchase = 3 - 1689
- Total_Purchases = 0 - 44
- NumWebVisitsMonth = 0 - 20
- Conversion_rate_web = 0.0 - 43.0
- Total_Cmp = 0 - 4
- Total_revenue = 0 - 44
- Month_joined = 1 - 12

**Numericals (one)**

- Z_CostContact = 3
- Z_Revenue = 11

**Numericals (Product)**

- MntWines = 0 - 1493
- MntFruits = 0 - 199
- MntMeatProducts = 0 - 1725
- MntFishProducts = 0 - 259
- MntSweetProducts = 0 - 263
- MntGoldProds = 0 - 362

**Numericals (Purchases)**

- NumDealsPurchases = 0 - 15
- NumWebPurchases = 0 - 27
- NumCatalogPurchases = 0 - 28
- NumStorePurchases = 0 - 13

**Timestamp**
- Dt_Customer = 2012-07-30 - 2014-06-29


## **📌 Feature Transformation (Numeric)**

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/4962331e-fede-4185-9b24-676068f53654)

Dari hasil temuan, kita dapat menentukan beberapa transformasi yang akan kita lakukan :
- **Scaling and Converting to a Normal Distribution :**
    - log Transformation
    - Box-Cox Transformation
    - Yeo-Johnson Transformation
    
    **Adapun daftar column yang akan kita transform pada proses ini :**
        - Conversion_rate_web
        - MntFishProducts
        - MntFruits
        - MntGoldProds
        - MntMeatProducts
        - MntSweetProducts
        - MntWines
        - NumCatalogPurchases
        - NumDealsPurchases
        - NumStorePurchases
        - NumWebPurchases
        - Primer_purchase
        - Spending
        - Tersier_purchase
        - Total_revenue
    
- **Just Scaling :**
    - Normalization
    - Standardization
    
    **Adapun daftar column yang akan kita transform pada proses ini :**
        - Age
        - Income
        - Lifetime
        - Month_joined
        - NumWebVisitsMonth
        - Recency
        - Total_Purchases
        - Year_Birth

- Sedangkan untuk beberapa kolom yang **tidak perlu melakukan Transformasi** karena rentang nilai yang masih wajar sebagai berikut :
    - Kidhome
    - Teenhome
    - Dependents
    - Total_Cmp

**Choice Determination:**

- Pada proses `Scaling and Converting to a Normal Distribution` ini kita menggunakan `Yeo-Johnson Transformation`, karena dari hasilnya kita bisa melihat hasil bentuk curve yang lebih Normal Distribusi
- Pada proses `Just Scaling` ini kita menggunakan `Normalization` karena lebih robust untuk algoritma yang akan kita gunakan 

**Yeo-Johnson Transformation**

Unlike the Box-Cox transform, it does not require the values for each input variable to be strictly positive.

It supports zero values and negative values. This means we can apply it to our dataset without scaling it first.

```html
pt = PowerTransformer(method='yeo-johnson')
df[log_cols] = pt.fit_transform(df[log_cols])
```

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/2c896c5e-4141-4085-ab20-490fb1d53ac0)

**Normalization**

```html
from sklearn.preprocessing import MinMaxScaler
# create a scaler object
scaler = MinMaxScaler()
# fit and transform the data
df[norm_cols] = pd.DataFrame(scaler.fit_transform(df[norm_cols]), columns=df[norm_cols].columns)
```

**Kesimpulan**

Berdasarkan hasil pengecekan pada beberapa fitur yang telah diproses menggunakan transformation sebelumnya, dapat diketahui bahwa keseluruhan nilai skewnessnya sudah memiliki rentang yang lebih seragam (tidak jauh dan tidak terlalu bervariasi). Sehingga dapat disimpulkan bahwa teknik fitur transformation yang telah kami lakukan sudah valid dan kami.

## **📌 Feature Encoding (Categoric)**

```html
===== Education =====
['Graduation', 'PhD', 'Master', 'Basic']

===== Marital_Status =====
['Single', 'Married', 'Divorced']

===== Age_group =====
['Senior Adult', 'Young Adult', 'Adult']

===== Income_sgmt =====
['Medium', 'High', 'Low']
```
Dari hasil temuan, kita dapat menentukan beberapa encoding yang akan kita lakukan :
- **Label Encoding :**
    - LabelEncoder
    - Manually Mapped
    
    **Adapun daftar column yang akan kita proses :**
    - `Education` - Basic (0), Graduation (1), Master (2), PhD (3)
    - `Age_group` - Young Adult (0), Adult (1), Senior Adult (2)
    - `Income_sgmt` - Low (0), Medium (1), High (2)
    
- **One Hot Encoding :**
    - get_dummies
    - OneHotEncoder
    
    **Adapun daftar column yang akan kita proses :**
    - `Marital_Status` - Single, Married, Divorced

**Choice Determination:**

- Pada proses `Label Encoding` ini kita menggunakan `Manually Mapped`, karena kita bisa menentukan secara fleksible urutan/order dari categorical feature
- Pada proses `One Hot Encoding` ini kita menggunakan `OneHotEncoder`, karena hasil encodingnya lebih rapi dan lebih mudah untuk dilakukan adjust

**Kesimpulan**

Berdasarkan hasil pengecekan pada beberapa fitur yang telah diproses menggunakan encoding sebelumnya, dapat diketahui bahwa keseluruhan nilai telah beripe numeric sesuai dengan nilai yang kita assign. Sehingga dapat disimpulkan bahwa teknik fitur encoding yang telah kami lakukan sudah valid dan kami.

## **📌 Feature Selection**

Ada beberapa fitur yang telah diproses menggunakan feature selection :
- Drop Unnecessary Feature
- Univariate Selection
    - Anova F-value
    - Variance Threshold
    - Mutual Information
    - SelectKBest
- Feature Importance
- Pearson Correlation
- Drop Redundace

### **1. Drop Unnecessary Feature**

- Drop kolom `ID` karena memiliki banyak kategori dan tidak berguna untuk pemodelan
- Drop kolom `Year_Birth` sudah dilakukan Feature extraction untuk mengambil data Umur/Age pada range tahun saat ini 2014 (sesuai pada data)
- Drop kolom `Dt_Customer` karena tidak terlalu mempengaruhi model prediksi
- Drop kolom `Z_CostContact` (3) dan `Z_Revenue` (11) karena  hanya memiliki satu nilai, tidak memberikan informasi yang signifikan terhadap model prediksi

### **2. Univariate Selection**

- #### **ANOVA F-value**

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/adc3f215-9dd5-424b-b20c-53a61e328c8a)

- #### **Variance Threshold**

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/6a369f9b-f13e-46a1-abeb-6fa28a0e960d)

- #### **Mutual information**

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/fce9e499-0769-4e3a-b8fa-5c3af1e351e3)

- #### **Scikit-learn’s SelectKBest**

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/fdb9ba08-f74b-466a-b576-b8549447682d)

### **3. Feature Importance**

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/03a29c62-7ad0-4c0b-9021-6b11741e4a60)

### **4. Correlation Matrix with Heatmap**

- Correlation states how the features are related to each other or the target variable.

- Correlation can be positive (increase in one value of feature increases the value of the target variable) or negative (increase in one value of feature decreases the value of the target variable)

- Heatmap makes it easy to identify which features are most related to the target variable, we will plot heatmap of correlated features using the seaborn library.

- Cek Feature Redundan pada korelasi Antar Feature, Drop salah satunya, yang rendah korelsinya dengan Response (target)

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/0e6b13a0-edf4-4dd1-be56-46092925d577)

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/9f660917-acd4-4669-a6c6-8f116e5520d6)

### **5. Check Data Redundancy**

Dari feature yang telah kita pilih dari gabungan Top 20 akan di lakukan pengecekan kembali melalui `redudansi antar feature`. Pada proses ini kita memilih antar feature yang memiliki korelasi diatas `threshold > 0.70`, yang kemudian akan di `bandingkan korelasinya dengan Target` untuk `drop salah satu feature`

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/490e565d-5bb6-4423-928f-e152cf117bd3)

Maka telah didapatkan feature yang akan digunakan pada proses modelling sebagai berikut :

```html
['AcceptedCmp1',
 'AcceptedCmp2',
 'AcceptedCmp3',
 'AcceptedCmp4',
 'Dependents',
 'Education',
 'Lifetime',
 'Married',
 'MntGoldProds',
 'NumCatalogPurchases',
 'NumDealsPurchases',
 'NumWebVisitsMonth',
 'Recency',
 'Recency_sgmt',
 'Total_Cmp']
```

## **📌 Data Splitting**

I will split the data into training set and testing set with proportion of 75:25.

```html
# define X and y
X = df.drop(['Response'], axis=1)[feature_importance] #features
y = df['Response'] #target
```

```html
from sklearn.model_selection import train_test_split

# splitting tha data
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.25, stratify= y, random_state=42)
print(X_train.shape, X_test.shape)
```

## **📌 Handling Imbalanced Data**

Status risiko highly imbalanced, dengan 15% Response dan 85% No Response. Itu sebabnya diperlukan resampling.

**Note**: Saat menerapkan  machine learning algorithms dengan data yang tidak seimbang, model yang diperoleh akan lebih condong ke kelas mayoritas. Artinya model akan memprediksi kelas mayoritas bukan kelas minoritas.

Jika kita ingin melakukan klasifikasi, maka seharusnya melakukan `stratified train_test_split` terlebih dahulu untuk menjaga ketidakseimbangannya (imbalance). Sehingga dataset test dan train memiliki distribusi yang sama, kemudian jangan pernah menyentuh test set lagi. Kemudian lakukan pengambilan sampel ulang hanya pada data train.

**Summary** : You must apply `SMOTE` after splitting into `training and test`, not before. Doing SMOTE before is bogus and defeats the purpose of having a separate test set.

![image](https://github.com/nurimammasri/Marketing-Campaign-Model-Prediction-by-Datalicious/assets/54845293/499d8c10-193b-45d7-9502-ed1da4604c47)

```html
from imblearn.under_sampling import RandomUnderSampler
from imblearn.over_sampling import RandomOverSampler, SMOTE

....

# Oversampling SMOTE
sm = SMOTE(sampling_strategy=0.5, random_state = 2)
X_balanced_res, y_balanced_res = sm.fit_resample(X_train,y_train)
```

Before OverSampling, the shape of X_train: (1677, 15)
Before OverSampling, the shape of y_train: (1677,) 

Before OverSampling, counts of label '1': 251
Before OverSampling, counts of label '0': 1426 

After OverSampling, the shape of X_train: (2139, 15)
After OverSampling, the shape of y_train: (2139,) 

After OverSampling, counts of label '1': 713
After OverSampling, counts of label '0': 1426



















