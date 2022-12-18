# Land_Management_System
Land management System using ipython
ipython pip Working of the BlockChain:

A block contains:
Block Index
Hash value of the previous block 4)Nonce
TimeStamp
Name of the buyer
Name of the seller
Merkle root The difficulty level of the block: A valid hash using SHA256 should have four leading zeros. During verification, two constraints are checked for the validity of blockchain:
If the buyer and seller are already registered in the system.
Seller needs to be the latest owner of the land which he is selling. Commands for running the code:
1)ipython 
2)import filename(blockchain)
3)bc=blockchain.blockchain() 
4)bc.mine_a_block("Name of the owner",Id of the land) in order to register a user with a property
5)bc.mine_a_transaction("Name of the seller","Name of the buyer",id of the property) in order to perform the operation
6)bc.view_transaction(Id of the property) Viewing the transaction history of the property
