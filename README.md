# blockchain

<details><summary>Prerequisites for Executing the Application</summary>
<p>

### Metamask

  1.Install Metamask extension and create your wallet
  2.Get Ropsten Test Ether
  3.Update your account in .env file
       
### 

### Remix IDE
    
 1.Edit the name and symbol of token on line 166
  ```js
    constructor() {
        _name = "x20246935";
        _symbol = "DC";
        
        _mint(msg.sender, 1000000000000000000000000);
    }
```
 2.Compile and deploy DeployedContract.sol on Remix IDE
 3.Update the contract address in .env file
       
### 
  
### Infura

 1.Register and create a new project on infura.
 2.Update infura token for ropsten endpoint in .env file.
       
### 
 
</p>
</details>

<details><summary>Execution of Code Without Docker</summary>
<p>

## Install Dependencies
     
    npm i big-number fs dotenv ethereumjs-tx web3

## Initialize package.json
     npm init
## Execute distribute.js
     node distribute.js
 
</p>
</details>

<details><summary>Execution of Code Without Docker</summary>
<p>

## Pull the docker image from docker hub
     docker pull kamalnyadav/x20246935-myproject:blockchain


## Run the docker image
     docker run -p 49160:8080 -d x20246935-myproject
     
## Check the docker processes running
     docker ps
## Check the log
     docker logs <your machines docker process-id>
</p>
</details>
