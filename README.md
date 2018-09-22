# C-Sharp Project Setup Script - Skye Nguyen

## Description

This bash script will set up your C# project following the structure below:
```
├───Project.Solution
   ├───Project
       ├───Models
           ├───Project.cs
       ├───Views
       ├───Controllers
       ├───Project.csproj
       ├───Program.cs
       ├───Startup.cs
    ├───Project.Tests
       ├───ModelTests
           ├───ProjectTests.cs
       ├───Project.Tests.csproj
    ├───README.md
    ├───.gitignore
```
It will also:
* Initialize your project as a git repository.
* Create an empty README.
* Create a .gitignore with a few relavant rules to C# projects. 
* Write to your .csproj files (including ASP.NET packages).
* Restore the dependencies for your project from the Tests folder.
* Configure MySql database.

## Setup/Installation Requirements

1. Clone this repository:
```
    $ git clone https://github.com/sn31/cs-setup
```
2. To run the script:
```
    $ sh PATH-To-App <ProjectName>
```

## Known Bugs

None known in this version.

## Support and contact details

Please contact us at skye@dames.es for more information and/or feedback.


###### License: MIT.

###### Copyright (c) 2018 Skye Nguyen
