#Katalon_Mobile_SwagLabs
Ini adalah repositori framework pengujian Mobile App, dibangun dengan Katalon. 

##Struktur Folder
- **Test_Cases/**: Berisi kumpulan kode pengujian fitur yang dipisahkan sesuai Test Case Suites.
    -
- **Object_Repository/**: Berisi kumpulan locator element-element yang akan dipakai di Test Case, yang dipisahkan sesuai kelompok yang digunakan oleh test case. 

- **Test_Suites//**: File untuk menjalankan test suites setiap kelompok test case.
- **Test_Suites/TSC_SWAG**: File untuk menjalankan semua test case suite secara langsung.
- **Data_File/**: Berisi file excel sebagai bahan data untuk pengetesan Data-driven testing(DDT).
- **Keywords/GridHelper.groovy**: Keyword Utility.
- **Test_Listeners/BaseSwag**:File kode untuk base setting framework pengujian.

##Saran Pengembangan
- Membuat Keyword utility seperti login agar pada saat record, state app langsung di bagian menu.
- Stabilkan Element Locator, gunakan WaitForElementPresent jangan pakai Delay.

