# CodeRandom3 Docs

The main page and documentation for the [CodeRandom3](https://summersphinx.itch.io/coderandom3) game.

The aim of the game is to decrypt messages to help fight the enemy(or something). This page will help you use the tools made to help decrypt the messages, and also teach you about the encryption methods used within the game.


## Getting Started

## Encryption Methods

A feature of the game is allowing you to write a simple script to decode a string of characters automaticly, as long as you write the script correctly. The guide below shows how to write the script to decipher each different encryption method used within the game.

### Caesar Cipher

: One of three basic ciphers used within the game. The Caesar cipher, also known as the shift cipher, shifts the alphebet *n* characters.

Example:

```
shift 7


# The Caesar cipher with a key of 7
#
# A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
# I J K L M N O P Q R S T U V Q X Y Z A B C D E F G H
```

### Atbash Cipher

: The second of three basic ciphers used within the game. The Atbash cipher, also known as the flip cipher, is a substitution cipher with a fixed key that reverses the alphabet.

Example:

```
flip


# The Atbash cipher
#
# A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
# Z Y X W V U T S R Q P O N M L K J I H G F E D C B A
```
