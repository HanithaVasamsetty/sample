# HRMS APP

This app is a mobile version of [HRMS TechAspect](http://hrm.techaspect.com/). Aimed to support features and functionalities like

  * Personal Details
    * Skills
    * Reporting Manager
    * JOB designation
  
  * Leave Management
    * Apply Leave
    * LeaveSummary


### Technology Used
  * Polymer JS 
  * HTML5, CSS3, JavaScript
  * PhoneGap
  * Sharepoint
 
### App Modules
  
  * Authentication Module: User is authenticated by sending a request to service . Authenticated users are redirected to     the Dashboard module of the app with respective privileges
  
  * Dashboard Module: This module provides the user a view of his profile and all the functionalities he is previliged to. for example only Manager should have privelege to approve leaves and this functionality will be hidden for an employee whose role isn't manager.
    * Apply Leave
    * Leave History
    * Leave Summary
 
  
  * Apply Leave: Here the User can apply leave for required number of days as long as he has sufficient leave balance. This leave request will be updated to he server with the help of a POST request. In case of insufficient leave balance the request should not be entertained.
    
  * Leave History: Here the user gets to see the details of leaves previously taken by him/her 
  
  * Leave Summary: Here the details of leave balance is clearly listed 
  
 
 ### Client Platforms
   Initially We choose to deploy the application on Android , ios and Windows platforms
  
  
  
 

