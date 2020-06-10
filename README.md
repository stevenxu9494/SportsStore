# Sports Store Demo

# http://mvcfivesportsstore.azurewebsites.net/

# A glimpse of the website

## Preview for PC users

![alt text](https://github.com/stevenxu9494/SportsStore/blob/master/Images/SportsStorePCHomeView.png?raw=true)

## Preview for Mobile users

![alt text](https://github.com/stevenxu9494/SportsStore/blob/master/Images/SportsStoreMOHomeView.png?raw=true)

## Preview for Received Order

![alt text](https://github.com/stevenxu9494/SportsStore/blob/master/Images/SportsStoreEmailReceipt.png?raw=true)

# Running SportsStore on your own machine

1. Restore the packages from Nuget Package console

2. Set SportsStore.WebUI as start up project

3. Start debugging<br /> 
(Only excute Steps 4 & 5 if you Encountered Error [Could not find a part of the path 'D:\git\projectName\bin\roslyn\csc.exe'].)

4. Open Nuget Package Console -><br /> 
PM> Uninstall-package Microsoft.CodeDom.Providers.DotNetCompilerPlatform<br /> 
PM> Uninstall-package Microsoft.Net.Compilers<br /> 

5. Rebuild project then start over debugging
