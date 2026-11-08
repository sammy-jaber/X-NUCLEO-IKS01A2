# X-NUCLEO-IKS01A2 Sensor Examples

Two Mbed programs for the ST X-NUCLEO-IKS01A2 expansion board:

- **`sensor_id.cpp`**: prints each sensor's device ID once at startup. It's a quick way to check that the board is connected and all sensors respond.
- **`main.cpp`**: reads every sensor and prints the results to the serial console every 20 seconds: temperature, humidity, pressure, and 3-axis magnetometer, accelerometer and gyroscope data.

## Hardware

- STM32 Nucleo board with Arduino headers
- X-NUCLEO-IKS01A2 expansion board

## Usage

1. Add one of the two files and the `X_NUCLEO_IKS01A2` library to an Mbed project (Mbed OS 2 or 5). Both files have their own `main()`, so build only one at a time.
2. Build and flash it to your Nucleo board.
3. Open a serial terminal at 9600 baud to see the output. For the ID check, press reset after the terminal is open.
