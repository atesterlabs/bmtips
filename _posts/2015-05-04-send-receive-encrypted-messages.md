---
layout: post
title: How to Send / Receive Encrypted Messages using APG / PGP app?
date: 2015-05-04 10:30:38.000000000 +03:00
type: post
published: true
status: publish
categories:
- Troubleshooting
tags: []
lang: en
permalink: /send-receive-encrypted-messages/
meta:
---

To send an encrypted message you must have the recipient’s public key. To receive an decrypt an encrypted message it must originally be encrypted using your public key.

You can check your key settings in APG through *Contacts* \| *My Keys* \| *Choose your key* \| *Edit*.

For security considerations it is safer to have separate keys with which to sign and encrypt messages, though you can use the same key for both purposes.

You do not need to specifically register the recipient to BlueMail in order to recognize them as recipients for encrypted mail, but their email address must be associated with their public key on APG.

Note: A “Key not Found” decryption error occurs most likely because the message was not encrypted using your public key, or that you no longer have access to the corresponding private key.