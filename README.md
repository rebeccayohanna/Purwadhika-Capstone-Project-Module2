# Purwadhika-Capstone-Project-Module2

**JCDSVL - Capstone Project Module 2**
**Nama : Yohanna Inawati Santoso**

Repository ini berisi tugas capstone project module 2 dengan details :

## **Context**

Perusahaan Northwind bergerak di bidang jual-beli produk makanan. Perusahaan tersebut ingin mengetahui gambaran umum tentang bisnis yang sedang mereka jalankan.
Terdapat database yang berfokus pada proses transaksi. Dari database tersebut, perusahaan ingin mendapatkan insight yang sesuai untuk penerapan strategi yang tepat sasaran untuk memperoleh keuntungan yang lebih baik.

## **Database Information**

Sumber Database: https://drive.google.com/drive/folders/1fTHrwh_gcLsOFKXHnUzUGEu_APxLoD9i

Terdapat 13 tabel pada database Northwind, yaitu:
 - Employees : Menyimpan informasi karyawan.
 - EmployeeTerritories : Menyimpan informasi teritori karyawan.
 - Territories : Menyimpan informasi data teritori.
 - Region : Menyimpan informasi wilayah.
 - Orders : Menyimpan informasi jual-beli yang terjadi.
 - OrderDetails : Menyimpan detail informasi dari setiap pesanan yang terjadi.
 - Products : Menyimpan informasi jenis produk.
 - Categories : Menyimpan informasi kategori produk.
 - Suppliers : Menyimpan informasi data supplier.
 - Shippers : Menyimpan informasi data ekspedisi.
 - Customers : Menyimpan informasi data pelanggan.
 - CustomerCustomerDemo : Menyimpan informasi demo pelanggan.
 - CustomerDemographics : Menyimpan informasi demografi pelanggan.

**Fokus utama dari analisis ini terdapat pada tabel Orders, OrderDetails, dan Shippers. Tabel lain akan digunakan sebagai penunjang informasi yang diperlukan untuk kedua tabel tersebut.**

## **Details Data Features yang Digunakan**
Data yang disimpan pada variabel ```df``` merupakan data dari tabel ```order```, ```orderDetails```, ```shippers```, ```products``` dan ```categories```. Data ini menjadi data utama yang akan dianalisa lebih lanjut. Dari tabel tersebut, diambil beberapa kolom dengan informasi yang dianggap penting. Informasi tersebut adalah :

 - OrderID dari tabel orders
 - CustomerID dari tabel orders
 - OrderDate dari tabel orders
 - RequiredDate dari tabel orders
 - ShippedDate dari tabel orders
 - ShipVia dari tabel orders
 - CompanyName dari tabel shippers
 - ShipName dari tabel orders
 - ShipAddress dari tabel orders
 - ShipCity dari tabel orders
 - ShipRegion dari tabel orders
 - ShipCountry dari tabel orders
 - ProductName dari tabel Products
 - CategoryName dari tabel Categories
 - UnitPrice dari tabel orderDetails
 - Quantity dari tabel orderDetails
 - Discount dari tabel orderDetails
 - totalRev merupakan perkalian UnitPrice dan Quantity dari tabel OrderDetails untuk mendapatkan totalRevenue

Informasi tersebut dijadikan DataFrame untuk proses pengolahan informasi.

## **EDA**
Exploratory Data Analysis menggunakan bahasa pemrograman Python, dengan library NumPy dan Pandas

## **Data Visualization & Statistics**
Tools pada data visualization ini akan menggunakan library Python yaitu Matplotlib dan Seaborn. Seaborn dibangun diatas Matplotlib. Namun, Seaborn memiliki kelebihan dibandingkan dengan Matplotlib yaitu hasil visualisasi yang lebih bagus serta serangkaian kodenya lebih mudah digunakan.
