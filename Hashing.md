## Hashing

***Hashing in blockchain is a cryptographic process which takes an input (such as text) and turns it into an output of fixed length and structure known as the 'hash value'. It is always the same length and one-way, meaning it cannot be reversed.***

**use cases:-**
    
   ****Hashing is primarily used for security purposes, and specifically those in cybersecurity. Ahashed 
     value has many uses, but it’s primarily meant to encode a plaintext value so the enclosed 
    information can’t be exposed. The hashing process is non-reversible or extremely difficult to 
    decode, making it often used as a cryptography technique****

# Key Takeaways

- ***Hashing in blockchain is a cryptographic process used to generate digital fingerprints for secure transaction verification and password storage.***
- eg:--![image](https://github.com/Rjesh2006/Block_chain/assets/143868643/2f7bef4e-81c0-4789-a3af-544cd2783f35)

***Each “block” contains***
- Data of transactions
- A unique fingerprint for all the data - in the block called a hash
- A hash of the previous block’s data


image:-![image](https://github.com/Rjesh2006/Block_chain/assets/143868643/5f3d4aea-8ae3-403b-a808-e0e472984389)



***What do each of these items mean?***

*Data in the block usually consists of transactions. A block can contain hundreds of transactions. Alice sending Bob $100 is an example of a transaction in a block*



image:-![image](https://github.com/Rjesh2006/Block_chain/assets/143868643/df039020-a83a-4ff3-845f-a5530c60913f)



*A hash is a unique combination of letters and numbers. It is like a fingerprint for the data in a block and it is always unique to every block in the Blockchain. When the data in a block changes, the hash will also change.*



image:-![image](https://github.com/Rjesh2006/Block_chain/assets/143868643/d263ebb7-ce72-4657-8062-ff1c95e7a0c3)



*Hence in a transaction, if the amount being sent Alice to Bob changes from $50 to $100, the hash of the block will completely change.*

*A block also contains the hash of the previous block. Hence forming a chain structure. Combining the above three together, this is what a Blockchain will look like*



image![image](https://github.com/Rjesh2006/Block_chain/assets/143868643/cffdef54-8fff-4514-9534-8725d618e61c)




- ***Hash functions are essential components of the Proof of Work consensus algorithm, providing security and stability to blockchain networks.***




- ***Bitcoin’s energy intensive mining has raised concerns about its environmental impact while Ethereum’s move to a Proof of Stake consensus leads to reduced energy consumption with lower carbon footprint.***




***Understanding Hashing in Blockchain
Hashing in blockchain implies the transformation of input data into a fixed size output through a specific algorithm. It establishes data integrity***

![image](https://github.com/Rjesh2006/Block_chain/assets/143868643/abda5d20-9fc1-4ae8-8831-d632d45098ad)


     

     Sources :[Hackernoon.com](https://hackernoon.imgix.net/hn-images/1*RYul-eUCR7irpT98XrylLg.png)
