A simple javascript XAHAU wallet to check the balance, send XAH, create new mainnet accounts offline and create testnet funded accounts. It uses the xrpl.js library.

It uses a seed to derive the account address and sign transactions, 2 options are possible:

Option A: 29 characters seeds (suNq9PQrYKEifmLdFs9NPjdLeyMKm) which correspond to the secp256k1 algorithm.

Option B: 31 characters seeds (sKdNVBLAmVjgcDrEfDSzTSBqsagHMEd) which correspond to the ed25519 algorithm.

Step by step guide to use the code:

1) Create an empty folder in your desktop and name it as you like.

2) Download the 4 files I have in this project to that folder.

3) Open the HTML file in your browser.

4) Select the network. It works for Mainnet and Testnet.

5) It allows to create a Mainnet account (which has to be activated later with XAH). Do it offline, it's purely mathematical.

6) It allows to create a Testnet funded account from the faucet. You can do it online as it's just testnet XAH.

7) It allows to send XAH.

Try the demo online here: https://skunk-proper-smoothly.ngrok-free.app/tools/simpleXAHAUwallet/xahauwallet
