# Raspberry-Pico
Estudo de plataforma embarcada - João Pedro Alcaraz

Manual Raspberry Pi Pico W

O Raspberry Pi Pico é um microcontrolador de baixo custo que foi projetado para ser uma solução compacta e acessível para projetos de hobby, educação e desenvolvimento profissional. a variante Raspberry Pi Pico W foi lançada para adicionar funcionalidades de conectividade sem fio ao dispositivo. O Pico W inclui um módulo certificado a bordo que oferece LAN sem fio e Bluetooth, permitindo a integração com aplicações que requerem comunicação sem fio. O microcontrolador suporta programação em MicroPython e C/C++.



Especificações técnincas:
- Dimensões: 21 mm × 51 mm
- Microcontrolador: RP2040
- Processador: Dual-core Arm Cortex-M0+
- Memória ram: 264kB SRAM on-chip
- Memória on-board: 2MB Flash QSPI
- Conexão sem fio: 2.4GHz 802.11n wireless LAN, Bluetooth 5.2
- Pinos GPIO: 26 multifuncionais (3 entradas analógicas)
- Interfaces de Comunicação: 2 × UART; 2 × SPI; 2 × I2C; 16 × PWM
- Controlador USB: USB 1.1

- <img width="1187" alt="image" src="https://github.com/joaoalca/Raspberry-Pico/assets/99261425/54efb733-e996-4a4a-8b77-c7fdf78d1c77">

Prova de conceito para descrever como utilizar uma das interfaces de comunicação com outros sistemas

Conexão I2C entre Raspberry Pi Pico e Display LCD (Simulação feita utilizando wokwi)

<img width="965" alt="image" src="https://github.com/joaoalca/Raspberry-Pico/assets/99261425/fb630089-3546-48a4-9149-14e4c0badc59">

Conexão:
- Pino LCD GND no Raspberry Pi Pico GND
- Pino LCD VCC no Raspberry Pi Pico VBUS
- Pino LCD SDA no Raspberry Pi Pico pino GPIO 0
- Pino LCD SCL no Raspberry Pi Pico pino GPIO 1
