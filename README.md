
# Jobsheet 1 (GPIO, PWM, ADC) - ESP32

Pada jobsheet 1 terdapat 3 project yaitu simulasi GPIO, PWM, dan ADC menggunakan ESP32.


### Alat dan Bahan

- ESP32
- Arduino IDE (Terinstal ESP32)
- Breadboard
- Kabel Jumper
- Resistor < 220Ω
- LED (5)
- Push Button
- Potensiometer

### Instalasi

1. Susun komponen sesuai dengan rangkaian
2. Buka Arduino IDE dan instal ESP32
- Masuk ke **Preferences**
- Isikan board url dengan link : https://dl.espressif.com/dl/package_esp32_index.json dan simpan
- Buka **Tools** > **Board** > **Boards Manager**
- Cari ESP32, by Espressif. Kemudian instal
- Pilih flash mode DIO/QIU menyesuaikan
3. Jalankan program .ino
4. Jika terdapat error saat uploading, tekan dan tahan tombol *Boot* pada ESP32 saat upload, hingga *Connecting* selesai
## Project 1 - GPIO

### Rangkaian

1. Led menyala saat button ditekan

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043480465459400754/GPIO1.png)

2. Led menyala dan *blink* saat button ditekan

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043480466159841370/GPIO2.png)

3. Led menyala, *blink*, dan berjalan saat button ditekan

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043480465866235975/GPIO3.png)
### Keluaran

1. Led menyala saat button ditekan

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043463435775655936/GPIO1.gif)

2. Led menyala dan *blink* saat button ditekan

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043463436551589908/GPIO2.gif)

3. Led menyala, *blink*, dan berjalan saat button ditekan

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043463436195078155/GPIO3.gif)
## Project 2 - PWM
### Rangkaian

1. Satu LED *breathing*

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043497654681866240/PWM1.png)

2. Tiga LED *breathing*

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043497654354706494/PWM2.png)
### Keluaran

1. Satu LED *breathing*

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043503682853023844/PWM1.gif)

2. Tiga LED *breathing*

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043503683217915994/PWM2.gif)
## Project 3 - ADC


### Rangkaian

1. Keluaran potensio pada serial monitor

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043497654681866240/PWM1.png)

2. Potensio terhadap cahaya LED

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043497654354706494/PWM2.png)
### Hasil

1. Keluaran potensio pada serial monitor

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043497654681866240/PWM1.png)

2. Potensio terhadap cahaya LED

![App Screenshot](https://cdn.discordapp.com/attachments/1043462519336996894/1043497654354706494/PWM2.png)
