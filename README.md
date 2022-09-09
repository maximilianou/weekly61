# weekly61

### Environment: local virtual environment 2022

#### First! Virtual Environment to work every day

> *Virtual Environment* help us be out of dependencies
> I mean dependencies from hour local environment for personal use of computer

> *Independent environment* just for the *sanity of the project*, and the others projects

> Clone Base System: Just after create a Simple Operating System Installation ( with or without GUI Desktop )
> Why Clone ? Because I need to check when I have added extra dependencies, or try new things fast.

> Docker: Clearly the end app must be in an environment like Docker, kubernetes, or simple local run docker as utility. Isolation of the environment ( versions of software like.. py2 py3, nodejs14 nodejs15, debian, alpine, libraries )


> ENV: Linux tools for Install to compile from Source Code any application
```tsx
# apt install build-essential linux-headers-amd64
```

> ENV: Download Virtual Box to install from source code, copiling it.
```tsx
https://download.virtualbox.org/virtualbox/6.1.38/VirtualBox-6.1.38-153438-Linux_amd64.run
```

> ENV: Change permision of the file, Executable +x
```tsx
# chmod +x VirtualBox-6.1.38-153438-Linux_amd64.run
```

> ENV: Execute the script that will download and compile from source code virtualbox
```
# ./VirtualBox-6.1.38-153438-Linux_amd64.run 
```

> ENV: Desktop Display config LXDE > Preferences > Monitor Settings > 1280x768 



```mermaid
stateDiagram-v2
    state Web3 {
        direction LR
        state Browser {
            direction LR
            MetaMask
            Brave
            MEW
        }
        Browser --> ENS
        Browser --> IPFS
        Browser --> Blockchain
    }
    state Blockchain {
        state BlockchainLocal {
            direction LR
            Hardhat
            Trufflesuite
        }
        state BlockchainL2 {
            direction LR
            Celo
            Polygon
        }
        state BlockchainL1 {
            direction LR
            EthereumMainnet
            EthereumTestnet
        }
    }
```

``` 
stateDiagram-v2
    state Web3 {
        direction LR
        state Browser {
            direction LR
            MetaMask
            Brave
            MEW
        }
        Browser --> ENS
        Browser --> IPFS
        Browser --> Blockchain
    }
    state Blockchain {
        state BlockchainLocal {
            direction LR
            Hardhat
            Trufflesuite
        }
        state BlockchainL2 {
            direction LR
            Celo
            Polygon
        }
        state BlockchainL1 {
            direction LR
            EthereumMainnet
            EthereumTestnet
        }
    }
```













