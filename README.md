# React.js-with-Salesforce
 The ‘home’ page shows a simple table of the Banner__c custom object.
A form to add a new feilds that are inserted into the Banner__c custom object.

#Steps to Run 
- Clone the repository

- Run npm install
- Run gulp watch

    When you run gulp watch /Dist directory is automatically generated. Zip up scripts and styles folders (in      /Dist), then create a Static Resource in Salesforce named 'banners' with that zip scripts and styles folders.Then      we need to create custom object named 'banner' with fields 
   - Image URL (data type:URL)
   - Target URL(data type:URL)
   - Active (data type:Pick List)
  
- Create visualsource page (Banner.page)

- Preview that page

- You can view the fields, can add new fields as well. It also refelects the custom fields in salesforce.


  
