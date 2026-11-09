# chaox-75-v1
<img width="1119" height="490" alt="1" src="https://github.com/user-attachments/assets/0e1d323f-38ee-485a-ac9e-dbe66c5c6a3f" />
<img width="935" height="622" alt="image" src="https://github.com/user-attachments/assets/ca72729d-548c-4103-8dd6-d4ceeb5c9c78" />
<img width="1017" height="670" alt="image" src="https://github.com/user-attachments/assets/cdfbce8c-92ea-4b02-8bc8-901a1554d9f0" />
<img width="1032" height="365" alt="image" src="https://github.com/user-attachments/assets/0a40b28d-8ecf-4462-8cca-545c3bf6ef00" />
<img width="1051" height="646" alt="image" src="https://github.com/user-attachments/assets/040eaf38-4fe6-4546-b5b7-2a041786c0bb" />

## What is this
This is a keyboard based on rp2040 with only wired connection and it has 82 keys and a rotary encoder.

## Why does this exits
i have a evofox keyboard which costs $10 i got it from a friend i used it for a long time but now teh keys sometimes doesnt work or doesnt press or something and i thought that lets make a keyboard so thats how this keyboard came to light. 

## How to assemble
u just have to solder all the things to the pcb and for that u will need a hot air gun for smalll capacittors and the mcu and a soldering iron to solder all the switches and rotary encoder.

## How to flash 
1. plug in your RP2040 board while holding the BOOT button.

2. Drag and drop the official Pico .uf2 firmware into the RPI-RP2 drive.
to check if this worked check The drive will reboot and reappears as CIRCUITPY.

3. Copy the kmk folder and main.py script from teh firmware folder straight into the root of CIRCUITPY.

thats it done. 

## Bill of Materials (BOM)

| Part | Qty | Approx. USD | Link |
|---|---:|---:|---|
| **RP2040 MCU** (QFN-56) | 1 | $1.20 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=RP2040+QFN56) |
| **W25Q16JV SPI Flash** (SOIC-8) | 1 | $0.40 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=W25Q16JV) |
| **MCP1700-3302E** 3.3V LDO | 1 | $0.35 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=MCP1700T-3302E) |
| **12 MHz SMD Crystal** (3225 4-pin) | 1 | $0.25 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=12MHz+3225+crystal) |
| **Type-C 16-Pin Receptacle** | 1 | $0.30 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=USB-C+16P+receptacle) |
| **Kailh MX Hot-Swap Sockets** | 82 | $6.50 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=Kailh+MX+hot+swap+socket) |
| **SK6812 MINI-E RGB LEDs** | 82 | $6.00 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=SK6812MINI-E) |
| **1N4148W Switching Diodes** (SOD-123) | 82 | $1.50 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=1N4148W+SOD-123) |
| **Passives (0603 Caps & Resistors)** | ~88 pcs | $2.50 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=0603+smd+resistor+capacitor+pack) |
| **EC11 Rotary Encoder + Knob** | 1 | $1.00 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=EC11+rotary+encoder) |
| **SMD Tactile Push Buttons** (Reset/Boot) | 2 | $0.30 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=SMD+tactile+push+button) |
| **Mechanical Switches (82-90 pcs pack)** | 1 pack (90 pcs) | $20.00–$32.00 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=Gateron+Kailh+switches+90pcs) |
| **82-Key Compatible Keycap Set** | 1 set | $15.00–$25.00 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=75+percent+keycaps) |
| **Plate/PCB-Mount Stabilizers** (3x 2u, 1x 6.25u) | 1 set | $4.00–$8.00 | [Alibaba](https://www.alibaba.com/trade/search?SearchText=keyboard+stabilizers+set) |
| **Custom PCB Fabrication** (5 pcs, JLCPCB 2-layer) | 5 pcs | $15.00–$25.00 | [JLCPCB](https://jlcpcb.com) |
| **Case & Switch Plate** (3D printed / CNC / Acrylic stack) | 1 | $15.00–$35.00 | [JLCPCB 3D Print](https://jlcpcb.com/3d-printing) |

### 💰 Total Cost Breakdown

| Category | Estimated Cost |
|---|---:|
| **PCB Components & Electronics** | ~$20 |
| **Switches (82 pcs), Keycaps & Stabs** | ~$40–$65 |
| **PCB Fab (JLCPCB + shipping)** | ~$15–$25 |
| **Case & Switch Plate (3D Printed / CNC)** | ~$15–$35 |
| **Total Build Cost** | **~$90–$200** |

## END
i guess thats it so thank you bye 
