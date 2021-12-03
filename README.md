# notes-on-software
Short notes and useful commands of software environment . 




# Shell

Verify that software is downloaded properly without corruption
- step 1 : generate the sha512 checksum of downloaded software on your local .
- step 2 : match it with original checksum
- step 3 : If they do not match then your software is corrupted while downloading . Please download again .
```
PSINGH6-M-KHCS:experiment psingh6$ openssl sha512 apache-maven-3.8.4-bin.tar.gz 
SHA512(apache-maven-3.8.4-bin.tar.gz)= a9b2d825eacf2e771ed5d6b0e01398589ac1bfa4171f36154d1b5787879605507802f699da6f7cfc80732a5282fd31b28e4cd6052338cbef0fa1358b48a5e3c8


PSINGH6-M-KHCS:experiment psingh6$ echo a9b2d825eacf2e771ed5d6b0e01398589ac1bfa4171f36154d1b5787879605507802f699da6f7cfc80732a5282fd31b28e4cd6052338cbef0fa1358b48a5e3c8 | grep -w a9b2d825eacf2e771ed5d6b0e01398589ac1bfa4171f36154d1b5787879605507802f699da6f7cfc80732a5282fd31b28e4cd6052338cbef0fa1358b48a5e3c8

a9b2d825eacf2e771ed5d6b0e01398589ac1bfa4171f36154d1b5787879605507802f699da6f7cfc80732a5282fd31b28e4cd6052338cbef0fa1358b48a5e3c8
```

# Java


# Maven


# Git


# Springboot



# Docker


# Redis


# Postgres



# Kafka


# brew : software to install and manage other software on macOS
- This command will show the directory of brew package.
```
brew ls tomcat
```
