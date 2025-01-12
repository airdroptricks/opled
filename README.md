# OPEN LEDGER BOT 

![banner](image.png)


- Website [https://openledger.xyz](https://testnet.openledger.xyz/?referral_code=eedgd534zu)
- Twitter [@OpenledgerHQ](https://x.com/OpenledgerHQ)


## Features

- **Auto Send Heartbeat**
- **Auto Connect/Reconnect Nodes**
- **Auto Claim Daily Rewards**
- **Support Multiple Accounts**
- **Support Proxy Usage (http/socks)**

## Requirements
- **Register**: [https://testnet.openledger.xyz/](https://testnet.openledger.xyz/?referral_code=eedgd534zu)
- **Node.js**: Ensure you have Node.js installed.
- **npm**: Ensure you have npm installed.

- **Wallets from open-ledger account**: how to get ???
- **Go To dashboard** [https://openledger.xyz](https://testnet.openledger.xyz/?referral_code=eedgd534zu) and copy your wallet, look at image below:

   ![wallet](image-1.png)



1. Clone this repository:
   ```bash
   git clone https://github.com/airdroptricks/opled.git
   cd opled
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Setup: paste you wallet to `wallets.txt` file 1 address per line.
   ```bash
   nano wallets.txt
   ```

4. Optionally use proxy: paste proxy in the proxy.txt file. 1 proxy per line.
- "It is recommended to use a proxy if you are running multiple accounts."
    ```bash
    nano proxy.txt
    ```
    format : `protocol://user:password@ip:port`   | or | `protocol://ip:port`


5. Run The Script:
   ```bash
   npm run start
   ```

## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is licensed under the [MIT License](LICENSE).
