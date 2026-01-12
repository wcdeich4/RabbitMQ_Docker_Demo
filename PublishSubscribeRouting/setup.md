sudo dotnet new console --name EmitLog
sudo dotnet new console --name ReceiveLogs
cd ./EmitLog
sudo dotnet add package RabbitMQ.Client
cd ../ReceiveLogs
sudo dotnet add package RabbitMQ.Client