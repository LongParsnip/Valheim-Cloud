# Valheim-Cloud Server Client, v1.03
A small app that syncs your server mods via cloud services.
This application is for Windows and onedrive only.

Written in Visual Basic Script using the windows scripting host.

## Version Summary:
* v1.00: Original release.
* v1.01: Converted to vbscript as windows defender was falsly flagging the .exe as a virus.
* v1.02: Added support for the steam overlay.
* v1.03: Changed the script to use a direct link to a zip file for mods, this allows the script to be a 'one click' operation for the end user.

  
## How to use:    ***NOTE*** The default setting in this file will load my server mod configuration and allow you to join my public server.
    1.) Create a zip file of all your mods from the root directory of valheim.
    2.) Upload to onedrive and generate an embedded link.
    3.) Copy the embedded 'src' link and replace the user setting variable embeddedURL with the new string.
    4.) Save the .vbs file and distribute to clients.
    5.) Launch the game via this vbs file.

    
    Note1: Each time you launch valheim you will need to launch it via this app.
    Note2: Check the 'How to use.pdf' file in the repository for more detailed instructions.
    
