# Iphone-Crypto-Wallet
This is a hardware wallet that uses a crypto hardware enclave chip to store private keys on an iPhone. 
# Design

## Goals
The main goal for this design was simplicity, a user should be able to just plug the device into their iphone and immediately get access to a wallet. The moment that the device is removed, then the access should also be removed. The current adapter for the iphone connection is a USB-Lightining plug so that it is compatibile with the majority of iphones. Adding support for USB-C would not be that difficult and would be something to do.

## Chips
A CP-2112 is used for communication
