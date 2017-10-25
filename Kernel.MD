# Materi Kernel
A. Sejarah Kernel

Kernel merupakan program komputer yang mengatur permintaan akan input/output dari perangkat lunak, dan menerjemahkannya ke dalam instruksi-instruksi pada CPU, ataupun komponen elektronik lainnya dalam sebuah komputer. Kernel merupakan bagian yang sangat mendasar pada sistem operasi komputer masa kini.

Karena akses terhadap perangkat keras terbatas, sedangkan ada lebih dari satu program yang harus dilayani dalam waktu yang bersamaan, maka kernel juga bertugas untuk mengatur kapan dan berapa lama suatu program dapat menggunakan satu bagian perangkat keras tersebut. Hal tersebut dinamakan sebagai multiplexing.

Akses kepada perangkat keras secara langsung merupakan masalah yang kompleks, oleh karena itu kernel biasanya mengimplementasikan sekumpulan abstraksi hardware. Abstraksi-abstraksi tersebut merupakan sebuah cara untuk menyembunyikan kompleksitas, dan memungkinkan akses kepada perangkat keras menjadi mudah dan seragam. Sehingga abstraksi pada akhirnya memudahkan pekerjaan programer.

Pada dasarnya, untuk menjalankan sebuah komputer tidak harus menggunakan kernel sistem operasi. Sebuah program dapat saja langsung dijalankan oleh komputer, yaitu saat sebuah program komputer akan digunakan tanpa bantuan abstraksi perangkat keras atau bantuan sistem operasi. Teknik ini umumnya digunakan oleh komputer-komputer generasi awal, sehingga bila ingin berpindah dari satu program ke program lain, pengguna harus mereset dan menjalankan kembali program-program tersebut.