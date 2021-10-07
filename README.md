# Amira_MaskFromLabels
Amira 3D software TCL module that allows the user to mask a dataset based on one or more label fields

SETUP:
Copy all three files into the directory [Amira installation directory]/share/script-objects
Open Amira

USAGE:
Use this module when you have defined one or more labels on a dataset and want to mask the dataset using those labels.

1. Load a dataset and create a label field with one or more materials. 
2. Right click the data object, choose the menu grouping "CAMI Custom", and select the module "Mask From Labels"
3. Connect the new object's "label field" port to your label field
4. If desired, select "Auto crop masked data" to apply the auto crop tool with a threshold of 0 to the masked data. This can be useful if you are only keeping a small portion of a large dataset and wish to reduce the file size.
5. Press the 'Apply' button. The script will create one new dataset per material, named by appending the material name to the dataset name.

Documentation within Amira can be accessed by clicking the '?' button in the top right hand corner of the Mask From Labels object's properties view.
