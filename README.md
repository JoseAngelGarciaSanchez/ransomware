# Ransomware : Encrypting files

<br>

## About the Project
Creating a ransomware from scratch to understand better how a ransomware works. It is based on cryptography librairy with Fernet encryptation. Fernet is a symmetric encryption method which makes sure that the message encrypted cannot be manipulated/read without the key. It uses URL safe encoding for the keys. Fernet also uses 128-bits AES.

In this repository, you will find the following elements:
* Three text files for testing the ransomware : file.txt, file2.txt, pleasedonthurtme.txt
* The ransomware :bug: : Voldermort.py
* The decrypt script : decrypt.py

<br>


<!-- Console Application -->
## Console Application:
The first part is the console version of the final application, our "beta-application" if you want. This version of the application takes into account two arguments : the data as a csv file, and the keyword that serves as your research (for example, Louvre, Opéra, or even Picasso) to let the recommendation system find the most similar events to suggest to the user.

### Installation and launching the ransomware:

1. Clone the repository
```sh
https://github.com/Pse1234/ransomware.git
```
2. Change your current working directory
```sh
cd ransomware
```
3. Install required dependencies
```sh
source install.sh
```
3. Launch the application
```sh
python voldemort.py
```

## Note
* Look the github repository of [Patrick H0lop - Malware Showcase](https://github.com/PatrikH0lop/malware_showcase)

## Contact
* [José Ángel García Sánchez 👨🏻‍💻](https://github.com/Pse1234) 
