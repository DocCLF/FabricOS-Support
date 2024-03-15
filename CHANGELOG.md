# FabricOS CLI Support Change Log

All notable changes to the "FabricOS CLI Support" extension will be documented in this file.


## [Unreleased]
* I am currently working on a module for VS-Code based on this snippet.
* add more "helper functions"
* add some powershell functions
* maybe i will change the snippet to *.json in the future

## 0.0.4
### Friday, March 15, 2024
Improvemnt
* rename trufos in trufos_setup in the Subcategory

Removed 
* ibm_usefull_thing Flag, so that only the Subcategory is needed

Bugfixes:
* fixed passwdcfg and passwd
* fixed secPolicyDelete 
* fixed lscfg and lscfg_Port
* fixed fosconfig --show
* fixed a bug between portCfgNPIVPort and portCfgNPort
* fixed a bug between firmwaredownload and firmwarecleaninstall
* fixed a bug between roleConfig_del and roleConfig
* fixed a lot of commas after, the last vscode update

## 0.0.3
### Saturday, March 03, 2024
Added:
* new Commandos 

Improvemnt 
* Added information on the procedure for the ibm_usefull_thing category

Bugfixes:
* fixed a bug at chuser and chusergrp 


## 0.0.2
### Friday, Febuary 16, 2024
Added:
* new Commandos 

Improvemnt 
* Categorization of commands for a better overview, for more information check the readme
* "fos" flagg added for better separation from other commands
* Icon adjusted

Bugfixes:
* removed unnecessary blanks in some commands
* unnecessary symbols removed


## 0.0.1
### Wednesday, Febuary 07, 2024

Initial release with the following features:

* initial release
* supports the commands from FOS 9.0 
