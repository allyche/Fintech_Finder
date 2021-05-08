# Module 18  Fintech Finder

As Fintech Finder’s lead developer, I have been tasked with integrating the Ethereum blockchain network into the application in order to enable our customers to instantly pay the fintech professionals whom they hire with cryptocurrency. In this Challenge, I will complete the code that enables ourcustomers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, I will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

## The following steps were carried out:
1. Generate a new Ethereum account instance by using your mnemonic seed phrase (which you created earlier in the module).

2. Fetch and display the account balance associated with your Ethereum account address.

3. Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

4. Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Kovan testnet.

5. Review the transaction hash code associated with the validated blockchain transaction.

## Python Library Imports
1. import os
2. import requests
3. from dotenv import load_dotenv
4. load_dotenv()
5. from bip44 import Wallet
6. from web3 import Account
7. from web3.auto.infura.kovan import w3
8. from web3 import middleware
9. from web3.gas_strategies.time_based import medium_gas_price_strategy
10. import streamlit as st
11. from dataclasses import dataclass
12. from typing import Any, List

## Results

* Screenshot with sender's address balance and history from Etherscan
https://github.com/allyche/Fintech_Finder/blob/main/etherscan.jpg
  
* Screenshot with all transaction details on Etherscan
https://github.com/allyche/Fintech_Finder/blob/main/transaction.jpg

* Screenshot with recipient's address, balance & history on Etherscan
https://github.com/allyche/Fintech_Finder/blob/main/recipient.jpg

## Author
ally.che@gmail.com