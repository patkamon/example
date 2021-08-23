# Example of Working with Remotes #   
   
by Patkamon Awaiwanont   

Use Case: You have a repository on your computer containing some code. How do you copy this repository to Github?   

   0. Create an empty repository on Github for your code.  
     
        - copy the URL that Github shows you.

   1. (on your computer) Add a remote to your local repository     
   
        ```git remote add origin https://github.com/jbrucker/example.git```
        
   2. Push some work and tell git to use this as the "default" upstream repository:  
     
        ```git push -u origin master```
        
   3. Next time (git knows your default upstream) just type:   
   
        ```git push```

# Git Branches #

Git branch provides you to add/edit your code into a specify branch by not interrupt other
branch, This made your work much more flexible to do with team/partner. 