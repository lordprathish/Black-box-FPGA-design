# Black-box-FPGA-design
The UART Blackbox Flight Recorder continuously receives sensor and control data through UART and stores it in address-based memory with timestamps and packet numbers. During faults or resets, the last 100 packets are retrieved and transmitted using SPI for crash analysis.
