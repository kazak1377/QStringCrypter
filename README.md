QStringCrypter
==============

This is simple header, wich allows you to use XOR ecryption to any QString.
And you don't need to create an object of Crypter class. Just use it;)
####Usage:

1. Add this header to your project
2. include it.
3. Edit the crypting string. 

####Example:
```
QString encryptedString = Crypter::cryptString("Here string you want to encrypt");
QString decryptedString = Crypter::decryptString(encryptedString);
//decryptedString is "Here string you want to encrypt".
```
