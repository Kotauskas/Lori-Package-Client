# Lori Package Client
***NOTE: This is a work-in-progress. The Lori Client-Side Installation Kit may or may not match the descriptions and instructions described here. For now, this is just a README about a future project.***  
The client side of the Lori Package System. It includes:
  - CLI for the Lori Package Installer (***NOTE:*** there are only `.EXE` binaries for Windows, licensed as closed-source freeware. I need some help with builds for other platforms - so mail `v.toncharov@gmail.com` if you want to help with PyInstaller building for Mac OS X and Linux)
  - Lori Package Installer Wizard (see note for the CLI)
  - Lori Package Center (see note for the Wizard and the CLI)

## Installer CLI/Wizard Installation
***NOTE:*** Currently there are only Windows binaries of the Installer CLI/Wizard. See note for the Installer CLI in the first section
### Using the Installation Wizard
 1. Even some Wizards need help of other Wizards to be installed. Download ZIP (or clone) of the repo and extract it.
 2. Find the Wizard (`LoriInstSetup.exe`) in the `bin/inst/win` directory and execute it.
 3. It will require Admin rights to install for all users so hit "Yes" in the Admin rights popup window (and, if required, enter the Admin password).
 4. Follow the Wizard Setup Wizard instructions.
 5. When it has succsessfully installed, profit! After installation you can open any `.lori` packages and install/upgrade/repair/modify installation of/uninstall (using `.unlori` files) software! CLI is also really useful.
