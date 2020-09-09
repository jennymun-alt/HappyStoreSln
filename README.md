# HappyStoreSln

SportsStore: A Real Application

Author: Adam Freeman (https://www.apress.com/gp/book/9781484254394)

    dotnet new globaljson --sdk-version 3.4.101 --output HappyStoreSln/HappyStore
    dotnet new web --no-https --output HappyStoreSln/HappyStore --framework netcoreapp3.1
    dotnet new sln -o HappyStoreSln
    dotnet sln HappyStoreSln add HappyStoreSln/HappyStore 
    dotnet new xunit -o HappyStoreSln/HappyStore.Tests --framework netcoreapp3.1
    dotnet sln BobsStoreSln add HappyStoreSln/HappyStore.Tests 
    dotnet add BobsStoreSln/HappyStore.Tests reference HappyStoreSln/HappyStore  
