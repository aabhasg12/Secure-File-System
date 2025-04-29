# Secure-File-System

## Introduction
The Secure File Management System is a web application designed to provide secure file encryption, decryption, and key management functionalities. Built using Flask, a web framework written in Python, this system allows users to encrypt files with a passphrase or a public key, decrypt files with the appropriate key, and generate key pairs for secure file transfer.

## Access the application
Open a web browser and navigate to http://127.0.0.1:5000/ to access the Secure File Management System.

How to Use
Encrypting a File with a Passphrase

Choose the file you wish to encrypt.
Enter a secure passphrase.
Click on "Encrypt File".
Decrypting a File with a Passphrase

Choose the file you wish to decrypt.
Enter the passphrase used during encryption.
Click on "Decrypt File".
Generating Key Pairs

Click on "Generate Key Pair".
Download the zip file containing the generated public and private keys.
Encrypting a File with a Public Key

Choose the file you wish to encrypt.
Upload the public key.
Click on "Encrypt File".
Decrypting a File with a Private Key

Choose the encrypted file.
Upload the private key.

## Security Practices

Always keep your private keys secure and do not share them.
Use strong, unique passphrases for encryption.
Verify the integrity of the files before and after encryption/decryption.

## Requirements
The application requires Python 3.6 or later and Flask. Other dependencies are listed in the requirements.txt file.

Click on "Decrypt File".
