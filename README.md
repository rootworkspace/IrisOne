# IrisOne
A small ESP32-C6-MINI-1 based dev board.

You can use this board with your own personal project and peripherals. The dev board uses only one IO pin and its IO0 for the white led.
Made this because of need for a small dev board with USB capabilities.

## Screenshots
<details>
    <summary>Click to expand</summary>
    <img width="1918" height="1033" alt="image" src="https://github.com/user-attachments/assets/8ef96f4a-d94d-447d-b104-ea9fc61cf14a" />
    <img width="1918" height="1033" alt="image" src="https://github.com/user-attachments/assets/5714098c-02a3-4c7b-b9e0-eddc97bd6895" />
    <img width="373" height="512" alt="image" src="https://github.com/user-attachments/assets/65f5b34f-077e-43a9-b4f9-cee913e7fc48" />
    <img width="356" height="511" alt="image" src="https://github.com/user-attachments/assets/04141805-dd64-4105-b89d-45bc759031c9" /><img width="1190" height="845" alt="SCH_Iris One_1-P1_2026-02-20" src="https://github.com/user-attachments/assets/c952167c-8ac1-4f11-bbe7-778d1d84cf88" />
    <img width="1899" height="864" alt="image" src="https://github.com/user-attachments/assets/32c3da24-b231-4b54-ba7a-5e01e683a9a4" />
</details>

## Bill of materials
### To find each component use the Supplier Part field at https://www.lcsc.com/
|No.|Quantity|Comment            |Designator|Footprint                                         |Value |Manufacturer Part  |Manufacturer       |Supplier Part|Supplier|
|---|--------|-------------------|----------|--------------------------------------------------|------|-------------------|-------------------|-------------|--------|
|1  |1       |1uF                |C1        |C0402                                             |1uF   |CL05A105KA5NQNC    |SAMSUNG(三星)        |C52923       |LCSC    |
|2  |2       |10uF               |C2,C3     |C0402                                             |10uF  |CL05A106MQ5NUNC    |SAMSUNG(三星)        |C15525       |LCSC    |
|3  |1       |10kΩ               |F1        |RES-ARRAY-SMD_0404-4P-L1.0-W1.0-BL                |10kΩ  |YC122-JR-0710KL    |YAGEO(国巨)          |C695179      |LCSC    |
|4  |1       |KT-0805W           |LED1      |LED0805-R-RD                                      |      |KT-0805W           |KENTO              |C34499       |LCSC    |
|5  |1       |10kΩ               |R1        |R0402                                             |10kΩ  |0402WGF1002TCE     |UNI-ROYAL(厚声)      |C25744       |LCSC    |
|6  |2       |5.1kΩ              |R2,R3     |R0402                                             |5.1kΩ |0402WGF5101TCE     |UNI-ROYAL(厚声)      |C25905       |LCSC    |
|7  |1       |75Ω                |R4        |R0402                                             |75Ω   |0402WGF750JTCE     |UNI-ROYAL(厚声)      |C25133       |LCSC    |
|8  |2       |SKTDLHE010         |SW1,SW2   |KEY-SMD_SKTDLHE010                                |      |SKTDLHE010         |ALPSALPINE(阿尔卑斯阿尔派)|C380198      |LCSC    |
|9  |1       |2.4GHz             |U1        |WIFIM-SMD_61P-L16.6-W13.2-P0.80-ESP32-C6-MINI-1-N4|2.4GHz|ESP32-C6-MINI-1-N4 |ESPRESSIF(乐鑫)      |C5736265     |LCSC    |
|10 |1       |AP2112K-3.3TRG1(MS)|U2        |SOT-23-5_L2.9-W1.6-P0.95-LS2.7-BR                 |      |AP2112K-3.3TRG1(MS)|MSKSEMI(美森科)       |C22365427    |LCSC    |
|11 |1       |TYPE-C 16P QTGM027 |USB1      |USB-C-SMD_TYPE-C-16P-QTGM027                      |      |TYPE-C 16P QTGM027 |SHOU HAN(首韩)       |C2681552     |LCSC    |

**Total: ~$8.28**
