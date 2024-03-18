# Obs-lisacollins

Obs-lisacollins is a Node.js module that provides functions for various cryptographic operations such as generating random strings, hashing passwords, comparing passwords, and generating RSA key pairs.

## Installation

You can install Obs-lisacollins using npm: `npm install obs-lisacollins`

## Usage
```javascript
const cryptoHelper = require('crypto-helper');

// Generate a random string
const randomString = cryptoHelper.generateRandomString(10);
console.log('Random String:', randomString);

// Hash a password
const password = 'secretpassword';
const hashedPassword = cryptoHelper.hashPassword(password);
console.log('Hashed Password:', hashedPassword);

// Compare password with hash
const isMatch = cryptoHelper.comparePassword(password, hashedPassword);
console.log('Password Match:', isMatch);

// Generate RSA key pair
const keyPair = cryptoHelper.generateKeyPair();
console.log('RSA Key Pair:', keyPair);
```

