## Installing Modules

```
go get github.com/spf13/viper
go get google.golang.org/grpc
go get gorm.io/gorm
go get gorm.io/driver/postgres
go get golang.org/x/crypto/bcrypt
go get github.com/golang-jwt/jwt
```

## Register a new User

```
curl --request POST \
  --url http://localhost:3000/auth/register \
  --header 'Content-Type: application/json' \
  --data '{
 "email": "elon@musk.com",
 "password": "1234567"
}'
```

## Login a User

```
curl --request POST \
  --url http://localhost:3000/auth/login \
  --header 'Content-Type: application/json' \
  --data '{
 "email": "elon@musk.com",
 "password": "1234567"
}'
```
