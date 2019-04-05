# Lab4
1. Open the terminal or cmd `git clone you-git-url`
2. Open the .sln file with Visual Studio
1. In Visual Studio Go to -> tools -> NuGet -> Console and run `Install-Package log4net`. 
(This command install the log4net package that we will use latter in this exercise)
4. In the terminal go the folder where the project located (cd lab4...)
5. Create a new branch `git checkout -b login`
6. Write a C# method that takes as a user input (Console.Readline) userid and password (type string) and check if they match a predefined username and password (lets assume "username" and "passowrd) 
More advanced: After 3 wrong attempts, user will be rejected.
7. Don't forget to add and commit after each step.
8. Merge back the branch to the master. (Go back to master and only than merge).
9. Delete the login branch (`git branch -d`).
10. Create a new branch `git branch log-login`
11. On the master add a message for failed and successful logins.
12. Additionally, add an object of a `Hashtable` type that will store a hard coded usernames and passwords.
13. Change your function that login validation will use the created `Hashtable`.
14. Move to branch log-login `git checkout log-login`
15. Add logging for each successful and failed attempts logging the username and number of attempt.
16. Give different levels of  log message to different log messages.
17. Merge back to the master
18. Resolve all the conflicts
