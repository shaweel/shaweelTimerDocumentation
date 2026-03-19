# Building from source
You can install shaweelTimer by building from source. **Do not do this on [Windows](https://windows.com)**, instead follow [Windows.md](windows.md). Only do this on [GNU](https://gnu.org/home.en.html)+[Linux](https://kernel.org).

You usually don't actually build the application, you mostly just `git clone` the repository and make a .desktop file for the program.

One requirement is that you will **NEED** to run the generateVersionData.sh script which will make a .json file which you need to move to /usr/lib/shaweelTimer
Syntax:
`./generateVersionData.sh "<build type> <version> <branch> <build(optional, is only used when the branch is "dev")`
Example:
`./generateVersionData.sh ".abc file" "1.2.3" "dev" "123"`
