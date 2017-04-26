# ageRanger


Net core and EF for SqlLite are used for building REST API. 
Front end built using Angular2 via Typescripts. Rely on typescript compiler to transcompile to javascript. 
Uses MSTest instead of XUnit due to compatibilities issue with build servers like Jenkins and code analysis tools like Sonarcube.

Requires nodejs and node package manager. 

Uses NSubstitute to mock unit test. 

Uses .Net core for DI

Bootstrap for front.

Download code and open using Visual Studio 2017 community edition. Might get an #### "assemblies incompatibility issue" #####, re-build 
and it should be good to go.

#### Step 1. Please ensure REST component is up and running by hitting F5 on Visual Studio.

Provide basic security for REST API - CORS, redirection and TLS. CORS access is allowed from localhost:3000. 

#### Step 2. Run front end 

Goto wwwroot directory, and run the following command :-

npm install -> to install all the required dependencies. 

npm start -> to run UI 

npm test -> to run front end unit testing.

# Notable UI

- Add Person form comes with validation and only submit when you have all the fields correctly validated. 

- Search waits for 800 milisec before firing query

- Karmized test available for ui components. 

