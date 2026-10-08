# HelloRustOnESP32

> Since Arduino was bought and I don't really like C++, why not have a look at Rust on the ESP32?

I need:

* A board with an SSD1306 display that listens for UDP messages for students and connects to Wi-Fi.
* A board that simulates a BLE mouse.
* A board that simulates a BLE keyboard.
* A board that simulates a BLE XInput controller.
* A board that communicates with an XArduino over Wi-Fi UART.

The goal is to remotely control devices using Bluetooth input.

I don't have time to work on this right now, but it's something I will need to work on eventually.

Doc:
- https://docs.espressif.com/projects/rust/book/introduction/hardware-overview.html
- https://github.com/embassy-rs/embassy
- https://github.com/arlyon/esp-wifi-async-example/tree/main
