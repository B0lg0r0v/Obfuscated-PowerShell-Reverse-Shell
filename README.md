# Obfuscated PowerShell Reverse-Shell

Obfuscated powershell Reverse-Shell script. It's designed to be used in combination with the c2 framework "Villain" by @t3l3machus.

Check out t3l3machus, he is amazing: https://github.com/t3l3machus

## How-To

Just place the python script into the template folder of the C2 "villain" framework. You can then generate through villain your custom obfuscated reverse shell. <br><br>
You can also use the ps1 one-liner to directly pop a reverse shell. Modify the "IP" & "PORT" values in the script, and you're good to go !

----
Currently undetected AVs (04.10.2023):
  - Sophos Intercept X
  - Fsecure
  - Kaspersky
  - Windows Defender
