# How to set custom terminal?

If you have maven properly installed, and you want to configure intelliJ terminal with a custom Terminal or if you want 
fix "command not found",follow these steps:
1. Click > File
2. Click > Settings
3. Click > Tools
4. Click > Terminal
5. Edit "Shell path" @ "Application Settings", if you want to use git bash change current path with:
   - ```C:\Users\PUT HERE YOUR USERNAME\AppData\Local\Programs\Git\bin\sh.exe --login```

   The path you may have differs based on your OS, in example:
   - ```installationPath\Terminal Folder\bin\sh.exe --login```
6. Click > Apply
7. Click > Ok

I used git bash, but technically it should work with every terminal.
Do not forget to add ```--login``` after the ```*.exe```

If it still doesn't work maybe you need to check:
1. Click > Environment variables
2. Click > System Properties
3. Click > Environment Variables
4. Click > System Variables
5. Select > Path from the list
6. Click > Edit
7. Click > New

Insert the path of your maven bin folder, in example:
- ```installationPath\apache-maven-3.8.6\bin```

Also insert the path of your jdk, in example:
- ```installationPath\Java\jdk-18.0.1.1```
