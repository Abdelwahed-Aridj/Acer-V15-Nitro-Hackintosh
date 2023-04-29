# [SUCCESS] Acer-V15-Nitro-Hackintosh
** MacOS Big Sur ** on acer vn7-571g. opencore. Educational purpose only, open for improvements and suggestions. Use it at your own risk. 

If you like my work, give it a ⭐

[![Preview](snap.png)](https://github.com/afkniladri/Acer-Nitro5-Hackintosh-OC/)

# macOS Big Sur : version 11.7.6

The project was made with the help of [Opencore - Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/). A huge thanks to the awesome community for the documantation.

`Opencore Version : 0.8.4` 

## Contents

- [Configuration](#configuration)
- [Current Status](#current-status)
- [DSDT-SSDT](#dsdt-ssdt)
- [Credits](#credits)

## Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Acer Aspire V15 Nitro VN7-571G   |
| Processor           | Intel Core i5-4210u ~2.4ghz turbo 2.70 GHz  |
| Memory              | Hynix 12GB 1600 MHz DDR3            |
| Hard Disk           | SATA3 2.5 SSD          |
| Integrated Graphics | Intel HD Graphics 4600                     |
| Monitor             | FHD 1920x1080 (15.6 inch)     |
| Sound Card          | Realtek ALC283                             |
| Wireless Card       | Atheros 946X|
| Touchpad            | Synaptics I2C HID based                              |

## Current Status
- **Discrete graphic card** never going to work!
- **Wireless Card is Atheros 946X and its fully fucntional without need for injection **
- **Sleep Doesnt work yet**
- **Touchpad Gestures** works after adding patched DSDT/SSDT (XOSI) in OC
- **Sound** Works perfectly on Speaker and ComboJack for headset.
- **HDMI** Won't work, since the port is hardwired to the dGpu (disabled).
- **Everything else works** 

## DSDT-SSDT
- Custom DSDT/SSDT files for this particular model has been created using dumping the DSDT from windows 10 and then modifying it for mac os to work.

> ***Note*** : Please don't use this if you're using a different model, it will definitely cause problem
