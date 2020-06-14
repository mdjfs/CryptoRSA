# CryptoRSA  
*encrypt/decrypt your binary buffers in JavaScript*

# How to Install
- **Download:**
  - **Normal:** Download the release and copy "CryptoRSA.js" in the folder of your project
  - **Clone:** insert the git bash command: 
```bash
git clone https://github.com/mdjfs/CryptoRSA.git
```
- **Install:**
  Add references for JavaScript file in your html like this: 
```html
<script src="CryptoRSA.js"/>
```
  
 # Usage
 Call a instance of CryptoRSA with this line of code: 
```javascript
var crypto = CryptoRSA(private_key, public_key)
```
**param** *private_key* = Insert array with two numbers primes greater than 16 bits (your private key). For example: [38501, 45541] This key is needed to decrypt binaries

**param** *public_key* = Insert a number result of the multiplication of the two previous numbers (your public key). For example: 1753374041 (38501 * 45541) This key is needed to encrypt binaries
