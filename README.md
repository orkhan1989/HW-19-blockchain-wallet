# HW-19-blockchain-wallet

The first file that you will use is called fintech_finder.py. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.
The second file that you will use is called crypto_wallet.py. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file.
Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.
Specifically, you will assume the perspective of a Fintech Finder customer in order to do the following:


Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.


Fetch and display the account balance associated with your Ethereum account address.


Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.


Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.


Review the transaction hash code associated with the validated blockchain transaction.


Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that you have successfully created the transaction, you will save screenshots to the README.md file of your GitHub repository for this Challenge assignment.
