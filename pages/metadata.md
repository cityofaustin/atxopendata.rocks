---
title: City of Austin Open Data Metadata Guideline
permalink: /metadata/
layout: default-intro
image:
lead: begin your open data journey here using this starter kit.
subnav_items:
---

Open data publishers must supply metadata for datasets published on data.austintexas.gov. Metadata describes the context, structure, and format of data.  It’s often defined as data about the data. Metadata can be used to manage information resources. It provides potential viewers of the data a better understanding of the data.

The use of standard metadata elements​ (a list of descriptors about a dataset) is required when publishing any dataset to Austin's Open Data Portal. These standard metadata elements provide a common language across City departments and help the public find the data they are searching for.

# Dataset Title
Definition:
Source: Project Open Data Metadata Schema V1.1:Title
ODS - Human-readable name of the asset. Should be in plain English and include sufficient detail to facilitate search and discovery.
City of Austin guidelines:
When choosing a dataset title, remember who your audience is.  Often, city staff use terms and abbreviations that the public won't be familiar with.  Try and create dataset titles that will help researchers find the information they are looking for.  Avoid Acronyms.
Example: Instead of “Unclaimed Property”  think about maybe “Unclaimed funds.”

# Brief Description
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
Human-readable description (e.g., an abstract) with sufficient detail to enable a customer to quickly understand whether the asset is of interest.  Think about providing a more detailed description than with the title.  Brief descriptions can also relate the origin and how it’s organized.
City of Austin guidelines:  
A clear, concise description of the data that can be readily understood by non-technical users. Good descriptions help visitors to the data portal locate and select useful datasets. Useful dataset info might include a list of fields, source, time frame, possible uses, very brief context or background, and what distinguishes it from similar datasets. Minimize government jargon and excessive legal terms or disclaimers.
Example: Rather than calling a dataset “Properties Affected by Organics Diversion Requirements of Universal Recycling Ordinance,” maybe just shorten the description to “Properties affected by Universal Recycling.”  

# Category
Definition:
Source: NO Project Open Data Metadata Schema V1.1:Description
No definition in metadata standards. Go to Project Open Data.
City of Austin guidelines:
Categories help visitors find data by topics they are interested in. Select the most relevant Category from the drop-down list. Only one category can be selected for each dataset.  
Example: Select Recreation and Culture for the dataset Library locations.

# Tags/Keywords
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
Tags (or keywords) help visitors discover your dataset; please include terms that would be used by technical and non-technical users.
City of Austin guidelines:
Suggestions, surround each keyword with quotes. Separate keywords with commas. Avoid duplicate keywords in the same record.
Examples: Dog, Park, leash,

# Row Label
Definition:
Source: No POD
No definition in metadata standards. Go to Project Open Data.  Or maybe Socrata.
City of Austin guidelines:

# License Type
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
The license or non-license (i.e. Public Domain) status with which the dataset or API has been published. There are many types of data licensing.  Only two will be recommended in this document.  
Definitions
For the purposes of Project Open Data, the term “Open License” is used to refer to any legally binding instrument that grants permission to access, re-use, and redistribute a work with few or no restrictions.

An “Open License” must meet the following conditions:
Reuse. The license must allow for reproductions, modifications and permit their distribution under the terms of the original work.

Redistribution. The license shall not restrict any party from selling or giving away the data.
No Discrimination. The license must not restrict anyone from making use of the work in a specific field of endeavor.

Public Domain
Indicates the dataset is not subject to copyright protection. As such, the data can be copied, modified, and distributed, even for commercial purposes, without asking permission.

Creative Commons License
some baseline rights regarding attribution, distribution, commercial use, and derivative works of copyrighted data. More information regarding license options can be found at creativecommons.org

To learn more about City of Austin Open Data Licensing refer to the link below.
data.austintexas.gov definition
PIO Licensing
PIO Terms of Use


Data Provided By
Definition:
Source: Project Open Data Metadata Schema V1.1:Publisher
The publishing entity and optionally their parent organization(s). The Project Open Data Schema refers to this as “Publisher.”
City of Austin guidelines:
This Socrata field corresponds to the “Publisher” field in POD V1.1 and is the plaintext name of the entity publishing this dataset. Be specific; when possible do not use the COA department name but a smaller subsidiary of the department that might have a closer connection with the data and could answer questions about it.
Example: The publisher of a dataset could be the Austin Animal Center, which is a group within the Austin Public Health department.
Related fields: Source Link, Department.


Source Link
Definition:
Source: No definition in Project Open Data metadata standards. Go to Socrata for this one?
City of Austin guidelines:
Optional. This is to be used when data is produced from a source outside the City of Austin organization. Again, be specific to make for easier inquiries about the data. When applicable, you may also include a URL in this field to allow retrieval of the data from the source, but be careful since URLs can break at any time.
You don’t need to put a link into this field… that actually belongs in another field called “Homepage URL”
Related fields: Data Provided By, Department.

Frequency
Definition:
Source: Project Open Data Metadata Schema V1.1:Frequency
The frequency with which dataset is published.
City of Austin guidelines:
This is a dangerous field since you are setting expectations for the frequency of updates. Specify how often the data is updated if it is produced by an automated, regular process or if the law requires it to be updated on a certain schedule. If neither is the case, specify “irregular” with [maybe?] a note about how often you expect the data to be updated.


Department
Definition:
Source: No definition in Project Open Data metadata standards. Go to Socrata for this one?
City of Austin guidelines: The formal name of the Department most closely related to the dataset, according to the current approved budget. Ideally, this would be a parent department of the entity listed in the Data Provided By field.
Example: Animal Services
Related fields: Data Provided By


Dataset Page
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
No definition in metadata standards. Go to Project Open Data. Maybe Socrata for this one.
City of Austin guidelines:
Guidelines go here


Row Class
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
No definition in metadata standards. Go to Project Open Data. Maybe Socrata for this one.
City of Austin guidelines:
Guidelines go here

Subject Column
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
No definition in metadata standards. Go to Project Open Data. Maybe Socrata for this one.
City of Austin guidelines:
Guidelines go here





Resource Name
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
No definition in metadata standards. Go to Project Open Data. Maybe Socrata for this one.
City of Austin guidelines:
Guidelines go here


Row Identifier
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
No definition in metadata standards. Go to Project Open Data. Maybe Socrata for this one.
City of Austin guidelines:
A row identifier can be established for any Socrata dataset. A row identifier is a specific column of a dataset that contains values that uniquely identify each row in the dataset. In other words, the value in this column cannot be the same for any two rows in the dataset, it must be different for each row. A common column to use is an ID column with some kind of number or code that identifies that row of data. Row identifiers are required for using the Upsert function within Datasync.
How to set a row identifier
Step 1: The row identifier is set through the "Edit Metadata" page, which can be accesed one of two ways.
Step 2: From the Primer page, select "Edit Metadata" in the About section of the page. If viewing the "Grid View", select the About pane on the dataset which will open up a box on the screen. From here select the "Edit Metadata" button.
Step 3: Once on the edit metadata page, Scroll to the subheader called “API Endpoint”, in this section you can select the row identifier from the drop down menu that contains all the columns within the dataset.
Step 4: After selecting the appropriate column. Click “Save” at the bottom.



Thumbnail Image
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
No definition in metadata standards. Go to Project Open Data. Maybe Socrata for this one.
City of Austin guidelines:
Guidelines go here

Attachments
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
No definition in metadata standards. Go to Project Open Data. Maybe Socrata for this one.
City of Austin guidelines:
Guidelines go here

Contact Information
Definition:
Source: Project Open Data Metadata Schema V1.1:Contact Name and Email
Contact person’s name and email for the asset.
City of Austin guidelines:
Please enter only an email address. [can they use multiple ones?] [why only email?]







City of Austin Priorities
Definition:
Source: No POD
Citywide priorities set forth by the City Manager’s Office. These groupings are available internally for sorting information.
City of Austin guidelines:
These categories help City staff working on projects to advance the Imagine Austin Comprehensive Plan (30-year horizon) and the Citywide Strategic Plan (3-5 year horizon).
Select the most relevant priority from the Imagine Austin and Strategic Planning Outcome drop-down lists. If none apply, select “Not Applicable.” For a complete description of the priorities, visit:
Imagine Austin Vision Statement
Imagine Austin Priority Programs
If your data is related to more than one City priority, you may select a “secondary” priority in the next field. This is optional but encouraged if you think your data would be of interest to another team.                                                                                                                     
Primary: (required)
1.       Household Affordability
2.       Healthy Austin
3.       Compact & Connected
4.       Land Development Regulations (CodeNEXT)
5.       Sustainable Water
6.       Green Infrastructure
7.       Workforce Development
8.       Creative Economy
9.       Complete Communities (Imagine Austin vision)
10.   N/A

Secondary: (optional)
1.       Household Affordability
2.       Healthy Austin
3.       Compact & Connected
4.       Land Development Regulations (CodeNEXT)
5.       Sustainable Water
6.       Green Infrastructure
7.       Workforce Development
8.       Creative Economy
9.       Complete Communities (Imagine Austin vision)
10.   N/A

City of Austin Strategic Outcomes
Definition:
Source: Project Open Data Metadata Schema V1.1:Description
Strategic Plan Outcome (3-5 year horizon)
Primary: (required)
1.       Economic Opportunity and Affordability
2.       Mobility
3.       Safety
4.       Health
5.       Cultural and Learning Opportunities
6.       Government that Works for All of Us
7.       N/A
Secondary: (optional)
1.       Economic Opportunity and Affordability
2.       Mobility
3.       Safety
4.       Health
5.       Cultural and Learning Opportunities
6.       Government that Works for All of Us
7.       N/A

City of Austin guidelines:
What should publishers think about when choosing one or more outcomes?
City of Austin Strategic Plan Outcomes
