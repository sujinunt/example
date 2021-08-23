## Example of Working with Remotes

by Sujinunt Puangmalai 

Use case: You have repository on your computer containing some code. How do you copy this repository to Github?

0. Create an empty repository on Github for your code.
   - copy the URL that Github shows you.

1. (On your computer) Add a remote to your local repository
   ```
   git remote add origin https://github.com/sujinunt/example.git
   ```

2. Push some work ***and*** tell git to use this as the "default" **upstream** repository: 
   ```
   git add yourfile
   git commit -m "Your update"
   git push -u origin master	
   ```

3. Next time (git knows your default upstream) just type:
   ```
   git push
   ```
