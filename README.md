# SkyWiper

## Note

-   The techniques you gone see in this malware are taken from a public malware samples


# Malware Stages

 Stage 1 - Destroy files content
 - the wiper start by looking for folders that contained important files, like documents, downloads, pictures, music, and videos: more or less everything that a user might value. After the code found these folders, the wiping code overwrote their contents.
 
 Stage 2 - Destroy MBR
 - The master boot record. The Master Boot Record 1 is vital for a computer’s hard drive and it contains information about how to store files and what the computer should do when it starts up. Without the guidance of the master boot, it’s almost impossible for the machine to function properly
 
 Stage 3 - Remove self
 - At the end of the script, the file is deleted & over-written

 Stage 4 - Shut it down!
 - Finaly the infected system should reboot immediately
