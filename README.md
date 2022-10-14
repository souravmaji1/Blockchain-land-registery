

## Technology Stack:
1. Ethereum Blockchain
2. Polygon/Matic
3. Web3Dart
4. IPFS
5. Flutter
6. Metamask



This is demo purpose. You can login as Land Inspector using this key:
 <pre><b>6b86cddfedbec68ed2a1c7e14b993840a0848595ba5787aec9e8a38b18f0d96a</b></pre>
For user: <pre><b>3ed4aff1a8ff8e28df3cd307112f9166886edcc85a27136908e3b1687b111f89</b></pre>\
For user you can also use your own Ethereum wallet key

#### Check Smart contract At Ropsten Ethereum Testnet: [here](https://ropsten.etherscan.io/address/0x702058ba021cd4e4f847b40f32b58aa5be3a4661)

## Run Application Locally
1.Clone the github repository and cd to the folder\
2.Install flutter,nodejs\

* use flutter version 2.10.5 *

3.Install ganache and truffle
```
npm install -g truffle
```
4.Open Ganache and keep it running in the Background\
5.Install Metamask chrome extension,choose local network and import accounts\
6.Compile and run our migrations from the command line like this
```
truffle compile
truffle migrate
```
6.Copy contract address paste in ./lib/constant/constant.dart - 'contractAddress'\
<pre>
2_deploy_migration.js
=====================

   Replacing 'Land'
   ----------------
   > transaction hash:    0x427b2b402f767ac6a90334ab3c687b086b274de747fe10d6e194743b15057d78
   > Blocks: 0            Seconds: 0
   <b>>contract address:    0xed690C24C60A48F8A9819c9A15AD75B70CFBEa5a</b>
   > block number:        3
   > block timestamp:     1650602828
   > account:             0x33e94e4619f0AecDf81e9676Eb82c109FBa53356
   > balance:             99.9154895
   > gas used:            3996227
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.07992454 ETH
</pre>
7.In constant.dart file Change chainId to '1337' and change 'rpcUrl' to "http://127.0.0.1:7545" \
8.Run flutter web app
```
flutter pub get

flutter run -d web-server --web-port 5555
```
9.Open the browser and the dapp will be running in http://localhost:5555/
10.Create mapbox api key from https://www.mapbox.com/ and Replace it with 'mapBoxApiKey' constant.dart file\
11.Create nftstorage api key from https://nft.storage/ and replace it.\
<<<<<<< HEAD
=======



Important :

If you are unable to deploy smart contract using truffle then just follow the below steps

1. go to remix ide by searching on google
2. create a "example.sol" file and paste the (land smart contract ) code over there
3. select the injected web3 option before deploying 
4. choose any test network like polygon mumbai , goerli 
5. then click on the deploy button to deploy the smart contract 
6. copy the smart contract address 
7. paste the smart contract address in the "lib/constants/constant.dart 

contract address : "jdsjdnsjdsjd"

replace the rpc url with that test network you have deployed also change the chain id in which testnetwork you have deployed

That's all








