# Multiple files per object

In some instances you may wish to upload a single digital object that contains multiple files, such as a GIS shapefile or 3d model. In this case please add all files to the upload folder but include only one object (or row) in the core metadata template. This ensures all files related to an object are ingested together and contain the same metadata. The Ingest system will recognise all of these files as a single object, but only if all files contain the same filename or are grouped in a folder.

## Some examples

Below are a number of common examples.

*GIS Shapefiles* - Shapefiles are usually composed of a series of files that have the same name but with a different file extension. A shapefile object may consist of the following files:

* example.shp
* example.shx
* example.dbf
* example.sbn
* example.prj

__Solution__ - Deposit all the files together in the upload folder, but list them as a single row in the core metadata template, using the filename 'example.shp'.

---

*Photogrammetry image sets or Laser Scans* - A series of images, likely with different files names but probably with the same extension. For example:

* example1.jpg
* example2.jpg
* example3.jpg
* example4.jpg

__Solution__ - Put all of your files within a single folder and list the name of the folder in the core metadata template. More information about using folders can be found on the [Folder Structure page](../cmt/cmt_folder_structure.md).

---

*3D models with textures* - A series of different file types, likely with different file names. For example.

* example.obj
* example_mat.mtl
* example_texture.jpg

Solution - You ave two options; either rename all of these files so that they have the same file name and list them in a single row in the core metadata template, using the filename 'example.obj', or put all the files in a single folder and list the name of the folder in the core metadata template.

## Accepted Data Categories

The list below contains all Data Categories that are required to be formatted in this way:

* Geophysics (Proprietary)
* Geophysics
* Geographic Information System (GIS) Data
* Light Detection and Ranging (LiDAR)
* Laser Scanning
* Mass Spectrometry
* Photogrammetric Survey
* Reflectance Transformation Imaging (RTI)
