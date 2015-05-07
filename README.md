# HRMS APP

This app is a mobile version of [HRMS TechAspect](http://hrm.techaspect.com/). Aimed to support features and functionalities like

  * Personal Details
    * Skills
    * Reporting Manager
    * JOB designation
  
  * Leave Management
    * Apply Leave
    * LeaveSummary

### Development Approach 
 We Use Hybrid app development approach owing to following advantages 
  * Hybrid app ports to Multiple platforms: Can support multiple platforms although native container should be developed for each platform
  
  * Low Development Costs: It is cheaper to develop using hybrid architecture as the development process involves writing a native cotainer over existing presentation layer using third party libraries
  
  * Code Reuse: A hybrid app can leverage common server-side components as the same HTML content is exposed for each platform
  
  * Functional Testing: Functionality tested for one platform should work for all the platforms
  
  * Existing Server side Components: We can utilise existing server side resources which are designed for Web Application
  
  * Enhancements: Rolling out new features is easier as no client app distribution is required
  
### Technology Used
  * Polymer JS 
  * HTML5, CSS3, JavaScript
  * PhoneGap
  * Crosswalk
  * Sharepoint
 
### App Modules
  
  * Authentication Module: User is authenticated by sending a request to service . Authenticated users are redirected to the Dashboard module of the app with respective privileges
  
  * Dashboard Module: This module provides the user a view of his profile and all the functionalities he is previliged to. for example only Manager has the privelege to approve leaves and this functionality will be hidden for an employee whose role isn't manager.
    * Apply Leave
    * Leave History
    * Leave Summary
 
  
  * Apply Leave: Here the User can apply leave for required number of days as long as he has sufficient leave balance. This leave request will be updated to he server with the help of a POST request. In case of insufficient leave balance the request should not be entertained. Manager should be notified when an employee applies for leave, so that he can approve or reject it
    
  * Leave History: Here the user gets to see the details of leaves previously taken by him/her 
  
  * Leave Summary: Here the details of leave balance  categorized based on leave types should be listed 


### Testing
* Unit Testing: Unit testing can be achieved through web-component-tester of polymer which provides browser-based testing environment configured with Mocha framework and Chai assertions 

* Functional testing: fucntional testing can be done using automated testing tool appium

### Client Platforms
   Initially We choose to deploy the application on Android , ios and Windows platforms

###Target Devices
Android 2.3 and above 
ios 6 and above
Polymer and and polyfills work only for android 4.3 above and ios 8 above. Crosswalk web view helps render the components consistently on older versionas as well




  
  
  
 

