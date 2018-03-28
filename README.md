# git-demo

* DEMO SOME BASIC CASE

### Step by step, your workflow under this model might look like this:

1. You need to fix a bug.
2. Create a branch called myfix that is based on the develop branch.
3. Work on the bug in this topic branch until it is fixed.
4. Merge myfix into develop. Run tests.
5. You discover your fix conflicts with another topic branch hisfix that your coworker merged into develop while you were working on your fix.
6. Make more changes in the myfix branch to deal with these conflicts.
7. Merge myfix into develop and run tests again.
8. Everything works fine. Merge develop into master.
9 .Deploy to production from master any time, because you know it's stable.

A: A adds this line