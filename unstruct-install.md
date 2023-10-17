## Download the install script (bash)
[Download the script here](https://github.com/unstructai/unincident/blob/master/docker/deploy_unstruct.sh)

## Make it an executable 
```bash
chmod +x deploy_unstruct.sh 
```

## Run the Script and follow the instructions 
```bash
./deploy_unstruct.sh install
```

> **Note**: You will need to run the script as sudo on Linux based machines. 

## Prerequisites
The install works well, for example, on a MacBook Pro with the following specs. We've tested this on i5 chips, and installation can be a bit of a challenge:

- **Model Name:** MacBook Pro
- **Model Identifier:** MacBookPro16,1
- **Processor Name:** 6-Core Intel Core i7
- **Processor Speed:** 2.6 GHz
- **Number of Processors:** 1
- **Total Number of Cores:** 6
- **L2 Cache (per Core):** 256 KB
- **L3 Cache:** 12 MB
- **Hyper-Threading Technology:** Enabled
- **Memory:** 16 GB

> **Note:** The system will become slow when the containers are being restarted and the app is loading up the code into the RAM. Once caches warm up, you should be good. 

On a Linux VM (tested on GCP) with the specs below, the install is much snappier. No slowness is experienced:

- **Machine Type:** c2-standard-4 
- **Memory:** 16GB RAM 
- **CPU:** 4 vCPU, 2 cores. 

## Post Install 
Follow the instructions on the prompt to access all the four applications.

## Questions? 
Please open a new discussion here: [UnStruct.AI Discussions](https://github.com/orgs/unstructai/discussions)
