# Exercise 9 - Viewing history

1. Make a commit with a multi line commit message
   (leaving an empty line after the first line)
   
    Answer:
    git commit -m "1. what i changed
>   2. blank
>   3. why i changed"

2. View that commit in the log

        git log -1

3. View the full commit log

        git log

*If the log fills your whole terminal, press `q` to exit*

4. View a shortened version of the commit log

        git log --oneline

5. Pick a commit hash from the log

   315353ba777d46a04fa7725ea1008ccd6880ea4b

6. View the commit log from the chosen commit backward

        git log --oneline <commit_hash>

7. How much of the commit hash do you need to specify? Hint, run `git help log`

   Answer:
   7 digits is the git default

8. How can you show just the last three commit messages?

   Answer:
   git log -3

