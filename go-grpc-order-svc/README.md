## Installing Modules

```
go get github.com/spf13/viper
go get google.golang.org/grpc
go get gorm.io/gorm
go get gorm.io/driver/postgres
```

## Create Order
```
curl --request POST \
  --url http://localhost:3000/order \
  --header 'Authorization: Bearer ...' \
  --header 'Content-Type: application/json' \
  --data '{
 "productId": 1,
 "quantity": 1
}'
```
