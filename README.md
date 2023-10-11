# CS_Conf
Config file for Counter-Strike 2

## HOW TO Set it up

1. First, head over to Steam and right click on CS2, then under 'Manage' click on 'Browse Local Files'.

2. A window will pop up. Here, navigate through folders in the following manner - Game > CSGO > CFG.

3. Paste The AutoExec.cfg file into the folder

4. Then head over to Steam, right click on CS2 to open 'Properties'. Within the 'General' tab itself scroll down to 'Launch Options' and if '+exec autoexec.cfg' is not present in the start of the long list of code then simply add it.

## Launch Settings
`-cl_showfps -novid -nojoy -high -console +fps_max 0 +violence_hblood 0 -tickrate 128 -refresh 160 +exec Autoexec.cfg -forcenovsync`

1. `-tickrate 128` : Pour les servs privés
2. `-novid` : Cut la vidéo au lancement
3. `-violence_hblood 0` : Supr les particules de sang + decals
4. `-forcenovsync` : désac la vSync
