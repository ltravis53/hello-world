# hello-world
getting started with GitHub and VS Code

//detail extensions downloaded and installed

helloworld.cpp is the code given in the walkthrough from the VS Code page on setting up the environment.
Configure VS Code for Microsoft C++
https://code.visualstudio.com/docs/cpp/config-msvc
  -  Installing the Microsoft Visual C++ (MSVC) compiler toolset
  -  Verify the workload is running
        -  Start/Task Bar > Search > Visual Studio Installer > Modify > verify "Desktop development with C++" is checked
        -  if not, install
  -  PATH variable for VS is absolutely bonkers.  Using Task Bar > Search > "Developer Command Prompt for VS 20**"
        - default PATH is: C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools
        - run type "cl" and it should show usage and you know its in there like swimwear
        - go ahead and switch to run vs code outside a developer command prompt!!!!

1.  Compiler and Integrated VS Development Command Line [here](tasks.json)
    -  invokes the Microsoft C++ compiler to create an executable file based on source code
    -  main menu/top menu > terminal > configure default build task > cl.exe build active file
    -  added path needed for VsDevCmd.bat
    -  modified file configs for file dir/name

2. Source Code [here](helloworld.cpp)
    -  I did not have the desired results by creating subfolders via Developer Command Prompt
    -  I personally prefer the GUI of VS Code to create a subfolder
    -  the "code ." is cool for breaking the current session out into its own editor though!
    -  write the code (copied from the VS Code docs)
    -  turn on autosave
    -  

3.  Debugging [here](launch.json)
    -  main menu/top menu > run > add configuration > C++ (Windows) > cl.exe - Build and debug active file"
