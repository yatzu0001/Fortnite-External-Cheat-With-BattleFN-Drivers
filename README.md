# Fortnite-External-With-BattleFN-Drivers


## not too much to say, a pasted external with a little bit cleaned code ( it was repeated like 10 times in some parts ) and changed some parts with 
## ReadProcessMemory, so can use the BATTLEFN cracked drivers ( see the repo if you don't what it is )

*if interested in what i changed, just check win_utils and externalmain

*how to use*

*Just put the file DLLHVMK.dll in the same directory of the external, and then you need to put the file "driver.sys" in your C:\directory, and create \
a batch file that contain this ( modify paths ) 
sc create VOICEMOD_Driver binpath="PATH_TO_VM_DRV\vmdrv.sys" type=kernel \
sc start VOICEMOD_Driver \
sc delete VOICEMOD_Driver \
sc create AJIFHJ24981 binpath="PATH_TO_DRV\AJIFHJ24981.sys" type=kernel \
sc start AJIFHJ24981 \
sc delete AJIFHJ24981 \
pause 


# then just build and run it ( when in game )
