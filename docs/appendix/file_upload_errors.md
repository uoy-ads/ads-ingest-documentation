Below is a table of errors that the Ingest system may present when uploading files as part of your deposit.


| Error | Description | Action (in Ingest) |
| :---- | :---- | :---- |
| Invalid Filenames | One or more uploaded files have an invalid filename \- file names must only contain alpha-numeric characters (a-z, A-Z, 0-9), hyphens (-), underscores (\_) and forward slashes (/) | Delete files and re-upload a new version with a valid filename |
| Filename Mismatch | When uploading a replacement file, the replacement file’s filename is not the same as the file the user is trying to replace | Re-upload a file with the correct filename |
| Not Listed in Spreadsheet | One or more files have been uploaded that are not listed in the metadata spreadsheet | Either delete the files or append rows to the metadata spreadsheet describing the files |
| File missing from upload | One or more files are listed in the metadata spreadsheet but are missing from the uploaded files | Upload the missing files or delete the rows describing the files from the metadata spreadsheet |
| Directories Missing From Upload | One or more directories are listed in the metadata spreadsheet but are missing from the uploaded files | Upload the missing directories or delete the rows describing the directories from the metadata spreadsheet |
| Undeterminable object type | The file type cannot be determined for one or more objects - an unexpected set of files has been uploaded for the specified “Data Category”. | Delete the object and/or any related files and rows from the metadata spreadsheet |
| Missing associated files | An object type was found but some files are missing, e.g. all necessary components of a Shapefile | Upload the missing files |
| Missing metadata | One or more objects that we would expect to have technical metadata do not have any technical metadata files listed | Ignore this warning or re-upload the metadata spreadsheet and files with the appropriate changes |
| Technical Metadata file missing from upload | One or more technical metadata files are listed in the metadata spreadsheet but are missing from the uploaded files | Upload the missing technical metadata files |
| Contains malware | One or more uploaded files were found to contain malware | Replace the infected files with clean versions |
| Password Protected PDFs | One or more password protected PDF files have been uploaded | Replace password protected PDF files with non-password protected PDF files |
| PDF Portfolios | One or more “portfolio” PDF files have been uploaded | Replace “portfolio” PDF files with regular PDF files |