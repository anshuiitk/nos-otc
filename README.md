<p align="center">
  <img src="./logo.png" width="150px" />
</p>

<h1 align="center">nos-otc</h1>

<p align="center">
  nos-otc is a <strong>nos dapp</strong> to facilitate a OTC like transaction on nos platform. A transaction requring asset transfer between two trading parties can be facilitated over this dapp.
</p>

<p align="center">
  <a href='https://www.npmjs.com/package/@nosplatform/create-nos-dapp'>
    <img src='https://badge.fury.io/js/%40nosplatform%2Fcreate-nos-dapp.svg'>
  </a>
  <a href='https://github.com/prettier/prettier'>
    <img src='https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat'>
  </a>
</p>

## Purpose
Lot of time we see that NEP-5 tokens are released but could not be traded. This is because either they are locked or not listed on any of the exchanges.

1. If they are locked then we cannot do much but to wait for the contract/company to unlock it before they can be used.
2. However if they are unlocked then we are under the mercy of exchanges to list them and then on begin trading.

This is also a problem where lot of new start-ups don’t want to on board on NEP-5 tokens because they fear listing and negotiations with limited exchanges.
Even decentralized exchanges such as switcheo are controlled when it comes to listing.

Similar was the case of APEX (CPX) tokens when they were visible in the wallets but could not be traded because of the lack of listing on an exchange. We all know the infamous story about it getting listed on switcheo before lbank when lbank was suppose to be the strategic launch platform.

But, even before APEX was listed it was transferable. No one could trade because of the lack of trusted buyers and sellers (Which an exchange provides). Many telegram groups and pools have members which can trust each other and contact. They can exchange tokens only if they knew the exchange of assets could be escrowed to ensure transaction success. The escrow will help develop trust.

nos-otc fills in the gap to establish that trust and provide an escrow facility which can last as long as the buyer and sellers agree. The escrow facility will expire if the participating parties do not honour the asset exchange. The expiry time is pre agreed while creating the otc trade.

## Installation
To run your dApp, execute:
1. 'cd nos-otc'
2. 'npm start' or 'yarn start'
3. Open the nOS client at nos://localhost:1234
