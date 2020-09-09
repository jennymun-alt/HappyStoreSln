# HappyStoreSln

SportsStore: A Real Application

Author: Adam Freeman (https://www.apress.com/gp/book/9781484254394)

dotnet new globaljson --sdk-version 3.4.101 --output HappyStoreSln/OutdoorProducts
dotnet new web --no-https --output HappyStoreSln/OutdoorProducts --framework netcoreapp3.1
dotnet new sln -o HappyStoreSln
dotnet sln HappyStoreSln add HappyStoreSln/OutdoorProducts 
dotnet new xunit -o HappyStoreSln/OutdoorProducts.Tests --framework netcoreapp3.1
dotnet sln BobsStoreSln add HappyStoreSln/OutdoorProducts.Tests 
dotnet add BobsStoreSln/OutdoorProducts.Tests reference HappyStoreSln/OutdoorProducts 
