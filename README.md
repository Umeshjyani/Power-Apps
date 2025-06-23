1.create new folder and install the Pac.

2. or install form here  
	 https://learn.microsoft.com/en-us/power-platform/developer/cli/introduction?tabs=windows
	 https://learn.microsoft.com/en-us/power-platform/developer/howto/install-cli-msi

3.also need to install the  dot net SDK form here.
	https://dotnet.microsoft.com/en-us/download/dotnet
	dotnet-sdk-9.0.101-win-x64.exe

4.after that open vs code and run that commands.
	pac --version
	dotnet --version
	pac package init -o DeploymentPackage
	cd .\DeploymentPackage\
	pac package add-solution -p C:\Users\UmeshJyani\Downloads\Helpdesk365_2024_12_04_1_managed.zip
	dotnet publish.

5. after that we find the our packer inside this directory.
	DeploymentPackage\bin\Debug\DeploymentPackage.1.0.0.pdpkg.zip

6. pic this solution and past in the package folder that we need to make for the share solutions.

*****************************************************************************************

Create an AppSource package for your app-

https://learn.microsoft.com/en-us/power-platform/developer/appsource/create-package-app

Video Link to build AppSource package
https://aka.ms/cepackage

******************************************************************************************

https://rohangoel.hashnode.dev/pcf-controls-using-react
