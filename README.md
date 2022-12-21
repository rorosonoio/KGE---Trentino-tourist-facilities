# KGE project- Tourist facilities
This project was developed in the academic year 2022/23 for the course Knowledge Graph Engineering.\
In this page there will be links to all the resources used for this project.

## Project purpose
The aim of this project is to create a KG that can provide information about Trentino’s touristrelated facilities. In another word, the final KG can be used to provide a general-purpose service helping tourists to find information about the various tourism-related hospitality facilities in the region of Trentino. In a nutshell, the purpose of this project is described as:

_”A service which helps the users to know about different tourist facilities in Trentino.”_

## Datasets
Initial resources were taken from the [Open Data](https://dati.trentino.it/) platform of the Trentino region and the website of [Trentino Trasporti](https://www.trentinotrasporti.it/open-data). Other resources were scraped from websites and OpenStreetMap (more information can be found in the report).\
After following the iTelos methodology, the final processed datasets can be found [here](https://github.com/rorosonoio/KGE---Trentino-tourist-facilities/tree/main/Datasets/Data%20Integration).


## Reference schemas
To ensure reusability we took the information from schema.org, which provided us with the structure of our model. In particular, here are the following references:
- [Lodging business](https://schema.org/LodgingBusiness) 
- [Person](https://schema.org/Person) 
- [Tourist attractions](https://schema.org/TouristAttraction) 
- [Food establishment](https://schema.org/FoodEstablishment) 


## ETG
Uniting the entities we extracted from the methodology phases with the reference ontology, we obtained the final ETG.
![ETG](https://github.com/rorosonoio/KGE---Trentino-tourist-facilities/blob/main/Teleologies/Formal%20Modeling/teleont_entity.png?raw=true)

## Knowledge Graph
At the end of this process we were able to construct the final Knowledge Graph and, through GraphDB, we called our queries presented as competency questions with SPARQL language. \
We ended up with:
- 15 E-types  
- 10 object properties  
- 27 data properties

## Repository
For more information please check [the complete repository](https://github.com/rorosonoio/KGE---Trentino-tourist-facilities).\
If more detailed information is needed, the complete report can be found [here](https://github.com/rorosonoio/KGE---Trentino-tourist-facilities/blob/main/KGE_2022_tourist-facilities.pdf).
