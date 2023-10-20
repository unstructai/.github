# Unstruct.AI install. 
*All it takes is to execute one command. That's it!*

## 1. Download the install script (bash)
[Download the script here](https://github.com/unstructai/unincident/blob/master/docker/deploy_unstruct.sh)

## 2. Make it an executable 
```bash
chmod +x deploy_unstruct.sh 
```

## 3. Run the Script and follow the instructions 
```bash
./deploy_unstruct.sh install
```

> **Note**: You will need to run the script as sudo on Linux based machines. <br><br>

## Prerequisites
The install works well, for example, on a MacBook Pro with the following specs. 

- **Model Name:** MacBook Pro
- **Processor Name:** 6-Core Intel Core i7
- **Processor Speed:** 2.6 GHz
- **Total Number of Cores:** 6
- **Memory:** 16 GB

We've tested this on MacBook with i5 chips, and installation was a challenge, and may not complete.

> **Note:** The system will become slow when the containers are being restarted and the app is loading up the code into the RAM. Once caches warm up, you should be good. 

On a Linux VM (tested on GCP) with the specs below, the install is much snappier. No slowness is experienced:

- **Machine Type:** c2-standard-4 
- **Memory:** 16GB RAM 
- **CPU:** 4 vCPU, 2 cores. 

## Post Install 
Follow the instructions on the prompt to access all the four applications.

## Questions? 
Please open a new discussion here: [UnStruct.AI Discussions](https://github.com/orgs/unstructai/discussions)
