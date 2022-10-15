# OFFICE365
ACTIVATE AND SETUP YOUR OFFICE 365 IN WINDOWS11

First of all install office setup 365 Link is given  

https://bit.ly/3rZ1YUF

After installing, office setup, Double click on it, it will be installing automaticly, after sometime it will install.

Now, "Run as Administrator" your command portal (cmd)

run command

   cd /d %ProgramFiles%/Microsoft Office/Office16

for /f %x in ('dir /b ..\root\Licenses16\ProPlus2021VL*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"

cscript ospp.vbs /setprt:1688

cscript ospp.vbs /unpkey:6F7TH >nul

cscript ospp.vbs /inpkey:FXYTK-NJJ8C-GB6DW-3DYQT-6F7TH

cscript ospp.vbs /sethst:kms.loli.beer

cscript ospp.vbs /act
