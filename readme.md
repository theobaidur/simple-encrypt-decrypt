# Simple Encrypt Decrypt

The simplest library to encrypt & decrypt text. This is suitable for small & simple applications.

`You should never use this library for serious projects.`

## Usage

```typescript
import config, { decrypt, encrypt } from "@theobaidur/simple-encrypt-decrypt";

// configuration

config.salt = "simple_encrypt_decrypt";

// encrypt some text

const encrypted = encrypt("Hello world");

console.log(encrypted); // output:: 4c6168686b24736b766860

// decrypt the encrypted text

const text = decrypt(encrypted);

console.log(text); // output:: Hello world

```

## Credits

Inspired from 
- https://stackoverflow.com/a/54026460
- https://stackoverflow.com/a/66938952