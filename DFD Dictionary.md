# DFD Dictionary

## Entities:
+ **Developer:** Person responsible for creation of the software package
+ **Manager:** Person responsible for policies of the software package

## Data Stores:
+ **NIST Vulnerability Database:** Database that consists of any known vulnerabilities of a particular software package
+ **License and Vulnerability Database:** Database that consists of all license and vulnerability information of a software package
+ **Policies:** Database that consists of all policy information of a particular software package

## Processes:
+ **License Scanner:** A process that scans for licenses of a particular software package 
+ **Management:** A process that controls the licenses and vulnerabilities of a particular software package 
+ **License and Vulnerability Database Query:** A process that returns the license and vulnerabilities request made by a manager and a developer
+ **Retrieve Policy:** A process that returns the policy results back to the manager after he or she requested for policies of a particular software package
+ **Create/Edit Policy:** A process that allows the manager to add a new policy or edit an existing policy

## Data Flows:
+ **Software Package:** Collection of files for a software
+ **Software Package Name:** Name of the particular software package
+ **Vulnerability Result:** Vulnerability information of a particular software package
+ **License Result:** License information of a particular software package
+ **Policy Request:** Request made by the manager in order to see the policy information of a particular software package
+ **Policy Result:** Policy information of a particular software package
+ **New/Edited Policy Information:** Allows the manager to add a new policy or edit an existing policy for a particular software package
+ **License and Vulnerability Request:** Request made by the manager and developer in order to see license and vulnerability information of a particular software package
+ **License and Vulnerability Response:**Results of all the known licenses and vulnerabilities of a particular software package
