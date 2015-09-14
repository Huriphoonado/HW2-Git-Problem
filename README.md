##Homework 2 Git Problem

Willie Payne
CSCI 5828 – Spring 2015

First Edit
Second Edit
Third Edit
Fourth Edit
Fifth Edit
Sixth Edit
Seventh Edit
Eighth Edit
Ninth Edit
Tenth Edit
11th Edit
12th Edit
13th Edit
14th Edit

-----------------------------------

0. git init
0. git add README.md
0. git commit -m "Initial Commit"

1. (Added "First Edit" to README)
1. git add README.md
1. git commit -m "First Commit"

2. (Added "Second Edit" to README)
2. git add README.md
2. git commit -m "Second Commit"

3. git log
3. git checkout 6bca3534999678717e0a4562b5e3817ca046fe81
3. git checkout -b bug-fix
3. (Added "Third Edit" to README on same line as "First Edit")
3. git add README.md
3. git commit -m "Third Commit"

4. (Added "Fourth Edit" to README)
4. git add README.md
4. git commit -m "Fourth Commit"

5. git merge master (Merge conflict in README.md)
5. (Fixed conflict so node 5 now has all edits, added "Fifth Edit")
5. git add README.md
5. git commit -m "fixed conflict merging to node 5"

6. (Added "Sixth Edit" to README)
6. git add README.md
6. git commit -m "Sixth Commit"

7. git log
7. git checkout ef1059fb2f8078e207c9445fc95f141f60ce6e18 (Return to node 4)
7. git checkout -b bug-fix-experimental
7. (Added "Seventh Edit" to README)
7. git add README.md
7. git commit -m "Seventh Commit"

8. (Added "Eighth Edit" to README)
8. git add README.md
8. git commit -m "Eighth Commit"

9. (Added "Ninth Edit" to README)
9. git add README.md
9. git commit -m "Ninth Commit"

10. git checkout master (Return to node 2)
10. (Added "Tenth Edit" to README)
10. git add README.md
10. git commit -m "Tenth Commit"

11. git checkout bug-fix (Return to node 6)
11. git merge bug-fix-experimental (Merge conflict in README.md)
11. (Resolved merge conflict, added "11th Edit")
11. git add README.md
11. git commit -m "fixed conflict merging to node 11 by ordering all edits"

12. (Added "12th Edit" to README)
12. git add README.md
12. git commit -m "12th Commit"

13. git checkout master (return to node 10)
13. git merge bug-fix
13. (Resolved merge conflict, added "13th Edit")
13. git add README.md
13. git commit -m "fixed conflict merging to node 13 by ordering all edits"

14. (Added 14th Edit, my name, and this file)
14. git add README.md
14. git commit -m "14th Commit"