# epitech-clion-2018

As no update is made for the new coding style, I take over QTimort's repo;


Epitech norm compliant configuration for CLion IDE.<br />
This CLion configuration is made to be as compliant as possible with the 
Epitech norm.<br />

If you have any suggestion please let me know.<br />

# Installation

**Code Style**<br />
*file -> settings -> code style -> manage... -> import*
- Import "Epitech C 2017.xml"

**Epitech Header**<br />
*file -> settings -> code style -> File and Code Templates -> Includes*
- Add an include named "C Epitech Header" with extension 'h' and paste 
the content of Header_Template.txt in the large field.<br />
- Replace the promo variable set by default to "2022" to your year of 
promo.<br />

*file -> settings -> code style -> File and Code Templates -> Files*<br 
/>
-> C Source File replace "C File Header.h" by "C Epitech Header.h"<br />
-> C Header File replace "C File Header.h" by "C Epitech Header.h"<br />

# Known problems:
- When creating a new project, the default main generated doesn't have 
the epitech header, you have to copy paste it manually.

# Warning
- The number of line in a function, line breaks != number of lines, more 
exactly 19 line breaks = 20 lines.
- When including the first include in a file, check that CLion didnt put 
the include before the Epitech Header.
