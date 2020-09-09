# HappyStoreSln

Sportsstore: A Real Application

dotnet new globaljson --sdk-version 3.4.101 --output HappyStoreSln/OutdoorProducts
dotnet new web --no-https --output HappyStoreSln/OutdoorProducts --framework netcoreapp3.1
dotnet new sln -o HappyStoreSln
dotnet sln HappyStoreSln add HappyStoreSln/OutdoorProducts 
dotnet new xunit -o HappyStoreSln/OutdoorProducts.Tests --framework netcoreapp3.1
dotnet sln BobsStoreSln add HappyStoreSln/OutdoorProducts.Tests 
dotnet add BobsStoreSln/OutdoorProducts.Tests reference HappyStoreSln/OutdoorProducts 
