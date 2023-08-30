# MSSQL-Install

>>> How to install Microsoft SQL Server 2022? (https://www.youtube.com/watch?v=iaUXjTL_F9U)
(1) Google search SQL server download
(2) Click on first link or https://www.microsoft.com/en-us/sql-server/sql-server-downloads
(3) Choose Express and click on Download now
(4) After download, click on the executable file
(5) Choose intallation type : Basic
(5) Next, Click on Accept
(6) Next, change install location if you want then Click on Install
Note: It can take around 10 minutes to complete the installation
(7) Once the installation has completed, you need to insall the IDE < Microsoft Sql Server Management studio >
Click on Install SSMS
(8) A page will open on your browser > Scroll to Download SSMS > Click on "Free Download for SQL Server Management Studio (SSMS) 18.2.1"

You can close the SQL Server installer for now.

>>> How to install Microsoft SQL Server Management Studio ?
(1) After download, click on the Executable file and complete the installation
(2) Next, change install location if you want then Click on Install
Note: It can take around 5 minutes to complete the installation
(3) When setup is complete you can close the installer window

>>> How to fix the error : TITLE: SQL Server Import and Export Wizard > The operation could not be completed. > ADDITIONAL INFORMATION: The 'Microsoft.ACE.OLEDB.16.0' provider is not registered on the local machine. (System.Data)
(https://www.youtube.com/watch?v=brGq2by7DvA)
(1) You can encounter this error when you are trying to import data, for example an Excel workbook, on SSMS 
(2) Google search Microsoft Access Database Engine 2016 Redistributable
(2) Click on first link or https://www.microsoft.com/en-us/download/details.aspx?id=54920
(3) Select language if you don't use English and click on Download
If your computer has a 64-bit machine, download accessdatabaseengine.exe
(4) Once download is completed, copy the path where the file is saved.
(5) Click the Start button of your windows and type "cmd" and open the <Command Prompt>
(6) cd to the file location
(7) Run the command >> accessdatabaseengine.exe /quiet
The import data in SSMS should work now.

>>> How to download Microsoft SQL server Native Client? (https://www.youtube.com/watch?v=wA87gobLIVA)
(1) Google search @Download Microoft SQL Server Native client"
(2) Click on first link or https://www.microsoft.com/en-US/download/details.aspx?id=50402
(3) Select language if you don't use English and click on Download
For 64-bit machine, download ENU\x64\sqlncli.msi
For 32-bit machine, download ENU\x32\sqlncli.msi
(4) After download, click on the Executable file and complete the installation

