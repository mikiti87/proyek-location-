# flutter_application_1

A new Flutter project.

nama; baruna akbar rizqi
kelas;trpl2b
nim;362458302069

jadi disini saya akan menjeaskan dengan versi saya 

jadi bisa dilihat dari cara untuk pengerjaan yang dikirimkan  
disana sudah ada petunjuk yang sudah jelas 

yaitu nomer 1 nah nomer satu itu sudah di beri petunjuk oleh bapak yaitu di tambahkan versi geocoing di pubspec.yaml

ditambahkan beserta versinya 

untuk nomer 2 yaitu kita hanya harus menambahkan import di main bebas boleh di bawah geolocator 

lalu untuk nomer 3 itu kita menambahkan variabel baru nah ini itu tinggal ngikurin apa yang sudah ada kan disana ada position dan string? jadi kita bisa menambahkan string? currentAddress; di bagian myhomepagestate

untuk nomer 4 saya sebenarnya sudah sedikit paham jadi disana saya mengamati dibagian mana itu ditambahkan yaitu dengan ctrl f lalu memasukkan handle agar saya tahu alur nya jadi saya telusuri di tiap tiap bagian lalu saya ctrl f lagi untuk memasukkan position position lalu saya menemukan di handlegetlocation disana saya menemukan getlcation awalnya saya bingung mau menambahkan di mana itu getaddresnya namun saya mencoba coba saya taruh di bawah getaddres from latng ternyata error lalu saya mencoba untuk melihat dari teman saya yang sudah benar lalu saya lihat bagaimana alurnya dan ternyata benar itu ditambahkan di try di getfromlatng dan disana ditambahkan di tengah tengah antara try du handle itu lalu saya mencoba untuk menyesuaikan lalu tidak error saya pikir sudah bisa tapi saya coba kembali ternyata tidak menampilkan varchar alamatnya jadi saya mencoba lagi mencocokkan kembali dari teman saya dan  ternyata itu ada beberapa yang masih kurang yang mana itu belum dipanggil jadi saya membenahkan apa yang kurang dan alhasil muncul 

![WhatsApp Image 2025-11-10 at 15 51 00 (1)](https://github.com/user-attachments/assets/4ed6e7bf-e525-432c-a439-f47f4502b733)
![WhatsApp Image 2025-11-10 at 15 51 00](https://github.com/user-attachments/assets/181cda2a-1c15-4474-b464-e63c5dd6e7b9)


disini saya menambahkan juga untuk location sekarang 
![WhatsApp Image 2025-11-11 at 20 35 11 (1)](https://github.com/user-attachments/assets/7229f976-3595-41d6-bc36-ca8efe89f619)
![WhatsApp Image 2025-11-11 at 20 35 11](https://github.com/user-attachments/assets/04c16e25-cc4d-4d25-b8b8-196716aec5c5)

jadi saya menambahkan di main.dart
Menambahkan field _isLoading dan memanggil _handleGetLocation() di initState() agar aplikasi mencoba mendapatkan lokasi saat startup.

Menambahkan CircularProgressIndicator di UI ketika _isLoading == true.
Mengubah _handleGetLocation() untuk mengatur state loading dan menampilkan error apabila terjadi.
ini untuk mengantisipasi agar tidak gagar total dan mengurangi adanya bug jadi kita membuat adanya error dulu agar bisa mengantisipasi error 

karena menurut saya proyek yang bagus bukan proyek yang paling aman dan bukan juga paling gampang di hack tapi
proyek yang paling aman adalah ketika kita bisa untuk mencoba untuk membuat error dan tau mana error itu dan bisa dijadikan pembelajaran sebelum di kasih tahu orang lain
