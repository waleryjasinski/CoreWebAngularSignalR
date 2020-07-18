# CoreWebAngularSignalR

dotnet new webapp --no-https


dotnet tool install -g Microsoft.Web.LibraryManager.Cli
libman 

libman install @microsoft/signalr -p unpkg -d wwwroot/lib/signalr --files dist/browser/signalr.js --files dist/browser/signalr.min.js