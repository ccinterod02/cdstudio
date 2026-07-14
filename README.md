# cdstudio

Zephyr boards for cdstudio PCBs.

| Board | SoC | Notes |
|---|---|---|
| `snake/esp32c6/hpcore` | ESP32-C6 | 802.15.4 + BLE + I2C, BME280 on I2C0 (0x76) |
| `fractal/stm32h573/xi` | STM32H573Xi | Cortex-M33, 2 status LEDs on PB0/PB1 |

## Build

```bash
west build -b snake/esp32c6/hpcore   app
west build -b fractal/stm32h573/xi   app
```