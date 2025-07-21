## Tutorial
### Install Compiler
1. Go to [MinGW](https://sourceforge.net/projects/mingw/), download and install the compiler. (The default install location is C:\MinGW, mark down if you customised)
2. Check all "Package" boxes in the MinGW Installation Manager
![image](https://github.com/ChoiGod330/Compile-.cpp-to-.exe/blob/main/Installation%20Manager.png)
3. Click "Installation" and "Apply Changes"
4. Wait for downloading the packages
5. Open "Environment Variables"
6. Select "Path" in user variables and click "Edit"
7. Add the path below or your own path and click "OK"
```Shell
C:\MinGW\bin
```
8. Enter "cmd" to open CommandPrompt or "powershell" to open PowerShell
9. Run the command below to check if successfully installed:
```Shell
gcc --version
```



### Compile .cpp file to .exe
1. Navigate to the script's(.cpp) folder:
```Shell
cd C:\[PATH]
```
2. Run the command below:
```Shell
g++ [FILENAME.cpp] -o [OUTPUTFILENAME.exe]
```
3. The .exe file will be created in the path
```Shell
C:\[PATH]\[OUTPUTFILENAME.exe]
``` 

This is a tutorial for compiling .cpp to .exe written by @ChoiGod330
