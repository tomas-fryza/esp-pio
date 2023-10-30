# esp-pio

1. Instalace VS Code
2. Instalace PlatformIO
3. Vytvoření nového projektu pro desku `Espressif ESP32 Dev Module`
https://github.com/platformio/platform-espressif32/blob/develop/examples/arduino-blink/src/Blink.cpp

viz `01-blink`

Pozn.: V konfiguračním souboru `platformio.ini` nastavit:
monitor_speed = 115200

Kompilace + Nahrání do desky + Serial monitor

Vysvětlit `setup()` a `loop()`

Pinout desky Expressif ESP32Dev
https://circuits4you.com/2018/12/31/esp32-devkit-esp32-wroom-gpio-pinout/

Vysvětlit nepájivé pole.
Přidat 2x externí LED + rezistory

4. Arduino APIs pro ESP32:
https://espressif-docs.readthedocs-hosted.com/projects/arduino-esp32/en/latest/libraries.html#apis

Přidat tlačítko a podmínit blikání stiskem.

Použití logického analyzátoru
https://support.saleae.com/logic-software/legacy-software/older-software-releases#logic-1-x-download-links

5. Komunikace s I2C zařízením
I2C scanner: připojit několik I2C zařízení na sběrnici
SCL - GPIO 22
SDA - GPIO 21
https://gist.github.com/walidamriou/1e759043d66340f9c76c7d13b6abf55e
0x68: Slave adresa senzoru MPU-6050

I2C čtení ze senzoru MPU-6050
https://randomnerdtutorials.com/esp32-mpu-6050-accelerometer-gyroscope-arduino/
TBD

6. Časovač, přerušení
https://espressif-docs.readthedocs-hosted.com/projects/arduino-esp32/en/latest/api/timer.html

7. Wi-Fi scan
https://github.com/platformio/platform-espressif32/blob/develop/examples/arduino-wifiscan/src/WiFiScan.ino

8. Wi-Fi STA
TBD

9. Wi-Fi + senzor + ThingSpeak
TBD
