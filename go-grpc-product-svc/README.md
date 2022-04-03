## Installing Modules

```
go get github.com/spf13/viper
go get google.golang.org/grpc
go get gorm.io/gorm
go get gorm.io/driver/postgres
```

## Create Product
```
curl --request POST \
  --url http://localhost:3000/product \
  --header 'Authorization: Bearer ...' \
  --header 'Content-Type: application/json' \
  --data '{
 "name": "Product A",
 "stock": 5,
 "price": 15
}'
```

## Fine One Product
```
   curl --request GET \
  --url http://localhost:3000/product/1 \
  --header 'Authorization: Bearer ...'
```
