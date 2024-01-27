# Competitive-Programming setup in Sublime Text editor

## C++14 Sublime build for Mac Users (OS X):

### Instructions :

- Go to Tools > Build Systems > New Build System
- Copy the code from C++14.sublime-build and paste it there and save it by any name
- Go to Tools > Build Systems ans select your new build system
- Create 2 files named inputf.in and outputf.in in same directory in which u have ur code
- Write input in inputf.in, save and run the code in sublime and you will get output in outputf.in

### Tips :

- You can use COMMAND + shift + B to directly compile run.
- You can use 3 pane setup to view code, input file and output file at once (View > Group > New group).

### To install gcc in OS X:

```
brew install gcc
```

### To install gtimout in OS X:

```
brew install coreutils
```

### Note: Change the version of gcc in the sublime build accrodingly based on what you have installed. I'm using gcc-13 

### This is how the setup looks:

![image](https://github.com/mounishvatti/competitive-programming-setup/assets/76279858/8705c78e-bd76-44e1-968e-420585c61d9f)

