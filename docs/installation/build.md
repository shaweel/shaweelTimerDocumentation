# Building from source
You can install shaweelTimer by building from source. This is only intended to be done on [GNU](https://gnu.org/home.en.html)+[Linux](https://kernel.org) distribution not in [linux.md](linux.md) or operating systems other than [Windows](https://windows.com) and [GNU](https://gnu.org/home.en.html)+[Linux](https://kernel.org)(unsupported).

You usually don't actually build the application, you mostly just `git clone` the repository and make a .desktop file for the program.

One requirement is that you will **NEED** to run the generateVersionData.sh script which will make a .json file which you need to move to /usr/lib/shaweelTimer  
Syntax:  
`./generateVersionData.sh "<build type> <version> <branch> <build(optional, is only used when the branch is "dev")`  
Example:  
`./generateVersionData.sh ".abc file" "1.2.3" "dev" "123"`  
