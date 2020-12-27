# Algorand-transactions-from-excel
This tutorial demonstrates how to execute different Algorand transactions from an imported excel sheet. Three transaction types are covered. First, is a pay transaction in Algorand. Second is a closToRemainder transaction, which transfers all the assets from one account to the other. The last is created Algorand standard assets from the sheet. The sheet is formatted with all these details. A set of conditions are used to check the type of transactions that will be performed based on a set of parameters.
# Requirements
1. Algorand Javascript SDK which can be downloaded here
2. Development environment for javascript. My set up is run on [Xampp](https://www.apachefriends.org/download.html)  but Wamp works as well. 
3. Algorand accounts loaded with faux tokens from the [testnet dispenser](https://bank.testnet.algorand.network/)
4. The [AlgoExplorerapi](https://testnet.algoexplorer.io/api-dev/v2) for getting and posting transactions to Algorand.  
5. Javascript excel reader, which is referenced in the header.

# Overview
Sometimes an organization may want to perform multiple transactions to different accounts. Performing these transactions one at a time could be time consuming. This tutorial demonstrates how this can be automated from an updated excel sheet. A master account which owns the assets performs the transactions. For security reasons, the asset balance can be transferred to a new account after performing the bulk transactions. Pay transaction, closToRemainder transaction and asset creation have been demonstrated. But the principle can be applied to rekying and bidding once you set the right conditions in the excel sheet. A sample excel sheet has been created to with the headers and accepted parameters. These can be changed to suite your unique coding needs. A simple html/javascript has been used to demonstrate this.
