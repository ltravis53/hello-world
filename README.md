# hello-world
getting started with GitHub and VS Code

//detail extensions downloaded and installed
//need original .vscode files for reference

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
***     - go ahead and switch to run vs code outside a developer command prompt!!!!

1.  Compiler and Integrated VS Development Command Line (hello-world/tasks.json)
  -  invokes the Microsoft C++ compiler to create an executable file based on source code
  -  main menu/top menu > terminal > configure default build task > cl.exe build active file
  -  modified file configs for file dir/name
  -  added path needed for VsDevCmd.bat

2. Source Code (hello-world/helloworld.cpp)
  -  I do not recommend creating file...

3.  Debugging (hello-world/launch.json)
  -  main menu/top menu > run > add configuration > C++ (Windows) > cl.exe - Build and debug active file"
