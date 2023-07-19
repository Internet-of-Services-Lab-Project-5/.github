# Internet of Services Lab - Project 5: Privacy-aware Unruly Passenger Identification (TU Berlin SS23)

## About this project

Sharing unruly passenger lists with other airlines entails privacy concerns and competitive risks. We create an interface where airlines can enter the passengers' data to find out if they misbehaved in the past, in a way that the no-fly list owners don't see the data that was entered and the querying airline doesn't see the lists. We do this using a web app connected to the iExec framework, which supports blockchain, decentralized computing, and confidential computation in hardware-based Trusted Execution Environments (TEEs). With our approach, airlines get the added value of shared no-fly lists while preserving the confidentiality of passenger data in the process.

## Repositories
- [server (Node Server)](https://github.com/Internet-of-Services-Lab-Project-5/server "server")
- [client (React App)](https://github.com/Internet-of-Services-Lab-Project-5/client "client")
- [gramine-app (Gramine App)](https://github.com/Internet-of-Services-Lab-Project-5/gramine-app "gramine-app")
- [scone-app (Scone App)](https://github.com/Internet-of-Services-Lab-Project-5/scone-app "scone-app")
- [smart-contracts (Smart Contract)](https://github.com/Internet-of-Services-Lab-Project-5/smart-contracts "smart-contracts")
- [templates](https://github.com/Internet-of-Services-Lab-Project-5/templates "templates")
- [deploymentFiles](https://github.com/Internet-of-Services-Lab-Project-5/deploymentFiles "deploymentFiles")

## Architecture
![architecture graph](./profile/iosl_pupd_architecture.png)

## Setup instructions
1. Create **Wallets**
2. Deploy **Smart Contract**
3. Deploy the **Scone App**
4. Deploy the **Gramine App** and push app secrets to the SMS
5. Setup the **Database** for the Node Server
6. Setup **Node Server** with `.env` and `wallet.json` file
9. Setup **React App** with `.env` file


## Old Repository
To facilitate easy deployment on [Render](https://render.com/), we have migrated our repository to GitHub. Here is the old repository on the GitLab server of TU Berlin:
https://git.tu-berlin.de/liaafk/iosl-pupd
