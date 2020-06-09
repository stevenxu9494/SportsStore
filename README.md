# Running SportsStore on your own machine

1. Restore the packages from Nuget Package console

2. Set SportsStore.WebUI as start up project

3. Start debugging<br /> 
(Encountered Error [Could not find a part of the path 'D:\git\projectName\bin\roslyn\csc.exe']. See Steps 4 & 5.)

4. Open Nuget Package Console -><br /> 
PM> Uninstall-package Microsoft.CodeDom.Providers.DotNetCompilerPlatform<br /> 
PM> Uninstall-package Microsoft.Net.Compilers<br /> 

5. Rebuild project then start over debugging



## Preview for PC users

![alt text](https://github.com/stevenxu9494/SportsStore/blob/master/Images/SportsStorePCHomeView.png?raw=true)

## Preview for Mobile users

![alt text](https://github.com/stevenxu9494/SportsStore/blob/master/Images/SportsStoreMOHomeView.png?raw=true)
