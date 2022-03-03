# Power Distribution Board
Conceptual overview of PDB:
![Concept](conceptual.drawio.svg)


# Main Components and Datasheet
| Part | Specs | Cost/# |
| --- | --- | --- |
| N Channel Mosfet [IRF60](https://www.mouser.de/datasheet/2/196/Infineon_IRF60DM206_DataSheet_v01_01_EN-1732441.pdf) | 60V, 135A, 2mOhm Rds(on), 5x6mm DirectFet | [2.50 EUR](https://www.mouser.de/ProductDetail/Infineon/IRF60DM206?qs=sGAEpiMZZMua3V2yDfsb6V0SAvrzyb%252BzUEYr31%2Fae00%3D) |
| N Fet [SiR626DP](https://www.vishay.com/docs/75255/sir626dp.pdf) | 60V 100 A 1.5mOhm 5x6mm | [2.00 EUR](https://de.farnell.com/vishay/sir626dp-t1-re3/mosfet-n-kanal-60v-100a-powerpak/dp/2729836) |
|High Side Mosfet Driver [LTC7004](https://www.analog.com/media/en/technical-documentation/data-sheets/ltc7004.pdf) | 60V (135V Variant), internal CP, fast switch-on | [6.00 EUR](https://www.mouser.de/ProductDetail/Analog-Devices-Inc/LTC7004EMSEPBF?qs=sGAEpiMZZMv0NwlthflBiwpFCaqJ1pgQZawfbnoBRKg%3D)
| Precharge, balance Mosfet [DMN6040](https://datasheet.lcsc.com/lcsc/1912111437_Diodes-Incorporated-DMN6040SVTQ-7_C461037.pdf) | 60V, 5A, Ciss=2nF | [0.30 EUR](https://lcsc.com/product-detail/MOSFETs_Diodes-Incorporated-DMN6040SVTQ-7_C461037.html) |
| Precharge, balance Driver [TCK401G](https://toshiba.semicon-storage.com/info/docget.jsp?did=59174&prodName=TCK401G) | **40V**, internal CP, 2nF max | [0.70 EUR](https://www.digikey.de/de/products/detail/toshiba-semiconductor-and-storage/TCK401G-LF/8543444) |
| Current Sense Amp [INA240A4](https://www.ti.com/general/docs/suppproductinfo.tsp?distId=10&gotoUrl=https%3A%2F%2Fwww.ti.com%2Flit%2Fgpn%2Fina240)| 200V/V, -6 to 90V Common Mode | [3.00 EUR](https://www.digikey.de/de/products/detail/INA240A4PWR/296-45091-2-ND/6562020?utm_campaign=buynow&utm_medium=aggregator&curr=eur&utm_source=octopart) |
|Step down [LM2679SD](http://www.ti.com/general/docs/suppproductinfo.tsp?distId=26&gotoUrl=http%3A%2F%2Fwww.ti.com%2Flit%2Fgpn%2Flm2679) | 8-40V in, 1.2-37V out, 5A | [6.60 EUR](https://www.mouser.de/ProductDetail/Texas-Instruments/LM2679SD-ADJ-NOPB?qs=X1J7HmVL2ZEt2AUSK4np2g%3D%3D) |
| P Channel Mosfet [DMP6110](https://www.digikey.de/de/products/detail/diodes-incorporated/DMP6110SFDF-7/7352983) | 60V 4.2A 110mOhm Rdson | [0.50 EUR](https://www.digikey.de/de/products/detail/diodes-incorporated/DMP6110SFDF-7/7352983) |
| Diode [S1B-13-F](https://www.digikey.de/de/products/detail/diodes-incorporated/S1B-13-F/725026) | SMA 1A 100V | [0.20 EUR](https://www.digikey.de/de/products/detail/diodes-incorporated/S1B-13-F/725026)|


# Pinout DSUB
DSUB Pinout
| Pin | Name |
| --- | --- |
| 1 | In+ |
| 2 | Cell6 |
| 3 | Cell5 |
| 4 | Cell4 |
| 5 | Cell3 |
| 6 | Cell2 |
| 7 | Cell1 |
| 8 | Cell0 |
| 9 | I2C CLK |
| 10 | R_NTC | 
| 11 | I2C Data |
| 12 | IN2- |