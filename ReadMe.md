# <span style="color:#0ec2b8">_Hair Salon Client Tracker_</span>

#### _Eau Claire's Salon app, 01/02/2021_

#### By _**Nataliya Zhuravleva**_

## <span style="color:#0ec2b8">Description</span>

_An MVC application to help Eau Claire's Salon manage the empoyees and clients._

## <span style="color:#0ec2b8">Setup/Installation Requirements</span>
### <span style="color:#c4f4ef">Open Online</span>
_This opportunity will be added later._
### <span style="color:#c4f4ef">Open Locally</span>
1. _Navigate to my [Hair Salon repo](https://github.com/NataliyaZhuravleva/HairSalon.Solution) at https://github.com/NataliyaZhuravleva/HairSalon.Solution_ to view the project files and commits.
2. _Click on the green button labeled "Code"_ to copy repository URL.
3. _Clone the repository to your local machine_ by opening your machine terminal and using the command "git clone https://github.com/NataliyaZhuravleva/HairSalon.Solution".
4. _Navigate to the folder "/HairSalon/" to see coding._
6. _To use this application you will need to install .NET. Please, see instructions below._

### <span style="color:#0ec2b8">.NET Installation</span> 


#### <span style="color:#c4f4ef">Mac</span> 

1. _Download this [.NET Core SDK (Software Development Kit)](https://dotnet.microsoft.com/download/dotnet-core/thank-you/sdk-2.2.106-macos-x64-installer) . Clicking this link will prompt a .pkg file download from Microsoft._
2. _Open the file. This will launch an installer which will walk you through installation steps. Use the default settings the installer suggests._ 
3. _Confirm the installation is successful by opening your terminal and running the command "$ dotnet --version". You should see something like this in response: 2.2.105. This means both .NET and C# are successfully installed._

#### <span style="color:#c4f4ef">Windows</span> 
Note on Windows Versions
These Windows instructions assume you're using Windows 10. If you currently run Windows 7 or Windows 8, you may have a free upgrade available.
If you are not running Windows 10 (and cannot or do not plan to upgrade), specific installation steps may differ. 
#### Installation Steps:
1. _Download either the the 64-bit .NET Core SDK (Software Development Kit). Clicking these links will prompt a .exe file download from Microsoft._
2. _Open the file and follow the steps provided by the installer for your OS._
3. _Confirm the installation is successful by opening a new Windows PowerShell window and running the command "dotnet --version". You should see something a response like this (version numbers do not need to be the same): 2.2.105_<br>
_This means .NET and C# are installed and your computer recognizes the dotnet command._

### <span style="color:#0ec2b8">MySQL Installation</span>
#### <span style="color:#c4f4ef">Mac</span> 
1. Download the MySQL Community Server .dmg file from the [MySQL Community Server page](https://dev.mysql.com/downloads/file/?id=484914). Click the download icon. Use the "No thanks, just start my download link."
2. Follow along with the Installer until you reach the Configuration page. Once you've reached Configuration, select or set the following options (use default if not specified):
    * Use Legacy Password Encryption.
    * Set password to "epicodus".
    * Click Finish.
    * Open the terminal and enter the command echo 'export PATH="/usr/local/mysql/bin:$PATH"' >> ~/.bash_profile. This will save this path in .bash_profile, which is where our terminal is configured.
    * Type in source ~/.bash_profile (or restart the terminal) in order to actually verify that MySQL was installed.
3. Verify MySQL installation by opening terminal and entering the command mysql -uroot -pepicodus. You'll know it's working and connected if you gain access and see the MySQL command line. If it's not working, you'll likely get a -bash: mysql: command not found error.
4. You can exit the mysql program by entering exit.
5. Download the MySQL Workbench .dmg file from the [MySQL Workbench page](https://dev.mysql.com/downloads/file/?id=484391). Use the "No thanks, just start my download link".
6. Install MySQL Workbench to Applications folder.
7. Open MySQL Workbench and select the Local instance 3306 server. You will need to enter the password "epicodus". If it connects, you're all set.

#### <span style="color:#c4f4ef">Windows</span> 
1. Download the MySQL Web Installer from the [MySQL Downloads page](https://dev.mysql.com/downloads/file/?id=484919). Use the "No thanks, just start my download link".
2. Follow along with the installer:
    * Click "Yes" if prompted to update.
    * Accept license terms.
    * Choose Custom setup type.
    * When prompted to Select Products and Features, choose the following:
        * MySQL Server 8.0.19 (This will be under "MySQL Servers > MySQL Server > MySQL Server 8.0")
        * MySQL Workbench 8.0.19 (This will be under "Applications > MySQL Workbench > MySQL Workbench 8.0")
    * Select "Next", then "Execute". Wait for download and installation. (This can take a few minutes.)
    * Advance through Configuration as follows:
        * High Availability set to "Standalone".
        * "Defaults are OK" under Type and Networking.
        * Authentication Method set to Use Legacy Authentication Method.
        * Set password to "epicodus". 
        * Defaults are OK under Windows Service. Make sure that checkboxes are checked for the options "Configure MySQL Server as a Windows Service" and "Start the MySQL Server at System Startup". Under Run Windows Service as..., the "Standard System Account" should be selected.
    * Complete Installation process.
3. Add the MySQL environment variable to the System PATH. You must include MySQL in the System Environment Path Variable. This is its own multi-step process:
    * Open the Control Panel and visit System and "Security > System". Select "Change Settings" and a pop-up window will display. Select the tab "Advanced" and select the "Environment Variables" button.
    * Within the System Variables navigator window, select PATH..., click Edit..., and then New.
    * Add the exact location of your MySQL installation, and click OK. (This location is likely C:\Program Files\MySQL\MySQL Server 8.0\bin, but may differ depending on your specific installation.)
4. Verify installation by opening Windows PowerShell and entering the command mysql -uroot -pepicodus. You'll know it's working and connected if you gain access and see MySQL's command line. You can exit the mysql program by entering exit.
5. Open MySQL Workbench and select the Local instance 3306 server (it may have a different name). You will need to enter the password "epicodus". If it connects, you're all set.

### <span style="color:#0ec2b8">Packages To Install:</span>
_In the command line run the following commands to install packages:
1. $ dotnet add package Microsoft.EntityFrameworkCore -v 2.2.0
2. $ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 2.2.0

### <span style="color:#0ec2b8">Running Program</span> 
#### <span style="color:#c4f4ef">Run Application</span>

1. _Use nataliya_zhuravleva.sql file to access database_ 
2. _Navigate to the "HairSalon.Solution/HairSalon" folder in the command line._
3.  _Run the following command: $ dotnet restore_
4. _Run the following command: $ dotnet build_
5. _Run the following command to execute this compiled code: $ dotnet run_


## <span style="color:#0ec2b8">Known Bugs</span>

_No known bags_

## <span style="color:#0ec2b8">Support and contact details</span>

_If you have any questions, ideas or concerns, please, contact me at [natalindria@gmail.com](mailto:natalindria@gmail.com)_


## <span style="color:#0ec2b8">Technologies Used</span>

* _C#_
* _.NET_
* _MSTest_
* _VisualStudio Code_
* _Git_
* _GitHub_


### <span style="color:#0ec2b8">License</span> 

*This software is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license*

Copyright (c) 2020 **_Nataliya Zhuravleva_**
