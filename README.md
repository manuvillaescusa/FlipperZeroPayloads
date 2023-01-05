# McAfee AV Evasion + Reverse Shell with BadUsb
Payloads for BadUsb or RubberDucky

On my first repository I will be adding some payloads I create for Bad Usb

For Mcafee Payload -> We will only need that our victim use a ENG keyboard so PC can read all chars fine.

Mcafee.txt will disable some McAffe-AV features such as real time analysis and Firewall after that it will call to download a Ps.ps1 (go check nishang repository to see some reverse shell ps scripts) file and run it

On our machine we will need to set up a http server so we can download ps.ps1 file and we will have to set a listener to get our reverse shell.

On McAffe.txt we have to fill it with our ip and directory where ps.ps1 file is.

# TV-IR
In this folder I will be adding all the controls infrared
