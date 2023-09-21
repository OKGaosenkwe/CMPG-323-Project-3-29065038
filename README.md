# CMPG-323-Project-3-29065038
# Overview
The web app code was provided for the students to align with the project's focus on Standards & Patterns. Necessary modifications were made mainly within the Startup.cs, and the concealed appsettings.json specified in .gitignore to successfully complete the project. Additionally, a "Repository" folder to organise a tier 2 repository pattern. This involves all controller repositories inheriting from a unified interface adhering to SOLID principles. Notably, specialized methods within the GenericRepository, effectively reducing redundant code and optimizing reusability in line with the dependency inversion principle. 

## How to Use the Wep App
The app was hosted locally and published on Azure because I ran out of credits, but once app has loaded the user will see such:![homepage](https://github.com/OKGaosenkwe/CMPG-323-Project-3-29065038/assets/92356409/d9e36973-ef35-4579-b1c8-bc53dd2fa03d)

The user then needs to specify the specific controller to use its endpoints by clicking on it. After specifying the clicking in the controller that wants to be used, the user will see a page like this which is also similar for Orders and Products:
![Customer](https://github.com/OKGaosenkwe/CMPG-323-Project-3-29065038/assets/92356409/d54f4d20-efa8-4f9b-b129-ed8cbb2b8444)

The user can then choose to edit, view or delete an existing record or create a new record.
Edit:![edit](https://github.com/OKGaosenkwe/CMPG-323-Project-3-29065038/assets/92356409/576e4b6b-2e41-4383-b152-056d7f6cb6cd)
Create:![Create](https://github.com/OKGaosenkwe/CMPG-323-Project-3-29065038/assets/92356409/93a370d8-4456-41bb-8f54-ac979c898794)
Delete:![Delete](https://github.com/OKGaosenkwe/CMPG-323-Project-3-29065038/assets/92356409/26cbd471-5cf5-4071-a4a6-bf9f751b5eef)

## Data Access Layer
The SuperStoreContext is only used in the GenericRepository class. The connection string used isfrom the given .json file, which links to a database hosted. The SOLID principles were followed, not directly getting data from each controller.

## Repository Layer
All classes and interfaces have been successfully implemented:
![Repository](https://github.com/OKGaosenkwe/CMPG-323-Project-3-29065038/assets/92356409/2ff311fe-e4f5-4157-810a-0bc76ec721fe)

Dependency injection was done in the Startup.cs file:
![dependencyInjection](https://github.com/OKGaosenkwe/CMPG-323-Project-3-29065038/assets/92356409/c12af47c-e8ca-4ba5-b25e-cc27cc4f6c69)

## Reference List
[References.pdf](https://github.com/OKGaosenkwe/CMPG-323-Project-3-29065038/files/12692214/References.pdf)


