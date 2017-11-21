obfuscators for anything needing to touch disk (download n exec, file share's etc).
offers a degree of evasion from signature based detection.

```
 gen-obfuscated.pl 
 creates an obfuscated vbs/vba downloader 

 Converts a character to it's ascii code value. Works as a 
 simple vb-s/a obfuscator specificly for shell command 
 execution. The current examples focus on powershell based 
 attacks but is not limited to them.

```

```

PS Obfuscator
originally started out as gen-obfuscated which was written in perl. I wanted to 
rewrite that perl script from scratch but instead kinda did it in powershell.
This was due to having the implants being able to generate obfuscated payloads
on there own. 
Not all of the functions from gen-obfuscated have been moved over and some 
of this stuff is original and was never on the perl script to begin with.
The code here has been removed from the implants for stand alone use.
And are tailored for the idea of "user initiated" lateral movement inside 
a network. Which should help remove the need of exploits.

```
