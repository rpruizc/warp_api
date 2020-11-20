### Simple API Rust & WARP

### POST
```
curl --location --request POST 'localhost:3030/v1/groceries' \
--header 'Content-Type: application/json' \
--header 'Content-Type: text/plain' \
--data-raw '{"name":"apple", "quantity":1}'
```

### GET
```
curl --location --request GET 'localhost:3030/v1/groceries'
```

### UPDATE
```
 curl --location --request PUT 'localhost:3030/v1/groceries' \
--header 'Content-Type: application/json' \
--header 'Content-Type: text/plain' \
--data-raw '{"name":"apple", "quantity":5}'
```

### DELETE
```
curl --location --request DELETE 'localhost:3030/v1/groceries' \
--header 'Content-Type: application/json' \
--header 'Content-Type: text/plain' \
--data-raw '{"name":"apple"}'
```