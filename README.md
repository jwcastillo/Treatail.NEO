<p align="center">
  <img src="Treatail.png" />
</p>

## This Repository
This repository contains the source code for the Award-Winning ([First Place in City of Zion dApps Competition](https://cityofzion.io/dapps/2/), and [Second Place in NEO / Microsoft Dev Competition](https://neo.org/awards.html)) Smart Contract for a Treatail NEP5 Token (TTL) and Treatail Asset management, Core middleware (leveraging [neo-lux](https://github.com/cityofzion/neo-lux)), REST API middleware, tests libraries, and test harness.

## The Product / dApp
### Overview
Treatail is a revolutionary commerce layer that sits on top of all the sites and marketplaces on the Internet.  Our platform allows for buyers, both consumer and business, to make offers and receive personalized deals on goods and services listed for sale on any site doing commerce on the Internet.  Our goal is to help buyers to get unpublished, personalized deals and help online retailers boost profits by optimizing inventory through precision discounts and reduced cart abandonment.

The cornerstone of the next evolution to the Treatail Ecosystem will be the creation of Treatail Token (TTL) and smart contracts to facilitate transactions on the blockchain and to further incent users.  To date, blockchain has primarily been available to technical users.  Treatail aims to change this by bringing the power of the NEO blockchain to the average user using intuitive interfaces and seamless integration into the Treatail platform.

Find out more at http://www.treatail.com and check out the whitepaper below.

### Documentation
#### Whitepaper
A brief whitepaper for the Treatail product and future blockchain offering can be found here:
https://drive.google.com/open?id=1UlcbIkmbPJnSHAFiY1V20TCX4s2XMsQO8NVwWSpfcnY

#### Product / dApp 
A quick demo video of the demo code in this repository in action can be found on YouTube:                
https://www.youtube.com/watch?v=Fcz8XJctHok

#### Code and API Documentation 
Commented code and Visual Studio XML comments, with additional compiled Microsoft HTML Help file (.chm) found in the /Docs folder

### Screenshots
#### Treatail website
<p align="center">
  <img src="/Screenshots/website.png" />
</p>

#### Login and signup
Login or sign up for an account
<p align="center">
  <img src="/Screenshots/login.png" />
</p>

#### Active deal list interface
This interface will show the user all the active deals they currently have outstanding.
<p align="center">
  <img src="/Screenshots/activedeals.png" />
</p>

#### Deal details
This interface shows the user the deal details (terms of the offer, captured information, etc) and allows the user to take action.
<p align="center">
  <img src="/Screenshots/dealdetails.png" />
</p>

#### Seller deal response interface (simple)
This is the interface that lets sellers send a basic response to the buyer based on USD and TTL price
<p align="center">
  <img src="/Screenshots/dealresponse.png" />
</p>

#### Seller deal response interface (advanced)
The advanced deal response interface will allow the seller to add or adjust line items, create multiple counter offer options for the buyer, and allow the buyer to share the deal(s).
<p align="center">
  <img src="/Screenshots/dealadvancedresponse.png" />
</p>

#### Buyer payment
This is the payment screen for the demo.  Treatail uses PayPal for all USD transactions, but this was unavailable in the demo site.  The demo site will only make the blockchain related TTL transfers at the close of a deal, but we skip over PayPal piece for brevity.
<p align="center">
  <img src="/Screenshots/payment.png" />
</p>

#### User details screen
This is the screen where the user can find their information - the links for them to share their referral link on social media, manage their TTL Token wallet and transfers, and see audit history of transfers of TTL.
<p align="center">
  <img src="/Screenshots/userdetails.png" />
</p>

#### Sending TTL Token to a Treatail user
Users can easily send TTL Tokens to other users in the Treatail ecosystem by providing just an e-mail address.  Treatail will find the hosted wallet information for that user and make the blockchain transfer on the behalf of the user.
<p align="center">
  <img src="/Screenshots/sendtoken-treatail.png" />
</p>

#### Sending TTL Token to a NEO Address
Users can also send TTL Tokens to an external NEO Address, for example, if they want to use their own NEP5 compatible wallet to manage their own keys for the TTL they earn.  They can always transfer back to their Treatail address if needed.
<p align="center">
  <img src="/Screenshots/sendtoken-neo.png" />
</p>

#### TTL Token transaction history
This provides an audit trail for any TTL Token transfer activity within Treatail.
<p align="center">
  <img src="/Screenshots/ttlhistory.png" />
</p>

#### List of user's Treatail Assets
Treatail Assets are blockchain verified asset receipts for purchases made in the Treatail Ecosystem.  Users can verify the purchase and authenticity of an item using blockchain as the source of truth.
<p align="center">
  <img src="/Screenshots/assetlist.png" />
</p>

#### Verified Treatail Asset details screen
This is the asset details screen that actively compares the details hash of the item against the blockchain and shows the "Blockchain Verified" badge if the data they are viewing matches the data stored to the blockchain.
<p align="center">
  <img src="/Screenshots/verifiedassetdetails.png" />
</p>

### Architecture and Hosting
#### Hosting
Treatail is hosted on Microsoft Azure - Platform as a Service

#### Frontend
Microsoft .NET Web Application and Mobile Apps available for iOS and Android

#### Backend
Microsoft .NET WebAPI (REST), Treatail.NEO Middleware

#### Databases
Microsft SQL Server, Redis, and Microsoft Cosmos DB

#### Storage
Azure Blob Storage, NEO Blockchain

## Credits
This project wouldn't have been possible without the support from the [City of Zion](https://github.com/CityOfZion) NEO development community.  A big shout out to Sérgio Flores ([Relfos](https://github.com/Relfos)) for his work on [neo-debugger-tools](https://github.com/Relfos/neo-debugger-tools) and [neo-lux](https://github.com/cityofzion/neo-lux), and for all his assistance in helping me get neo-lux implemented in the project.  Thanks to Chris Hager ([Metachris](https://github.com/metachris)) for his assistance in getting started with neo-python and NEO development, and for his great work on [hosting a privatenet docker](https://medium.com/proof-of-working/how-to-run-a-private-network-of-the-neo-blockchain-d83004557359)




