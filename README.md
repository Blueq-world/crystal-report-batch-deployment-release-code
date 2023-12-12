# crystal-report-batch-deployment-release-code
[![Build status](https://ci.appveyor.com/api/projects/status/2exf5ulw51klq8wt?svg=true)](https://ci.appveyor.com/project/Blueq-world/crystal-report-batch-deployment-release-code)
[![GitHub release](https://img.shields.io/github/release/Blueq-world/crystal-report-batch-deployment-release-code.svg)](https://github.com/Blueq-world/crystal-report-batch-deployment-release-code/releases)
[![Github All Releases](https://img.shields.io/github/downloads/Blueq-world/crystal-report-batch-deployment-release-code/total.svg)](https://github.com/Blueq-world/crystal-report-batch-deployment-release-code/releases)

Use the .net SDK to batch upload reports and update the report login information in the Crystal Report Server.

## Usage 
* ### Configuration in the App.config
![](Guideline%20Image/Capture10.PNG)

* ### Click "CrystalReportDeploy.exe" file

* ### Input the "Path of publish source folder" and the "Deployment folder of the Crystal Service"
![](Guideline%20Image/Capture.PNG)

#### The report list in the publish source folder
![](Guideline%20Image/Capture4.PNG)

* ### Click OK button

* ### Input the corresponding "Deployment Folder" and the "Deployment Folder" in the gridview
![](Guideline%20Image/Capture1.PNG)

* ### Click Deply button

* ### Deployment successful
![](Guideline%20Image/Capture2.PNG)

#### Backed up to "TestSITBACKUP20231212" folder
![](Guideline%20Image/Capture6.PNG)

#### Uploaded to "TestSIT" folder
![](Guideline%20Image/Capture5.PNG)

#### Backed up to "TestUATBACKUP20231212" folder
![](Guideline%20Image/Capture8.PNG)

#### Uploaded to "TestAUT" folder
![](Guideline%20Image/Capture9.PNG)

#### Updated the database logon information
![](Guideline%20Image/Capture7.PNG)
