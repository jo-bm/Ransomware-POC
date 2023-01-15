# Ransomeware (Proof Of Concept)

This software is a proof of concept designed to demonstrate the danger of ransomware. It is not intended to be used maliciously, or to be distributed or copied.
Ransomware is malicious software designed to encrypt files on a user's computer. The user is then asked to pay a ransom, usually in the form of cryptocurrency, in order to decrypt the files.
This software is designed for educational purposes only, and is not to be used for any malicious purpose. It is not intended to be used to infect or damage computers.

inspired by WannaCry ransom but is vastly less efficient.

1. The user opens the malicious file, pc with a lot of diffrent files

![alt text](https://i.imgur.com/OhhcHtT.png)

2. Within a few seconds to a minute, the program will encrypt the data on the computer and the external disks.
The wallpaper will change, the instruction image will automatically open, and a new file will appear on the desktop for the decryption.

![alt text](https://i.imgur.com/S1P25KL.png)
![alt text](https://i.imgur.com/RbbNQEj.png)

3. The user opens the new file and enters a decryption key.

![alt text](https://i.imgur.com/rVPln4G.png)

A few seconds later, if the key is valid, all of the files are decrypted.

but.. the wallpaper stays foreverrr....

and the best part..
The file was analyzed by virustotal.com with more than 70 of best antivirus, but none of them identified it as a virus,
most likely due to the fact that it's entirely written in Python, which is not typical for ransomware (at least at the time I scanned it back in April 2021)

![alt text](https://i.imgur.com/iN8sQDL.png)

##note
The encryption algorithm used in this software is not developed by me due to his comlexity, i used an open-source algorithm that i found online.

