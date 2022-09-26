# EntityFrameWorkTutorial

## History of .NET
- .NET Framework == Only for Windows, closed source
- .NET Core == Cross platform (Windows, Mac, Linux, Mobile), open source
- .NET 5 and .NET 6 is the most recent version of what was known as .NET Core

## Dynamic-Link Library
-Library of code that contains functions that we are going to call

## Object Code
Relocatble code (take it and load it on another computer)


## Nuget Packages
- Packages of code for others to use based on the needs of their project and they are available in Tools --> Nuget Package Manager
- Packages that we need for the project:
(see https://wecancodeit.instructure.com/courses/137/pages/setting-up-entity-framework-core)

## Set up Our Model
- Set up the data in a models folder

## Set up our DbContext
- Override OnConfiguring method with connection string
- Put in our seed data in an overridden OnModelCreating method

## Migrating our data
- After we've added our seed data, we can then send it over to the database
1. We need to add a migration
	-Access the Package Maanger Console from Tools--> NuGet Package Manager --> Package Manager Console
	- 
2. Update our database