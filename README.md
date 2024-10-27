# TRNSYS_Custom_Types
This repository was created to share custom TRNSYS18 types that were developed by the author DRAOU MOHCINE within the frame of his PhD thesis. All the components that will be shared here were developed using the ProcEDE Laboratory official TRNSYS License. For contact: mohcine.draou@ced.uca.ma ProcEDE FSTG Cadi Ayyad University Marrakech. 

Each custom type comes with and requires 3 files in order to be compiled properly. These file are: 

1- TRNSYS Model File (.tmf) which can be used from this repo or manually created by the user using the TRNSYS18 UI. (NB: if manually created, the user should also export the TRNSYS model file as a Fortran file).
2- Fortran file (.f90), this file is used to define equations that simulate the model behaviour.
3- BMP file (.bmp) which is an optional ICON for your custom  TRNSYS type.


Each model I share here should have these 3 files (sometimes only 2).
