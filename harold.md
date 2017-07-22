---
layout: default
title: Remote access to the Keil MDK IDE license server
---

# One-time installation tasks

## Install `plink`

1. Ensure that the `putty` tools are installed on your system. If they are not, you can download 
[a Windows installer](https://the.earth.li/~sgtatham/putty/latest/x86/putty-0.67-installer.msi) and run it
in the usual way to install the tools. Accept all the default installation options.
2. Check that `plink` can be run from a command prompt: `Windows Logo Key + R`,
   type `cmd`, then `Enter`. Now type `plink` in the command prompt window. You
   should see some usage instructions for `plink`. If instead you see an error
   message indicating that the command cannot be found, you need to edit your
   `Path` variable to include the directory `C:\Program Files\PuTTY\`  (See
   [these
   instructions](http://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/)
   if you don't know how to edit your `Path` variable). Check again to make sure that `plink` is now executable
   from the command prompt.

## Install `harold`

1. Right-click on  [harold]({{site.raurl}}/harold.cmd) and choose `Save link as` to download the program to some convenient location in your file space.
2. Use  the file explorer to browse to the location that you saved `harold` and double-click on it to run it.
3. The first time that you run `harold`, it will warn you that a key is not recognised and prompt you to store it in the
cache. Choose `'y'` in response to the prompt. The program may then terminate. If it doesn't, just close it anyway - no need to login just yet.

## Edit `C:\Windows\System32\drivers\etc\hosts`

1. Modify the file `C:\Windows\System32\drivers\etc\hosts` to include the line below at the end:

    ```
    127.0.0.1        rtlab1
    ```
You will need administrative privileges on your system to do this.

2. Open a command window and type `ping rtlab1`. Check that you get a reply from `127.0.0.1`, e.g.:

    ```
    Pinging rtlab1 [127.0.0.1] with 32 bytes of data
    Reply from 127.0.0.1: bytes=32 time<1ms TTL=128
    Reply from 127.0.0.1: bytes=32 time<1ms TTL=128
    Reply from 127.0.0.1: bytes=32 time<1ms TTL=128
    Reply from 127.0.0.1: bytes=32 time<1ms TTL=128

    Ping statistics for 127.0.0.1:
        Packets: Sent = 4, Received = 4, Lost = 0 (0
    Approximate round trip times in milli-seconds:
        Minimum = 0ms, Maximum = 0ms, Average = 0ms
    ```
If not, then you may need to disable and reenable your network adapter, or, perhaps, even restart your OS.

# Normal use following installation

## Connect to the license server

1. Run `harold`. Login with the usual username and password that you use when accessing the machines in PB S2.
2. The `cmd` window will remain open but will not display any further output. This is expected.  

## Start uVision

## Edit `Flex server` details

1. Choose `File->License Management->FlexLM License`.
2. Edit the `Use Flex Server` text box to `8224@localhost`. You should see the license details appear under
`Product` as `MDK-ARM Professional: 46 user(s)`. Click `Close`.

## You can now use uVision as usual

# Notes

1. These instruction have been tested only on Windows 7. If you have a
   different version, some details may be different.
2. `harold` will not maintain its connection to the server indefinitely. If
   the connection is dropped, just run `harold` and login again. 
3. Remote access to the license server is being provided initially on a trial
   basis. If it is found that its use is detrimental to normal activities in
   University labs, it will be withdrawn.


