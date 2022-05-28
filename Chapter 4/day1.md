### 1. Explain what lives inside of an account. 
Contract code and account storage live inside of an account.

### 2. What is the difference between the `/storage/`, `/public/`, and `/private/` paths?
- `/storage/` - all data lives here and only account owner can access it & Owner can every access it
- `/public/` - available to everyone & Owner can place things in
- `/private/` - available to account owner & people the account owner give access & Owner can place things in

### 3. What does `.save()` do? What does `.load()` do? What does `.borrow()` do?
- `.save()`- Save to account
- `.load()` - Take data out of account storage
- `.borrow()` - Allows you view something in your account

### 4. Explain why we couldn't save something to our account storage inside of a script.
Access to an account requires `AuthAccount` which is only allowed with prepare which is apart of a transaction.

### 5. Explain why I couldn't save something to your account.
Only the account owner will have the appropriate access to save to their account.

### 6. Define a contract that returns a resource that has at least 1 field in it. Then, write 2 transactions:
![Quest_Chapter_4.d1_contract.JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest_Chapter_4.d1_contract.JPG)

####    1) A transaction that first saves the resource to account storage, then loads it out of account storage, logs a field inside the resource, and destroys it.
![Quest_Chapter_4.d1_transaction(1).JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest_Chapter_4.d1_transaction(1).JPG)

####    2) A transaction that first saves the resource to account storage, then borrows a reference to it, and logs a field inside the resource.
![Quest_Chapter_4.d1_transaction(2).JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest_Chapter_4.d1_transaction(2).JPG)
