## 🔌 Power & Voltage Pins

VCC: Main power input (typically 3.3V or 5V).

VIN: Voltage input to the board's regulator (often 6–12V).

3.3V / 5V: Regulated voltage outputs from the board.

GND: Ground reference for the circuit.

EN: Enable pin; pulling high enables the board's voltage regulator.

VL: Logic voltage level reference for certain sensors or modules.

VBAT: Battery input for RTC and backup registers.

VREF+ / VREF-: Reference voltages for ADCs.

LDO / VREG: Low Dropout Regulator output or voltage regulator pins.

VBUS: USB power supply voltage.​

## 🧠 Communication Pins

### I²C (Inter-Integrated Circuit)

SCL (Serial Clock Line): Clock line for I²C communication.

SDA (Serial Data Line): Data line for I²C communication.​

### SPI (Serial Peripheral Interface)

SCK (Serial Clock): Clock line for SPI communication.

MOSI (Master Out Slave In): Data line from master to slave.

MISO (Master In Slave Out): Data line from slave to master.

CS / SS (Chip Select / Slave Select): Selects the active SPI device.​

UART (Universal Asynchronous Receiver-Transmitter)
TX / TX0: Transmit line.

RX / RX0: Receive line.

CTS (Clear To Send): Flow control signal.

RTS (Request To Send): Flow control signal.​

### USB

DP / DM: USB data lines.

ID: USB identification pin.​


CAN (Controller Area Network)

CAN_H / CAN_L: Differential pair for CAN communication.​

## ⚙️ Control & Interrupt Pins

IRQ (Interrupt Request): Signals an interrupt to the microcontroller.

INT (Interrupt): Another label for interrupt pins.

NMI (Non-Maskable Interrupt): High-priority interrupt that cannot be disabled.

EXTI (External Interrupt): Configurable external interrupt pins.

RST / NRST / RESET: Resets the microcontroller when activated.

BOOT / BOOT0 / BOOT1: Determines the boot mode of the microcontroller.

DRDY (Data Ready): Indicates new data is available from a sensor.

L/R (Left/Right): Used in audio modules to select or indicate left/right channels.​


## 🧪 Analog & Sensor Pins
A0–A5: Analog input pins on Arduino boards.

VP / VN: Analog input pins on ESP32 (VP = GPIO36, VN = GPIO39).

ADC / AIN (Analog-to-Digital Converter / Analog Input): Reads analog voltage levels.

DAC (Digital-to-Analog Converter): Outputs analog voltages generated from digital values.

SENSOR_VP / SENSOR_VN: Analog sensor inputs, commonly found on ESP32 boards.​

## 🛠️ Debugging & Programming Interfaces

SWD (Serial Wire Debug): Two-pin interface for debugging.

JTAG (Joint Test Action Group): Standard for verifying designs and testing printed circuit boards.

TCK (Test Clock): Clock signal for JTAG.

TMS (Test Mode Select): Mode select signal.

TDI (Test Data In): Data input.

TDO (Test Data Out): Data output.​


## 🎛️ Miscellaneous
PWM (Pulse Width Modulation): Pins capable of outputting PWM signals for controlling devices like motors or LEDs.

OSC_IN / OSC_OUT: Pins connected to an external oscillator or crystal for clock generation.​

