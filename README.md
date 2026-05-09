# Spoodis
A simple box that shows my spotify status and can play the song through spotify connect.

# Items needed

To build this you would only need 
1. A 1.8" TFT Display Module
2. A MAX98357A I2S DAC Class D Mono Amplifier Module
3. Seeed Studio XIAO ESP32-S3 Microcontroller Board
4. Lipo Battery of your choice (I'm using two 600 mAh 602025 lipo)

Here's the complete BOM I used:
|Name                       |Purpose                                                     |Quantity|Total Cost (USD)|Link                                                                                                                                                                                                                                                                                                                                                             |Distributor    |
|---------------------------|------------------------------------------------------------|--------|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|
|ADS1115 ADC I2C Module     |Converts Analog output from joystick to digital             |1       |3.00            |https://www.aliexpress.com/item/1005012085141253.html?spm=a2g0o.detail.0.0.2458sroksrokv5&mp=1&pdp_npi=6%40dis%21USD%21USD+9.69%21USD+3.00%21%21USD+2.97%21%21%21%40212e520d17782950406122191e65cc%2112000057491846745%21ct%21BD%216073142226%21%211%210%21                                                                                                      |AliExpress     |
|Speaker                    |Play The Music                                              |1       |2.90            |https://www.daraz.com.bd//products/i322948195-s1531329388.html?spm=a2o42.cart.0.0.117128298zWR8E&urlFlag=true&tradePath=%2CcartPriceDrop%2Ccart                                                                                                                                                                                                                  |DarazBD        |
|3D Print                   |3D Printed Case                                             |1       |20.00           |https://printlegion.hackclub.com/                                                                                                                                                                                                                                                                                                                                |Printing Legion|
|1.8" TFT SPI Module ST7735S|The main Display                                            |1       |2.36            |https://www.aliexpress.com/item/1005006949272318.html?spm=a2g0o.cart.0.0.49e738da443r96&mp=1&pdp_npi=6%40dis%21USD%21USD+3.19%21USD+2.36%21%21USD+2.36%21%21%21%40212a70c017778941571476547e6d9a%2112000038825304681%21ct%21BD%216073142226%21%211%210%21                                                                                                        |AliExpress     |
|Seeedstudio XIAO ESP32-S3  |Main MCU for driving the display as well as sound processing|1       |14.08           |https://www.aliexpress.com/item/1005009532378267.html?spm=a2g0o.cart.0.0.49e738da443r96&mp=1&sourceType=620&pdp_npi=6%40dis%21USD%21USD+28.05%21USD+14.02%21%21USD+13.88%21%21%21%40212a70c017778941571476547e6d9a%2112000049385728703%21ct%21BD%216073142226%21%211%210%21&pdp_ext_f=%7B%22cart2PdpParams%22%3A%7B%22signature%22%3A%228f2de86badb5ec91%22%7D%7D|AliExpress     |
|MAX98357A                  |I2S MONO Audio Ampliphier                                   |1       |3.67            |https://store.roboticsbd.com/electronics-module/2919-max98357a-i2s-dac-class-d-mono-amplifier-module-robotics-bangladesh.html                                                                                                                                                                                                                                    |Robotics BD    |
|LiPo Battery 600 mAh       |To Power The Device                                         |2       |2.60            |https://www.daraz.com.bd/products/600mah-602025-37v-i325474931.html?spm=a2a0e.searchlist.list.20.2bf24e22Htcvdt                                                                                                                                                                                                                                                  |Daraz BD       |

                                                                                                                                    



For the case you can either print it yourself or use a service like BDtronics or JLC3DP

# Building
To build it yourself use the print 3d files in CAD/PrintParts to 3D print the parts. Then wire the components according to this wiring diagram.
<img width="632" height="463" alt="image" src="WiringDiagram.png" />
<img width="548" height="369" alt="WiringDiagram copy" src="https://github.com/user-attachments/assets/b2394376-a464-48c7-999a-0e54d82dd435" />


Now put everything inside the case and screw the back side in and its done.

** If you need to change or modify anything use the OnShape document here: [https://cad.onshape.com/documents/127f76d6721a894aa68b7aad/w/a87aa85b129c19d2610ae0ad/e/92650a9be47494a4742bc179](https://cad.onshape.com/documents/127f76d6721a894aa68b7aad/w/a87aa85b129c19d2610ae0ad/e/92650a9be47494a4742bc179) (Just make a copy and do your modifications)**

# Pics:
Here are some pics (will update once I finish building it IRL)

<img width="575" height="397" alt="image" src="https://github.com/user-attachments/assets/586fd5c1-a8d3-4742-aaa7-d2d4911aea48" />
<img width="567" height="386" alt="image" src="https://github.com/user-attachments/assets/921ae76d-a2f7-46a6-9448-0990b4a1c088" />

<img width="548" height="399" alt="image" src="https://github.com/user-attachments/assets/96603b97-3017-4ad9-b190-16674d9892d1" />


<img width="632" height="463" alt="image" src="https://github.com/user-attachments/assets/58c49c78-4372-4214-b7ac-7132e97ee467" />
<img width="648" height="477" alt="image" src="https://github.com/user-attachments/assets/5521cf14-877c-42ed-ab44-d2be9607260e" />
<img width="1365" height="662" alt="image" src="https://github.com/user-attachments/assets/0d10316e-cfed-4a04-969d-63a9c857aac4" />

