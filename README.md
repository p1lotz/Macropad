# Macropad; 9 keys, 1 encoder and an OLED
(first time making a readme for a macropad so bear with me <3)
<img src="images/macropad_render.png" width="600">

### Hello yall! So this is the forth project which I posted on Stardance! (let's just ignore the other 3)
The first 3 were software projects, but this one (as you may or may not saw) its a hardware project! **Hardware > Software**
A macropad, who wouldn't want that? Plus you make it yourself AND get funded from our dear friends from Stardance! Now, who wouldn't what **THAT**.

As you saw (actually you didnt but let's ignore that), the Hackpad consists of 2 parts, the bottom part, the case itself and the top panel which makes it look prettier.

It has 9 switches, 1 encoder and an OLED, the case is very lovely in my opinion can't wait to 3D print it and the firmware is as basic as it gets basically, I will make it better as I finish the hardware and start using it.

Right now only 3 keys and the encoder are in use, the encoder for the volume and the 3 keys for media, the only things I NEED to have to be able to LIVE.


## Here's the PCB

<img src="images/PCB_2D.png" width="600">
<img src="images/PCB_3D.png" width="600">

## And the Schematic

<img src="images/Schematic.png" width="600">

##

What else can I say, it has a 3x3 matrix with diodes, uses almost all the parts from the Hackpad kit (doesn't use the LEDs, screws, heat inserts and the extra switches and keycaps) and I have the XIAO on the BACK of the board to minimise the area of the board, to make it as compact as I can.
The top panel uses M2 screws with I will supply them myself and the case uses M2 heat inserts, same idea.

## BOM

|          Part          | Qty |Price|Link|
|------------------------|-----|----|-----|
| Seeed XIAO RP2040      |  1  |$3.90/18.53 RON|https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html
| MX-Style Switches      |  9  |~$2.70/~12.82 RON|https://www.divinikey.com/products gateron-ks-3-milky-yellow-pro-linear-switches
| White DSA Keycaps      |  9  |  White DSA Keycaps,9,~$5.35/~25.44 RON|https://www.adafruit.com/product/4998
| EC11E Encoder          |  1  |EC11E Encoder,1,$5.74/27.26 RON|https://www.digikey.com/en/products/detail/alps-alpine/EC11E1820402/21721574
| 0.91 inch OLED Display |  1  |0.91 inch OLED Display,1,$3.90/18.52 RON|https://www.displaymodule.com/products/0-91-inch-oled-graphic-display-128x32-with-i2c
| 1N4148 Diodes          |  9  |1N4148 Diodes,9,$0.90/ 4.27 RON|https://www.digikey.com/en/products/detail/onsemi/1N4148/458603
| M2 Screws              |  4  | $ 6.33/30.26 RON| https://www.aliexpress.com/item/1005009393815442.html?spm=a2g0o.productlist.main.12.58de26ab2TBGmF&aem_p4p_detail=2026103012063913891125749010510002557345&algo_pvid=83519af8-cef8-47bf-a938-ebaf77f97a94&algo_exp_id=83519af8-cef8-47bf-a938-ebaf77f97a94-11&pdp_ext_f={%22order%22%3A%2217329%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22}&pdp_npi=6%40dis!RON!25.45!25.45!!!34.23!34.23!%400b884c0217933871997487337e0f37!12000048962946395!sea!RO!0!X!1!0!n_tag%3A-29919%3Bd%3Ab9047a9f%3Bm03_new_user%3A-29895&curPageLogUid=a6W47JtdcEx5&utparam-url=scene%3Asearch|query_from%3A|x_object_id%3A1005009393815442|_p_origin_prod%3A&search_p4p_id=2026103012063913891125749010510002557345_3
| M2 Heat Inserts        |  4  | $6.13/29.30 RON   |https://www.aliexpress.com/item/1005003582355741.html?spm=a2g0o.productlist.main.5.79a83820jo5k76&algo_pvid=b5ca7594-b5cb-446f-aaba-d851b61526b0&algo_exp_id=b5ca7594-b5cb-446f-aaba-d851b61526b0-4&pdp_ext_f={%22order%22%3A%2251090%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22}&pdp_npi=6%40dis!RON!26.94!26.93!!!36.24!36.23!%400b88a96117933872832992703e0ffa!12000026370649842!sea!RO!0!X!1!0!n_tag%3A-29919%3Bd%3Ab9047a9f%3Bm03_new_user%3A-29895&curPageLogUid=ZhzOiMhmMZi9&utparam-url=scene%3Asearch|query_from%3A|x_object_id%3A1005003582355741|_p_origin_prod%3A 
| Main PCB | 1 | $4.00/19.12 RON |
| 3D Printed Case        |  1  |
| 3D Printed Panel       |  1  |
