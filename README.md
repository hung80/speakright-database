# speakright-database
public database for free pronunciation practice


access by: @github/hung80/speakright-database/en/sample/test.json
source:https://lingua.com/english/reading

#1 Structure


testdb/prodb
    language (en...)
        filter.json
		licensetype.json
		topics-x.json
		meta.json
-----------
licensetype.json
[{"id":"1", "name":"Free"},{"id":"1", "name":"Pro"}]
topics-x.json
[{"id":"1","parents":"1,2,5","title":"Title of topic","content":"content", "filter":"0", "leaf":0|1,"autosplit":0|1}]
filter.json
[{"id":"0", "name":"none"}, {"id":"1","name":"admin"}]

meta.json 
{"files": {"filter": 1, 
	"licensetype": 1, 
	"topic-proverbs.json": 1
	}
}
------
https://api.gitrows.com/@github/hung80/speakright-database/testdb/en/meta.json
https://api.gitrows.com/@github/hung80/speakright-database/testdb/en/category.json
https://api.gitrows.com/@github/hung80/speakright-database/testdb/en/filter.json
https://api.gitrows.com/@github/hung80/speakright-database/testdb/en/licensetype.json
https://api.gitrows.com/@github/hung80/speakright-database/testdb/en/proverbs.json

