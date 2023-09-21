# CMPG-323-Project-3-29065038
# Overview
The web app code was provided for the students to align with the project's focus on Standards & Patterns. Necessary modifications were made mainly within the Startup.cs, and the concealed appsettings.json specified in .gitignore to successfully complete the project. Additionally, a "Repository" folder to organise a tier 2 repository pattern. This involves all controller repositories inheriting from a unified interface adhering to SOLID principles. Notably, specialized methods within the GenericRepository, effectively reducing redundant code and optimizing reusability in line with the dependency inversion principle. 

## How to Use the Wep App
The app was hosted locally and published on Azure because I ran out of credits, but once app has loaded the user will see such:![homepage](https://github.com/OKGaosenkwe/CMPG-323-Project-3-29065038/assets/92356409/d9e36973-ef35-4579-b1c8-bc53dd2fa03d)


## Data Access Layer
The SuperStoreContext is only used in the GenericRepository class. The connection string used isfrom the given .json file, which links to a database hosted. The SOLID principles were followed, not directly getting data from each controller.

## Repository Layer

