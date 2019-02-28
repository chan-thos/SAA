- If Container Event is an event in CQRS, and "Undo" event is one kind of it, then how can the snapshot be built to restore the snapshot to previous image?
- If microservie(A) needs to call update APIs to another 3 microservies(B/C/D), this will update data in B&C&D, since every microservice has each own data store, how to ensure all the update ops are successful/roll backed?
How to implement Saga Pattern?
