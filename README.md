# Parallelized-RSA-Algorithm
A parallel implementation of modified 3-key RSA alogirthm in C language using OpenMP.
asciiart.txt is used to display an asciiart animation wheen the code is run.
 3 prime numbers p,q and r are used for our modified 3-key RSA algorithm and generate the public key and private key pair. 
 The message which needs to be encrypted is taken from the user either as direct input or via a text file. Then using the public key generated above, 
 the message is encrypted and stored in a text file. Then when the user wants to decrypt the message, they can navigate to the Decryption menu to 
 decrypt the file using their private key and obtain the message.
The code is implemented in C language using the OpenMP library
