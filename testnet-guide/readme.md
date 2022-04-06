# How to use the FIO Domain Marketplace

## Create a keypair
We are going create a brand new account and register a domain so it can be listed for sale on the marketplace.

Visit the FIO Testnet Monitor https://monitor.testnet.fioprotocol.io and click "Create Keypair"

<img alt="img_1.png" src="images/img_1.png"/>

Copy the 3 pieces of information from the popup window, the **Public Key**, **Private Key**, and **actor name**.

```
Public Key: FIO4uxNZhNxbCpxxkzqFWXJL4xEddyKu8DJS6fXZTJQsYPfSMk68q
Private key: 5JzsRFUnV8T99qjzPaevr9FsrpTAbBsAM4VLMNQJswNppYr8GfH

FIO Internal Account (actor name): 3okzexo3vzt3
```

`DO NOT USE THIS KEY, IT IS JUST FOR DEMO PURPOSES`

## Get Coins from Faucet
Click on the Faucet link

<img alt="img_2.png" src="images/img_2.png"/>

1. Copy the public key you saved from above, it starts with **FIO** and paste it in the _Pub Key_ field.
2. Click _I'm not a robot_ and pass the captcha
3. Click _Send Coins_.

<img alt="img_3.png" src="images/img_3.png"/>

The faucet only works every 6 hours per address. You are able to create multiple addresses and get free tokens per address.

## Setup Anchor Wallet

Download Anchor wallet for your OS. I will go over Windows, but it is a similar process on other OS's. The latest version is __1.3.3__.

<img alt="img_11.png" src="images/img_11.png"/>

Click __Setup an Account__

Set a secure password that you will remember but that is hard to guess. This password will give access to all the private keys stored in Anchor. It is important this is a secure password and stored safely.

<img alt="img_12.png" src="images/img_12.png"/>

We're going to choose _FIO (Testnet)_. To do this, (1) tick the checkbox _Show blockchain test networks_ then (2) click on the drop down menu and scroll to (3) _FIO (Testnet)_ and select it.

<img alt="img_28.png" src="images/img_28.png"/>

Click _Import an existing Account_

<img alt="img_13.png" src="images/img_13.png"/>

Click _Import Private Key_

<img alt="img_14.png" src="images/img_14.png"/>

(1) Paste the private key saved earlier (it starts with a __5__).

Anchor will detect the public key and (2) show the accounts associated with that public/private keypair. (3) select the __@active__ account on the list and then (4) click __Import Account(s)__. You will be prompted for the password you created in the previous step.

On the Account(s) Overview page it should now show the FIO account in the list and at the top of the UI.

<img alt="img_15.png" src="images/img_15.png"/>

## Register a domain

Visit https://greymass.github.io/fio-register/?testnet

Click 'Sign in'.
<img alt="img_29.png" src="images/img_29.png"/>

There will be a popup asking which wallet to use. Select Anchor.

<img alt="img_30.png" src="images/img_30.png"/>

Click `Open Anchor App` at the bottom

<img alt="img_31.png" src="images/img_31.png"/>

Click "Open Anchor Wallet"

<img alt="img_32.png" src="images/img_32.png"/>

Click the green pencil icon in the bottom right corner.

<img alt="img_33.png" src="images/img_33.png"/>

You will then get a screen like this. Click on the `Domain Management` tab
<img alt="img_34.png" src="images/img_34.png"/>

Click on `Register Domain`
<img alt="img_35.png" src="images/img_35.png"/>

Make sure you have enough (1) FIO available for the (2) Domain Registration Fee. Fill out the (3) `Fio Domain` field and click (4) 'Register Domain'
<img alt="img_36.png" src="images/img_36.png"/>

Anchor will popup with a _Signing Request_. Click the green pencil icon in the bottom right.
<img alt="img_37.png" src="images/img_37.png"/>

## Use FIO Marketplace
This site is currently not very mobile friendly. It is highly recommended to use a computer when interacting with the FIO Marketplace. Please note this website is in active development so things might look different compared to the screenshots or instructions because of ongoing updates.

Navigate to https://fiomarket.place

Click the top right corner and then "Log In"

<img alt="img_16.png" src="images/img_16.png"/>

You will get a popup window with a large QR code. Click on "Launch Anchor" at the bottom.

<img alt="img_17.png" src="images/img_17.png"/>

You will get yet another pop up window "Open Anchor Wallet?". This will popup when ever you login to the site. Tick the checkbox to "Always allow..." if you don't want to have this popup every time. Click on "Open Anchor Wallet"

<img alt="img_18.png" src="images/img_18.png"/>

The next window that pops up is a __Signing Request__. Verify the account in the middle of the screen is the one you want to use (this is handy if you have multiple accounts set up) then click the blue lock icon in the bottom right, you'll be prompted for your anchor password.

<img alt="img_19.png" src="images/img_19.png"/>

There is a bug that doesn't refresh the page right away sometimes so if nothing changes please refresh the page and the left-side links should show up. 

Click "My Domains" and you should see the domain you registered earlier. To list it for sale click "List Domain for Sale".

<img alt="img_20.png" src="images/img_20.png"/>

On this page you can set the price you want for the domain. Remember you paid around 380 FIO to register it so you probably don't want to go less than that. I will list mine for 425 FIO. When I enter the price some information appears breaking down the costs for listing and the commission the marketplace takes out. Currently it's a _3% commission_ and _5 FIO_ listing fee. When the domain sells, I'll receive 388 FIO out of the 400. The 5 FIO is taken at the time of listing. 

Click _Confirm_ when you're satisfied with the amount of FIO you will receive for the domain.

<img alt="img_21.png" src="images/img_21.png"/>

Another signing request window will popup detailing the information about the domain being listed for sale. Click the green pencil icon to sign the transaction.

<img alt="img_22.png" src="images/img_22.png"/>

The domain will now show up on the _My Listings_ page with details about the listing. You are able to cancel the listing from this page.

<img alt="img_23.png" src="images/img_23.png"/>

(1) It also shows up on the dashboard page.

You will notice that because you are the one listing the domain, the 'Buy Now' button is disabled. This is because you cannot buy a domain you listed yourself with the same account.

(2) You can also purchase a domain from this page. Click "Buy Now" on any domain.

<img alt="img_25.png" src="images/img_25.png"/>

The purchase page summarizes the domain being purchased and for how much.

<img alt="img_26.png" src="images/img_26.png"/>

Clicking "Buy" will pop up another _Signing Request_ window with a summary of the purchase information. Click the green pencil icon in the bottom right corner to purchase the domain.

<img alt="img_27.png" src="images/img_27.png"/>
