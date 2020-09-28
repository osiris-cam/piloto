# **Data Preprocessing Resume**
-------------------------------------------------------------------------------------------------------------------------
## Data Importation.
### Define the data table concept.        
Datatables allow you to create data tables with features such as paging, instant search, export, and multi-column sorting.
DataTables comes with an extensive API that is used to manipulate or obtain information about the DataTables on a page.
The API can be accessed in 3 ways:

```
var table = $('#tableid').DataTable(); //DataTable() returns an API instance immediately
var table = $('#tableid').dataTable().api(); //dataTable() returns a jQuery object
var table = new $.fn.dataTable.Api('#tableid');
```

In Python is widely used for fast aggregation of large datasets, low latency add/update/remove of columns, quicker ordered joins, and a fast file reader. Here you need to instal your modul:        

```import datatable as dt```   


![DataTable](https://miro.medium.com/max/1342/1*hgMH-aKTyU7UF43rf6n_Zg.png)

### Data types: 
#### Categorical:   
represent characteristics such as a person’s gender, marital status, hometown, or the types of movies they like. Categorical data can take on numerical values for example  *1* indicating a person is male or *2* indicating female, however these numbers don’t have a mathematical meaning. Another examples is the typical YES/ NOT. In this type we have a classification of data ( but in this picture we have the resume of both types of data):     


![Categorical](https://o.quizlet.com/8UUywzzaMhY2ZGHrWE7VkA_b.png)
#### Numeric:   
These data have meaning as a measurement, such as a person’s height, weight, IQ, or blood pressure. In this type we have a classification of data:   


![Numeric](https://miro.medium.com/max/802/1*lheLiN7y4sSD2JKvow-clw.jpeg)
#### Boolean:       
The field values for importing Boolean or checkbox data fields are as shown below:
- If checkbox is selected - True or 1
- If checkbox is not selected - False or 0
We must to take sure that the data we plan to import from Boolean or checkbox fields contain values that get properly converted during the import process.
#### Dates:          
The Date data type stores the calendar date. DATE data types require four bytes. A calendar date is stored internally as an integer value equal to the number of days since December 31, 1899. The Date values are stored as integers, we can use them in arithmetic expressions. On another hand, The time data type consists of a time in hour, minutes, seconds, optional fractions of a second, and optional time zone. For example:       

```TIME [time_precision] [time_zone_spec]```
#### Strings.
A string is a sequence of characters. A string is noted by surrounding a group of letters with double quotes "". A String is actually a class with its own methods, some of which are featured below.   


### [Common data formats] (https://data.gov.ie/formats): 
#### csv:
CSV (comma separated values) files are used to store tabular data in plain text format. Most often the fields in this data are separated by commas but other delimiters can be used such as |. TSV (tab separated values) files are similar but breaks are delimited by tabs. Both formats are widely supported and are often used to exchange data across multiple different computers and systems that support the format.
#### json:     
Json (javascript object notation) files are human-readable text files used to transport data in key/value pairs. It is a format widely used on the web and is often the type of data returned from an API call.
Whilst human readable, json is generally used by software as a data source.
#### xml:         
Extensible Markup Language (XML) is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable. The design goals of XML emphasize simplicity, generality, and usability across the Internet. Although the design of XML focuses on documents, the language is widely used for the representation of arbitrary data structures such as those used in web services.

XML is generally more useful to developers and software systems.
#### xls.
To maintain formatting data we will want to save in a proprietary format like XLS (Microsoft Office Excel), ODS (Open Office spreadsheets) or .numbers (Apple Mac), depending on the software we use. 
### Differentiate between local and remote repositories: url, apis.

### Identify the secure data transfer protocols.

### Describe the procedures for data importing.

