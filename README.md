<h1>Hashing Lab</h1>

<h2>Overview</h2>
This project touches on the basics of encryption including the importance of hashing, the types of hashing and algorithms, and the types of keys that are used while working with these algorithms. We practiced using relevant commands to enable encryption as well as why it’s important in daily cyber life.
(Screenshots Below)
<br />
<h1>Asymmetric vs. Symetic Encryption</h1>
Symmetric encryption: is the process of converting text into ciphertext using one key only. This single key is used for both sides when communicating in the ciphertext. This is advantageous because the process is quicker and the keys are shorter. For the same reasons, Symmetric encryption is disadvantageous because the higher the number of people with the key, the higher chance it gets compromised. This method is used for data at rest such as USB and laptop disk drives.


EXAMPLE: Text > Public key > Ciphertext (OR) Ciphertext > Public Key > Text

Asymmetric encryption: is also public key based, the concept is known as the key pair, The sender and recipient use a pair of keys known as a private key and a public key. Private keys are kept secret by the sender. The public keys can be shared but only the public key can be shared. The keys are technically ‘related’ to each other. A public key cannot generate what the private key can ultimately do. This is advantageous because the private key is never shared and is ultimately held by the owner, this also makes it disadvantageous because it slows down the process via workload. An area in which this method is used is when digital signatures are required to enter a space.

EXAMPLE: Text > Public key > Ciphertext (AND) Ciphertext > Private Key > Text

<h1>Why Hashing?</h1>
Hashing is important because it adds a value, or unique ID to everything you create or write. If you decided to hash text one day, you could easily turn it into a hashed text which would then give it a unique ID and not change the said ID unless the original text was edited. A well-made hash not only turns a file into a fixed-length value but also represents the original string as well. Hashing is important because you can calculate values without opening the file. If the value is changed, immediately you will know if the file is different. Hashing is a step used for verifying the integrity of files. They also range in various lengths of strings depending on how secure you plan on being.

<h2>Collision</h2>
A collision occurs when a hash algorithm produces the exact hash value for another existing input value. Two pieces of data in a hash have to share the same hash value. This can be manipulated and taken advantage of by hackers as well if discovered.

<h2>Levels of hashing and algorithms</h2>
There are many types of different hashing algorithms including MD5 and SHA that we used in this lab. The difference is that they use their own unique algorithms and you are able to expand them to be more secure. When an expansion is used, the unique hash typically extends which makes it more unique and harder to gain access to. The greater the output, the more protected it ends up being.

<h2>Public Key Infrastructure</h2>
PKI uses different key algorithms to lock and unlock the encryption. A public key is used to encrypt the data, while a private key is used to decrypt the data. Essentially both users have access to a private key used to decrypt data, although the information is sent over a public key. This is done to prevent others from picking up on the communication lines and being able to decrypt the information received. PLI is very similar, but known as being more cost-effective and decentralized.

<h2>Summary</h2>
In conclusion, encryption is a tool used to communicate with others while trusting that it cannot be found. This tool is a little like hiding your answers while taking a test. The encrypted information is encrypted for a reason. It has a value and if it is found, it can cause harm. This is a necessary and easy step for most. This is nothing that can’t be done by taking an extra step and a couple of extra commands.

<h2>Enviorments and Utilities Used</h2>

- <b>SHA256</b> 
- <b>MD5 Hash</b>
- <b>Kali Linux</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
SHA256: <br/>
<img src="https://i.gyazo.com/db03547aa80d6e91accf19ca109d3c95.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
MD5 Hash:  <br/>
<img src="https://i.gyazo.com/b2c090b70ea2333ba1df1609a1babe2e.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
SHA512 Encrypted file: <br/>
<img src="https://i.gyazo.com/d40c659530b37f16933f5bae61dbbfbf.png" alt="Disk Sanitization Steps"/>
<br />
<br />
SHA256 File:  <br/>
<img src="https://i.gyazo.com/b85feb9903b313cbb69124ec86248f52.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
MD5 File:  <br/>
<img src="https://i.gyazo.com/0e77c43dbe669bc77cfe484766cf36a3.png" alt="Disk Sanitization Steps"/>
<br />
<br />
