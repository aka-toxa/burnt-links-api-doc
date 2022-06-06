# Burnt links API

The Links API microservice is a service that provides intermediate storage for the links to the uploaded images and jsons of future nft to ipfs/nft-storage/s3.

Using that links later we will be able to mint the actual NFT on any other service.

![general design diagram](./docs/burnt.drawio.png)

## Detailed design for Burnt UI interactions

![Burnt UI App interaction](./docs/create-nft.png)

## Detailed design for future mint service interaction

![Mint service interaction](./docs/mint-nft.png)

## Service swagger definition:

[swagger.yaml](./docs/swagger.yaml)