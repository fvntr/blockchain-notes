a block contains: 

* previous block hash
    * hash value for the block that comes before the chain 
* timestamp 
    * when the block was made 
* merckle root 
    * single hash value that represents every transaction that happens in the block
* nonce 
    * arbitrary number that can only be used once used to generate hash value 

block data + nonce = hash value 

Attributes: 
* block difficulty: the number of zeros required to figure out nonce 
* block size: the amount of information that fits in a block, defined by specs 
* hash value: unique fingerprint used to identify block 

