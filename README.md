# NFTCreation
Open Sea Testnet NFT Deployed Link : https://testnets.opensea.io/assets/sepolia/0x7FeFa47F564E087a9e27BFdF47ae62F26af484B2/1
## Overview
This project demonstrates the creation and deployment of ERC-721 NFTs on the Sepolia testnet. It comes with a smart contract for minting NFTs that can be tested and implemented with MetaMask and the Remix IDE.The NFTs' metadata is served through a Vercel-based API, allowing dynamic retrieval of NFT attributes. The project integrates with OpenSea's testnet to display the minted tokens.

## Key Components:

- Smart Contract: An ERC-721 contract (`MyToken.sol`) deployed on the Sepolia testnet.
- Metadata API: A Vercel-hosted API that returns metadata for NFTs based on token IDs, using data from `MetaData.json`.
- OpenSea Testnet: NFTs can be viewed on OpenSea's Sepolia testnet once minted.
- Testing: Smart contract is tested using `remix_tests.sol` to verify the name and symbol of the token.
