# Example of a revit not shared project

![image](https://github.com/user-attachments/assets/2fd422dc-5193-43d3-9372-ddef712e827a)
## Code Structure
All I did was take 2020 project and add **conditional compilation symbols** to seperate code changes between the years 
## Folder Structure
- src
  - RevitSharedProject
    - ExtensibleStorageManagerShared
    - SchemaWrapperToolsShared    
    + **RevitSharedProject.sln**
      
The shared projects became a normal project with multiple configuration for selection the correct version of Revit API.

The `libs` folder was removed and replaced with Nuget packages `Revit_All_Main_Versions_API_x64` to make it easier to manage the Revit API versions.