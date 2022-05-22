### 1. Explain why we wouldn't call `changeGreeting` in a script.
`changeGreeting` requires a change, just like the name implies, to be made within the blockchain and any changes within the blockchain are made through transactions and not scripts, which only allow you to view data.

### 2. What does the `AuthAccount` mean in the `prepare` phase of the transaction?
`AuthAccount` in the prepare `phase` of a transaction means to access the information/data in your account.

### 3. What is the difference between the `prepare` phase and the `execute` phase in the transaction?
In a transaction, the difference between `prepare` and `execute` is; prepare accesses account information and execute calls functions to change data on the blockchain.

### 4. Add two new things inside your contract:
   ####   (1) A variable named `myNumber` that has type `Int` (set it to 0 when the contract is deployed)
   ####   (2) A function named `updateMyNumber` that takes in a new number named `newNumber` as a parameter that has type `Int` and updates `myNumber` to be `newNumber`
  ![Quest%20Chapter%202.d2%20contract.JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest%20Chapter%202.d2%20contract.JPG)
### Add a script that reads `myNumber` from the contract.
  ![Quest%20Chapter%202.d2%20script.JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest%20Chapter%202.d2%20script.JPG)

### Add a transaction that takes in a parameter named `myNewNumber` and passes it into the `updateMyNumber` function. 
  ![Quest%20Chapter%202.d2%20transaction.JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest%20Chapter%202.d2%20transaction.JPG)
### Verify that your number changed by running the script again.
  ![Quest%20Chapter%202.d2%20script%20new%20number.JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest%20Chapter%202.d2%20script%20new%20number.JPG)
