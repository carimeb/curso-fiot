# Modelo (ESP8266 Node MCU V3 ESP-12E)

- Classificação: microcontrolador
- Nome técnico: Módulo WiFi ESP-12E 
- Ano de lançamento: 2013

O módulo NodeMcu ESP-12E é uma placa de desenvolvimento que combina o chip ESP8266, uma interface usb-serial e um regulador de tensão 3.3V. A programação pode ser feita usando LUA ou a IDE do Arduino, utilizando a comunicação via cabo micro-usb. Usado em projetos de Iot em geral.

## Características
Suas principais características são:

- Padrões wireless: IEEE 802.11b, IEEE 802.11g, IEEE 802.11n;
- Faixa de frequência: 2.4GHz;
- Taxa de transmissão: 110 à 460 Mbps;
- Antena Embutida;
- Interface USB: CH340;
- Interface: Serial UART (Tx / Rx);
- Segurança: WEP / WPA / TKIP / AES;
- Alimentação: 4,0 à 9,0 VDC (conector Micro USB);
- Tensão Lógica: 3,3 VDC;
- Consumo: Min 70 mA (Standby) e Máx 220 mA (802.11b, CCK 1Mbps,Pout=+19.5dBm);
- Conversor A/D: 10 bits ADC e Vin 0 à 1 VDC;
- GPIO: 11 portas;
- Dimensão: 6,0 x 3,0 x 1,5 cm (C x L x A);
- Peso: 10g;

### Arquitetura

O conjunto de instruções Xtensa é uma arquitetura de 32 bits com um conjunto de instruções compacto de 16 e 24 bits. O conjunto de instruções básicas tem 82 instruções RISC e inclui uma ALU de 32 bits, 16 registros de 32 bits de uso geral e um registro de propósito especial.

### Conjunto de instruções

Novo ISA pós-RISC voltado para produtos integrados, de comunicação e de consumo

### CPU

- Clock: 80MHz a 160MHz
- Cache: sim, mas não está informado o quanto na planilha técnica
- Núcleos: Tensilica Xtensa® 32-bit LX106

### GPU

- Clock: não achei
- Cache: não achei
- Núcleos: não achei

### Memória

- Tipo: 128 KB internal RAM and 4MB of external Flash memory
- Tamanho: acima

### GPIO

- Quantidade: 17
- Tipos: ADC channel, UART interface, PWM outputs, SPI, I2C, I2S interface.

### Recursos

- Bluetooth: sim
- Rede: 802.11b/g/n HT40 Wi-Fi transceiver

## Fotos


## Referências

[Google](https://components101.com/sites/default/files/component_datasheet/ESP12E%20Datasheet.pdf)
[Insight Into ESP8266 NodeMCU Features] (https://lastminuteengineers.com/esp8266-nodemcu-arduino-tutorial)
[Wikipedia] (https://en.wikipedia.org/wiki/Tensilica)
(https://0x04.net/~mwk/doc/xtensa.pdf)

