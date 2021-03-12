# LV32.2020..PPL.ProjectBuilder
Automate the test and build process
To get started examine the contained example bat files in "\data" to see how an agent should be configured to call "CLI Build from Project Path.bat".
"CLI Build from Project Path.bat" is responsible for calling LabVIEW to ensure a reply gets back to the calling agent.

For a more complete description see the readme for [LV32.2020..ProjectBuilder][1].

## Implemented Functions
Run Caraya unit test, 
Change build spec version to version from project repository git tag, 
Execute build specification,
Copy build product to another folder

### Dependencies
PPL.ClassLoader - HenrikDueholm - https://github.com/HenrikDueholm/LV32.2020..PPL.ClassLoader

## Installation
Link the contained PPLs and batch files into the folder that contains your other PPLs (including the dependency PPLs).
This should be a PPL folder next to the other source repositories.

## Build and Test
Only contains build products so there are no tests here. 
The tests can be found in the source repository: [LV32.2020..ProjectBuilder][1]

[1]: https://github.com/HenrikDueholm/LV32.2020..ProjectBuilder