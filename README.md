# About This Repository
This repository contains templates for project bases:
* template TwinCAT 3.1 project with correct base settings and a default plc project, named as required in the .gitIgnore file
* template .gitIgnore file
* template library categorization xml 
* best practices XAE environment setup for git integration 


# Template TwinCAT 3.1 project

## Specifics
* Contains PLC project
* PLC project is named PLC according the PLC.tmc ignore rule of the template .gitIgnore file
* PLC project is not pinned
* PLC project libraries are not fixed
* File/Email Archive only contains Project sources (smaller archives by default)

## Usage
* fork / clone
* use


# Template .gitIgnore file
Created by https://www.toptal.com/developers/gitignore/api/twincat3,visualstudio
Edit at https://www.toptal.com/developers/gitignore?templates=twincat3,visualstudio

## Usage
Best practice for this .gitIgnore is to name the PLC project PLC

## Remark on tmc file(s) inclusion
The .gitIgnore file includes the following tmc rules
Don't include the tmc-file rule if either of the following is true:
   1. You've got TwinCAT C++ projects, as the information in the TMC-file is created manually for the C++ projects (in that case, only (manually) ignore the tmc-files for the PLC projects)
   2. You've created a standalone PLC-project and added events to it, as these are stored in the TMC-file.
   3. shared tmc files are used to exchange data types that should be persisted in the project
#*.tmc
plc.tmc
*.tmcRefac


# Template library categorization xml

## 2 templates included
* base template 'Example.libcat.xml'
* example template 'Oscat.libcat.xml'

## Usage
* create a unique GUID for the different sub elements https://guidgenerator.com/
* use the created GUID
* name the different subelements
* fill in the necessary data for the different sub elements


# Best practices XAE environment setup for git integration 


