## 🔌 Power & Voltage Pins

VCC: Main power input for the board (typically 3.3V or 5V, depending on the board).​

VIN: Voltage input to the board's voltage regulator (often 6–12V).​

3.3V: Regulated 3.3V output from the board.​

5V: Regulated 5V output from the board.​

GND: Ground reference for the circuit.​

EN: Enable pin; pulling this high enables the board's voltage regulator.​

VL: Logic voltage level reference for certain sensors or modules.​

## 🧠 Communication Pins

SCL (Serial Clock Line): Clock line for I²C communication.​

SDA (Serial Data Line): Data line for I²C communication.​

SCK (Serial Clock): Clock line for SPI communication.​

MOSI (Master Out Slave In): Data line from master to slave in SPI communication.​

MISO (Master In Slave Out): Data line from slave to master in SPI communication.​

TX0 / TX: Transmit line for UART communication.​

RX0 / RX: Receive line for UART communication.​

## ⚙️ Control & Interrupt Pins

IRQ (Interrupt Request): Pin used to signal an interrupt to the microcontroller.​

INT (Interrupt): Another label for interrupt pins.​

RST (Reset): Resets the microcontroller when pulled low.​

DRDY (Data Ready): Indicates that new data is available from a sensor.​

L/R (Left/Right): Used in audio modules to select or indicate left/right channels.​

## 🧪 Analog & Sensor Pins

VP / VN: Analog input pins on ESP32 (VP = GPIO36, VN = GPIO39).​

A0–A5: Analog input pins on Arduino boards.
