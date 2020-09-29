# **Data Preprocessing Resume**
-------------------------------------------------------------------------------------------------------------------------
## Data Importation.
### Define the data table concept.        
Datatables allow us to create data tables with features such as paging, instant search, export, and multi-column sorting.
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
Represents characteristics such as a person’s gender, marital status, hometown, or the types of movies they like. Categorical data can take on numerical values for example  *1* indicating a person is male or *2* indicating female, however these numbers don’t have a mathematical meaning. Another examples is the typical YES/ NOT. In Pytho we can use the Categorical data with Pandas. In this type we have a classification of data ( but in this picture we have the resume of both types of data):     


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


### [Common data formats](https://data.gov.ie/formats): 
#### csv:
CSV (comma separated values) files are used to store tabular data in plain text format. Most often the fields in this data are separated by commas but other delimiters can be used such as |. TSV (tab separated values) files are similar but breaks are delimited by tabs. Both formats are widely supported and are often used to exchange data across multiple different computers and systems that support the format.
#### json:     
Json (javascript object notation) one of the standart formats for sending data by HTTP request between web browsers and other applications. It is a much more free-fform data format than a tabular text form like CSV. Example:    
```
onj= """
{"name" = "wes,     
"places_lived": ["United States", "Spain", "Germany"],
"pet": null,
"siblings:[{"name": "Scott", "Aage": 30, "pets":["zeus", "zuko"]}   
{"name": "Katie", "age": 38,    
"pets": ["Sixes", "Stache", "Cisco"]}]     
}     
"""
```

#### xml:         
Extensible Markup Language (XML) is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable. The design goals of XML emphasize simplicity, generality, and usability across the Internet. Although the design of XML focuses on documents, the language is widely used for the representation of arbitrary data structures such as those used in web services.

XML is generally more useful to developers and software systems.
#### xls.
To maintain formatting data we will want to save in a proprietary format like XLS (Microsoft Office Excel), ODS (Open Office spreadsheets) or numbers (Apple Mac), depending on the software we use. 
### URL vs API
#### URL: 
Universal Resource Locator. It is the specific address that is assigned to each one of the resources available on the network so that they can be located or identified. Thus, there is a URL for each of the resources (pages, sites, documents, files, folders) in internet.        
#### API.
Application Programming Interfaces. It is a set of definitions and protocols that is used to develop and integrate application software, allowing communication between two software applications through a set of rules. API is like a formal specification that establishes how a module of a software communicates or interacts with another to fulfill one or many functions. All depending on the applications that are going to use them, and the permissions that the API owner gives to third-party developers.
#### DIFFERENCE: 
Both of these services work as a medium of communication but there is a difference between both of them which is that a web service allows communication between 2 machines over an internet
### [Secure data transfer protocols.](https://www.globalscape.com/solutions/secure-file-transfer)
#### Secure File Transfer Protocol (SFTP).
SFTP transfers files with the Secure Shell (SSH) connection – SFTP is an encrypted network protocol that can enable a remote login to operate over a network that lacks security.
#### File Transfer Protocol – Secure (FTPS):
FTPS offers encryption and uses an application layer wrapper, known as Secure Sockets Layer (SSL) to enable secure and private communications across a network.
#### Hypertext Transfer Protocol – Secure (HTTPS).
HTTPS secures websites when users are providing sensitive information like credit card numbers or other personal information.
#### Applicability Statement 2 (AS2)
AS2 is a standard used to transfer Electronic Data Interchange (EDI) messages and other data in real time. 
### Describe the procedures for data importing.
#### Importing TXT
```file = open("sample.txt")
data = file.read()
print(data)
file.close()
```
#### Importing CSV
```file = open("sample.csv")
data = file.read()
print(data)
file.close()
```
### Data structure as a function of its types. 
- Linear: arrays, lists
- Tree: binary, heaps, space partitioning etc.
- Hash: distributed hash table, hash tree etc.
- Graphs: decision, directed, acyclic etc.

