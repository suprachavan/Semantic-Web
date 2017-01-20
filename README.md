# Semantic-Web
Analysis of Movie data on DBpedia using Semantic Web
## Background: 
With numerous movies releasing every week, and still many in their production phase, the film industry is one of the fields offering abundance of data. The challenge comes from the fact that the information pertaining to movies is almost always scattered on the web in form of disjoint websites. Hence, it becomes burdensome to collect the information from the web and present it in form of unified statistics or surveys. This application enables this scattered information to be inferred and presented in a meaningful format.
## Objectives: 
The aim is to build an expert system which acts on the data available on the web pertaining to movies (e.g. release date, budget, profits earned, etc.) over a specific period and infer different informations such as highest grossing films, profits earned by a particular movie or which movies were a financial disaster, etc. This project also has a learning objective as it explores the Semantic Web technologies and how it correlates with developing an expert system.	 	
## Scope: 
In this project, the data of movie is retrieved from the information boxes of Wikipedia’s web page for a particular movie. The data will be restricted for a specific time-frame (e.g. movies released in a specific year or month). The DBpedia ontology is used in conjunction with RDF query language- SPARQL.
By querying the DBpedia ontology with SPARQL queries, we can retrieve meaningful information from the information boxes such as- 
* Highest grossing film of the year.
* Films which were a financial disaster.
* Films which were low on budget but still managed to fare well.
* The profits earned by a particular film.
The system offer an interactive interface where user can enter a specific movie name and can get the above mentioned statistics in return from the system. This UI will be created in Java and Apache Jena framework is used for integrating Java code with SPARQL.
### Take a look at the presentation by visiting this [Link](https://docs.google.com/presentation/d/1TFMww6WFOuVQgt4iiTtjEfW6kPzNXoP_xwXHMlg-rKI/edit?usp=sharing) 
