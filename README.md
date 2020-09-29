# HappyStoreSln

## SportsStore: A Real Application

Author: Adam Freeman (https://www.apress.com/gp/book/9781484254394)

    dotnet new globaljson --sdk-version 3.4.101 --output HappyStoreSln/HappyStore
    dotnet new web --no-https --output HappyStoreSln/HappyStore --framework netcoreapp3.1
    dotnet new sln -o HappyStoreSln
    dotnet sln HappyStoreSln add HappyStoreSln/HappyStore 
    dotnet new xunit -o HappyStoreSln/HappyStore.Tests --framework netcoreapp3.1
    dotnet sln BobsStoreSln add HappyStoreSln/HappyStore.Tests 
    dotnet add BobsStoreSln/HappyStore.Tests reference HappyStoreSln/HappyStore  

Below are the screenshots

## Chapter 7: A Real Application

Welcome Screen

![Welcome Screen](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/WelcomeScreen1.GIF)

Figure 7-9

![Figure 7-9](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/Figure%207-9.JPG)

## Chapter 8: Navigation and Cart

Figure 8-5

![FIgure 8-5](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/Figure%208-5.JPG)

Figure 8-10

![Figure 8-10](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/Figure%208-10.JPG)

Figure 8-11

![FIgure 8-11](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/Figure%208-11.JPG)

Tests

![Tests](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/HappyStoreTests.JPG)


## Chapter 9: Completing the Cart

Figure 9-4

![Figure 9-4](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/Figure%209-4.JPG)

Figure 9-5

![Figure 9-5](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/Figure%209-5.JPG)

Figure 9-6

![Figure 9-6](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/Figure%209-6.JPG)

Tests

![Tests](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/Test%209.JPG)

## Chapter 10: Administration

![Final Page](https://github.com/jennymun-alt/HappyStoreSln/blob/master/screenshots/Chapter%2010.JPG)
