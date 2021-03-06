# EmeddedSystemProject
This repo contains all the material about the project of the Embedded Systems course @Polimi (AA2020/21)

**Please, use the release menu to download our latest version of the project (v1.0-rc)**

## Abstract
During the development of softwares for simulated hardware on Vivado, it sometimes happens that the module UART is chosen to carry out communications to other devices rather than to the user. If we consider an hardware simulated by software on Vivado, no practical system to decode inbound (RX) or outbound (TX) UART signals is observed. To simplify the data transmission debug on UART, we have decided to develop a module which is able to run the decodication process of the RX and TX signals; in this way human interaction is possible. To increase the reliability level of the long-distance transmission, we have also developed a module which can evaluate 4+1 bit more than the simple parity bit; as a consequence, in addition to the error detection, we can also carry out the error correction on errors on a single or two bits and signal an error over errors with more bit. The UART 0 module is transparent with respect to the final users of the transmission, so that it can be used without necessarily acting on the software side for correct data transmission. Even if only tested on Cortex M3 and AXI UART Lite, the module developed by us should not theoretically have compatibility problems with other implementations, as it is independent of the ARM architecture used.

More information can be found in the PDF on this repo.
