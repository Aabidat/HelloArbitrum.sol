1.I opened Remix IDE and and I navigated to the file eplorer on the interface and opened an existing folder named "Arbitrum deployment" to get a work space. In the folder I created 3 solidity file also called "storagefactory. sol,AdvancedStorage.sol, ConflictExamlple.sol" to write my smart contract there. 2.I started writing my smart contract by adding a licence identifier and then wrote the compiler directive version which will be used to compile my code. After that I defined my contracts respectively as I stated a variable uint256 favoriteNumber for the AdvancedStorage.sol and the  storagefactory.sol and used the import function which gave it the ability to deploy instances of another contract and also pulls in code from that contract. Again I made it public for others have access to it.For the ConflictExamlple.sol three functions where written which where the parent1,parent2 and the child function in order to reduce conflict the child function inherits and overrides the parents function.

Compiling my contract
I selected the solidity compiler from the sidebar and I made sure that the compiler version matches the one specicified in my solidity file and I clicked on compile i saw a green checkmark on the solidity compiler which indicates that it was nothing wrong with my smart contract.

Deploying my contract
I navigated to the "Deploy & Run Transactions" tab and selected injected Web3(MetaMask) and deployed 'storage factory'clicked on deploy I tested the contact by entering values into the contract functions and observed it's response. I tested data retrieval and updates on the Arbitrum Seploia Testnet.

My challenges 
My test and data retrieval from Arbitrum Sepolia Test etc was not successful.
