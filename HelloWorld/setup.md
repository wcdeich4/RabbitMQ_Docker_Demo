dotnet new console --name Send
dotnet new console --name Receive
cd ./Send
sudo dotnet add package RabbitMQ.Client
cd ../Receive
sudo dotnet add package RabbitMQ.Client

write code in Receive/Program.cs and Send/Progeram.cs

sudo dotnet run

[third console in the Send directory]
sudo dotnet run