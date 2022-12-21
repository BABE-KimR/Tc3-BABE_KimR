# About This Repository

Default .gitIgnore file
Created by https://www.toptal.com/developers/gitignore/api/twincat3,visualstudio
Edit at https://www.toptal.com/developers/gitignore?templates=twincat3,visualstudio

# Usage
Best practice for this .gitIgnore is to name the PLC project PLC

# Remark on tmc file(s) inclusion
The .gitIgnore file includes the following tmc rules
Don't include the tmc-file rule if either of the following is true:
   1. You've got TwinCAT C++ projects, as the information in the TMC-file is created manually for the C++ projects (in that case, only (manually) ignore the tmc-files for the PLC projects)
   2. You've created a standalone PLC-project and added events to it, as these are stored in the TMC-file.
   3. shared tmc files are used to exchange data types that should be persisted in the project
#*.tmc
plc.tmc
*.tmcRefac
