# Online-Compiler-Windows-Server
This is an Online Compiler For Windows Server 

# SET UP

```
Install CodeBlocks IDE
```

```
Go To  Codeblocks Installed Folder bin Location And Copy The Path. Mine Is

C:\Program Files\CodeBlocks\MinGW\bin

```

```
Then Set Your Compiler Path On Environment Variable From Windows System Property Otherwise It will not work 

```

```
At Last Replace Path in putenv() function by your path

```

For Java Install Java
```
Go To Java Installed Folder bin Location And Copy The Path. Mine Is

C:\Program Files\Java\jdk1.8.0_(Your Version)\bin

```


```
At Last Replace Path in putenv() function by your path
```

Now(BUG)

    1. C++로 할 경우 컴파일이 안된다.