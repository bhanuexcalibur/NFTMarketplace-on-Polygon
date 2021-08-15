# NFTMarketplace-on-Polygon

This is a NFT marketplace on Polygon
I have used Infura for the network, IPFS for the storage, NextJs just for little bit frontend.
In this the main focuse was on the backend and how the contracts work during exeuction


To use it locally on your desktop 
You need hardhat, node modules, waffle, ether and few other dependencies.



You need to also add the secret phrase in the .secret file as i have cleared it
Note - Do not share the secret phrase of wallet to anyone.

In the file "hardhat.config.js" you also need to configure the network using your Infura Id. Well 
i have kept that default from the network only but you can change it to infura.

Run first 
    npm install 

Then start local hardhat node
to do that run
    npx hardhat node

Now deploy the contracts in a local network with separate terminal
For that you need to run
    npx hardhat run scripts/deploy.js --network localhost

Now start the app
    npm run dev
