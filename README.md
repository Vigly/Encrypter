# Introduction
This program is written in Python3 and is designed to for file encryption and file hash generation.

## Installation
Required libraries in order to run this program are specified in requirements.txt  
```bash
pip3 install -r requirements.txt
```

## Types of Hash Generation
MD5  
SHA1  
SHA256  
SHA384  
SHA512  
SHA3-256  
SHA3-512  

## Types of File Encryption
Symmetric File Encryption using Fernet  
Asymmetric File Encryption using RSA

## How to use this program
Since this program is written in python3, you need to specify python3 when running the program

###### Usage regardless of OS:
List available argument options:
```
python3 Encrypter.py -h
```
Example usage:
```
python3 Encrypter.py --sha3_512 <file>
```