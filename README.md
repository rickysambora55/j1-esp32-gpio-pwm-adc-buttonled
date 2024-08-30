## 🚀 About Me

Nama : Ricky Sambora<br>
NIM : 4.31.20.1.21<br>
Kelas : TE-3B

# Jobsheet 1 (GPIO, PWM, ADC) - ESP32

Pada jobsheet 1 terdapat 3 project yaitu simulasi GPIO, PWM, dan ADC menggunakan ESP32.

### Alat dan Bahan

-   ESP32
-   Arduino IDE (Terinstal ESP32)
-   Breadboard
-   Kabel Jumper
-   Resistor < 220Ω
-   LED (5)
-   Push Button
-   Potensiometer

### Instalasi

1. Susun komponen sesuai dengan rangkaian
2. Buka Arduino IDE dan instal ESP32
    - Masuk ke **Preferences**
    - Isikan board url dengan link : https://dl.espressif.com/dl/package_esp32_index.json dan simpan
    - Buka **Tools** > **Board** > **Boards Manager**
    - Cari ESP32, by Espressif. Kemudian instal
    - Pilih flash mode DIO/QIU menyesuaikan
3. Jalankan program .ino
4. Jika terdapat error saat uploading, tekan dan tahan tombol _Boot_ pada ESP32 saat upload, hingga _Connecting_ selesai

## Project 1 - GPIO

### Rangkaian

1. Led menyala saat button ditekan

<img src="https://github.com/user-attachments/assets/cbf747fa-3777-4cfe-95f0-151ad95e4bfc" width="480px">

2. Led menyala dan _blink_ saat button ditekan

<img src="[https://cdn.discordapp.com/attachments/1043462519336996894/1043480466159841370/GPIO2.png](https://github.com/user-attachments/assets/dc2597ba-f644-4dcf-bd4f-460f56b9caad)" width="480px">

3. Led menyala, _blink_, dan berjalan saat button ditekan

<img src="[https://cdn.discordapp.com/attachments/1043462519336996894/1043480465866235975/GPIO3.png](https://github.com/user-attachments/assets/f8603a57-3d71-43a0-975c-634a9b208b4f)" width="480px">

### Keluaran

1. Led menyala saat button ditekan

![GPIO1](https://github.com/user-attachments/assets/29d32a0b-d03c-4c9b-9a0d-1164b5481b6b)

2. Led menyala dan _blink_ saat button ditekan

![GPIO2](https://github.com/user-attachments/assets/475c65fd-c85c-453d-8f4f-8dcbe66b6ae7)

3. Led menyala, _blink_, dan berjalan saat button ditekan

![GPIO3](https://github.com/user-attachments/assets/04adaef7-653b-494b-8719-61fbd2a21d95)

## Project 2 - PWM

### Rangkaian

1. Satu LED _breathing_

<img src="https://github.com/user-attachments/assets/98923ab1-c8fc-4b1c-b64a-3d8110797c2e" width="480px">

2. Tiga LED _breathing_

<img src="https://github.com/user-attachments/assets/999ce152-d8a8-44ca-8471-d3aac8083cd9" width="480px">

### Keluaran

1. Satu LED _breathing_

![PWM1](https://github.com/user-attachments/assets/2a6b760a-d9ed-4432-b0fb-db5f556c1d21)

2. Tiga LED _breathing_

![PWM2](https://github.com/user-attachments/assets/6e49c803-d872-4992-b204-88c164550a0b)

## Project 3 - ADC

### Rangkaian

1. Keluaran potensio pada serial monitor

<img src="https://github.com/user-attachments/assets/55a858a6-ba38-4ee9-afce-214f0c5578d9" width="480px">

2. Potensio terhadap cahaya LED

<img src="https://github.com/user-attachments/assets/8f06d718-b2e5-4b61-b79e-f2ea9a3f376a" width="480px">

### Hasil

1. Keluaran potensio pada serial monitor

![ADC1](https://github.com/user-attachments/assets/a4ad0153-e20d-4a30-8ea8-d99648b9a92d)

2. Potensio terhadap cahaya LED

![ADC2](https://github.com/user-attachments/assets/e8f17403-82c0-4a3b-9698-98c06e58ca2c)
