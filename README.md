# ERC115_NFTs_Smart_contract
Multi token standard 

A standard interface for contracts that manage multiple token types. A single deployed contract may include any combination of fungible tokens, non-fungible tokens or other configurations (e.g. semi-fungible tokens).

## ERC1155 vs ERC721
The distinctive feature of ERC1155 is that it uses a single smart contract to represent multiple tokens at once. This is why its *balanceOf* function differs from ERC20’s and ERC777’s: it has an additional id argument for the identifier of the token that you want to query the balance of.


