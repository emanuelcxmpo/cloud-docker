# REPOSITORIO CLOUD

https://hub.docker.com/repository/docker/emanuelcxmpo/sqlserver-2022/general

docker pull emanuelcxmpo/sqlserver-2022:1.0

docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=Cloud202402" -p 1433:1433 --name sqlserver2022 -d emanuelcxmpo/sqlserver-2022:1.0
