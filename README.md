# How to add yarn workspace in react.js(windows7,8.1,10)?
![maxresdefault](https://user-images.githubusercontent.com/69615463/146716062-06cf5081-9654-4011-a28d-7e6666aa3900.jpg)

<h6>Solution:RKT(Rahat Khan Tusar)</h6>


### Windows Execution Policy(PowerShell): ###

  Execution Policy Site:https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.security/set-executionpolicy?view=powershell-7.2

+ Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
+ Get-ExecutionPolicy -list
+ npm install -g yarn
+ npm install yarn-workspaces
+ yarn install
+ yarn add create-react-app 
+ yarn create-react-app my-app

<h6>set file location</h6>

+ set PATH=%PATH%;C:\Users\Rahat Khan Tusar\AppData\Local\Yarn\bin\




### ScreenShot ###

![Screenshot (2)](https://user-images.githubusercontent.com/69615463/146715853-1f6c57f4-8477-4dce-a79b-9df052138677.png)











