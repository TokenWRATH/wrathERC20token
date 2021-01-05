---
title: "Detecting crypto tokens scams."
date: 2021-01-04
---
$WRATH other than aiming at becoming a secure and trustworthy ERC-20 Token, aspires to raise awareness on the vastity of crypto scams that sadly flood the Ethereum blockchain and to which many people fall for.
In fact, $WRATH is determined to show affidability and security by letting the investor know what they are dealing with instead of hiding the true purposes and making the investor unaware of a possible scam. 

### Main types of scams:
There are several types of scams which take advantage of people unawareness to steal their money. These can be either through impersonating another token/project, promising big returns and telling people to invest but stealing all their money afterwards or even modifying the token source code in a way that stops the user from selling the token.

### 1. Fake tokens impersonating other tokens.
#### Method:

By copying a token's name and properties, scammers will create a custom token that "impersonates" the token of a legit project people are going to invest in. Doing so, people whill received the wrong token address (the one of the 
fake coin) or by choosing the wrong coin when looking it up and not verifying the address is the legit one, and so they will swap/buy this fake token. The moment the people who bought the fake token try to swap it, sell it back or withdraw the liquidity they added (especially on Uniswap), they 
will encounter an error that will stop them from getting their money or tokens back, leaving it all in the hands of the scammers. This is possible because the creators of the fake token will add a huge amount of liquidity to the fake token pool and this causes more people to think it's the legit token; 
After enough people have been scammed, the perpetrators will completely withdraw all the liquidity and so all the money in it. Investors when trying to sell or withdraw the liquidity, they'll find an "undefined" error that is completely unavoidable and cannot be bypassed. The way this is done relies in the 
source code of the token itself; the scammers will program the token in a way that only the owner of the contract can sell the token, or by putting selling fees so high that Uniswap cannot process the swap.

![image](https://github.com/TokenWRATH/wrathERC20token/blob/main/_images/scamcoin.png?raw=true "Type of Error")

#### How to detect it:
In this case it's fairly easy, you need to check that the address of the token you're dealing with is __absolutely the same__ of the address the official project of the token is giving. Aside from this, fake tokens will most likely not have any sort of token logo on Etherscan, plus their source code is most likely not showing and not verified.
(In case, if you have the knowledge, you could directly check the code to find any form of irregularities as listed before, or if the code isn't present, you can check the decompilation of the contract executable Etherscan allows you to do).

![image](https://github.com/TokenWRATH/wrathERC20token/blob/main/_images/checking_code.PNG?raw=true "Checking the source Code")
### 2. Tokens that cannot be sold.
#### Method:

It's basically the same as the first, except that there is no "impersonation" of another token but instead they will try to pass as a completely legitimate token while still programming the token to not let anyone sell it or withdraw it from the liquidity pool. The scammers then will act in the same way as stated before.

#### How to detect it:
This time it's not so easy. The best way to see if the token allows to withdraw/sell is by testing it by buying a small amount and then trying to swap the token back, this will confirm with almost complete certainty whether the token allows to sell or not. To deal with it in a more in-depth way, it's still possible to check the source code or,
if it's not present, decompile the contract with the tool Etherscan allows you to use and check the decompiled code.

![image](https://github.com/TokenWRATH/wrathERC20token/blob/main/_images/bytecode.PNG?raw=true "Decompile ByteCode")

### 3. Exit scams/Rug pulls
#### Method:

What happens in this case is that the token is actually completely safe and secure, but the team behind it has bad intentions. The team will lure lots of people into investing in their token by increasing the liquidity and getting people to swap it. Once the token price reached a level that will deliver a good profit, they'll do what's called a "rug pull".
This act consists in the team selling all their tokens and withdrawing all the liquidity pool, completely draining it and taking the money along. The effect of this is that the price of the token plummets to near 0 levels and the token holders are unable to sell their tokens either because there isn't enough liquidity or because the token has become completely worthless.

![image](https://github.com/TokenWRATH/wrathERC20token/blob/main/_images/rugpull.PNG?raw=true "Example of rug pull")

#### How to detect it:
This is quite hard and could also be very unexpected to happen. First what can be done is to check the validity and trustworthiness of the project and team behind it, always check for a good whitepaper, the existence of a website, social media, company or team history and so on. If the projects seems a bit shady, be very very wary of what you're dealing with as you could lose everything.

### 4. Fake airdrops/giveaways
#### Method:

The scammers will make a website that impersonates a specific project or that promises great amounts of crypto but that will lead to requests of crypto or of private data. In these types of scams, the perpetrators will ask the victims to submit their wallets private key claiming that they need it to give them the crypto; in other instances they will ask for crypto to be sent to their wallets 
claiming that they need it to send the free crypto back (which they won't send of course). This can lead to entire wallets being emptied or rendered compromised.

#### How to detect it:
Fairly easy to. First of all, NO ONE will ever need to ask you for your wallet private key because of legitimate reasons. Second of all, You absolutely need to be sure that the airdrop/website is absolutely affiliated or related to the actual project they claim to be part of. Most importantly never also send any sort of crypto to people you do not trust.

### 5. Mass minting
#### Method:

The scammers will use a common function in many ERC-20 token that consists in the mint function. It allows more tokens to be minted  (the counterpart of this is burning, essentially deleting the tokens) for various purposes. Scammers could use this to mint extremely large amounts of their tokens and sell them all, making the price fall and the tokeen to be rendered useless. This function is made to be 
accessible only to the owners and creators of the tokens.

#### How to detect it:
Similarly to point 3, this cannot be easily detected. It all comes behind trusting the team and the project.

### 6. Hacked Token
#### Method:

Sometimes it could happen that the cryptocurrency you're dealing with has a legit team behind it.. but that coded it with some flaws that lead to exploitation by hackers who'll use them to completely drain all sort of liquidity or value from the currency.
A notorious example is the recent hacking of the COVER protocol, where the hackers exploited the contract by printing an infinite amount of tokens which they sold immediately after , leading to the price to completely plummet and the currency to be rendered unusable.
![image](https://github.com/TokenWRATH/wrathERC20token/blob/main/_images/COVER_hacking.PNG?raw=true "COVER protocol")

#### How to detect it:
There is no way this can be detected unless someone finds the flaw before and, if possible, fixes it.


### Conclusion:
Thank you for reading this post. $WRATH tries to be a completely trustworthy transparent token and so the project also tries to raise awareness on scams. For any inquiries be free to contact us on Twitter @TokenWRATH .
