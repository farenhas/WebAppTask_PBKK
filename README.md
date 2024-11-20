- instead of using ```curl http://localhost:8080/albums \
    --header "Content-Type: application/json" \
    --request "GET" ```,

   use 
  ``` Invoke-RestMethod -Uri "http://localhost:8080/albums" `
    -Headers @{"Content-Type" = "application/json"} `
    -Method GET ```
