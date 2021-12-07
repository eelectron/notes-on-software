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

Generate shasum of any file .
```
PSINGH6-M-KHCS:Documents psingh6$ shasum -a 512 apache-zookeeper-3.7.0-bin.tar.gz
64e2701c019ed46f45f4d53b2c5eaeaf7cf48c342bbafa032a0819d527fc77caebfada6bdad34e5171e6d838f40b16c95b62ce378b53dfc827af2d60cec0b17c  apache-zookeeper-3.7.0-bin.tar.gz
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


# Tomcat
- Check location of tomcat installed with brew on Mac
```
PSINGH6-M-KHCS:~ psingh6$ brew ls
==> Formulae
gettext		git		maven		openjdk		pcre2		tomcat@9

PSINGH6-M-KHCS:~ psingh6$ brew ls tomcat@9
/usr/local/Cellar/tomcat@9/9.0.55/.bottle/etc/ (10 files)
/usr/local/Cellar/tomcat@9/9.0.55/bin/catalina
/usr/local/Cellar/tomcat@9/9.0.55/homebrew.mxcl.tomcat@9.plist
/usr/local/Cellar/tomcat@9/9.0.55/homebrew.tomcat@9.service
/usr/local/Cellar/tomcat@9/9.0.55/libexec/bin/ (17 files)
/usr/local/Cellar/tomcat@9/9.0.55/libexec/lib/ (32 files)
/usr/local/Cellar/tomcat@9/9.0.55/libexec/temp/safeToDelete.tmp
/usr/local/Cellar/tomcat@9/9.0.55/libexec/webapps/ (1002 files)
/usr/local/Cellar/tomcat@9/9.0.55/libexec/ (2 files)
/usr/local/Cellar/tomcat@9/9.0.55/RELEASE-NOTES
/usr/local/Cellar/tomcat@9/9.0.55/RUNNING.txt
```
