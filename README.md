# Deltra - Delta 3D Printer

![Deltra Frame Open](./img/Deltra_Frame_open.png)

## Overview

Deltra is a high-performance delta 3D printer purpose-built for large-format printing. With an impressive 500x737mm build volume and a maximum flowrate of 100mm³/s, the Deltra delivers exceptional speed and quality for demanding print jobs. Featuring dual 48V axis drives, this printer is engineered to handle challenging prints with precision and reliability.

## Documentation

This repository contains all the files necessary to build and maintain a Deltra printer, including:

- **[CAD/](./CAD/)** - Complete 3D models in Fusion 360 (.f3z) and 3MF formats
- **[BOM/](./BOM/)** - Bill of Materials for printer construction
- **[Electronics/](./Electronics/)** - Electrical schematics and PCB designs
- **[Klipper/](./Klipper/)** - Klipper firmware configuration files and macros

### Prerequisites

- Please note that this Printer runs of off 3-Phase Power. So **extreme caution** needs to be taken when assembling the electronics as a wrong or faulty installation could be life threatening

## Klipper Configuration

The Klipper folder contains pre-configured settings for the Deltra printer:

- `printer.cfg` - Main printer configuration
- `includes.cfg` - Included configuration files
- `params.cfg` - Parameter definitions
- `print.cfg` - Print-specific settings
- `autotune_tmc.cfg` - TMC motor tuning
- Additional macro and speed configuration files

## Important Notes

⚠️ **Please Note:** This Printer was a diploma-thesis and therefor a one off build. All files for building this printer are available, but this project won't be actively maintained by us

## Contributing

Contributions and improvements are welcome! Please feel free to fork this project to help improve the Deltra printer project.
