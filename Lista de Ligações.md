# Lista de Ligações

### EBYTE LoRa E220

**E220 -> ESP32-WROOM-32**

* M0 -> D4
* M1 -> D22
* RXD -> D17/TX2
* TXD -> D18/RX2
* AUX -> D21
* VCC -> 3V3
* GND -> GND

### ADS115 ADC

**ADS115 -> Power Supply**

* VDD -> 5V
* GND -> GND

**ADS115 -> ESP32-WROOM-32**

* SCL -> D19
* SDA -> D18

**ADS115 -> Sensor de pH**

* A1 -> DATA

**ADS115 -> Sensor de Turbidez**

* A0 -> D

**ADS115 -> TDS**

* A2 -> A

**ADS115 -> Sensor de Temperatura**

* A3 -> DATA

### Sensor de pH

**Sensor de pH -> Power Supply**

* GND -> GND
* VCC -> 5V

**Sensor de pH -> ADS115**

* DATA -> A1

### Sensor de Turbidez

**Sensor de Turbidez -> Power Supply**

* GND -> GND
* +5 -> 5V

**Sensor de Turbidez -> ADS115**

* D -> A0

### TDS

**TDS -> Power Supply**

* GND -> GND
* VCC -> 5V

**TDS -> ADS115**

* A -> A3

### ESP32-WROOM-32(Powering Pins)

**ESP32-WROOM-32 -> Power Supply**

* 3V3 -> 5V
* GND -> GND

### Power Supply

**Power Supply -> Painel Solar**

* USB-Type-C -> USB-Type-C

#

![Projeto Guarda Rios](https://guarda-rios.pt/wp-content/uploads/2024/04/guarda_rios-removebg-preview-10.png)
