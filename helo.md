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
#### Boolean
#### Dates
#### Strings.

### Describe the common data formats: csv, json, xml y xls.

### Differentiate between local and remote repositories: url, apis.

### Identify the secure data transfer protocols.

### Describe the procedures for data importing.
