Visual Studio 2015 - MVC 5

The BBC news service is in Services folder.

The DB access in in DataLayer folder.
Uses Repository and Unit of Work patterns. A bit overkill probably for this but wanted to demonstrate.

Ninject for IOC. Config for this in the Infrastructure folder.

Used Home controller and Index() so no surprises.
Each new request generates an ID on the wrapper 'Headline' object. All saved articles thereafter use this as their parent Id.

Two tests. One for the Controller accessing the BBC service. The other the Service direct.
