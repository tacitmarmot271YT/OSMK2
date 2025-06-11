# EXEC Formats

This folder contains header files for major executable formats across various hardware systems.

- `DOL.h`: GameCube/Wii native format
- `PRX.h`, `SELF.h`, `PKG.h`: PlayStation variants (PSP → PS5)
- `XEX.h`, `XVC.h`: Xbox 360, One, Series
- `ELF.h`: General format, shared by multiple systems
- `RPX.h`: Wii U format
- `NS1.h`: Placeholder for experimental loader format

All formats are parsed using custom-built loaders with no dependency on official SDK tooling.
