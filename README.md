# CLEO Redux

This is the official port of CLEO Library for re3 and reVC.

At the moment it's very barebone and has a limited number of features (see below).

## Installation

CLEO Redux only supports "Windows D3D9 MSS 32bit" version of re3. It might work with reVC but hasn't been tested yet.

- Download and install re3 from https://github.com/GTAmodding/re3#installation

- Copy cleo.asi to re3 directory.

Make sure `cleo.asi`, `re3.exe` and `re3.pdb` are located in the same folder.

- Install CLEO scripts. You can try a classic `showsavescreen.cs` from CLEO 3. Press `F4` to display the save screen while on foot.

**NOTE: CLEO scripts written for GTA III/Vice City should work, but CLEO Redux does not support most of the common CLEO commands yet (see the list of supported commands below).**

If the script only uses vanilla commands, or commands listed below it should work.

## Features

- Loading and unloading CS files from CLEO directory
- Reload scripts when the game starts
- basic scm log. To enable trace for executed commands open up re3.ini or reVC.ini and add these lines:

```
[CLEO]
LogOpcodes = 1
```

## Writing CLEO scripts

Use [Sanny Builder 3.8.0](https://sannybuilder.com) in GTA III or GTA VC edit modes respectively. Check out [this page](https://cleo.li/scripts.html) for more information.

## Custom Commands

- 0A93
  [TERMINATE_THIS_CUSTOM_SCRIPT](https://library.sannybuilder.com/#/sa/CLEO/0A93)
- 0AB0 [IS_KEY_PRESSED](https://library.sannybuilder.com/#/sa/CLEO/0AB0)

## Links

- re3 project: https://github.com/GTAmodding/re3
- CLEO library: https://cleo.li/
