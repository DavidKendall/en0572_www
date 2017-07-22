---
layout: default
title: Installing the Keil MDK IDE
---
The Keil MDK tools are installed on the machines in PB S2. In addition, it is
also possible to use the tools in other Computing labs: PB F1, PB S3, PB S4 and
a small number of machines in Pandon basement. This may be helpful in
conjunction with the loans system for the ARM boards. The tools have not been
installed by default on the machines outside PB S2. If you choose to use one of
the machines, you may need to install the tools. This only needs to be done
once. The instructions below describe the procedure.

# Download
Download the [installer](http://www.hesabu.net/downloads/mdk521a.exe).

# Run the installer
Run the installer. You can just accept all the defaults. Allow the installer to install the `ULINK` drivers.

# Install the software packs
When the installer has completed, the pack installer will run automatically. Select
`All Devices->NXP->LPC4000 Series->LPC408x`. Select the last of the 4 devices
listed here. The software pack will be downloaded. Go to `Packs->Device
Specific` and install the pack that you have just downloaded.

# Install the Windows serial drivers
Download the [installer for the serial
drivers](http://www.hesabu.net/downloads/mbedWinSerial_16466.exe). **Plug in an
ARM board** before running the installer. This is important. Run the installer,
accepting the defaults.

# Install the software license
Start the Keil uVision 5 tool. Select `File->License Management`. Select the `FlexLM License` tab and click the
`Edit` button. Enter the string `8224@192.168.100.21` into the text box for `Flex License Server`. Click `Ok`. Make sure
that the `Use Flex Server` checkbox is ticked. Click
`Close`. 

# That's all
You should now be able to use the Keil MDK tools as usual.

