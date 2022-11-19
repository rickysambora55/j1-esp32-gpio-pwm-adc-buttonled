## 🚀 About Me

Nama : Ricky Sambora
NIM : 4.31.20.1.21
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

<img src="https://cdn.discordapp.com/attachments/1043462519336996894/1043480465459400754/GPIO1.png" width="480px">

2. Led menyala dan _blink_ saat button ditekan

<img src="https://cdn.discordapp.com/attachments/1043462519336996894/1043480466159841370/GPIO2.png" width="480px">

3. Led menyala, _blink_, dan berjalan saat button ditekan

<img src="https://cdn.discordapp.com/attachments/1043462519336996894/1043480465866235975/GPIO3.png" width="480px">

### Keluaran

1. Led menyala saat button ditekan

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043463435775655936/GPIO1.gif)

2. Led menyala dan _blink_ saat button ditekan

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043463436551589908/GPIO2.gif)

3. Led menyala, _blink_, dan berjalan saat button ditekan

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043463436195078155/GPIO3.gif)

## Project 2 - PWM

### Rangkaian

1. Satu LED _breathing_

<img src="https://cdn.discordapp.com/attachments/1043462519336996894/1043497654681866240/PWM1.png" width="480px">

2. Tiga LED _breathing_

<img src="https://cdn.discordapp.com/attachments/1043462519336996894/1043497654354706494/PWM2.png" width="480px">

### Keluaran

1. Satu LED _breathing_

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043525436740747344/PWM1.gif)

2. Tiga LED _breathing_

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043525436325507082/PWM2.gif)

## Project 3 - ADC

### Rangkaian

1. Keluaran potensio pada serial monitor

<img src="https://cdn.discordapp.com/attachments/1043462519336996894/1043512224053985410/ADC1.png" width="480px">

2. Potensio terhadap cahaya LED

<img src="https://cdn.discordapp.com/attachments/1043462519336996894/1043512224393728091/ADC2.png" width="480px">

### Hasil

1. Keluaran potensio pada serial monitor

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043514762471931984/ADC1.gif)

2. Potensio terhadap cahaya LED

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043526036496863362/ADC2.gif)
