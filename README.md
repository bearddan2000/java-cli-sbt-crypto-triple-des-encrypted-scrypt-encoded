# java-cli-sbt-crypto-triple-des-encrypted-scrypt-encoded

## Description
Encrypt and decrypt password with 3DES
encoded with scrypt.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- java
- sbt

## Docker stack
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://stackoverflow.com/questions/20227/how-do-i-use-3des-encryption-decryption-in-java)
