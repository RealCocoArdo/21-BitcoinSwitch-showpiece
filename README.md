# 21 BitcoinSwitch showpiece
 A simple seven segment display that displays the number 21 after a lightning payment.

 This project has no use other than to showcase the simplicity of a BitcoinSwitch on meetups.

<img src="pictures/front.PNG" width="45%"></img>
<img src="pictures/inside.PNG" width="45%"></img>

## Requirements:
- <a href="https://github.com/lnbits/bitcoinswitch">BitcoinSwitch repo</a>
- <a href="https://lnbits.github.io/bitcoinswitch/installer/">BitcoinSwitch Installer</a> & <a href="https://legend.lnbits.com">Lnbis</a>(ideally selfhosted)
- ESP-32 controller (+USB cable)
- 2x seven segment displays
- Some wires and a box
- Soldering iron (Not nessarily required)

## Notes
I did link the ESP32 to my hotspot to make it mobile.

You connect all required pins of your seven segment display to your selected pin of your ESP-32(following Ben's tutorial it's Pin 27).

<img src="https://i.pinimg.com/originals/9d/c4/2d/9dc42ded10a66036664661cffbc99ed1.png"></img>

"com" is GND.<br>
To display the number 2 you need to connect a, b, g, e, d<br>
To display the number 1 you need to connect b, c <br>