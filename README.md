# Power Distribution Board
Conceptual overview of PDB:
![Concept](conceptual.drawio.svg)


# Main Components and Datasheet
| Part | Specs | Cost/# |
| --- | --- | --- |
| N Channel Mosfet [IRF60](https://www.mouser.de/datasheet/2/196/Infineon_IRF60DM206_DataSheet_v01_01_EN-1732441.pdf) | 60V, 135A, 2mOhm Rds(on), 5x6mm DirectFet | [2.50 EUR](https://www.mouser.de/ProductDetail/Infineon/IRF60DM206?qs=sGAEpiMZZMua3V2yDfsb6V0SAvrzyb%252BzUEYr31%2Fae00%3D) |
|High Side Mosfet Driver [LTC7004](https://www.analog.com/media/en/technical-documentation/data-sheets/ltc7004.pdf) | 60V (135V Variant), internal CP, fast switch-on | [6.00 EUR](https://www.mouser.de/ProductDetail/Analog-Devices-Inc/LTC7004EMSEPBF?qs=sGAEpiMZZMv0NwlthflBiwpFCaqJ1pgQZawfbnoBRKg%3D)
| Precharge, balance Mosfet [DMN6040](https://datasheet.lcsc.com/lcsc/1912111437_Diodes-Incorporated-DMN6040SVTQ-7_C461037.pdf) | 60V, 5A, Ciss=2nF | [0.30 EUR](https://lcsc.com/product-detail/MOSFETs_Diodes-Incorporated-DMN6040SVTQ-7_C461037.html) |
| Precharge, balance Driver [TCK401G](https://toshiba.semicon-storage.com/info/docget.jsp?did=59174&prodName=TCK401G) | **40V**, internal CP, 2nF max | [0.70 EUR](https://www.digikey.de/de/products/detail/toshiba-semiconductor-and-storage/TCK401G-LF/8543444) |
