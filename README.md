# UART-Transmitter
UART-Transmitter
Project Structure ├── transmitter.v # UART transmitter module ├── transmit_debouncing.v # Debouncing logic for push-button input ├── top.v # Top-level module integration ├── Basys3_Master.xdc # FPGA constraint file for pin mapping └── steps to follow.txt # Setup and usage instructions

⚙️ Tools & Requirements

Xilinx Vivado (for synthesis, simulation, and FPGA programming)

Basys3 FPGA Board

Serial terminal (e.g., Tera Term, PuTTY, or minicom) for viewing transmitted data

🚀 How to Run

Clone this repository and open the project in Vivado.

Add the Verilog and XDC files.

Synthesize, implement, and generate bitstream.

Program the Basys3 board with the generated bit file.

Open a serial terminal on your PC (default: 9600 baud, 8N1).

Press the button on the FPGA → observe transmitted data on terminal.

📖 Future Improvements

Adding UART receiver module for full-duplex communication

Support for variable baud rates

FIFO buffer integration for continuous data transmission
