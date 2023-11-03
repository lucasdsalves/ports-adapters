docker-compose up -d

docker exec -it appproduct bash

go mod init ports-adapters

mockgen -destination=application/mocks/application.go -source=application/product.go application