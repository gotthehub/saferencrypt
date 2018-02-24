# saferencrypt

A way to utilize PGP intended for personal public email use NOT for fully optimal privacy settings:
- You can avoid by getting a protonmail account

RFC's:

PGP
RFC 1991 PGP Message Exchange Formats (obsolete)
OpenPGP
RFC 2440 OpenPGP Message Format (obsolete)
RFC 4880 OpenPGP Message Format
RFC 5581 The Camellia Cipher in OpenPGP
RFC 6637 Elliptic Curve Cryptography (ECC) in OpenPGP
RFC 4880bis (draft) OpenPGP Message Format
PGP/MIME
RFC 2015 MIME Security with Pretty Good Privacy (PGP)
RFC 3156 MIME Security with OpenPGP

Remember: 

SSL and TLS will not save your life, yet I am happy they exist

OpenPGP's encryption can ensure secure delivery of files and messages, as well as provide verification of who created or sent the message

And nothing else magical

(WiKi)

With the advancement of cryptography, parts of PGP have been criticized for being dated:

The long length of PGP public keys
Difficulty for the users to comprehend and poor usability
Lack of ubiquity
Lack of forward secrecy
In October 2017, the ROCA vulnerability was announced that affects RSA keys generated on the Yubikey 4 tokens, often used with PGP. Many published PGP keys were found to be susceptible.

What the large email companies do that is very, very greasyshithanded for users:

G00Gle 
- https://www.google.com/policies/privacy/

- "People should take them at their word; if you care about your email correspondents' privacy, don't use Gmail."
- Google said "all users of email must necessarily expect that their emails will be subject to automated processing."
- According to Google: "Just as a sender of a letter to a business colleague cannot be surprised that the recipient's assistant opens the letter, people who use web-based email today cannot be surprised if their communications are processed by the recipient's ECS [electronic communications service] provider in the course of delivery." - Gaurdian
- Gmail looks for keywords | A conversation thread about meeting up at a spinning class, for example, might trigger an ad for a weight-loss product.
- When people send and receive messages using a free e-mail service, they are sharing details about their interests, who their connections are and what their finances look like.- CNN

I picked on Gmail but any email that comes to your head is highly dirty

My Safe email to your unsafe email
Your unsafe email to my safe email

You get it .. I don't come in your house and wipe my shoes on your couch

Easy - 1. Generate Key Pair 2. Extract Public Key 3. Extract and safley hide Private key 4. Test

`
