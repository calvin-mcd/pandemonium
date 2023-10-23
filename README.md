# Pandemonium
 
Pandemonium is an alpha staggered ISO pcb with KLE by HaiZeus. It uses an [XIAO nRF52840](https://www.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html) for bluetooth support. The desgin for that is based on [NoahK#1290's](https://kiserdesigns.bigcartel.com/) [Asymptote](https://github.com/KiserDesigns/Asymptote). For a build guide you can mostly refer to the steps from the [Asymptote Guide](https://github.com/KiserDesigns/Asymptote#asymptote-build-guide). Just take extra care with the right orientation of the diodes, as these change quite a bit on this pcb design.

## Layout

![](https://github.com/calvin-mcd/pandemonium/blob/main/Images/KLE.png)
![](https://github.com/calvin-mcd/pandemonium/blob/main/Images/top.png)
![](https://github.com/calvin-mcd/pandemonium/blob/main/Images/bottom.png)

[Link](http://www.keyboard-layout-editor.com/#/gists/b0a595a186fab9d96212efed305105f0)

## Case

HaiZeus designed the case to be either used for resin or FDM printing. Use the respective top file for that. 

A universal plate file is included as well as two thick plate options for different bottomrow layouts.  

Hardware needed to assemble the cases is:
- 8x M3x4mm heat set inserts or 8x M3 square nuts (depending on case top printing method) (see reference picture below for the kind of square nuts)
- 8x M3x6mm screws

The bottom has cutouts for SKUF rubber feet available at a couple different online retailers.
  
![](https://github.com/calvin-mcd/pandemonium/blob/main/Images/IMG_1803.jpg)
![](https://github.com/calvin-mcd/pandemonium/blob/main/Images/IMG_1804.jpg)
![](https://github.com/calvin-mcd/pandemonium/blob/main/Images/97259A101_Low-Strength20Steel20Thin20Square20NutM.png)

## Firmware

Firmware has been created in zmk by Falconloft. A basic layout to flash the pcb has been provided. The source code is there to edit and create personal layouts for the board.

## Todo

- [X] order & test pcb
- [X] print & test case
- [X] create ZMK firmware

## Disclaimer

This PCB has been fully tested and confirmed to work. The members of the PCB development team are however not liable if you end up with a non-functional pcb. Order at your own risk. Support will not be provided but pull requests will be reviewed and possibly accepted.

## License

This project is released under the GPL v3 License. Please refer to the LICENCE file.

## Credits

Thanks to HaiZeus for the inspiration, KLE and case design.

Many thanks to Falconloft for his work and patience with the firmware.

Big, big thanks to NoahK#1290 for the design inspiration and support. Do check out Noah's work. It is amazing!

And, as always big thanks to the 40s community!

Any questions, contact calvin0563 on Discord. 
