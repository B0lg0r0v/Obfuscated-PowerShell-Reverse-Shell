# Obfuscated PowerShell Reverse-Shell

Obfuscated powershell Reverse-Shell script. It's designed to be used in combination with the c2 framework "Villain" by @t3l3machus.

Check out t3l3machus, he is amazing: https://github.com/t3l3machus

## How-To

Just place the python script into the template folder of the C2 "villain" framework. You can then generate through villain your custom obfuscated reverse shell. <br><br>
You can also use the ps1 one-liner to directly pop a reverse shell. Modify the "IP" & "PORT" values in the script, and you're good to go !

## Obfuscation Creation

I recommend creating your own obfuscated reverse shell. There are plenty of resources available online, but here is a quick way to achieve:

- Check out the entropy of your code. The lower it is, the more chances you have for evading AV. -> https://planetcalc.com/2476/
- Rename your objects (variables, classes, etc.)
- A great trick is to use cmdlet quote infos. Ex. `iex pwd` could also be `i''ex p''wd`
- Change your loops. Ex. instead of a "for loop” do a "Do-While Loop".



## Disclaimer

You are responsible for your actions. Don't do bad things.

----
Currently undetected AVs (04.10.2023):
  - Sophos Intercept X
  - Fsecure
  - Kaspersky
  - Windows Defender
