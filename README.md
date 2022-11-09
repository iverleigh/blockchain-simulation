# blockchain-simulation
This is a very simplified implementation of a blockchain written in Python. <br>
Blockchains are secured by consensus algorithms, in this case I have shown how Proof-of-Work (PoW) works.
In the blockchain, every block's data is hashed and used as an input in the next block. This means that every block in the chain is linked to the previous block.
Any change in the data points to a different hash, so it is computationally infeasible to try to reverse engineer data given a hash string. The way PoW works is that the computer is changing an element of the block (called a nonce) and recomputing a hash that meets the requirements of the consensus algorithm.<br> 
You can change the difficulty of the algorithm in the code and see that as you increase the difficulty, the time and computational power it takes to verify the blocks increases. <br> 
When you run this code, you can try to modify the data that is already mined in the chain, but it will return as invalid and every single block succeeding the modified block will also be deemed invalid.
