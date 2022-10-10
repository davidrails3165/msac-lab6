# Exercise 3 - Configuring your first repository

1. Enable color

        git config --global color.ui auto

2. Set your name

        git config --global user.name "John Doe"
        git config --global user.name "davidrails3165"

3. Set your email address

        git config --global user.email "john.doe@somewebsite.com"
        git config --global user.email "kurofune1@gmail.com"

4. Why did we use the `--global` flag?  (What does that do?)

Answer:
    1) it is applied to an operating system user
    2) it is used to configure this option for all the Git repositories the user will personally use


5. Check your git config to show the changes you have made

        git config -l
        
        settings below:
        user.name=davidrails3165
        user.email=kurofune1@gmail.com
        color.ui=auto

For more information, check out [Customizing Git Configuration](https://www.git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)