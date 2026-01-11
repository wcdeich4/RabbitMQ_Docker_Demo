sudo dotnet new console --name NewTask
sudo dotnet new console --name Worker
cd NewTask
sudo dotnet add package RabbitMQ.Client
cd ../Worker
sudo dotnet add package RabbitMQ.Client