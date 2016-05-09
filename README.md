# PyAES
Simple implementation of AES using Python. Written for a university cryptology course

Currently, the main test function only supports encryption of 128 bit hexadecimal plaintext/key input.

I am developing methods for padding (in the case of inputs being too short) and splitting inputs greater than 128 bits into blocks.
I am also working on methods for encrypting ASCII plaintext. Once this is done, I'll add decryption.

##Test Example:

######128 bit hex plaintext:

32 43 f6 a8 88 5a 30 8d 31 31 98 a2 e0 37 07 34

######128 bit hex key:

2b 7e 15 16 28 ae d2 a6 ab f7 15 88 09 cf 4f 3c

######128 bit hex ciphertext:

39 25 84 1d 02 dc 09 fb dc 11 85 97 19 6a 0b 32

##Running the test file

######OSX/Linux Terminal
```
python3 AES.py
```

######Windows Command Prompt
```
C:\Python3x\python.exe C:\FileLocation\AES.py
```
