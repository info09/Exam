## Tedu Exam project

## Docker Command Example

- docker run --name sqlserver -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=123456a' -p 1433:1433 -d mcr.microsoft.com/mssql/server:2017-latest
- docker ps or docker container ls
- docker run -d --name mongodb -e MONGO_INITDB_ROOT_USERNAME=mongoadmin -e MONGO_INITDB_ROOT_PASSWORD=123456a -p 27017:27017 mongo
