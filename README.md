# Zenec Recovery

Instructions - [PDF](https://github.com/peteichuk/zenec-recorery/blob/master/Recovery%204110%20English%20new%20fileserver.pdf)

Sources from link PDF in folder `sources`

Master code - `390082`

Default code - `0000`

files for SD in folder `for_sd`

files for USB in folder `for_usb`

replied to [video](https://www.youtube.com/watch?v=A6eootQBsCA) on YouTube

## If shows a checksum error

But after that, the most interesting thing began for me. In order to copy updates to the system, I came up with a workaround. In the SW_Update/Application/Update folder there is an Explorer.exe file that I copied to the SW_Update/Bin folder and renamed Explorer.exe to Mpeg_Update.exe after that I booted from USB as when updating, then I selected only 5. MPEG and then the WindowsCE interface opened and then, in manual mode, the SW_Update/Application folder was copied to Zenec in the Flash section of the file system, because it had an empty Application folder (as I understood that it was there that the files with updates were copied). This way I got around the error and Zenec started working.
