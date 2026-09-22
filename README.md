# 🚧 Catraca Automática com ESP32

Projeto de uma catraca automática utilizando **ESP32**, **sensor ultrassônico**, **servo motor**, **LED** e **display OLED**.

## ⚙️ Funcionamento

O sensor ultrassônico mede a distância de um objeto:

* 📏 **Até 90 cm:** abre a catraca e liga o LED.
* 📏 **A partir de 110 cm:** fecha a catraca e desliga o LED.
* 🖥️ O OLED mostra o estado da catraca.
* 📡 O Monitor Serial exibe a distância medida.

## 🔌 Componentes

* ESP32
* Servo motor
* Sensor ultrassônico
* Display OLED 128x64
* LED
* Protoboard e jumpers

## 📍 Pinos

| Componente | ESP32   |
| ---------- | ------- |
| Servo      | GPIO 23 |
| TRIG       | GPIO 12 |
| ECHO       | GPIO 14 |
| LED        | GPIO 4  |
| OLED       | I²C     |

## 📚 Bibliotecas

```cpp
ESP32Servo
Wire
Adafruit_GFX
Adafruit_SSD1306
```

## 🎯 Objetivo

Criar um sistema simples de **controle automático de acesso**, demonstrando o uso de sensores, servo motor, LED e display OLED com ESP32.

**Projeto desenvolvido para fins educacionais.**
