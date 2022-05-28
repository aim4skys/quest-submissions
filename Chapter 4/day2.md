### 1. What does `.link()` do?
.link() is the syntax used to link resource to public so others can access it.
### 2. In your own words (no code), explain how we can use resource interfaces to only expose certain things to the `/public/` path.
We use resource interfaces to expose certain things to a /public/ path because it assists in restricting access.  Allowing only those items a person wants to share while protecting those items a person does not want to share.
### 3. Deploy a contract that contains a resource that implements a resource interface. Then, do the following:
![Quest_Chapter_4.d2_contract.JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest_Chapter_4.d2_contract.JPG)
####    1) In a transaction, save the resource to storage and link it to the public with the restrictive interface. 
![Quest_Chapter_4.d2_transaction.JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest_Chapter_4.d2_transaction.JPG)
####    2) Run a script that tries to access a non-exposed field in the resource interface, and see the error pop up.
![Quest_Chapter_4.d2_transaction(2).JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest_Chapter_4.d2_transaction(2).JPG)
####    3) Run the script and access something you CAN read from. Return it from the script.
![Quest_Chapter_4.d2_script.JPG](https://github.com/aim4skys/quest-submissions/blob/main/images/Quest_Chapter_4.d2_script.JPG)
