# Receipt-Processor
To run the code locally we can use: 
go run main.go


For testing we can use:
curl -X POST http://localhost:8080/receipts/process -d @morning-receipt.json -H "Content-Type: application/json"
curl http://localhost:8080/receipts/{id}/points


curl -X POST http://localhost:8080/receipts/process -d @simple-receipt.json -H "Content-Type: application/json"
curl http://localhost:8080/receipts/{id}/points

