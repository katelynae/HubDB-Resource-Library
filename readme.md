![HubSpot](https://cdn2.hubspot.net/hubfs/327485/HubSpot%20Wordmark%20-%20Full%20Color.png "HubSpot")
## Code Gallery

---

# Module - HubDB Resources Library w/ Filters
This module is intended to be used with [HubSpot's HubDB tool](https://designers.hubspot.com/docs/tools/hubdb) to create a library section for external resources. The list of available resources can be filtered by search or content type and a 'Featured' resource can also be chosen.


## How to use this module

Before using this module you must create a HubDB table first to store your resources listing information. Instructions on how to create and edit a HubDB table can be found [here](https://knowledge.hubspot.com/articles/kcs_article/cos-general/how-to-edit-hubdb-tables).

### Step 1 - Create HubDB table

In order for the HubL contained within this module to work correctly the HubDB table must contain the following columns, column names must match exactly:

| Column Label        	 | Column Name           | Column Type   |
| ------------------- 	 |:---------------------:| ------------: |
| Name                	 | name                  | text          |
| Content Type		  	 | content_type 		 | select 		 |
| Image 			  	 | image 				 | image 		 |
| Description 		  	 | description 		  	 | rich text 	 |
| Download Link 	 	 | link 		 		 | URL 	 		 |
| Featured Resource 	 | featured 			 | checkbox 	 |



### Step 2 - Place module on any HubSpot CMS Page

Once you have your table created and this module downloaded into your design manager you can place the module on any HubSpot template or page. Choose the HubDB table data you wish to use within the module by selecting the 'HubDB Table' module field.


