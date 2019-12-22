# Neo4j-Database-exploration
In this project, Graph Database “Neo4j” has been explored by building a relationship/ visualization by creating vertices, edges, and attributes.

Using the below web link:
https://www.arcgis.com/apps/MapJournal/index.html?appid=a546b46a7fb942008455e072c69ea767
extracted the names of the volcanos, name of the continent/ area/ country, where it is located, and when last erupted.
Downloaded, and installed graph database - “Neo4j”, and performed the following steps:
1. Considering each continent or country as a node,
2. For each continent or country, added a name. (e.g. name: “USA)
3. Considered each volcano as a node
4. For each volcano, added eruption history, and area. (e.g. name: “Novarupta”, and location:
“Alaska, USA”, Last erupted: 1912)
5. All continents must be connected using edges (neighbor relationship).
6. All super volcanoes within each continent must be connected using edges (neighbor
relationship)
7. There should be an edge between continent and the volcanoes within that continent
(contains relationship)
8. Once the graph is constructed using Neo4j, using analytics and visualization displayed the
continent that has more number of super volcanoes.
