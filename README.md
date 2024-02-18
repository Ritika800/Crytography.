# Crytography.
File encryption and decryption which will keep your file secure with the help of key.
The code starts by opening the file "filekey.key" in read mode and reading its contents into the variable "key". 
The key is used for encryption. Then, a Fernet object is created using the generated "key".
The code then opens the original file "ritika.txt" in read mode and reads its contents into the variable "original".
The file is then encrypted using the Fernet object by calling the encrypt() method, passing the "original" data as the argument.
The encrypted data is stored in the variable "encrypted".
Finally, the code opens the file "ritika.txt" in write mode and writes the encrypted data to it.


