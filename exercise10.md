# Exercise 10 - Understanding Commits

1. Look at your commit log

        git log --oneline

2. Choose a commit hash

    hash = e0fa311

3. See what type of object that hash names

        git cat-file -t <hash>
        $ git cat-file -t e0fa311
        commit

4. Examine the contents of that commit closely

        git cat-file -p <hash>

5. Find the parent's hash in the commit log
   
    Answer: 
    07ce240e025cada4352206177b504ce4a2c18bb3
    
6. Look at the contents of the tree

        git cat-file -p <hash>

7. Examine the contents of one of the blobs

8. What type of object does the parent hash represent?

        git cat-file -t <hash>
        
        Answer: Tree

9. Examine the contents of the parent and its tree

10. Do the trees you looked at have any matching hashes listed?

    Answer:
    No
