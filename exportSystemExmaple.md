curl -u AdminUser:Pass -H "Content-Type: application/json" -X  POST  http://hostname:8081/artifactory/api/export/system -d '{ 
"exportPath" : "<PhisicalPath>" ,
"includeMetadata" : true,
"createArchive" : false ,
"bypassFiltering" : false,
"verbose" : false ,
"failOnError" : true ,
"failIfEmpty" : true ,
"m2" : false ,
"incremental" : false ,
"excludeContent" : false 
}'
