# Read-database-polarized-images-
A jupyter notebook to read a database composed of polarized images acquired during two months

The database is here: https://entrepot.recherche.data.gouv.fr/dataset.xhtml?persistentId=doi:10.57745/9L2YUB

Here is a Git describing the database: https://github.com/mol-1/A-2-month-long-annotated-skylight-polarization-images-database---associated-code?tab=readme-ov-file

**If you use this database, please cite this paper:** https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-024-06959-6

The three following files can downloaded from the database:  alpha_crop.npy, theta_crop.npy and orientation_pixels_ENU.npy
The other calibration files can be downloaded from the github.

The input directory (i.e., where the files of the database have been locally downloaded) must be indicated.
The output directory (i.e., where the files of the database processing will be recorded) must be indicated.
The calibration directory must be provided. 

In the jupyter notebook, the cell used to process the images can be run in parallel processing. 
This code requires high computational ressources.
