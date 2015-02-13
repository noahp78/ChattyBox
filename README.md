# ChattyBox
Secure chat over any IRC network

## What is it?
It's a simple IRC client and 'protocol' that uses RSA to exchange encrypted messages.

## Something to note
The protocol doesn't have a good / easy way to regenerate keys.
It's as secure as the weakest member - if someone leaks their keys the group key is also 'leaked'
