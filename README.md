# Solr PSQL

http://stackoverflow.com/questions/31733876/solr-and-postgresql-integration

https://wiki.apache.org/solr/DataImportHandlerFaq#Running_Out_of_Memory_with_Postgresql

http://blog.comperiosearch.com/blog/2014/08/28/indexing-database-using-solr/

https://gist.github.com/rnjailamba/8c872768b136a88a10b1

https://gist.github.com/rnjailamba/dc5068fbd883d963f7ec

url of psql http://stackoverflow.com/questions/41921820/solr-postgresql-basic-configuration

http://stackoverflow.com/questions/23228727/deleting-solr-documents-from-solr-admin

querys https://cwiki.apache.org/confluence/display/solr/Common+Query+Parameters

boost http://yonik.com/solr/query-syntax/

https://wiki.apache.org/solr/SolrQuerySyntax

edismax https://cwiki.apache.org/confluence/display/solr/The+Extended+DisMax+Query+Parser

boost query http://stackoverflow.com/questions/29377720/how-to-down-boost-a-term-in-dismax

functions https://cwiki.apache.org/confluence/display/solr/Function+Queries

!boost stuff https://cwiki.apache.org/confluence/display/solr/Other+Parsers#OtherParsers-BoostQueryParser

show score http://lucene.472066.n3.nabble.com/How-to-get-the-score-in-the-result-td493812.html

proximity to number

food_group:"Proteins" OR
calories:100

(
food_group:"Proteins"  OR
food_group:"Dairy"  OR
food_group:"Grains" 
 )
 AND
calories:[0 TO 300]


calories desc


cors mac 
open -a "Google Chrome" --args --disable-web-security --user-data-dir

