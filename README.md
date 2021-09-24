# speakright-database
public database for free pronunciation practice


access by: @github/hung80/speakright-database/en/sample/test.json
source:https://lingua.com/english/reading

#1 Structure


testdb/prodb
    language (en...)
        category.json
		filter.json
		licensetype.json
		topics-x.json
		meta.json
-----------
category.json
[{"id": "1", "title": "Proverbs", "sort": "0"}]
licensetype.json
[{"id":"1", "name":"Free"},{"id":"1", "name":"Pro"}]
topics-x.json
[{"id":"1","category":"1,2,5","title":"Title of topic","content":"content", "filter":"0"}]
filter.json
[{"id":"0", "name":"none"}, {"id":"1","name":"admin"}]
meta.json 
{"file": ["category", "filter", "licensetype", "proverbs.json"]}
------
@github/hung80/speakright-database/testdb/en/meta.json
@github/hung80/speakright-database/testdb/en/category.json
@github/hung80/speakright-database/testdb/en/filter.json
@github/hung80/speakright-database/testdb/en/licensetype.json
@github/hung80/speakright-database/testdb/en/proverbs.json

