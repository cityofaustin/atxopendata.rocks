---
title: City Data Liaisons & Publishers
permalink: /publish/
layout: default-intro
image:
lead: begin your open data journey here using this starter kit.
subnav_items:
  - text: Introduction
    permalink: /publish/#introduction
  - text: Meet the City of Open Data Liaisons
    permalink: /publish/#meet-the-city-of-open-data-liaisons
  - text: What Open Data Liaisons and Publishers Do
    permalink: /publish/#what-open-data-liaisons-and-publishers-do
  - text: How to Publish and Import Data
    permalink: /publish/#how-to-import-and-publish-data
  - text: How to Identify Datasets for Publication
    permalink: /publish/#how-to-structure-your-metadata
  - text: How to Publish Data Manually
    permalink: /publish/#how-can-i-publish-data
  - text: How to Structure your Metadata
    permalink: /publish/#how-can-i-publish-data

---

## Introduction
This section is for City of Austin Data Liaisons and Publishers.
Open Data Liaisons and Publishers implement their department’s Open Data plans in relation to the City of Austin’s Open Data Initiative (ODI) and City Manager’s “open by default” directive.

## Meet the City of Austin Open Data Liaisons & Publisher
The Open Data Liaison and Publisher may be a data owner, implementer or coordinator of departmental data and data-related resources. The Open Data Liaison and Publisher will be the single point of contact between the department and the Open Data Initiative team.

## What Open Data Liaisons Do
- Coordinate and manage departmental Open Data efforts in relation to the City of Austin’s ODI.
- Identify new data sets to be published on the COA Open Data Portal.
- Facilitate proper assessment, review and approvals for data to be published and ensure it complies with legal, ethical and security concerns.
- Manage published data sets on the Open Data Portal ensuring data quality, standards and usability.
- Identify various uses of department Open Data that promote transparency, innovation, advanced analytics and performance measurement.
- Participate in City of Austin Open Data outreach, workshops, hackathons, projects and partnerships.


## How to Publish Data on Austin's Open Data Portal
You need to be a city employee with data ready to be used. If you haven't created an account <a href="/atxopendata.rocks/start/">please click here</a> and follow these instructions on how to create an account. Once you have an account, contact the Open Data team and you will be assigned the appropriate permissions.

Before publishing, you will need to identify datesets for publication.

## How to Identify Datasets for Publication

- Consult Public Information Requests: If information is frequently requested by citizens or other agencies, publishing this information on the data portal may be very valuable to the public and decrease the amount of time spent on PIRs. Review reports your department provides to federal or state agencies. These reports (and their underlying data sources) can help identify data which can also be provided to the public.

- Explore what other cities are doing: A number of other cities in the U.S. and around the world are releasing open data to external users. What are people in other cities looking for? What kinds of data are other governments making available? Chances are that if there is a high demand for certain kinds of data in other cities, there may be a high demand for it in Austin as well.

- Search for data already posted on the Portal: Look at Microsoft Excel files or public facing applications, which allow visitors to search for records. The data may not necessarily be available in bulk or in a machine-readable format, but this is a good place to start.

- Review published reports: Published reports are often populated with data that is either compiled or aggregated from internal applications. For example, a public record may indicate that the City has closed 100 projects this month. The application, which maintains information on each project, will likely have additional details (such as the type of project, location, budget, etc.) that could be made public.

- Ask the public for ideas: If you want to find out what data people are looking for, one of the best ways to find out is simply to ask. Check to see on social media/other outlets to see if there are comments or tweets about data you might be able to make available. You can also check on the portal on our forum "Data suggestions"

There are three methods for publishing datasets to data.austintexas.gov:

- Manual: This method is generally used with datasets that are fairly uncomplicated and not updated frequently (refresh rate >4 times/year).

- Automation: When a dataset is updated more frequently, this method allows for automatic updates to Austin's Open Data Portal. If you need wish to choose this route. Please contact the Austin Open Data Initative team or feel free to explore Socrata’s tool, Datasync​, a tool that can be learned by technical and non-technical data publishers/Liaisons alike.

- Programmatic (API to API): If a dataset needs to be updated in real-time, the programmatic method is the best option. However, it requires some technical savvy.​

Using one of these publication methods, the next steps are to upload the data to Austin's Portal. Please note a Data Liaison/Publisher along with his or her department is responsible for reviewing the datasets for its security, quality, and metadata.

### How to Publish Data Manually

To begin publishing manually will need to upload and import your data. Please note, this section is for City employees who are Data Liaisons and Publishers for thier departement.  

Log in from the <a href="http://data.austintexas.gov">Data Portal homepage</a> using your Socrata Account.

<img src="{{ site.baseurl }}/images/starterkit/2.png" class="shrink">

<img src="{{ site.baseurl }}/images/starterkit/3.png" class="shrink">

You will go to your profile page by default.

<img src="{{ site.baseurl }}/images/starterkit/4.png" class="shrink">

Click the “Create a new Dataset” button.

<img src="{{ site.baseurl }}/images/starterkit/5.png" class="full">

#### Note:
- If you do not see this button, contact a facilitator to verify your account has the appropriate role.

You will now be presented with several options.   Select the button that’s labeled “Import a Data File”.

<img src="{{ site.baseurl }}/images/starterkit/6.png" class="full">

We will be using a sample CSV file called "101Sample1.csv".  Select “On my computer”.

<img src="{{ site.baseurl }}/images/starterkit/7.png" class="shrink">

Click “Upload a file”

<img src="{{ site.baseurl }}/images/starterkit/8.png" class="full">


Navigate to the file location: <b>\\coacd.org\dfs\CTMSharedData\Socrata101</b>

<img src="{{ site.baseurl }}/images/starterkit/9.png" class="shrink">


Once loaded, you will be presented with the following.  This is a listing of the target column names to be created on Socrata, the data type, and the current column names from your source file.

<img src="{{ site.baseurl }}/images/starterkit/10.png" class="shrink">


Let's make a few quick edits with public friendly labels.  Change “SR_Desc “ to “SR Description” and “Owning_Dept” to “Owning Department”

<div class="pagebreak"></div>

<img src="{{ site.baseurl }}/images/starterkit/11.png" class="full">

Scroll down to the bottom of the page, click the “Next” button to import your data.


<img src="{{ site.baseurl }}/images/starterkit/12.png" class="full">

<div class="pagebreak"></div>

<img src="{{ site.baseurl }}/images/starterkit/13.png" class="full">

<div class="pagebreak"></div>

## How to Structure your Metadata

Fill in the appropriate “About” information using the <a class="link-color" href="{{ site.baseurl }}/metadata/"> metadata publishing guidline.</a>  This would be the metadata for this dataset. Click “Next” and the dataset will start the creation process.

To learn more about Metadata standards please review the <a href="{{ site.baseurl }}/metadata/">Metadata Guideline</a></p>
Metadata


## How to Create and Edit your Dataset

Click “Next” and the dataset will start the creation process.  Once completed and a notice that it has finished is displayed, click “Finish”.

<img src="{{ site.baseurl }}/images/starterkit/15.png" class="full">

You are now in the Edit mode which is a working copy of your dataset.   Take note of the message window on the screen.  
You have another opportunity to review your dataset and make changes before publishing.

<img src="{{ site.baseurl }}/images/starterkit/16.png" class="full">

Click “OK” and review the dataset.  It looks like we've missed renaming “SR_Stat” so we'll make that edit.

<img src="{{ site.baseurl }}/images/starterkit/17.png" class="shrink">

Click on a column menu for SR_Stat and select “Edit Column Properties”

<img src="{{ site.baseurl }}/images/starterkit/18.png" class="full">

A window will slide out from the right providing an option to rename the column.  Let’s rename it to “SR Status” and click “Update” at the bottom of this window.  The column should now be updated.

<img src="{{ site.baseurl }}/images/starterkit/19.png" class="full">

It also looks like “Zip Code” column has commas.  Let’s make an edit by removing commas.  Like the previous step, click on the column menu title “Zip Code” and select "Edit Column Properties".

<img src="{{ site.baseurl }}/images/starterkit/20.png" class="full">

Review the Zip Code properties and check the “No Commas” check-box under the Number Formatting header.  At the bottom of the window, click “Update” and the formatting should now be updated.

<img src="{{ site.baseurl }}/images/starterkit/21.png" class="full">

## Publish Dataset
Now that all changes have been completed, let’s publish it by hitting the “Publish Dataset” button at the upper right corner of the page. Note that this does NOT make your dataset available to the public; it simply saves the dataset from edit mode.

<img src="{{ site.baseurl }}/images/starterkit/22.png" class="full">

Now that you have learned how to load a dataset, When you are ready,
    continue to the next lesson to learn

## How to Create Filter Views within your Dataset.

Let's create 2 filtered views to show a subset of the new dataset that we've just uploaded. </p>

- Filter Through Records: For the first view you will be able to view all the records with a status change date for the current year of 2015.
- Filter Using a Value: For the second view you will be able to view all the records that are based in one of our new 10-1 districts.

## Filter through Records

For the first view, we'll be creating a filter to show records with Status Change dates starting in 2015 to current.
Let us begining. From the top right menus, select "Filter" (see image below).

<img src="{{ site.baseurl }}/images/gettingstarted/downloaddata3.PNG" class="shrink">

The Filter's window will slide out (see image below). There will be a few options available.  
    We'll be selecting the Filter heading.

<img src="{{ site.baseurl }}/images/starterkit/25.png" class="full">


For the first view, we'll be creating a filter to show records with Status Change dates starting in 2015 to current.  
  Clicking on the "Add a New Filter Condition" provides us options to select the column, a condition, and provide values.
  Select and fill in the options so that it looks similar to the following.

  <img src="{{ site.baseurl }}/images/starterkit/26.png" class="full">

<img src="{{ site.baseurl }}/images/starterkit/27.png" class="full">


Notice that the filtering is done automatically and you are now presented an option to save the view in the upper left corner of the page.Go ahead and click on the "Save As..." button, label the new view appropriately, then Save.

<img src="{{ site.baseurl }}/images/starterkit/28.png" class="full">

<img src="{{ site.baseurl }}/images/starterkit/29.png" class="full">

Congratulations! You've just created and saved your first view!

Note how many records this new view contains.

## Filter Using A Value

Let's return to your original dataset by using the shortcut link within your view page.

Using the same steps from above, create a view that shows all records for Council District 9. Note how many records this new view contains, and how it compares to the previous last step.

<img src="{{ site.baseurl }}/images/starterkit/30.png" class="full">

<img src="{{ site.baseurl }}/images/starterkit/31.png" class="shrink">

At this point you have learned to:
- Load a Dataset
- Create Filter Views

In this tutorial, you will have an opportuinity to:
- Update your dataset with a new file that contains newly added records
- Create a working copy
- Use the Append and Replace Wizard
- Replace and update a dataset

### Support
At any point during this tutorial you need help please contact the Open Data Initiative team.


## How To Update A Dataset </b></h1>

### Step 1
Open your original dataset and click on the "Edit" button from the menu

<img src="{{ site.baseurl }}/images/starterkit/32.png" class="shrink">

### Step 2
A window will slide out on the right.  Click on the "Edit Dataset" button.

<img src="{{ site.baseurl }}/images/starterkit/33.png" class="full">

### Step 3

After a few moments, a working copy of your dataset will be created.  This copy can be identified by the header above the dataset title.

<img src="{{ site.baseurl }}/images/starterkit/34.png" class="full">

### Step 4

Click on the "Edit" button on the menu again and you will now have the option to "Append and Replace".  Select this option and Launch the Append and Replace wizard.


<img src="{{ site.baseurl }}/images/starterkit/35.png" class="full">


<img src="{{ site.baseurl }}/images/starterkit/36.png">

  <hr>

### Step 5

In this case, we will be replacing the current dataset with the new CSV file that has additional records.  Choose "Replace".

<img src="{{ site.baseurl }}/images/starterkit/37.png" class="full">




### Step 6

- Click "Upload a file" and navigate to the file 101Sample2.csv by <a href="\\coacd.org\dfs\CTMSharedData\Socrata101">opening.</a>

<img src="{{ site.baseurl }}/images/starterkit/38.png" class="full">

- Once you have uploaded the file, you will be presented with the following Columns Import interface similar to when creating a new dataset.

- Make sure that all your file columns match the destination columns.

<img src="{{ site.baseurl }}/images/starterkit/39.png" class="full">



### Step 7

Click "Next" button and this should start the process.

<img src="{{ site.baseurl }}/images/starterkit/41.png" class="full">

Once completed, Click the "Finish" button and you will be returned to the "Working Copy" of you dataset.

<img src="{{ site.baseurl }}/images/starterkit/42.png" class="full">



### Step 8

Click the "Publish Dataset" button to complete the replacement update (please be patient as this process may take several minutes.)

   <u> Notice how many records this updated dataset contains.</u>

<img src="{{ site.baseurl }}/images/starterkit/43.png" class="full">



### Step 9

Let's verify that our views were updated as well by clicking your profile button above the menu bar.

<img src="{{ site.baseurl }}/images/starterkit/44.png" class="shrink">



### Step 10

Notice that your dataset and views are now listed under your Account profile.

<img src="{{ site.baseurl }}/images/starterkit/45.png" class="full">



### Step 11

Select the “Status Change 2015” view and compare the number of records we observed from Exercise 2 and notice that the amount of records have changed.  These were automatically updated to reflect the source dataset.

<img src="{{ site.baseurl }}/images/starterkit/46.png" class="full">


### Step 12
Select the “District 9” view and compare the number of records we observed from Exercise 2 and notice that the amount of records have changed.  These were also automatically updated to reflect the source dataset.

<img src="{{ site.baseurl }}/images/starterkit/47.png" class="full">

Congratulations! You have successfully updated a dataset.

## Adding Co​​ntext​

Narratives are a great way to add context to data! This context could be added through a detailed description in the metadata or by creating a separate document. Socrata has a feature called ‘Socrata Narrative,’ where a story about your data can be added and published on the Austin Open Data Portal along with the dataset.


As data visualization expert Stephen Few said, “Numbers have an important story to tell. They rely on you to give them a clear and convincing voice.” A narrative accompanying data helps explain to the audience what is happening in the data and what points to focus on.

## Data Standardization

Data standardization refers to the process of transforming data into a common format that allows for consistency, reliability, and better analyses.

​Socr​ata recommends the adoption of open data standard in three areas:

Data Catalog Interoperability: Enable universal federation of different open data catalogs using a standard catalog schema, based on the W3C Data Catalog Vocabulary (DCAT)
Data Portability Based on Standard Data Formats: Standardize outputs including JSON, XML, and CSV, as well as RDF and other Linked Data standards. The goal is to move towards standard schemas that developers can use for popular datasets, based on real-world examples and collaboration between data publishers
Application Portability Based on Open Data API Standards: Standardize the application programming interfaces (APIs) used to programmatically access open data, using established paradigms and protocols such as REST, HTTP, and Structured Query Language (SQL)
