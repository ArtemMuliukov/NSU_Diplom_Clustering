# Cluster_IP - version 0.3

## Content of the repository

### License
The libriary is a product of work under master thesys of Muliukov AR. You could use any content of the code in this repository under license GPL3.

### Content

Here you could find

## Presented files

Here you can find all significant parts of the work. Text version (and more deep description) of the work you can reed in the file [Dipoma_final_version](Diploma_final_version.pdf) (in Russian)

All current code is in the folder 'actual_code'. There you can find 2 folders - "Labview" and "dll". 

"Labview" - with an example of dll usage in IDE LabVIEW. 
The code itself in the file "Experiment_treatment1_ArtemVer1KG.vi" and in "Experiment_treatment1_ArtemVer2_FastKG.vi" (for 2 functions of indicatrices analysis, with and without return of detailed clusters information).
You can find the connection of the dll in page 4 of code window.

"dll" is a full project for Microsoft Visual Studio. You can reassemble it with any needed changes, all needed code is in one file, 
by the adress "NSU_Diplom_Clustering/actual_code/dll/test_dll_creation/test.cpp". MVS project may be opened (with all needed dll installations) by runnig a file "test_dll_creation.sln". All needed files are supplied.

The prepeared dll you can already find on adress "NSU_Diplom_Clustering/actual_code/dll/Release/test_dll_creation.dll".


Also you can find Jupyter notebooks used for tests in Python or constructing of graphs (for conferences or the diploma work itself) in folder "Python tests". Short information about it's content you can find in local readme file.
