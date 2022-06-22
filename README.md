# ERC1155-721-Fractional-Assets
A contract that allows your holders of an ERC721 token to mint ERC1155 tokens with some extra features.

This contract will allow your holders of an ERC721 token to mint an ERC1155 token that you create within the contract. 

There is a createAsset function that allows you to create new assets as your collection expands. You just simply put a value in, and then you can in return update your baseURI with that image number and corresponding json. 

The mintBatch function allows you to mint several tokens of the asset you just created for a ridiculous low value, when we deployed this contract - we minted 1000 tokens for about $2.43. We used this functions to airdrop the tokens to our holders. 

The mint function that is inside the contract allows holders of a certain contract address to be the only people that mint that amount. You can also set the amount to how many you want holders to mint, and you can also change the corresponding ERC721 address for any types of collabs. 

This contract is extremely gas optimized as well for holders to mint, batch mints for owners, and also airdrops.

This contract was written by devCarl.eth (@stocksmenCarl) for BRAQ FRNDS (@braq_io)
