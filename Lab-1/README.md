# Questions:
Q1: If we wanted to list all the .txt files in the current directory, what command would we want to use?
<img width="1383" height="77" alt="image" src="https://github.com/user-attachments/assets/614e18aa-40b9-435c-9119-7f10ea6df3dc" />

Q2: What command can we use to read the contents of the file /etc/passwd?
<img width="1393" height="830" alt="image" src="https://github.com/user-attachments/assets/40119315-7594-4c2b-bf25-59dc7bd73727" />
<img width="1526" height="720" alt="image" src="https://github.com/user-attachments/assets/a4f49af5-311b-4801-92b7-96946906751e" />

Q3:If we wanted to search for the string Error in all files in the /var/log directory, what would our command be?
<img width="1666" height="808" alt="image" src="https://github.com/user-attachments/assets/c8d2b1dc-1156-4b6e-913e-ad32aa77ed18" />

Q4: What would be the commands to calculate MD5 and SHA1 hashes of the file /etc/passwd?
<img width="1538" height="85" alt="image" src="https://github.com/user-attachments/assets/2e087021-2232-45c7-b6f7-1da9b72c8d0e" />

<img width="1240" height="90" alt="image" src="https://github.com/user-attachments/assets/8a2f3a15-a532-4ce6-ab19-8e4d48296085" />

Q5: Use the file command to determine the type of the file /usr/bin/cat and explain the output in 2-3 sentences.
<img width="1886" height="108" alt="image" src="https://github.com/user-attachments/assets/eeb61dd5-1359-4cc0-83ae-41e4a8f188f0" />

Q6: What command can we use to display all printable strings of length ≥ 8 in the file /bin/bash?
<img width="1540" height="504" alt="image" src="https://github.com/user-attachments/assets/e43dae7a-d1d2-4991-8d28-164b3585cfe3" />

Q7: Given the following output of the file command, can you determine what’s wrong with this file?
$ file image.jpg
image.jpg: ELF 64-bit LSB pie executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, BuildID[sha1]=3ab23bf566f9a955769e5096dd98093eca750431, for GNU/Linux 3.2.0, not stripped

A: This file is a trap. It is named `image.jpg` to look like a harmless picture, but the `file` command reveals it is actually an **ELF executable**, which is a computer program. This mismatch means someone disguised a program (likely a virus) as a photo to trick you into running it.
