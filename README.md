# Rivalz_AI_Node
Rivalz Node CLI Installation Script

## First step

Create an account here : https://rivalz.ai?r=Chan_cr08

## Requirements

Ensure your system meets the following requirements:

- RAM 4GB

- 4 Cores (2.2GHz)

- 50GB SSD

- 1Mbps Internet

- Ubuntu operating system

## Installation

Follow these steps to install and run the Rivalz Node CLI using the provided script.

```
sudo apt-get update && sudo apt-get upgrade -y
```

Install Curl : 
```
sudo apt install -y curl
```

Install Node.js 20 

```
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
```
```
sudo apt install -y nodejs
```
```
node --version
```

Open Screen : 
```
screen -S rivalz
```

Install Rivalz : 
```
npm i -g rivalz-node-cli
```

Run rClient : 
```
rivalz run
```

Your Connected Rivalz Wallet Adress : your linked account address in the account creation process

CPU Core (Choose between 2-5)

RAM ( choose between 3 - 5)

Disk Type (press enter)

Disk Serial Number ( press enter ) 


Enter disk size, you want to allow the client use ( for 400gb vps - enter between 50 to 150)


## Quit Screen:

### CTRL + A + D


After setting up your node, do not forget to press the validate button on the site.

https://rivalz.ai/dashboard/node-validate


Update Rivalz node

```
rivalz update-version
```
```
rivalz run
```

