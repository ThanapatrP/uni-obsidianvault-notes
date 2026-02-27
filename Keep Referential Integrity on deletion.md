Many ways to do 
1. *Set to null* - When a [[Record]] in *referenced* is deleted -> set [[Foreign Key]] in *referencing* to *null*
2. *Cascade* - Delete all [[Record]] in *referencing* that has the *deleted* [[Record]] in [[Foreign Key]]
3. *Disallow deletion* - When [[Record]] that got referenced in *referencing* is about to be deleted -> ***reject it***