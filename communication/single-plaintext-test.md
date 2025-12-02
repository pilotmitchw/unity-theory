# The Single Plaintext Test
This test comes from cryptography. A useful encrypted message must have a single sensible decoding or *plaintext*.
When someone claims to know secret knowledge or claims that something has a secret meaning, apply this test.

## How broad is it?
An interpretation that can apply to anything is useless and defeats the purpose of encryption, which is to communicate a
specific message. 
## How public is it?
There is no reason to put secret meanings in public messages when it is possible to put them in private messages. 
## Does it need to be secret?
Encryption is hard, and people don't do it unless it's worth it. More importantly, every use of a non-random encryption 
algorithm gives an attacker useful information that can be used to defeat the encryption.
## Is there a consensus?
A message that has been successfully decrypted does not invite opinions because the intended plaintext is the 
only one that makes sense.
## Does it rely on multiple meanings of words, proximity of words in a message, or other mechanics of language?
If it does, you are playing a word game. Good encryption does not preserve the patterns in a language. Algorithms that
do are subject to an attack called *frequency analysis*.
