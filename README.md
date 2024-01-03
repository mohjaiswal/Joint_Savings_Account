# Solidity Smart Contract

![Solidity Smart Contract Header](headerjoint.png)

The "Solidity Smart Contract" project is dedicated to developing smart contracts to automate financial processes in institutions, particularly focusing on creating joint savings accounts using blockchain technology.

## Project Overview

Our initiative involves automating the creation of joint savings accounts through a Solidity smart contract. This contract allows two users to control a joint savings account, implementing ether management functions to meet various financial requirements.

## Key Steps in the Smart Contract

1. **Local Blockchain Development:** Utilizing the JavaScript VM in Remix IDE.
2. **JointSavings Contract:** Scripting and deploying a **JointSavings** smart contract.
3. **Contract Interaction:** Managing fund transfers and withdrawals through the deployed contract.

## Set Up for Test Run

We set up the contract using the `setAccounts` function, specifying authorized Ethereum addresses:

- Dummy Account 1: `0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb`
- Dummy Account 2: `0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0`

![Initialized Contract](Execution_Results/Initialized.png)

## Transactions

Testing the contract involved depositing 50 ether and conducting withdrawals:

- **Transaction 1:** Withdrawal of 1 ether to `accountOne`.
- **Transaction 2:** Withdrawal of 10 ether to `accountTwo`.
- **Transaction 3:** Withdrawal of 5 ether to `accountOne`.

After each transaction, we verified the contract balance and the details of the withdrawals.

![Transaction 1](Execution_Results/Transaction1.png)
![Transaction 2](Execution_Results/Transaction2.png)
![Transaction 3](Execution_Results/Transaction3.png)

## Error Handling

Our smart contract includes robust error handling:

- **Insufficient Funds:** Ensuring balance sufficiency for withdrawals.

  ![Insufficient Funds Error](Execution_Results/Error1.png)

- **Account Ownership Check:** Verifying the recipient's ownership of the account.

  ![Account Ownership Error](Execution_Results/Error2.png)

## Conclusion

The "Solidity Smart Contract" project represents a significant advancement in automating financial processes using blockchain technology. Our successful implementation of a joint savings account smart contract showcases the potential for further innovations in this space.

## Legal Disclaimer

### This analysis is for educational and research purposes only and should not be construed as financial or investment advice. The creator of this repository bears no liability for actions based on this information.

---

[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)](https://github.com/SoliditySmartContract/Project)
