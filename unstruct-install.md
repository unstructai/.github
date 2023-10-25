# Unstruct.AI install. 
*All it takes is to execute one command. That's it!*

## 1. Download the install script (bash)

```bash
curl -LO https://raw.githubusercontent.com/unstructai/unincident/master/docker/deploy_unstruct.sh
```

## 2. Make it an executable 
```bash
chmod +x deploy_unstruct.sh 
```
> **Note**: This script can be in any DIR where you have write permissions and enough disk space for opensearch, postgres, etc. <br><br>

## 3. Run the Script and follow the instructions 
```bash
./deploy_unstruct.sh install
```

> **Note**: You will need to run the script as sudo on Linux based machines. <br><br>

## Prerequisites
1. Make sure you have docker installed.
2. MacBook Pro or similar with at least 6-Core Intel Core i7, 2.6 GHz, 16 GB RAM.
3. GCP c2-standard-4 type: 4 vCPU, 2 cores, 16G RAM, or similar.

> **Note:** The system might become slow on a less powerful box when the app is loading up the code into the RAM. Once caches warm up, you should be good. 

## Post Install 
Follow the instructions on the prompt to access all the four applications.

## Questions? 
Please open a new discussion here: [UnStruct.AI Discussions](https://github.com/orgs/unstructai/discussions)
