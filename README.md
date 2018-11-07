**Key Generation**

Run `java -jar LimaKeyGeneration.jar` then send the following to the person you want to receive a message from:
* LimaEncryption.jar
* publicKey.txt

**Encryption**

Run `java -jar LimaEncryption.jar <message>` where message is space separated bit values then send the following back:
* cipher.txt

**Decryption**

Run `java -jar LimaDecryption.jar` the message will be printed on the console.
