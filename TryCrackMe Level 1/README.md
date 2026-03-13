# TryCrackMe Level 1 Write-Up
Welcome! This is an official write-up for the CTF
[TryCrackMe Level 1](https://tryhackme.com/room/trycrackmelevel1), made by the room's creator 
[CyberFalcon101](https://tryhackme.com/p/CyberFalcon101).  

Note that although the steps to find the answers are given, the actual solutions are not provided.

## Task 1 - Encodings
Note: For this task I will be using [CyberChef](https://gchq.github.io/CyberChef/). Check [this room](https://tryhackme.com/room/cyberchefbasics) out if you don't know how to use CyberChef.

### ❓Question 1:

01011001 01101111 01110101 00100000 01100111 01101111 01110100 00100000 01101001 01110100 00100001

### 💡 Hint: Binary 

Using the `From Binary` operation, we get:

![](1.png)

### ❓Question 2:

4c 6f 6f 6b 73 20 6c 69 6b 65 20 61 20 62 75 6e 63 68 20 6f 66 20 6e 6f 6e 73 65 6e 73 65 20 74 6f 20 6d 65 2e

### 💡 Hint: Hexadecimal 

Using the `From Hex` operation, we get:

![](2.png)

### ❓Question 3:

SSdtIHByZXR0eSBzdXJlIHRoaXMgb25lIGxvb2tzIHRoZSBtb3N0IGp1bWJsZWQtdXAgc28gZmFyLg==

### 💡 Hint: Base64

Using the `From Base64` operation, we get:

![](3.png)

### ❓Question 4:

AI^SZP'b*&qE+21?-A<jk<W-#plHBU0OJN&:O^bCyij-*]^<Dz#He_'c:kj@;BMNJo',Zmd-?/

### 💡 Hint: Base92

Using the `From Base92` operation, we get:

![](4.png)

### Task 1 is successfully complete!

## Task 2 - Ciphers
Note: For this task I will be using [CyberChef](https://gchq.github.io/CyberChef/) again.

### ❓Question 1:

Guvf vf EBG13, bgurejvfr xabja nf Pnrfre pvcure ebgngrq 13 gvzrf.

### 💡 Hint: ROT13 

Using the `ROT13` operation, we get:

![](5.png)

### ❓Question 2:

20 8 9 19 15 14 5 9 19 19 15 5 1 19 25 25 15 21 3 1 14 4 15 9 20 23 9 20 8 15 21 20 1 20 15 15 12

### 💡 Hint: A1Z26 Cipher

Using the `A1Z26 Cipher Decode` operation, we get:

![](6.png)

### ❓Question 3:

Mlg z evib xlnnlmob-pmldm xrksvi, yfg hgroo vcrhgh.

### 💡 Hint: Atbash Cipher

Using the `Atbash Cipher` operation, we get:

![](7.png)

### ❓Question 4:

籍籲籭 粂籸籾 籽籱籲籷籴 籽籱籲籼 粀籪籼 籪 籵籪籷籰籾籪籰籮籈

### 💡 Hint: ROT8000

Using the `ROT8000` operation, we get:

![](8.png)

### Task 2 is successfully complete!

## Task 3 - Hashes

Note: For this task I will be using [Hashes.com](https://hashes.com/en/decrypt/hash).

### ❓Question 1:

2ff229022db807a41c5e84e859107422

### 💡 Hint: md5

Copy-paste the hash into the box, pass the captcha test (yes, it has to be done), and get the answer:

![](9.png)

### ❓Question 2:

62b487bc84825b3df028a932f082526e195eeff2

### 💡 Hint: SHA-1

Copy-paste the hash into the box, pass the captcha test and get the answer:

![](10.png)

### ❓Question 3:

6a5439e9ffc3f6e138d1767560f7aa618423f6ff5866a1e9fb95f7b11a4cc6aae6301939592af56a

### 💡 Hint: RIPEMD

Copy-paste the hash into the box, pass the captcha test and get the answer:

![](11.png)

### ❓Question 4:

d7468b178ad4b49b01e9cea48afad6a59ab33ac519c2be6818e1839252910f7144491ee791aa56a1e874a2cb4241d647313e7a8a415e189136425a5de5185157

### 💡 Hint: SHA-512

Copy-paste the hash into the box, pass the captcha test and get the answer:

![](12.png)

## If you found this useful, go follow me on [TryHackMe](https://tryhackme.com/p/CyberFalcon101) and [Github](https://github.com/CyberFalcon101)


Do put this in grey box `Just do this`
```
OR THISSSSSSSSSSSSSSSSS
```

