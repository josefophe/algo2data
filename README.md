# Algo2Data

## Summary
Algorand Web/Mobile Wallet Interface Using Reach and React to Connect to My Algo Wallet for Airtime and Data P2P market place
![cover](https://user-images.githubusercontent.com/23031920/142118845-f9b4ac55-7287-4379-b20f-f7c7b4cfb47d.png)

## Team name: Team Awesome

## Member 
Joseph Ebin and Blessing Ebin

## Project Overview

Algo2Aritime/Algo2Data is a solution that helps bring crypto to a mass exposure to smartphone users in Africa as data is one important factor every smartphone users consume therefore having an alternative to purchase it via algo tokens will bring mass adoption and exposure of the algorand blockchain users to the space. As the demand of data is increasing gradually adding this feature to the algo wallet will give room for non web3 users to adopt this technology as it will serve their need.

We are targeting the Africa communities starting with Nigeria as we can see the increasing trends of smartphone users and the growth of telecommunication industry in Nigeria.

## Problem Statement and solution

This project came as a result of demand for data comsumption according to the [report](https://punchng.com/telecoms-nigerias-data-usage-rises-by-202-in-three-years/#:~:text=Data%20usage%20in%20Nigeria%20surged,and%20205%2C880.4TB%20in%202020.) which shows how it has surge by about 200 % and still increasing as the world is going more digital by the day. Indeed there are existing methods of buying data and airtime on this device but with the use of blockchain and the power of its decentralisation it can be done better as it give every individual access to swap data or airtime for algo token and vice versa. This solution will serve in as a mini marketplace where algo2data and algo2airtime can be swap and traded easily and convinently without any centralised authority. 

## How it will be built

This will be web/mobile based wallet that users can easily connect to their algo account and view, transact their balance for airtime/data purchase. We will make use of this technologies algorand blockchain, wallet connector, reach-sh language, airtime/data API, React, Nodejs

Connecting to a wallet is one important requirements most DApp developers will have to integrate in their application when creating a DApp on the Algorand Blockchain. My Algo Wallet Connect with Reach, connecting to My Algo Wallet is part of the inbuilt integration in reach which provides a fallback to connect to the wallet. 

## My Algo Wallet Connect With Reach
- Using Reach to connect to the My Algo Wallet
- Checking of account information, like address and account balance
- Using Reach Faceut to fund account
- Transferring of Airtime and Data using Reach


# Setup Instructions
- clone the repository
- open a terminal cd to the reach-react folder
- From there run the command npm install
- once that has completed  cd src
- Run the `curl https://raw.githubusercontent.com/reach-sh/reach-lang/master/reach -o reach ; chmod +x reach` command to download reach into the src folder
- Run the ./reach version command to ensure it installed
- Run the REACH_CONNECTOR_MODE=ALGO ./reach devnet command to start the testnet
- Start up a new terminal and navigate to the reach-react folder
- Now run the npm start command to run the applications frontend
- Navigate to the localhost link given by the above command to view the application

## video link

[![Algo2Airtime](http://img.youtube.com/vi/CF6xEb1vlC8/0.jpg)](http://www.youtube.com/watch?v=CF6xEb1vlC8)






