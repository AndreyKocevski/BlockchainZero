# BlockchainZero
Off-chain Crypto Transactions Between Hardware Wallets

## Overview
BlockchainZero is an off-chain, hardware-enforced, peer-to-peer network for sending and receiving cryptocurrencies. It works by using tamper resistant Smart Cards as hardware wallets in order to send and receive digital assets between devices that are in close proximity.

## How It Works
### Sending and Receiving Assets
BlockchainZero works on the following premise: instead of publishing the transactions on the blockchain, parties can safely perform the same trade by exchanging the private keys of their cryptocurrency addresses. This, of course, can only work if the network is certain that once parties exchange private keys, the previous owner would not be able to retrieve those keys and will not have access to them in any way. Our hardware wallets, which are made of tamper resistant Smart Cards, will allow us to do exactly that, leaving no opportunity for the user to have access to the private keys once they exchange them. The chips are able to generate addresses locally, and most importantly are able to securely store the private keys, making them safe from any kind of physical tampering. This way we can be certain that the private keys would only be accessible from a single BlockchainZero hardware wallet at a time.

### The Hardware Wallets - The Smart Cards - VerbaCard
The Smart Card technology, also called Integrated Circuit Chips, is behind what we use everyday from SIM Cards, credit cards and ATM Cards, to personal ID verification and cybersecurity. They have proven to be tamper resistant and therefore they are the perfect choice for a hardware wallet.

At BlockchainZero we have considered many different forms of smart cards to be used on the network, but for now our conclusions were that for an initial product we needed to choose something that was easily accessible, reliable, and without a steep learning curve . Therefore, we chose to use smart cards in the form of SIM Card Stickers that, as the name suggests, stick to the SIM Card that you use in your phone. The installation process is fairly quick and easy, the SIM Sticker is attached to the SIM Card you use, and then together they are inserted back into the slot of your phone, be it a smartphone or a featurephone. The phone becomes the Smart Card Reader, allowing the card to fully run as intended.  All the computation done by the smart card chip will be executed internally within the chip, outside of the phone’s reach, or anyone’s reach for that matter. This secure computing environment is the cornerstone of the BlockchainZero network.

### Loading The Wallets
The cards can be loaded with any cryptocurrency or tokens (BTC, ETH, ERC20 or ERC721 tokens, anything is supported as long as it can be accessed by a private key). BlockchainZero will initialize the software on the cards and provide a certificate, which will be used in order to establish trust between cards when exchanging assets. 
Loading the cards with assets that are not currently in the BlockchainZero network would first require a procedure of initiating those assets on the network. 
The first step is to initiate the procedure on the BlockchainZero card. The card will create  hundreds, if not thousands of addresses internally, and will output the public addresses. The number of addresses created depends on how many assets you are transferring. 
The second step is to sign a transaction with your digital wallet with multiple outputs, sent to the previously generated addresses.
̄Once the assets are initiated onto the network and loaded to a card, they can be freely transferred between other BlockchainZero cards. 

### Transferring Assets Between Wallets
Using an app you will be able to communicate with the smart card chip installed in your phone. Once both parties agree to trade, the following steps occur:
The recipient will initiate the transfer on their app, and the app will request a public address from the recipient’s smart card chip installed on their phone. This public address will stem from the card's own unique identity from the certificate installed. The address will then be displayed as a QR code on the app, so that the sender can scan it.
Once the sender scans the QR code displayed on the recipient’s phone, it passes the public address to their smart card chip, which it then uses in order to encrypt all of the private keys containing the assets. Then, it outputs the encrypted private keys and their respective public addresses as a QR code, so that this time the recipient can scan them.
The recipient then scans the QR code from the sender, verifies on the blockchain that the addresses do in fact contain the agreed amount of value, and completes the trade.


### Unloading The Cards Off the BlockchainZero Cards
You can request on the installed BlockchainZero app to unload the cards. The app will then communicate with the chip and perform the request, and in return the chip would export all the private key addresses stored and delete them from internal memory. Once the process finishes you won't be able to load the cards with the same private addresses again. If you want to use the card again you would have to perform the loading procedure once again, or acquire some assets from another BlockchainZero card owner. 



