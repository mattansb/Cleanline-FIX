# README

This is a fix for the `EEGLAB` pluging [`Cleanline`](https://www.nitrc.org/projects/cleanline/), caused by a conflict between an internal function and a matlab function `strjoin`. This fix changes `Cleanline`'s function's name to `strjoinCL`.

All the files you need to replace  are in the following directory:  
`external/bcilab_partial/dependencies/PropertyGrid-2010-09-16-mod`

They are:  
  
  - `Contents.m`  
  - `helpdialog.m`  
  - `PropertyGrid.m`  
  - `PropertyGridField.m`  
  - `PropertyType.m`  
  - `strjoin.m`  
  - `strsplit.m`  




