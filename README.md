# IrisOne
A small ESP32-C6-MINI-1 based dev board.

You can use this board with your own personal project and peripherals. The dev board uses only 2 IO pins and its IO0 for a white LED and IO18 for a SK6805-EC14 LED.
Made this because of need for a small dev board that can be used for IoT stuff like ESPHome.

## Screenshots
<details>
    <summary>Click to expand</summary>
    <img width="730" height="546" alt="image" src="https://github.com/user-attachments/assets/b41eb8c5-96a7-4187-91c0-ea09a2c27388" />
    <img width="886" height="565" alt="image" src="https://github.com/user-attachments/assets/32b9a7f7-46bf-44ab-8c6b-4a5ff156bc18" />
    <img width="1190" height="845" alt="SCH_Iris One_1-P1_2026-02-21" src="https://github.com/user-attachments/assets/661119a0-4e99-4e52-b4ad-c71b180db1e2" />
    <img width="423" height="648" alt="image" src="https://github.com/user-attachments/assets/41c58928-78ab-4b92-b9c0-abb3be6d7ecd" />
    <img width="417" height="659" alt="image" src="https://github.com/user-attachments/assets/524489ae-6145-4c76-b92a-e6cdbb2cc685" />
    <img width="1905" height="883" alt="image" src="https://github.com/user-attachments/assets/770af719-774c-47b4-9821-4dddc8c4dbc4" />

</details>

## Bill of materials
### To find each component use the Supplier Part field at https://www.lcsc.com/
|No.|Quantity|Comment            |Designator|Footprint                                         |Value |Manufacturer Part  |Manufacturer       |Supplier Part|Supplier|
|---|--------|-------------------|----------|--------------------------------------------------|------|-------------------|-------------------|-------------|--------|
|1  |1       |1uF                |C1        |C0402                                             |1uF   |CL05A105KA5NQNC    |SAMSUNG(三星)        |C52923       |LCSC    |
|2  |2       |10uF               |C2,C3     |C0402                                             |10uF  |CL05A106MQ5NUNC    |SAMSUNG(三星)        |C15525       |LCSC    |
|3  |1       |10kΩ               |F1        |RES-ARRAY-SMD_0404-4P-L1.0-W1.0-BL                |10kΩ  |YC122-JR-0710KL    |YAGEO(国巨)          |C695179      |LCSC    |
|4  |1       |KT-0805W           |LED1      |LED0805-R-RD                                      |      |KT-0805W           |KENTO              |C34499       |LCSC    |
|5  |1       |SK6805-EC14        |LED2      |LED-SMD_4P-L1.4-W1.4-TL                           |      |SK6805-EC14        |欧思科光电              |C2909055     |LCSC    |
|6  |1       |10kΩ               |R1        |R0402                                             |10kΩ  |0402WGF1002TCE     |UNI-ROYAL(厚声)      |C25744       |LCSC    |
|7  |2       |5.1kΩ              |R2,R3     |R0402                                             |5.1kΩ |0402WGF5101TCE     |UNI-ROYAL(厚声)      |C25905       |LCSC    |
|8  |1       |75Ω                |R4        |R0402                                             |75Ω   |0402WGF750JTCE     |UNI-ROYAL(厚声)      |C25133       |LCSC    |
|9  |2       |SKTDLHE010         |SW1,SW2   |KEY-SMD_SKTDLHE010                                |      |SKTDLHE010         |ALPSALPINE(阿尔卑斯阿尔派)|C380198      |LCSC    |
|10 |1       |2.4GHz             |U1        |WIFIM-SMD_61P-L16.6-W13.2-P0.80-ESP32-C6-MINI-1-N4|2.4GHz|ESP32-C6-MINI-1-N4 |ESPRESSIF(乐鑫)      |C5736265     |LCSC    |
|11 |1       |AP2112K-3.3TRG1(MS)|U2        |SOT-23-5_L2.9-W1.6-P0.95-LS2.7-BR                 |      |AP2112K-3.3TRG1(MS)|MSKSEMI(美森科)       |C22365427    |LCSC    |
|12 |1       |TYPE-C 16P QTGM027 |USB1      |USB-C-SMD_TYPE-C-16P-QTGM027                      |      |TYPE-C 16P QTGM027 |SHOU HAN(首韩)       |C2681552     |LCSC    |


**Total: ~$8.83**
