# dbpedia-sparql-simplify
This library lets you easily create and run SPARQL queries on dbpedia SPARQL endpoint even if you don't know sparql query language.
## What is SPARQL
SPARQL is a semantic search query language. It is short for "SPARQL Protocol and RDF Query Language". You can create and run queries on semantic web using SPARQL query language.
## Why use this library?
In order to retrieve data stored in ``semantic web``, you need to use **SPARQL** queries. You may want to write an application on semantic web or you may just want to examine it. To do both, you need to know SPARQL query language. To learn SPARQL query language, you need to have basic knowledgement on databases. This librarly lets you create SPARQL queries (with some limitations) without knowing SPARQL query language or anything about databases. You can use example.py to do some interesting searches on dbpedia in seconds which would probably take very long on a google search. For example you can do a search like 'Show me the birthdays of children of partners of Johnny Depp'.
## How to use this library
Install dbpedia-sparql-simplify using pip
```console
pip install dbpedia-sparql-simplify
```
Download and run example.py above to examine the structure of SPARQL. Example.py requires unicodecsv to export query results to a .csv file. Use following command to install unicodecsv if you want to run example.py.
```console
pip install unicodecsv
```
All the usages of the library is shown in example.py. I recommend you to look into example.py to understand how to use dbpedia-sparql-simplify.
