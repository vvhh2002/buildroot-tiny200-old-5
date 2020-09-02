# Progress of F1C100s/F1C200s Driver Support
## <span style="color:green;">Working & Tested</span>
### Boot Device:
- SPI NOR Flash
- SPI NAND Flash
- MMC 0
- MMC 1
### U-Boot Driver:
- Basic LCD
- GPIO Backlight
- USB Peripheral
- MTD Devices
### Linux Driver:
- Simple Peripheral: GPIO, SPI, UART, IIC, SDIO, PWM
- DMA Controller
- Audio Codec: Playback, Mic-IN
- USB: Peripheral Mode
- DVP Camera: OV2640, OV5640
- Display Engine: Frontend, Backend, TCON
## <span style="color:cyan;">Should working && Not tested</span>
### U-Boot Driver:
- PWM Backlight
### Linux Driver:
- Audio Codec: FM-IN, Line-IN
- USB: Host Mode, OTG Mode
- IR Receiver
- Keypad ADC
## <span style="color:yellow;">Work-In-Progress && Partially working</span>
### Linux Driver:
- TV(CVBS) Encoder
- Touchscreen Sensor
- Cedar Video Engine
## <span style="color:red;">Unsupported</span>
... below and not mentioned devices.
### Linux Driver:
- TV(CVBS) Decoder
- Digital Audio
- DE-interlace
- RSB Bus
- OWA Bus
