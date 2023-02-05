# Search Microservice

## Opis / Description
Mikroserwis służący do wyszukiwania pełonetekstowego za pomocą Elastic Search.

Mikroserwise stworzony w ramach grupowego projektu studenckiego, polegającego na napisaniu platformy e-learningowej w architekturze mikroserwisowej.
Ja byłam odpowiedzialna za mikroserwisy związane z wyszukiwaniem pełnotekstowym oraz za mikroserwis autoryzacyjny.

[ENG]

Microservice that allows full-text search with Elastic Search.

The microservice was created as a part of a university group project, the goal of which was to write a e-learning platform in the microservices architekture.
I was responsible for creating the full-text search microservice and the authentication microservice.


## Elastic search:

ES version: 7.17.3

Download and start with:

docker run -p 9200:9200 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:7.17.3


