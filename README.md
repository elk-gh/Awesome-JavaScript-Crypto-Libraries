# Gabo's Awesome JavaScript Crypto Libraries

List of Awesome JavaScript Crypto Libraries based on 
[JavaScript Crypto Libraries](https://gist.github.com/jo/8619441) by
[Johannes Jörg Schmidt](https://github.com/jo)



## Categories

* [The W3C Specification (1)](#the-w3c-specification)
* [The Big Ones (5)](#the-big-ones)
* [The Rest of The Pack (19)](RestOfThePack/README.md)
* [No Longer Maintained (9)](NoLongerMaintained/README.md)
* [Unknown Status (7)](UnknownStatus/README.md)



## The W3C Specification

### _WebCryptoAPI_

[![Website](https://img.shields.io/badge/WebSite-On-brightgreen.svg?style=flat-square&maxAge=5184000)](http://www.w3.org/TR/WebCryptoAPI/)
[![GitHub Repo](https://img.shields.io/badge/github-repo-brightgreen.svg?style=flat-square&maxAge=5184000)](https://github.com/w3c/webcrypto)
![GitHub last commit](https://img.shields.io/github/last-commit/w3c/webcrypto.svg?style=flat-square&maxAge=5184000)
![GitHub watchers](https://img.shields.io/github/watchers/w3c/webcrypto.svg?style=flat-square&maxAge=5184000)
![GitHub stars](https://img.shields.io/github/stars/w3c/webcrypto.svg?style=flat-square&maxAge=5184000)
![GitHub forks](https://img.shields.io/github/forks/w3c/webcrypto.svg?style=flat-square&maxAge=5184000)
![GitHub issues](https://img.shields.io/github/issues/w3c/webcrypto.svg?style=flat-square&maxAge=5184000)

This specification describes a JavaScript API for performing basic
cryptographic operations in web applications, such as hashing, signature
generation and verification, and encryption and decryption.
Additionally, it describes an API for applications to generate and/or
manage the keying material necessary to perform these operations. Uses
for this API range from user or service authentication, document or code
signing, and the confidentiality and integrity of communications.


[_Return to Categories_](#categories)



## The Big Ones

Frameworks with more than ~4KB GitHub Stars.


### _Crypto Module in NodeJS_

[![Website](https://img.shields.io/badge/WebSite-On-brightgreen.svg?style=flat-square&maxAge=5184000)](https://nodejs.org/api/crypto.html)
[![GitHub Repo](https://img.shields.io/badge/github-repo-brightgreen.svg?style=flat-square&maxAge=5184000)](https://github.com/nodejs/node)
![GitHub last commit](https://img.shields.io/github/last-commit/nodejs/node.svg?style=flat-square&maxAge=5184000)
![GitHub watchers](https://img.shields.io/github/watchers/nodejs/node.svg?style=flat-square&maxAge=5184000)
![GitHub stars](https://img.shields.io/github/stars/nodejs/node.svg?style=flat-square&maxAge=5184000)
![GitHub forks](https://img.shields.io/github/forks/nodejs/node.svg?style=flat-square&maxAge=5184000)
![GitHub issues](https://img.shields.io/github/issues/nodejs/node.svg?style=flat-square&maxAge=5184000)

The `crypto` module provides cryptographic functionality that includes a
set of wrappers for OpenSSL's hash, HMAC, cipher, decipher, sign and
verify functions. **NOTE:** GitHub stats are from all NodeJS project.
  
  
### _crypto-js_

![Website](https://img.shields.io/badge/WebSite-Off-red.svg?style=flat-square&maxAge=5184000)
[![GitHub Repo](https://img.shields.io/badge/github-repo-brightgreen.svg?style=flat-square&maxAge=5184000)](https://github.com/brix/crypto-js)
![GitHub last commit](https://img.shields.io/github/last-commit/brix/crypto-js.svg?style=flat-square&maxAge=5184000)
![GitHub watchers](https://img.shields.io/github/watchers/brix/crypto-js.svg?style=flat-square&maxAge=5184000)
![GitHub stars](https://img.shields.io/github/stars/brix/crypto-js.svg?style=flat-square&maxAge=5184000)
![GitHub forks](https://img.shields.io/github/forks/brix/crypto-js.svg?style=flat-square&maxAge=5184000)
![GitHub issues](https://img.shields.io/github/issues/brix/crypto-js.svg?style=flat-square&maxAge=5184000)

JavaScript library of crypto standards based on the inactive
**CryptoJS**.


### _SJCL - Stanford Javascript Crypto Library_

[![Website](https://img.shields.io/badge/WebSite-On-brightgreen.svg?style=flat-square&maxAge=5184000)](http://bitwiseshiftleft.github.io/sjcl)
[![GitHub Repo](https://img.shields.io/badge/github-repo-brightgreen.svg?style=flat-square&maxAge=5184000)](https://github.com/bitwiseshiftleft/sjcl)
![GitHub last commit](https://img.shields.io/github/last-commit/bitwiseshiftleft/sjcl.svg?style=flat-square&maxAge=5184000)
![GitHub watchers](https://img.shields.io/github/watchers/bitwiseshiftleft/sjcl.svg?style=flat-square&maxAge=5184000)
![GitHub stars](https://img.shields.io/github/stars/bitwiseshiftleft/sjcl.svg?style=flat-square&maxAge=5184000)
![GitHub forks](https://img.shields.io/github/forks/bitwiseshiftleft/sjcl.svg?style=flat-square&maxAge=5184000)
![GitHub issues](https://img.shields.io/github/issues/bitwiseshiftleft/sjcl.svg?style=flat-square&maxAge=5184000)

The Stanford Javascript Crypto Library on GitHub is a project by the
Stanford Computer Security Lab to build a secure, powerful, fast, small,
easy-to-use, cross-browser library for cryptography in Javascript.


### _OpenPGP.js_

[![Website](https://img.shields.io/badge/WebSite-On-brightgreen.svg?style=flat-square&maxAge=5184000)](https://openpgpjs.org)
[![GitHub Repo](https://img.shields.io/badge/github-repo-brightgreen.svg?style=flat-square&maxAge=5184000)](https://github.com/openpgpjs/openpgpjs)
![GitHub last commit](https://img.shields.io/github/last-commit/openpgpjs/openpgpjs.svg?style=flat-square&maxAge=5184000)
![GitHub watchers](https://img.shields.io/github/watchers/openpgpjs/openpgpjs.svg?style=flat-square&maxAge=5184000)
![GitHub stars](https://img.shields.io/github/stars/openpgpjs/openpgpjs.svg?style=flat-square&maxAge=5184000)
![GitHub forks](https://img.shields.io/github/forks/openpgpjs/openpgpjs.svg?style=flat-square&maxAge=5184000)
![GitHub issues](https://img.shields.io/github/issues/openpgpjs/openpgpjs.svg?style=flat-square&maxAge=5184000)

This project aims to provide an Open Source OpenPGP library in
JavaScript so it can be used on virtually every device. Instead of other
implementations that are aimed at using native code, OpenPGP.js is meant
to bypass this requirement.


### _node.bcrypt.js_

![Website](https://img.shields.io/badge/WebSite-Off-red.svg?style=flat-square&maxAge=5184000)
[![GitHub Repo](https://img.shields.io/badge/github-repo-brightgreen.svg?style=flat-square&maxAge=5184000)](https://github.com/kelektiv/node.bcrypt.js)
![GitHub last commit](https://img.shields.io/github/last-commit/kelektiv/node.bcrypt.js.svg?style=flat-square&maxAge=5184000)
![GitHub watchers](https://img.shields.io/github/watchers/kelektiv/node.bcrypt.js.svg?style=flat-square&maxAge=5184000)
![GitHub stars](https://img.shields.io/github/stars/kelektiv/node.bcrypt.js.svg?style=flat-square&maxAge=5184000)
![GitHub forks](https://img.shields.io/github/forks/kelektiv/node.bcrypt.js.svg?style=flat-square&maxAge=5184000)
![GitHub issues](https://img.shields.io/github/issues/kelektiv/node.bcrypt.js.svg?style=flat-square&maxAge=5184000)

bcrypt for NodeJs. 



[_Return to Categories_](#categories)
