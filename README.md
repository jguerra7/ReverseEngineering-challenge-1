# Reverse engineering - challenge 1
Reverse engineering capture the flag challenge.
You need to find the flag: {artist name - song name}.
The complete challenge file which is under: the_challenge directory.
If you want you can practice just the executable file which is under: setup_files directory.

# setup_file
* challenge.c - The challenge program itself.
* hetText.c - Helper program to convert sentences in ASCII-string format to Hex-string format.
* hexTextOutput.txt - Contains the sentences used in the challenge.c file.
* Hashes.txt - Contains MD5 hashes of passwords used in the challenge.c file.
* Reverse-Memes.jpg - Picture for the challenge.
* challenge.exe - The compiled challenge executable file.

# Compiling the challenge
1. Make sure gcc installed.
2. Open command prompt.
3. Type: <code>gcc -o challenge.exe challenge.c</code>
4. Type: <code>copy /b challenge.exe + Reverse-Memes.jpg Challenge.jpg</code>
4. Have fun!
