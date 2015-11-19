Sample CURL requests to try out the REST API in Go Lang ! :D

curl -H "Content-Type: application/json" -X POST -d '{"Name":"John Smit","Address":"1600 Amphitheatre","City":"Mountain View","State":"CA","Zip":"94113"}' http://localhost:8083/locations

curl -H "Content-Type: application/json" -X PUT -d '{"Name":"John Smit","Address":"16007 Amphitheatre","City":"Mountain View","State":"CA","Zip":"94113"}' http://localhost:8083/locations/1

curl -H "Content-Type: application/json" -X DELETE http://localhost:8083/locations/1
