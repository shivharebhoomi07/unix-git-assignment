# Exercise 3: Conflict Resolution

## Branches Created
- conflict-branch-1
- conflict-branch-2
(Both branches created from `main`)

## Steps Performed

1. On **conflict-branch-1**:
   - Created file `conflict.txt`
   - Added line:  
     `This line is written from conflict-branch-1.`
   - Committed the changes

2. On **conflict-branch-2**:
   - Created file `conflict.txt` (same path)
   - Added line:  
     `This line is written from conflict-branch-2.`
   - Committed the changes

3. Merged `conflict-branch-1` into `main` successfully.

4. Attempted to merge `conflict-branch-2` into `main`:
   - GitHub could not automatically merge because of conflicting changes
   - Conflict manually resolved by creating a new file `conflict_resolved.txt` in `main` containing both changes:
     ```
     This line is written from conflict-branch-1.
     This line is written from conflict-branch-2.
     ```
   - Committed the resolved file

## Outcome

- Demonstrated **how conflicts occur** when two branches modify the same file
- Demonstrated **manual conflict resolution**
- Showed the **final merged content** in main branch
