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
























