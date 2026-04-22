Below is a table of errors that the Ingest system may present when uploading the Core Metadata Template.


| Error | Description |
| :---- | :---- |
| Missing “filename” | “Filename” field is empty. |
| “Filename” cannot be more than 4000 characters | “Filename” field is too long. Please restrict to 4000 characters or under. |
| “Filename” contains invalid characters \- must only contain alpha-numeric characters (a-z, A-Z, 0-9), hyphens (-), underscores (\_) and forward slashes (/) | “Filename” field is invalid due to the presence of characters that are not accepted. |
| Empty directory in “Filename” | “Filename” field contains an empty directory e.g. MyFiles/Images//trench1.jpg. |
| “Filename” is missing a file extension | “Filename” field is not a directory (doesn’t end with /) and is missing a file extension e.g. MyFiles/Images/trench1. |
| “Filename” has a file extension that is not accepted | “Filename” field contains a file extension that is not in the list of accepted file extensions. Please note geophysics objects containing proprietary file types should be listed as directories. |
| “Filename” has a file extension that is not accepted for the selected “Data Category” | “Filename” field has a file extension that is not in the list of accepted file extensions for the specified “Data Category”. Please note Geophysics objects containing proprietary file types should be listed as directories. |
| "Filename" cannot be a directory for the selected "Data Category" | The “Filename” column contains a directory, however, the selected Data Category does not accept multiple constituent files for an object. |
| Duplicate “Filename” found. | The “Filename” column must contain a unique value for each row. |
| Duplicate “Filename” (excluding extension) found | The “Filename” column must contain a unique value for each row, disregarding the file extension. |
| Missing “Data Category” | “Data Category” field is empty. |
| Invalid “Data Category” | “Data Category” field contains a category that is not in the list of valid data categories. |
| Missing “Title” | “Title” field is empty. |
| “Title” cannot be more than 500 characters | “Filename” field is too long. Please restrict to 500 characters or under. |
| “Description” cannot be more than 4000 characters | “Description” field is too long. Please restrict to 4000 characters or under. |
| “Tag” cannot be more than 500 characters | “Tag” field is too long. Please restrict to 500 characters or under. |
| Missing “Creator” | “Creator” field is empty. |
| “Creator” cannot be more than 500 characters | “Creator” field is too long. Please restrict to 500 characters or under. |
| Missing “Copyright Holder” | “Copyright Holder” field is empty. |
| “Copyright Holder” cannot be more than 500 characters | “Copyright Holder” field is too long. Please restrict to 500 characters or under. |
| Missing “Creation History” | “Creation History” field is empty. |
| “Creation History” cannot be more than 500 characters | “Creation History” field is too long. Please restrict to 500 characters or under. |
| “Language” cannot be more than 500 characters | “Language” field is too long. Please restrict to 500 characters or under. |
| Missing “Date File Digitally Created | “Date File Digitally Created” is empty. |
| Invalid “Date File Digitally Created” \- must be in dd/mm/yyyy format | “Date File Digitally Created” is not in dd/mm/yyyy format. |
| A “Technical Metadata” filename is missing a file extension | A filename in the “Technical Metadata” field is missing a file extension, e.g. MyFiles/technical. |
| A “Technical Metadata” filename has a file extension that is not accepted | A file listed in the “Technical Metadata” field has a file extension that is not in the list of accepted file extensions. |
| A “Technical Metadata” filename contains an empty directory | A “Technical Metadata” filename contains an empty directory e.g. MyFiles/Metadata//technical.csv |
| A “Technical Metadata” filename contains invalid characters \- must only contain alpha-numeric characters (a-z, A-Z, 0-9), hyphens (-), underscores (\_) and forward slashes (/) | “Technical Metadata” field is invalid due to the presence of characters that are not accepted.  |
| Missing or invalid “Survey Area” | “Data Category” is “Geophysics” and “Survey Area” is either empty or not a valid number. |

