# Blockchain in Java

A simple Java blockchain with transactions.

This blockchain can:
- Allows users to create wallets with ```new Wallet();```
- Provides wallets with public and private keys using *Elliptic-Curve cryptography*.
- Secures the transfer of funds, by using a digital signature algorithm to prove ownership.
- Allow users to make transactions on the blockchain with ```Block.addTransaction(walletA.sendFunds(walletB.publicKey, 20));```