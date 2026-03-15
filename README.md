# System.dat
This is my own custom-made System.dat DAT file in the style of No-Intro, based on [RetroArch's System.dat](https://github.com/libretro/libretro-database/blob/master/dat/System.dat). 

I have tried my best to match the [Libretro BIOS documentation](https://docs.libretro.com/library/bios/), as well as using some checksums and file info from [RetroPie Docs](https://retropie.org.uk/docs/).

In theory, this System.dat can be used with [RomVault](https://www.romvault.com/) to quickly compile the required BIOS files for [RetroArch](https://retroarch.com/) and related projects such as [EmuDeck](https://emudeck.github.io/) and [RetroDECK](https://retrodeck.net/). 

Some files are hard to track down, so I am still missing data for the following files:

| Machine   | BIOS File        | File Size | CRC32    | SHA1                                     | MD5                              |
| :-------- | :--------------- | :------------------- | :--------------------------------------- | :------------------------------- |
| NEC PC-98 | `bios9821.rom`     | ?         | ?        | ?                                        | ?                                |
| Palm OS   | `palmos40-en-m500` | ?         | ?        | ?                                        | `f50e4d5e4d98dc831f2c34a9107651eb` |
|           | `palmos52-en-t3`   | ?         | ?        | ?                                        | `de46ec84d9aabf655eabdf9b00a3845d` |

In addition, many BIOS files are still missing a proper description (i.e. the proper identity of the file, not just the filename).
If you have any of this information, please open an issue or pull request so I can confirm it and add it to the DAT file.
Please note that RetroDECK's BIOS checker is a poor source of information, as it has many erroneous checksums, filenames, and often omits required directories.
