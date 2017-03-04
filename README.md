# NuGet client for MS Dynamics NAV
This repo contains NuGet client for MS Dynamics NAV. 
Right now deploys the libraries (packages) just on the server side. The client part is still missing.
The idea is to have your own NuGet server (easy to do) and be able to deploy your .NET developments there into the repository and then download them from NAV and leave them in the *add-ins* folder.


# Disclaimer
I am uploading these objects just to have them in the repo. 
There have been some changes made in the text files so it is quite possible there could be some issue related to the changes.

I am going to test and eventually fix the objects soon.


# Getting started
* Renumber NAV objects to fit your requirements.
* Import objects.
* Run the initialization process - REPORT: **NuGet Setup Init.**
* All required libraries will be deployed automatically during the previous step. NAV setups will be created as well.
* Open PAGE: **NuGet Packages**
* Select a package + press button **Install** (or select a specific package and version + **Install package version**)


# To-do
* Package lists (deploy automatically all packages from the list and their dependencies).