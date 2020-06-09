See other samples: https://github.com/abpframework/abp-samples
## Build
[## Open & Build the Visual Studio Solution](https://docs.abp.io/en/abp/latest/Samples/Microservice-Demo#open-build-the-visual-studio-solution)
Open the samples\MicroserviceDemo\MicroserviceDemo.sln in Visual Studio 2017 (15.9.0+).
Run dotnet restore from the command line inside the samples\MicroserviceDemo folder.
Run dotnet build from the command line inside the samples\MicroserviceDemo folder.
Build the solution in Visual Studio.


[## MsDemo_Identity Database](https://docs.abp.io/en/abp/latest/Samples/Microservice-Demo#msdemo_identity-database)

Right click to the AuthServer.Host project and click to the Set as startup project.
Open the Package Manager Console (Tools -> Nuget Package Manager -> Package Manager Console)
Select AuthServer.Host as the Default project.
Run Update-Database command.

[## MsDemo_ProductManagement](https://docs.abp.io/en/abp/latest/Samples/Microservice-Demo#msdemo_productmanagement)

Right click to the ProductService.Host project and click to the Set as startup project.
Open the Package Manager Console (Tools -> Nuget Package Manager -> Package Manager Console)
Select ProductService.Host as the Default project.
Run Update-Database command.

[## Run Projects](https://docs.abp.io/en/abp/latest/Samples/Microservice-Demo#run-projects)
Run the projects with the following order (right click to each project, set as startup project an press Ctrl+F5 to run without debug):

AuthServer.Host
IdentityService.Host
TenantManagementService.Host
BloggingService.Host
ProductService.Host
InternalGateway.Host
BackendAdminAppGateway.Host
PublicWebSiteGateway.Host
BackendAdminApp.Host
PublicWebSite.Host
