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

Q8: If we wanted to look for files modified in the last 30 minutes in /home directory, what command would we want to use?
Hint: Explore how you can use find command to achieve this.
<img width="1730" height="316" alt="image" src="https://github.com/user-attachments/assets/20a20d74-64ff-4362-bba2-9ec665903a4c" />

Q9: What command can we use to display information about all active TCP connections on the system?
<img width="1753" height="845" alt="image" src="https://github.com/user-attachments/assets/95f14370-3d41-4985-b79d-985a0cf72119" />

Q10: Given this corrupted image file, can you find a way to recover and view its contents?
     Hint 1: A quick google search for “magic bytes” might help.
     Hint 2: Explore how hexedit can help you here.
     You may download the image using following command:
     curl https://raw.githubusercontent.com/vonderchild/digital-forensics-lab/main/Lab%2001/files/challenge.png -o challenge.png

A: flag{d1g1tal_f0r3ns1cs_101}




