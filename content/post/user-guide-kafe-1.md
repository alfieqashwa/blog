---
title: "User Guide Kafe 1"
date: 2018-06-10T02:31:42+07:00
draft: false
categories: ["User Guide", "Kafe"]
tags:
- kafe
- user guide
thumbnailImagePosition: left
thumbnailImage: /img/kafe-business-process.jpg
---

# Pendahuluan


Posting ini diperuntukkan untuk para user **Kafe & Resto** yang telah di training, khususnya back-office dan kasir. Tujuannya sebagai dokumentasi untuk membantu para _user_ atau pengguna memahami lebih baik tentang bagaimana cara mengoperasikan sistem aplikasi ini.

Sebagai pendahuluan, sistem aplikasi ini berbasis teknologi [ERP](https://en.wikipedia.org/wiki/Enterprise_resource_planning "Enterprise Resource Planning") yang dapat di implementasikan baik secara *online (cloud-base)* maupun *offline (LAN)*. Sistem aplikasi ini berbasis web sehingga dapat dijalankan selama terinstall aplikasi browser seperti [Chrome](https://www.google.com/chrome/) atau [Firefox](https://www.mozilla.org/en-US/firefox/new/) pada __PC__, __Notebook__, __iPad__, __Tablet__, atau __SmartPhone__.

Sistem berbasis teknologi [ERP](https://en.wikipedia.org/wiki/Enterprise_resource_planning "Enterprise Resource Planning") secara fundamental sifatnya saling terkait antar satu aplikasi dengan aplikasi lainnya sehingga data-data transaksi yang telah tercatat sangat sulit dimanipulasi atau dihilangkan karena *jejak-digital* transaksi-transaksi bisnis Anda saling __terintegrasi__ secara sistematis.

Secara umum, [ERP](https://en.wikipedia.org/wiki/Enterprise_resource_planning "Enterprise Resource Planning") terdiri dari modul-modul aplikasi **Purchase Management**, **Inventory & Stock Management**, **Manufacture / Bill of Material**, **Sales**, **CRM**, **Project Management** dan **Accounting & Finance**.

Beberapa sistem [ERP](https://en.wikipedia.org/wiki/Enterprise_resource_planning "Enterprise Resource Planning") terkenal yang mungkin familiar di telinga Anda adalah [SAP](https://www.sap.com/index.html "Systemanalyse und Programmentwicklung"), [Oracle ERP](https://www.oracle.com/applications/erp/index.html "Oracle-ERP"), dan [Micrososft Dynamics GP](https://dynamics.microsoft.com/en-us/gp-overview/ "Dynamics GP"). Ketiganya berbasis _closed-source_. Sedangkan sistem [ERP](https://en.wikipedia.org/wiki/Enterprise_resource_planning "Enterprise Resource Planning") lainnya yang berbasis _open-source_ diantaranya [InoERP](http://inoideas.org/ "PHP"), [ERPNext](https://erpnext.com/ "Python"), [OpenBravo](http://www.openbravo.com/ "Python"), [Odoo](https://www.odoo.com/ "Python"), [Flectra](https://flectrahq.com/ "Python"), [Hexya](http://hexya.io/ "Golang"), dan lain sebagainya.

Pada posting tersendiri akan saya share lebih lanjut tentang sistem [ERP](https://en.wikipedia.org/wiki/Enterprise_resource_planning "Enterprise Resource Planning") yang saya gunakan dan bagaimana cara mengimplementasikan serta menggunakannya baik secara _functional_ (dari sisi user) maupun secara _technical_ (dari sisi developer/programmer).

---



# Bisnis Proses Kafe

Meskipun cakupan postingan ini secara khusus hanya akan membahas bisnis **Kafe & Resto**, namun sistem aplikasi ini dapat di implementasikan dengan bisnis lain seperti _konveksi_, _distro multi-cabang_, *Travel*, *Rental*, *Salon*, *Sekolah*, baik bisnis skala UKM hingga skala perusahaan menengah serta *franchise*. Sistem ini pun terdiri dari modul-modul aplikasi lainnya seperti **E-Commerce**, **CRM**, **Project Management**, **HR & Payroll**, dan lain sebagainya yang keseluruhannya saling terintegrasi serta bermuara dengan modul **Accounting & Finance**.

Sebagai Pemilik Kafe & Resto tentu Anda ingin mengetahui kapan tepatnya segala transaksi pembelian serta penjualan terjadi dan berapa jumlah nominal transaksinya, siapa pihak suplier maupun customer yang berhubungan dengan bisnis Anda, produk apa yang di beli serta yang di jual dan berapa qty-nya berikut siapa user/staf yang bertanggungjawab dalam melakukan input data.

Lebih lanjut tentu Anda ingin mengetahui secara detil menu-menu paling laku terjual, yang mana informasi tersebut dapat dijadikan acuan untuk menentukan strategi usaha Anda dalam meningkatkan penjualan yang lebih baik lagi.

Anda pun ingin mengetahui berapa jumlah _stock_ barang atau bahan-bahan makanan & minuman dalam gudang / dapur Anda serta produk-produk mana yang tidak layak terpakai atau tidak dapat digunakan lagi oleh sebab rusak, pecah, dan basi atau _expired_. Dan yang terakhir, tentu Anda ingin mengetahui laporan-laporan finansial Anda seperti *income*, *expense*, profit, neraca keuangan, dan laporan lainnya.

Jika bisnis Anda memiliki beberapa cabang di pelbagai daerah, Anda pun dapat memantau tiap transaksi bisnis secara real-time serta memeriksa laporan keuangan dimanapun Anda berada _selama ada akses jaringan internet_ tanpa harus berkunjung _secara fisik_ ke masing-masing cabang-cabang bisnis Anda. 

>Ibarat **CCTV**, sistem aplikasi ini memang tidak dapat menangkap maling. Tetapi ia dapat dijadikan sebagai alat bukti _valid_ manakala terjadi manipulasi yang dilakukan salah satu pegawai Anda, serta sangat efektif sebagai acuan preventif dalam mereduksi kecurangan-kecurangan dalam transaksi bisnis suatu perusahaan.

Secara garis besar, gambar berikut ini adalah bisnis proses sebuah **Kafe & Restoran** dari __Supplier__ --> __Inventory__ --> __Manufacture__ --> __Point of Sale__ --> __Customer__ yang keseluruhannya bermuara pada __Accounting & Finance__.

![Kafe Business Process](/img/kafe-business-process.jpg)

Pada posting selanjutnya akan disertakan video berikut deskripsi tentang bisnis proses **Kafe & Resto**.

Anda pun dapat mencoba __Demo Sistem Kafe & Resto__ di [Demo Kafe](http://kafe.circleq.co/ "Demo Kafe").
Hubungi kami di [Circle\`Q](http://circleq.co/page/contactus "My Whatsapp: +62-812-8093-1980") untuk mendapatkan akses user demo atau sekedar ingin berkonsultasi tentang bisnis Anda yang unik dan membahas permasalahan serta menemukan solusinya.