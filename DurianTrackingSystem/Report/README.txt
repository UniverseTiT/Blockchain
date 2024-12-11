==================================================================================
BMIS2003 Blockchain Application Development
==================================================================================
Durian Tracking System
==================================================================================
Team Members:
--------------
1) Lim Weng Ni
2) Ong Yee Yung
3) Tan Chee Fung
4) Chiew Chin Chong
5) Loh Jian Wei

==================================================================================
Software Installation Requirement
==================================================================================
1) Ganache
Download Link: https://www.trufflesuite.com/ganache

2) Visual Studio Code
Download Link: https://code.visualstudio.com/

3) Metamask
Download Link: https://metamask.io/

4) Remix
Download Link: https://remix.ethereum.org/

5) Node.js
Download Link: https://nodejs.org/en/download/
==================================================================================

==================================================================================
Configuration Instructions
==================================================================================
-------------
Setup Ganache
-------------
1) Install Ganache
2) Open Ganache
3) Copy 12 phrase under MNEMONIC

--------------
Setup Metamask
--------------
1) Install Metamask
2) Click Import Existing Wallet
3) Paste the 12 phrase copy from Ganache
4) Click Comfirm
5) Create Password
6) Click Next and Confirm
7) Add Ganache network
8) Switch to Ganache network

-----------
Setup Remix
-----------
1) Open Remix in browser
2) Upload smart contract .sol file
3) Change compiler version to less than 0.8.15 and more than 0.8.0
4) Click on Environment
5) Click Customize this list...
6) Search and select "Ganache"
7) Change to Dev - Ganache Provider
8) Deploy the uploaded smart contract

------------------------
Setup Visual Studio Code
------------------------
1) Install Visual Studio Code
2) Open project folder
3) Copy ABI form remix and paste in action.js ABI field
4) Copy smart contract address and paste in action.js address field
5) Open terminal
6) Navigate to current directory
7) Type "node server.js"
8) Go to browser and type "http://127.0.0.1:5003"