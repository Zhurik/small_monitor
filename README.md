# small_monitor

Маленький мониторчик для малинки.

Работает на базе [этого репозитория](https://github.com/juj/fbcp-ili9341).

## Параметры сборки:

```text
cmake -DSPI_BUS_CLOCK_DIVISOR=6 -DST7735R=ON -DDISPLAY_SWAP_BGR=ON -DGPIO_TFT_DATA_CONTROL=22 -DGPIO_TFT_RESET_PIN=27 -DSTATISTICS=0 ..
```

## Схема подключения

* VCC -> 5V

* GND -> GND

* CS -> CE0

* RESET -> 27

* A0 -> 22

* SDA -> MOSI

* SCK -> SCLK

* LED -> 3.3V
