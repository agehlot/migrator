## Summary
⟹ A Migration Module that can help you to move items from XP (traditional) to Headless CMS or XM Cloud 

  - Module will convert .Net MVC based all sitecore items, renderings, layouts, page templates to Headless compatible items.



## Pre-requisites and Dependencies

•	Sitecore XP/XM required
•	You should have the MVC website. 
•	Install headless service in your XP/XM


## Installation instructions
•	Install Sitecore package. Available here: 

•	Open the URL. https://{Your-domain}/MVCToJSS/DashBoard.
 
•	Enter the MVC website Root item home page you want to migrate.
 
![image](https://user-images.githubusercontent.com/121872851/222935728-01cc8139-13e0-469f-ae71-8eff68f6a811.png)

* Click submit

 

If you create sample jss get started template and point your MVC layout service. It can expose layout service as showed below.
 
 


### Configuration


## Usage instructions

![image](https://user-images.githubusercontent.com/121872851/222935728-01cc8139-13e0-469f-ae71-8eff68f6a811.png)

•	Before update.
 ![image](https://user-images.githubusercontent.com/121872851/222935735-74c6b310-9e5c-4f7f-8626-ff7275275edf.png)
o	Layouts are MVC layout.
o	All renderings are MVC View rendering/ Controller renderings.
o	Page items not referred the JSS route items

![image](https://user-images.githubusercontent.com/121872851/222935760-75d391a5-f118-4583-94d6-eeb9a6b6ff4e.png)


•	Post update
o	New JSS layout will create and point
o	Both shared and final layout will get updated with the new JSON rendering
o	Pages will inherit JSS base route templates
o	All the actions are one time execution, If rendering created it will re use the same.

![image](https://user-images.githubusercontent.com/121872851/222935767-0fcccd65-7bcf-4056-bee8-5e3bd842e39d.png)
![image](https://user-images.githubusercontent.com/121872851/222935785-cfb7ce28-d4dd-4762-9db8-f6561ea73841.png)
![image](https://user-images.githubusercontent.com/121872851/222935791-a15daa0a-fbf4-4a18-b0cd-b6205291f879.png)


## Comments
If you'd like to make additional comments that is important for your module entry.
