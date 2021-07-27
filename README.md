# soloNFT
soloNFT is single NFT where data can be added for multiple addresses

This is meant for Swarm network and not IPFS

### Instantiate Contract
'constructor (string memory name_, string memory symbol_)' to create NFT collection of 1

### Call createReferenceFor
'creteReferenceFor(address to, bytes32 metadataSwarmLocation, bytes32 tokenDataSwarmLocation)'
(only owner can add and override this) 

This collection is a 1/1 with many references(meta,data) binded to addresses can be written to. 
