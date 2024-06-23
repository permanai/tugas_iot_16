1462100069_Permana Iswahyudi

Pada proyek ini, kita menggunakan Proteus untuk mensimulasikan pengukuran suhu menggunakan sensor LM35 dan menampilkannya pada LCD melalui Arduino Uno.

1. Arduino Uno R3: Membaca tegangan dari LM35 melalui pin A0, menghitung suhu, dan mengirimkan data ke LCD.
2. LM044L: Menampilkan teks dan nilai suhu yang dibaca oleh Arduino.
3. LM35: Sensor suhu yang mengeluarkan tegangan linear sesuai suhu.

Library LiquidCrystal: Digunakan untuk mengontrol LCD. 
lcd.print("CEK SUHU RUANGAN"): Menampilkan teks "CEK SUHU RUANGAN" pada baris pertama. 
lcd.print("TUNGGU 1 DETIK"): Menampilkan teks "TUNGGU 1 DETIK" pada baris kedua. 
delay(1000): Menunggu selama 1 detik. 
lcd.print(Celcius): Menampilkan nilai suhu dalam derajat Celcius.
lcd.print("C"): Menampilkan huruf "C" untuk Celsius.
lcd.print((char)223): Menampilkan simbol derajat (°).

