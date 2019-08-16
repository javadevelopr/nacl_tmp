## NACL-Mini

[![Build Status](https://travis-ci.org/javadevelopr/nacl-mini.svg?branch=master)](https://travis-ci.org/javadevelopr/nacl-mini)))]]

A partial rust implementation of authenticated encryption functions of libsodium using cryptographic primitives
from the Rust-Crypto project.

This includes the seal() and open() functions. 
seal() encrypts a packet and prepends a Poly1305 MAC authentication tag, open() performs the reverse.
For details see https://nacl.cr.yp.to/ 
