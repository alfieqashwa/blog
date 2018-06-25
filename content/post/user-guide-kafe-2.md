---
title: "User Guide Kafe 2"
date: 2018-06-11T00:49:26+07:00
draft: false
categories: ["User Guide", "Kafe"]
tags:
- kafe
- user guide
thumbnailImagePosition: left
thumbnailImage: /img/kafe-business-process.jpg
---

# Workflow

Berikut modul-modul aplikasi yang terinstall pada sistem kafe: 

![Kafe Module](/img/kafe-apps.png)


## Contoh Kasus

Kafe ingin menjual menu makanan __Nasi Goreng Kambing__ dimana untuk membuat menu tersebut memerlukan _sedikitnya_ dua produk bahan, yaitu __Beras__ dan __Daging Kambing Muda__ dimana masing-masing di beli dari __Agen Beras__ dan __Agen Daging__.

---
|Suplier        |Produk Bahan           |Harga/kg|Qty   |Total  |
|---            |---                    |---     |---   |---    |
|Agen Beras     |Beras                  |10 rb   |10 kg |100 rb |
|Agen Daging    |Daging Kambing         |60 rb   |1 kg  |60 rb  |

---

# Membuat Data Suplier

Video di bawah adalah cara membuat suplier berikut produk bahan-bahan yang akan di beli oleh Kafe & Resto.
___

<iframe width="560" height="315" src="https://www.youtube.com/embed/chsqXFWvjiY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>



### Create Vendor
>Klik _Menu_ __Purchases__ --> _Sub-Menu_ __Purchase__ --> __Vendors__ --> __Create__

### Create Product
>Klik _Menu_ __Purchases__ --> _Sub-Menu_ __Purchase__ --> __Products__ --> __Create__

### Note !
Hilangkan centang kolom __Can be Sold__ namun tetap di centang kolom __Can be Purchased__ karena product yang di create sifatnya hanya dapat di beli _only_ dan _ga_ untuk dijual.

Pada tabel __Unit of Measure__ isikan satuan _gram_ serta pada tabel __Purchase Unit of Measure__ isikan dengan satuan _kilogram_. Tujuannya adalah, kita membeli ke suplier dengan satuan _kilogram_ dimana nanti di konversi dengan satuan _gram_ dalam _stock opname_ inventory/gudang saat produk pembelian tersebut telah di terima. 

---

## Melakukan PO (Purchase Order)

Berikut adalah video tentang cara melakukan pembelian produk bahan ke suplier hingga di terima di _inventory_ :
___

<iframe width="560" height="315" src="https://www.youtube.com/embed/gbOCC_f9F-Q" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Bisnis Proses

> __Request for Quotation__ --> __Purchase Orders__ --> __Inventory__

---

## Cek Stock Opname

Ada beberapa cara untuk mengecek qty produk di inventory:

>Klik _Menu_ __Purchases__ --> _Sub-Menu_ __Purchase__ --> __Nama Product__ --> dan lihat __On hand__ pada sudut kanan atas

__Atau__

>Klik _Menu_ __Inventory__ --> _Sub-Menu_ __Reports__ --> __Inventory Valuation__

Lebih rinci sila _klik kanan pada mouse_ lalu klik _Open Link in New Tab_ pada video di bawah ini:
___

<iframe width="560" height="315" src="https://www.youtube.com/embed/xdxmzFVENZ8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

---

# Cara Membuat Product Category dan Product Menu

Ada dua jenis Product Category:

1. Internal Category
2. Pos Product Category

### Internal Category

Internal Category berguna untuk melihat laporan penjualan atau pembelian berdasarkan category. Pada contoh, produk-produk bahan (untuk di beli) di setting ke dalam Internal Caterory __All/Ingredients__.
Sedangkan produk menu (untuk di jual) di setting ke dalam Internal Category __All/Sealable/__.

Menu terbagi menjadi makanan dan minuman, berikut kategori-kategori turunan yang di buat sesuai keperluan, misalnya __All/Sealable/Food/NasGor__ dan __All/Sealable/Beverage/Juice__.

>Klik _Menu_ __Inventory__ --> _Sub-Menu_ __Configuration__ --> __Product Categories__ --> __Create__

### Pos Product Category

Pos Product Category berfungsi sebagai tampilan Kasir untuk mempermudah penjualan serta setting _printer order_ yang akan di kupas pada posting tersendiri.

>Klik _Menu_ __Point of Sale__ --> _Sub-Menu_ __Configuration__ --> __Pos Product Categories__ --> __Create__



Pada video di bawah ini kita membuat Category baru bernama __All/Sealable/Food/Khas Indonesia__ pada __Internal Category__ dan __FOOD/KHAS INDONESIA__ pada __Pos Product Category__.

Kemudian kita membuat sebuah menu baru __Nasi Goreng Kambing__ yang di centang kolom __Can be Sold__ saja dan menghilangkan centang __Can be Purchase__ karena menu ini hanya untuk di jual. Kita set menu __Nasi Goreng Kambing__ dengan harga jual sebesar _Rp 25,000.-_.
___


<iframe width="560" height="315" src="https://www.youtube.com/embed/33WIF3BPJ0M" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

---

Beberapa fungsi pada video di atas tidak dijelaskan secara rinci di blog ini oleh sebab hanya dijelaskan secara tuntas pada training saja. Tujuan posting hanya sekedar untuk melengkapi pemahaman training semata.

Demikian akan kita lanjutkan lagi pada posting selanjutnya.
