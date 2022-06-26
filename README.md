# FDD CDX2
## Port Based Floppy Disk Drive controller for MSX computer

Recreated Microsol Tecnologia CDX-2 FDD interface.

* Based on WD2793 or TMS2793 floppy disk controller
* Support for 3.5' and 5.25' floppy drives
* Modified to work with computers that support the BUSDIR signal
* Jumper to switch between two different ROMs
* Fits MSX cartridge
* Tested on MSX1 and MSX2

### ROMs tested with this interface:

* CDX-2 (Microsol Tecnologia)
* Angeisa (Angeisa Eletronica LTDA)
* FAST!DiskROM

### ROMs that should work with this interface:

* DDX 1.0 (Digital Design)
* DMX 1.2 (Conector Informatica LTDA.)
* LIFTROM (Liftrom Informatica)
* MANUT (AMT Mamute)
* TPX 1.02 (TPX - Perifericos)

#### Test Points

- TP1 - PIN 16 (DIRC)
- TP2 - PIN 29 (TG43)
- TP3 - PIN 31 (WD)

J3 must be closed to enable test mode. For normal use J3 must be **open.**

![CDX-2](/photos/cdx-2_03s.jpg)

### Look at YouTube:
[![YouTube link](https://img.youtube.com/vi/UTZCwYuuAXE/0.jpg)](https://www.youtube.com/watch?v=UTZCwYuuAXE)