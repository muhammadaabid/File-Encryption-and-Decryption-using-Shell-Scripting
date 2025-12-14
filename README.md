# File Encryption and Decryption using Shell Scripting

## **INTRODUCTION**
For securing the data from unauthorized persons or victims, file encryption 
and decryption plays a very crucial role to protect the files. The exponential growth of 
digital data is making the data more unsecure, and the data could be the target of any 
attacker, and it’s our responsibility to make the data as secure. In this context, the 
development of File Encryption and Decryption tools emerges the practical solution. 
With the scripting capabilities of shell, this project aims to create a user-friendly 
environment to encrypt and decrypt the files efficiently, enhancing data confidentiality 
and integrity.

## **METHODOLOGY**
This File Encryption and Decryption tool uses a software library named 
OpenSSL for providing strong security settings and algorithms, OpenSSL is also used to 
encrypt and decrypt the file. The various algorithms are used in this project including 
AES-256-CBC for encryption, HMAC/SHA-256 for verification purposes and PBKDF2 
(Password-Based Key Derivation Function 2) using SHA-256 (with 200,000 iterations) 
for converting password to key. With this tool, we can encrypt any file of any extension. 
After encryption a .enc file will be generated and stored in the folder Encrypted and 
decrypted file having extension .dec will be stored in the folder Decrypted.

## **FUNCTIONALITIES**
There are number of different functionalities in this project and let take a 
deep dive into each functionality and understand what functions can be performed by 
this powerful File Encryption and Decryption Tool. Here are the functionalities. 
1. Generating a Secure Key: This function generates a different secure key on 
each attempt and can be used with -g flag. 
2. Encryption: This function encrypts an input file with a secure key or password 
and stores the encrypted file on the output file path with .enc extension. The 
f
lag to perform this function is -e. 
3. Decryption: This function decrypts an input encrypted file using secure key or 
password and stores decrypted file on the output file path with .dec extension. 
The flag to perform this function is -d. 
4. Large File Test: This function tests the large file (1 – 3 GBs) encryption and 
decryption, this may take some time to be executed. The flag to perform this 
function is -l. 
5. Core Unit Test: This function tests a unit and verifies that the system is running 
properly, this usually runs in 3 to 20 seconds. The flag to perform this function 
is -t. 
6. Unit Test for PBKDF2: This function tests a unit for PBKDF2 (Password-Based 
Key Derivation Function 2), this is for developer testing. The flag to perform 
this function is -b.
