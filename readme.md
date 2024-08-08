# D-Monitize

## Introduction
D-Monitize is a TypeScript project aimed at bridging the gap between companies seeking alternative data sources and individuals looking to monetize their personal information. The primary purpose of the project is to create a secure, decentralized data marketplace where data seekers can specify their needs and users can contribute relevant personal data to a collective pool. This pool becomes a rich source of nuanced insights, enhancing the predictive abilities of AI models at scale while ensuring fair compensation and privacy protection for participants.

## Features
Currently, the project offers the following key features:

* Secure and decentralized data transactions
* Fair compensation for data providers
* Encryption to protect privacy
* Automated data fetching and encryption process
* Integration with IPFS for secure data storage and access

## Installation
To install the project, follow these steps:

1. Clone the repository using `git clone https://github.com/fenilmodi00/D-Monitize`
2. Install the required dependencies by running `npm install`
3. Run the project using `npm start`

## Usage
To use the project, follow these examples:

* **Purchasers**: Create Data Listings detailing their desired data.
* **Providers**: Sell their data by sending encrypted API Data keys to the Listing contract.

### Workflow
1. The DataListing contract decrypts the provider's API key using a Functions script.
2. It fetches the provider's API data and encrypts it with the purchaser's key.
3. The encrypted data is posted to IPFS for the purchaser to access.

This workflow ensures providers share access without exposing their API keys, and purchasers can only view the data they purchased. The entire transaction happens securely on-chain.

## Contributing
Contributions to the project are welcome. To contribute, please follow these steps:

1. Fork the repository
2. Create a new branch for your changes
3. Make the necessary changes and commit them
4. Submit a pull request for review

## License
The D-Monitize project is licensed under the MIT License.

## Contact Information
If you have any questions or need assistance, you can reach out to the author at:

* Email: [fenilmodi00@gmail.com](mailto:fenilmodi00@gmail.com)
* Twitter: [@fenilmodi00](https://twitter.com/fenilmodi00)
* LinkedIn: [linkedin.com/in/fenilmodi00](https://linkedin.com/in/fenilmodi00)

## Badges

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub last commit](https://img.shields.io/github/last-commit/fenilmodi00/D-Monitize)](https://github.com/fenilmodi00/D-Monitize/commits)
[![GitHub issues](https://img.shields.io/github/issues/fenilmodi00/D-Monitize)](https://github.com/fenilmodi00/D-Monitize/issues)
[![GitHub forks](https://img.shields.io/github/forks/fenilmodi00/D-Monitize)](https://github.com/fenilmodi00/D-Monitize/network/members)
[![GitHub stars](https://img.shields.io/github/stars/fenilmodi00/D-Monitize)](https://github.com/fenilmodi00/D-Monitize/stargazers)
[![Language](https://img.shields.io/badge/Language-TypeScript-blue)](https://www.typescriptlang.org/)

Note: The badges may need to be updated based on the actual repository data.