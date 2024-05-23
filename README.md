# STM32F303_NUCLEO_64_CAN-Bus_LoopBack
Proof of concept test project for HAL-based CAN-bus communication in loopback mode with a STM32F303 NUCLEO-64 board. 
Two messages with different 11-bit IDs are sent and filtered to different FIFO mailboxes.
Callback functions for each Rx FIFO reads the messages and copies it to separate positions in an RxData-array.   
