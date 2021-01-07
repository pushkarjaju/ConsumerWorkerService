# Building a windows service using .NET Core

##### - .NET Core 3.1
##### - Visual Studio
##### - Serilog
##### - Windows Service

###### Nuget Packages & Commands
▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
#######  Microsoft.Extensions.Hosting.WindowsServices
#######  New-Service -Name {SERVICE NAME} -BinaryPathName {EXE FILE PATH} -Description "{DESCRIPTION}" -DisplayName "{DISPLAY NAME}" -StartupType Automatic

####### Example : New-Service -Name ConsumerWorkerService -BinaryPathName D:\ConsumerWorkerService\ConsumerWorkerService\bin\Release\netcoreapp3.1\ConsumerWorkerService.exe -Description "This is test service" -DisplayName "ConsumerWorkerService" -StartupType Automatic
