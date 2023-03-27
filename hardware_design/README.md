# Hardware Design

## ESP32 Variants

Sadly, `ESP32` only has [1 CAN driver](https://docs.espressif.com/projects/esp-idf/en/v5.0.1/esp32/api-reference/peripherals/twai.html):

> "The ESP32’s peripherals contains **a TWAI controller** that can be configured to communicate on a TWAI bus via an external transceiver."

However, `ESP32-C6` has [2 CAN drivers](https://docs.espressif.com/projects/esp-idf/en/latest/esp32c6/api-reference/peripherals/twai.html):

> "The ESP32-C6 contains **2 TWAI controller(s)** that can be configured to communicate on a TWAI bus via an external transceiver."

[ESP32-C6](https://www.espressif.com/en/products/modules?id=ESP32-C6) should be "pin-for-pin" compatible with ESP32 modules. Only a few DevKits are available for `ESP32-C6` at the time of this writing.