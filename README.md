# Tiny Pogo AVR

Tiny Pogo AVR is a project to make a cheap and easy AVR programmer, that can be connected to a PC using a mini USB, and can be soldered by anyone at home with a knowledge of soldering.

The electronic design is influenced by the Tiny AVR Programmer built by [Ahmed Ibrahim](https://www.pcbway.com/project/member/?bmbno=9AA55DC0-7B9F-43), which was in turn influenced heavily by the AVR programmer built by [FabOptimus](http://fab.cba.mit.edu/classes/863.16/doc/tutorials/FabISP/FabISP_Demystified.html). Although I have added my own flair, and additional hardware options. The pogo pin configuration is taken from the ideas shown by [loneoceans](https://www.loneoceans.com/labs/pogoprog/) and I would like to add a 1.27mm programmer based on their designs in the future.

The design itself is built around an ATTiny44 chip, which takes the programming signals from the USB connector (after some voltage converting). It then produces the required signals to program an AVR based device. There are switches to decide the voltage supplied to the target, and whether the target even gets powered.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
