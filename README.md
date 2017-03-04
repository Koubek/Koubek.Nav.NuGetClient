# NuGet client for MS Dynamics NAV
This repo contains NuGet client for MS Dynamics NAV. 
Right now the packages can be installed on both, on the server and client side.
The idea is to have your own NuGet server (easy to do) and be able to deploy your .NET developments there into the repository and then download them from NAV and leave them in the *add-ins* folder.


# Disclaimer
There are some issues related with the paging (partial loading of the next buckets).


# Getting started
* Renumber NAV objects to fit your requirements.
* Import objects.
* Run the initialization process - REPORT: **NuGet Setup Init.**
* All required libraries will be deployed automatically during the previous step. NAV setups will be created as well.
* Open PAGE: **NuGet Packages**
* Select a package + press button **Install** (or select a specific package and version + **Install package version**)


# To-do
* Package lists (deploy automatically all packages from the list and their dependencies).