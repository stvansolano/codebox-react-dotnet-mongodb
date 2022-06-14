# CodeBox

[Twitter: @stvansolano](https://twitter.com/stvansolano)

## Do you like it? Give a Star! :star:

If you like or are using this project to learn or start your own solution, please give it a star. I appreciate it!

A ready-to-use, multi-purpose dev environment.

[![Try in PWD](https://raw.githubusercontent.com/play-with-docker/stacks/master/assets/images/button.png)](https://labs.play-with-docker.com/?stack=https://raw.githubusercontent.com/stvansolano/codebox-dotnet/main/docker-compose.yml)

## Docker / Compose / .NET Commands

```
git clone https://github.com/stvansolano/codebox-dotnet.git
cd codebox-dotnet
docker-compose up -d --build
docker exec -it <CONTAINER> bash
dotnet new webapi --name MyWebApi
cd MyWebApi
dotnet run --urls "http://*:5000"
```
