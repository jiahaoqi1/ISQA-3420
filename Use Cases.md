
##1) Title:  Determine License and Vulnerability Information 

**Primary Actor:**  Manager

**Goal in Context:** The manager is able to determine license and vulnerability information from provided project information.

**Stakeholders:** 
+ Manager: To receive clear and relevant project information 
+ Developer: To provide the relevant file and package information

**Preconditions:**
+ Relevant file/package is sent to Management process
+ Proper project information has been provided

**Main Success Scenario:** Manager receives accurate license and vulnerability information for the requested project packages

**Failed End Conditions:** Manager receives inaccurate license and vulnerability information for the requested project packages

**Trigger:** Manager uploads or identifies project information to which license and vulnerability information is provided

  ------------------------------------------------------------------------------------------------------------------ 
##2) Title: Create/Change Policy Information
  
**Primary Actor:** Manager
  
**Goal in Context:** The manager is able to add new policies or edit existing policy information.
  
**Stakeholders:**
+ Manager: To create or change policy information for the project  

**Preconditions:**
+ Relevant file/package is in the Policies database
+ All relevant updates are provided for new and existing policies 
  
**Main Success Scenario:** Manager receives and obtains an accurate record of policy information for the requested project packages
  
**Failed End Conditions:** Manager receives and obtains an inaccurate record of policy information for the requested project packages

**Trigger**: Manager identifies a software package to push through


  ------------------------------------------------------------------------------------------------------------------ 
##3) Title: Determine Policy Information
  
**Primary Actor:** Manager
  
**Goal in Context:** The manager is able to determine the policy information based on the respective software package. 
  
**Stakeholders:**
+ Manager: To receive clear and relevant policy information for a software package
+ Developer: To provide the relevant file and package information
  
**Preconditions:** 
+ Relevant file/package is in the License and Vulnerabilities database
+ All known licenses and vulnerabilities are informed
  
**Main Success Scenario**: Manager receives accurate policy information for the requested project packages
  
**Failed End Conditions:** Manager receives inaccurate policy information for the requested project packages
  
**Triggers:** Manager uploads or identifies policy information from the License and Vulnerabilities database
