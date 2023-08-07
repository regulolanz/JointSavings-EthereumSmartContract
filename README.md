# Joint Savings Account
This repository contains a Solidity smart contract for a joint savings account, developed for a fictitious fintech startup. The contract allows two users to manage a joint savings account, enabling them to deposit and withdraw funds. The solidity smart contract uses ether management functions to implement the financial features.

## What's Inside?
The main feature of this repository is the Solidity contract `joint_savings.sol`, which allows the creation and management of a joint savings account.

## Instructions
The contract `JointSavings` was developed, compiled and deployed in the Remix VM (London) provided by the Remix IDE.

### Step 1: Create a Joint Savings Account Contract in Solidity
The contract was created according to the instructions in the starter code file `joint_savings.sol`.

### Step 2: Compile and Deploy Your Contract
The contract was compiled without any errors and was deployed successfully in the Remix VM (London).

### Step 3: Interact with Your Deployed Smart Contract
The deployed contract was interacted with in the following steps:

- The `setAccounts` function was used to define the authorized Ethereum addresses that will be able to withdraw funds from your contract. 

    ![Setting Accounts](./Execution_Results/setAccounts.png)

- The deposit functionality of the contract was tested by sending ether in the following transactions:

    - Transaction 1: Sent 1 ether as wei.
    
    ![Transaction 1](./Execution_Results/transaction1.png)

    - Transaction 2: Sent 10 ether as wei.

    ![Transaction 2](./Execution_Results/transaction2.png)

    - Transaction 3: Sent 5 ether.
    
    ![Transaction 3](./Execution_Results/transaction3.png)

- The contract’s withdrawal functionality was tested by withdrawing 5 ether into `accountOne` and 10 ether into `accountTwo`. The `contractBalance`, `lastToWithdraw` and `lastWithdrawAmount` functions were used to verify the transactions.

    - Withdrawal 1: 5 Ether from accountOne.

    ![Withdrawal 1](./Execution_Results/withdraw1.png)

    - Withdrawal 2: 10 Ether from accountTwo.

    ![Withdrawal 2](./Execution_Results/withdraw2.png)

## Conclusion
The `JointSavings` contract was successfully deployed and tested in the Remix VM (London). It demonstrated the expected functionality of a joint savings account, providing the ability to deposit and withdraw funds to and from the account. The ether management functions implemented in the contract worked well in reflecting the transactions on the account. The contract can be further developed and used as a basis for more complex joint account features for real-world fintech applications.


