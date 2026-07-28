# X2-USB-Hub
<img width="1369" height="812" alt="Screenshot 2026-07-28 at 2 44 02 PM" src="https://github.com/user-attachments/assets/3ec43971-fbc9-44d6-9bc5-ab1cd252e5cd" />



This is a 7 Port USB Hub that I made for the Hack Club Macondo program. It features 4 USB-C ports and 3 USB-A ports at USB2 High Speed.

A clever design is that I used 2 SL2.1S USB Controllers for double the ports. This reduces complexity from a more advanced USB 3 controller that supports more ports. It is also much cheaper than a USB 3 controller.

It is designed for portability, and it has an interesting beveled design.


EasyEDA/OSHWLAB Link: <https://oshwlab.com/jlc9mmb5/project_wpitkgvw>

# Cost
It costs me 50$ (60 after shipping) to order 5 Assembled PCBs from JLCPCB. PCBWAY and NextPCB had super high prices. 

# Schematic
<img width="822" height="582" alt="Screenshot 2026-07-28 at 3 18 45 PM" src="https://github.com/user-attachments/assets/e985bcb7-f404-45b6-bdec-fac1c7f61714" />

# PCB
<img width="282" height="567" alt="Screenshot 2026-07-28 at 3 19 40 PM" src="https://github.com/user-attachments/assets/f51f4f66-da39-4e03-af1b-ccd183ffc330" />


# BOM
## Bill of Materials (BOM)

| No. | Quantity | Comment | Designator | Footprint | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier | Price |
|----:|---------:|---------|------------|-----------|-------|-------------------|--------------|---------------|----------|------:|
| 1 | 14 | 1uF | C1, C2, C3, C4, C5, C6, C7, C8, C10, C11, C13, C16, C17, C19 | C0603 | 1uF | CL10A105KB8NNNC | Samsung | C15849 | LCSC | $0.68 |
| 2 | 6 | 100nF | C9, C12, C14, C15, C18, C20 | C0603 | 100nF | CC0603KRX7R9BB104 | Yageo | C14663 | LCSC | $0.07 |
| 3 | 2 | 5.1K | R1, R2 | R0603 | 5.1K | 0603WAF5101T5E | UNI-ROYAL | C23186 | LCSC | $0.01 |
| 4 | 8 | 56K | R3, R4, R5, R6, R7, R8, R9, R10 | R0603 | 56K | 0603WAF5602T5E | UNI-ROYAL | C23206 | LCSC | $0.03 |
| 5 | 2 | SL2.1s | U1, U2 | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL | — | SL2.1s | CoreChips (和芯润德) | C2684433 | LCSC | $0.24 |
| 6 | 5 | TYPE-C 16PIN 2MD(073) | USB1, USB2, USB3, USB5, USB7 | USB-C-SMD_TYPE-C-16PIN-2MD-073 | — | TYPE-C 16PIN 2MD(073) | SHOU HAN (首韩) | C2765186 | LCSC | $0.19 |
| 7 | 3 | 10.0 QHHTZB6.3 | USB4, USB6, USB8 | USB-A-TH_10.0QHHTZB6.3 | — | 10.0 QHHTZB6.3 | SHOU HAN (首韩) | C668591 | LCSC | $0.11 |



# License
MIT
Open Source
