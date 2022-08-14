# EVehicleSimulator

Installation Guide

   This install, config, and run the project following installation and setup must be done. Followings are the tools and technologies need to be installed.

1.	Git
2.	Visual Studio 2022
3.	MySQL
4.	Here API Registration

•	Git: 
o	Git used to keep track of version and source control. Once you download the git and install it with the default configuration. During the installation, please make sure to check "add git to path" configuration.  
o	Once installed successfully. You need to connect to repository and clone it. Steps to clone. 
i.	 Open file explorer 
ii.	Go to your destination path.
iii.	Open command line and enter 
o	git clone https://github.com/dhruviSanghani/E-vehicle-simulator.git
o	Download Link for Git: https://git-scm.com/downloads

•	Visual Studio 2022
o	Follow default installation stop while selecting workloads.
o	Select ASP.NET and web Development and make sure to select .NET CORE 6.
o	You can download .NET CORE 6 separately from https://dotnet.microsoft.com/en-us/download/dotnet/6.0

•	 MySQL
o	Go to the https://dev.mysql.com/downloads/windows/installer/8.0.html and download installer file. 
o	Run the installer and select custom install. 
o	Select MySQL server, MySQL Workbench, MySQL for Visual Studio and Connector/NET in products to be installed. 
o	Execute all the operations.
o	Setup server name and password.







•	Project Setup Guidelines
o	Download or copy database file residing in database folder from repository
o	Open MySQL workbench.
o	Go to the administration section.
o	Import database from self-contained file.
o	Once done with importing. Go to the local repository path and open E-vehicle-simulator.sln solution file.
o	Wait until everything is loaded. 
o	Run the project from the toolbar
•	Here API Registration
o	Sign Up with Here.com : https://platform.here.com/sign-up?step=verify-identity
o	Add basic profile details and credit card details to get started.
o	Here API will provide a API key token that should be used to make API requests.
o	Update the API key token in “directions.cshtml” and merge to master branch.
