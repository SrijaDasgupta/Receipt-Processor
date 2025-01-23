# Receipt-Processor
To run the code locally we can use in bash: 
go run main.go


For testing we can use in bash:
curl -X POST http://localhost:8080/receipts/process -d @examples/morning-receipt.json -H "Content-Type: application/json"
curl http://localhost:8080/receipts/{id}/points


curl -X POST http://localhost:8080/receipts/process -d @examples/simple-receipt.json -H "Content-Type: application/json"
curl http://localhost:8080/receipts/{id}/points

