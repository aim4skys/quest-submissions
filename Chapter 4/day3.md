### 1. Why did we add a Collection to this contract? List the two main reasons.
Added a collection to this contract to be a container for resources, aka NFTs, so all could be in one storage path and have a way for others to give us NFTs.

### 2. What do you have to do if you have resources "nested" inside of another resource? ("Nested resources")
You must destroy nested resources.

### 3. Brainstorm some extra things we may want to add to this contract. Think about what might be problematic with this contract and how we could fix it.
####    - Idea #1: Do we really want everyone to be able to mint an NFT? 🤔. 
No, you may want ot add a limit on the minting amount of NFTs.  Resource interface can assist with limiting.

####   - Idea #2: If we want to read information about our NFTs inside our Collection, right now we have to take it out of the Collection to do so. Is this good?
Moving resources is not a good idea, which is why they are a bit difficult to deal with.  Instead borrow to read the resource without moving it.
