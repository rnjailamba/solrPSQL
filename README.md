# Solr PSQL

solr better than sql - http://stackoverflow.com/questions/4960952/when-to-consider-solr

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

functions and show score https://cwiki.apache.org/confluence/display/solr/Function+Queries

!boost stuff https://cwiki.apache.org/confluence/display/solr/Other+Parsers#OtherParsers-BoostQueryParser

show score http://lucene.472066.n3.nabble.com/How-to-get-the-score-in-the-result-td493812.html

search for prefix* http://stackoverflow.com/questions/21576868/solr-search-for-near-matches

fuzzy searches http://lucene.apache.org/core/3_6_0/queryparsersyntax.html#Fuzzy%20Searches

To read - querys
https://www.finalist.nl/techblog/2015/06/improving-search-result-with-search-api-solr-custom-boosting/
https://lucidworks.com/2011/12/14/options-to-tune-documents-relevance-in-solr/
http://stackoverflow.com/questions/20217686/multiple-boost-queries-in-solr
https://cwiki.apache.org/confluence/display/solr/Local+Parameters+in+Queries
https://home.apache.org/~hossman/bbuzz2014/
https://nolanlawson.com/2012/06/02/comparing-boost-methods-in-solr/
https://cwiki.apache.org/confluence/display/solr/The+Extended+DisMax+Query+Parser
https://cwiki.apache.org/confluence/display/solr/Other+Parsers#OtherParsers-BoostQueryParser

To read - search
http://stackoverflow.com/questions/11474778/solr-nearest-match-does-this-functionality-exist
auto gen phrase querys http://stackoverflow.com/questions/16175234/solr-how-to-get-most-nearest-match-of-title

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

