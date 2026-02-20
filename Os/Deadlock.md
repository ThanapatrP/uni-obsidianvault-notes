- Happens with **> 1** Processes
-  Each Processes wait for each other to **finish/release** resource
-  Every processes in Deadlock group are ***PERMANENTLY BLOCKED***

## Deadlock != Starvation
- Very close but isn't
- Deadlock -> if happened **can't** be solved by [[Scheduler]]
- Starvation -> **can** be solved by [[Scheduler]] *(if ur lucky lol)*

![[Pasted image 20260220223244.png]]

## System Model
Process will use resource in these steps
1. **Request** - request resource from system
2. **Use** - process use the resource
3. **Release** - return resource back to system


## Resource Types
### Reusable
**Can be used by ONE process at a time**
Usually the type of resource that cause Deadlock
*ex. CPU, Memory, I/O channels, etc.*

### Comsumable Resource
**2 types of process**
1. Producer
2. Consumer
This type of resource is rare to cause Deadlock

*ex. Signal, Message*

## Condition for Deadlock
#### (Must have all of these for Deadlock to happens)
- **Mutual Exclusion** - Condition for only one process can use resource at a time
- **Hold-and-wait** - 








