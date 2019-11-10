mempool is the storage place for all trancation before they are added to the blockchain 
transactions leave the memory pool when a miner has validaed it and added it to a block

ways a transaction leaves the mempool: 
* the transaction expires by timeout
* transation was located at the bottom of the mempool and was deprioritized due to transaction fees 
* transation was included in a block 
* transation or one of its unconfirmed ancestors conflicts with a transaction that was included in a block  

