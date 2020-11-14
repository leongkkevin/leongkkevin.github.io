---
layout: page
title: Block Chain
permalink: /blockChainNetwork/
---
# Block Chain

This project was to create a simplified block chain network between three peers: Lyle School of Engineering, Cox Business School, and Meadows School of The Arts. The program uses object oriented programming and polymorphism in order to record detailed transactions between the peers in the network.

![Block Chain Diagram](/assets/blockChainDiag.png) 

As shown in the diagram, each school has their own ledger filled with transactions that occured between each school. Every transaction was either a cash, check or credit card transaction - each with its own randomly generated ID and money amount. Each cash transaction noted the total money paid and the change returned. Each check transaction had a specific routing and account number. Each credit card transaction noted the card number, expiration date, and cvv. 

In order to create each ledger, I made a a <a href="https://github.com/leongkkevin/blockChain/blob/feedback/Peer.h">Peer Object</a> that held the ID, name, and a <a href="https://github.com/leongkkevin/blockChain/blob/feedback/LinkedList.h">linked list</a> of <a href="https://github.com/leongkkevin/blockChain/blob/feedback/Transaction.h">Transaction objects</a> that represented each peer's ledger. Each Transaction object created a randomly generated ID per transaction as well as recorded the sender ID, receiver ID, and amount paid. I also created a <a href="https://github.com/leongkkevin/blockChain/blob/feedback/Cash.h">Cash</a>, <a href="https://github.com/leongkkevin/blockChain/blob/feedback/Check.h">Check</a>, and <a href="https://github.com/leongkkevin/blockChain/blob/feedback/CreditCard.h">Credit Card</a> object that inherited from the Transaction object. Finally, I made a <a href="https://github.com/leongkkevin/blockChain/blob/feedback/Network.h">Network object</a> that contained a linked list of all ledgers in the network. This object was used to parse and process each transaction from the input file as well as display each ledger in the console.

<a href="https://github.com/leongkkevin/blockChain">*Click here for the full Github Repository*</a>

*Below is a sample console output for this <a href="https://github.com/leongkkevin/blockChain/blob/feedback/transactions.txt">input text file</a>:*

![Ledger Output](/assets/ledgerOut.png) 