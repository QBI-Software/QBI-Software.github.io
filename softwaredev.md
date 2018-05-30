# Software development guidelines

## Developer code style

*Keep it simple* applies to coding more than ever.  

Ensure your code meets the software standards of 
+ **reusability** (avoid repeating code, redundant code, too many arguments, too much code in one module, not setting defaults for args, long overly-complex method names, 'clever' code which no-one understands not even you later on)
+ **maintainability** (code with the idea that you may not come back to this code for another 12 months - will you be able to easily understand and modify it at a later date)
+ **testability** (provide some tests in the 'tests' directory or in the module main() so when updates are made, these can be run to ensure functionality is not broken)

## Respect the version control system! 
1. Always ensure you have the latest version by doing a `git pull` (available in the menu or an icon in PyCharm or from the commandline or Github desktop 'sync') before you start.
1. Do not check in any binary code (unless required such as a database)
1. Ensure you don't check any sensitive information (login/passwords) as this is a public repository. If you do, change the password/s immediately.
1. Create a branch if there is going to be a major deviation, but be aware that merging back can be time-consuming.
1. Github Desktop allows you to have multiple commits before you push to the online repository - this can be helpful in describing each change per module.
