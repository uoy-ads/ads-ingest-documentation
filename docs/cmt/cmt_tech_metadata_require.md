# Technical Metadata Requirements

Below is a list of all the fields required Technical Metadata uploaded to the Ingest system. Please see the [Technical metadata page](cmt_technical_metadata.md) for further information including a full list of data categories that require technical metadata to be deposited alongside your collection.

---

## Audiovisual

[Download the Audiovisual Technical Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/audiovisual_metadata_template.xlsx)

| Field name | Description |
|---|---|
| **Filename** | Filename of each separate audiovisual file including file extension |
| **Video codec** | The name and version of video codec (where appropriate) |
| **Video dimension** | The video dimension (in pixels) |
| **Frame rate** | Frame rate per second (fps) |
| **Bit rate** | The video bit rate |
| **Audio codec** | The codec used in creating the file e.g. FLAC or AAC |
| **Audio sample frequency** | Sample rate e.g. 44.1kHz |
| **Audio bit-rate** | Optional, often recorded as kbps |
| **Audio channels** | e.g. stereo, mono |
| **Length** | Length of recording in hh : mm : ss |
| **Transcript file name** | Transcripts of interviews can be important documentation particularly in clarifying those involved in recordings and allowing specific individuals to be identified |

---

## Geographic Information System (GIS)

[Download the GIS Data Technical Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/gis_metadata_template.xlsx)

| Field Name | Description |
|---|---|
| **Filename** | Filename of each separate GIS file including file extension |
| **Data type** | Please specify if the file is vector (i.e. point, polygon or line) or raster |
| **Scale/resolution** | The scale/resolution of the data at capture (and at storage, if this differs from the original capture resolution) |
| **Assessment of data quality** | An assessment or statement about the quality and accuracy of the data used and/or created within the GIS |
| **Method of data capture** | How the data used within the GIS was created or captured |
| **Purpose of data creation** | The reason why the data was collected, and the GIS created |
| **Coordinate grid system** | The coordinate grid system utilised within the GIS |
| **Source** | The source of the data used in the creation of the GIS ('bought from Ordnance Survey', etc.) |
| **Table attribute / field** *(vector)* | Please list each attribute/field/column within the GIS attribute table |
| **Table attribute description** *(vector)* | A description of attribute, explaining codes or abbreviations |

---

## Geophysics and Geophysics (Proprietary)

[Download the Geophysics Technical Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/main/technical_metadata/geophysical_survey_metadata_template.xlsx)

### All survey types

The following should be provided for all geophysical survey types:

| Field Name | Description |
|---|---|
| **File names** | Including file extension, place a comma between each name |
| **Survey name** | If your survey has an alternative title to the one provided during the creation of the project metadata, you can add it here |
| **Survey index** | The identification number or code used internally for the survey and any related data identifier |
| **Survey purpose** | A brief description of the purpose of the geophysical survey |
| **Survey duration** | Start and end date for the survey |
| **Survey by** | The person and/or organisation responsible for carrying out the survey |
| **Solid geology** | A record of the base geology for the location where the survey was carried out |
| **Drift geology** | The overlying drift geology for the place where the survey was carried out |
| **Land use** | The prevailing land use for the area being surveyed |
| **Survey type** | The technique used to carry out the survey |
| **Instrumentation** | Specific information about the type and configuration of the equipment used during the survey |
| **Area surveyed** | The

The following should be also be included for the relevant survey type(s):

### Electro-magnetic

| Field Name | Description |
|---|---|
| **Coil configuration** | The distance of the coils within the instrument used for the electromagnetic survey |
| **Recorded component** | The recorded electromagnetic component needs to be specified |

### Ground Penetrating Radar

| Field Name | Description |
|---|---|
| **Antenna information** | For surveys using pulse radar systems, the centre frequency of the antenna should be recorded |
| **Time delay** | The time delay for the recording of the first reflection expressed in seconds |
| **Time sampling resolution** | The resolution of the time sampling expressed in seconds |
| **Time span** | The maximum time span of the recording expressed in seconds |
| **Average subsurface velocity** | An estimate of the electromagnetic velocity to allow the conversion of two way travel times to depth |
| **Average subsurface note** | A statement/note about how the Average Subsurface Velocity was derived |

### Magnetometer

| Field Name | Description |
|---|---|
| **Magnetic north** | The orientation of the coordinate system/grid in relation to Magnetic North |
| **Instrument drift** | During any survey the magnetometer may exhibit evidence of a gradual change in its readings |

### Resistance

| Field Name | Description |
|---|---|
| **Electrode configuration** | Any responses from below ground features are heavily influenced by the configuration of electrodes used |
| **Electrode spacing** | The distance between electrodes must be recorded in order to process the data collected during a survey |
| **Multiple configurations** | Earth resistance data can be recorded at each measurement location using different electrode configurations by means of a multiplexer |

### Maritime Sonar

| Field Name | Description |
|---|---|
| **Average water velocity** | The average water velocity during the survey in m/s |
| **Sonar frequency** | The frequency of the sonar in kHz |
| **Beam width at nadir** | An estimate of the beam width gap in degrees at nadir |

---

## Laser Scanning

[Download the 3D Technical Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx)

Please note that this template is utilised by multiple data categories including LIDAR, Photogrammetric Survey and Virtual Reality and Visualisation.

This template contains several worksheets that should be completed. The headings below relate to the names of the specific worksheets that should be completed for this Data Category.

### Datasets - Components

| Field Name | Description |
|---|---|
| **File/Group Name** | The name of the file or group of files e.g. model1.obj; /source_images/; /raw_scans/; registered_point_cloud.e57 |
| **Title** | e.g. Landscape Surrounding Site 1 (Reduced Model) |
| **Description** | e.g. Decimated model created from model1 |
| **Software Used** | Specify software and version used for meshing, e.g. 3DReshaper 11.1.4.24994 |
| **Source File(s) / Relationships** | Specify file names/locations of source files e.g. point cloud source data for meshing (laser scan) or list of photos (photogrammetry). Large lists of e.g. images can be stored in a separate file (include name here) |
| **Point Cloud Decimation (pre-meshing)** | Yes or No. If yes, specify amount/level |
| **Hole Filling** | Yes or No |
| **Smoothing** | Yes or No |
| **Data Reduction** | Yes or No. If yes, specify level of decimation |
| **RGB Colour or Texture Included** | Yes or No. If Yes then provide details |
| **Number of Triangles or Polygons** | Total number of triangles in the mesh file where applicable |
| **Number of Vertices** | Number of vertices in data where applicable |
| **Validated as Watertight** | Yes or No |
| **Additional Processing Notes** | Notes on any additional processing |
| **Healing/Despiking** | Yes or No |
| **Coordinate System Used / Adjusted** | Yes or No. If yes and adjusted then provide details (e.g. transformation matrix) |
| **Scale** | If scale used, what is represented by 1 unit |
| **Creators** | Creators for this data |
| **Copyright Holders** | Copyright holders for this data |
| **Creation Date** | Date file was created |

### Laser Scan - Capture

| Field Name | Description |
|---|---|
| **Scanner details** | Specify the name, technology, serial number, firmware version and last calibration date of scanner(s) used in the project |
| **Scan Resolution** | Resolution settings on scanner |
| **Noise/Quality Settings** | Noise settings on scanner |
| **Lens or FOV details** *(optional)* | Triangulation scanners only. Indicate which lens or FOV was used during scan |
| **Number of points per scan** *(optional)* | Specify number of points per scan |
| **Measurement Technology** | Specify technology used: TOF (first or last return), Phase (frequency settings), Waveform |
| **Onboard photography?** | Whether the scanner captures images. Y/N |

### Photography - Camera

| Field Name | Description |
|---|---|
| **Photography Type** | Specify photography type e.g.: still, HDR (specify brackets), onboard scanner, 360°, etc. |
| **Exposure settings** | Exposure settings set on scanner (if applicable) |
| **Camera and lens** | Specify camera model and lens used |
| **Firmware version** | Specify camera firmware version |
| **Aperture** | Specify the f-stop |
| **Image resolution** | Specify image resolution |
| **Image file format** | Specify the file format |
| **Reference card / calibration target used?** | Was a reference card captured for calibrating white/grey balance? Include target dimensions, creator and description |
| **Camera Calibrated?** | Yes / No. If Yes complete 'Photography Calibration' section |

### Photography - Calibration

| Field Name | Description |
|---|---|
| **Calibration Date** | Date that the calibration was performed |
| **Camera Calibration File** | File name for the camera calibration |
| **Array Dimensions** | Width and height of digital array measured in pixels and millimeters |
| **Focal Length and Principal Point** | Exact focal length and principal point location as measured by the camera calibration |
| **Lens Distortions** | Radial and decentering distortion parameters as measured by the camera calibration |
| **Affine Distortions** | Affine distortion parameters as measured by the camera calibration (if measured) |
| **Calibration Quality Values** | Quality values such as overall RMS, maximum residual, and photo coverage (%) from the calibration process |
| **Calibration Adjustment Report** | A report on the quality of the camera calibration including at a minimum the correlation between exterior and interior parameters |

### Survey Control

| Field Name | Description |
|---|---|
| **Control Data** | Yes/No. Specify if control data has been collected |
| **Related Control Files** | Specify filenames if related control files (e.g. software exports) or witness diagrams are included |
| **Permanent Survey Markers (PSM)** | Yes/No. Where used, specify when PSM coordinates were obtained (preferably within 12 months of survey) |
| **Scale Used** | Yes/No. Specify type e.g. measurement, scale bar, 3D reference, etc. |
| **Additional Notes** | Additional notes on survey control and reference information. Describe any existing reference information available to the surveyors, including paper plans or digital spatial data |
| **GNSS** | Yes/No. If yes complete fields below |
| **Instrument details (GNSS)** | Specify the name, serial number, firmware version and last calibration date of instrument(s) used in the project |
| **GNSS method** | Fixed base station / virtual reference system |
| **Transformation system used for georeferencing** | Transformation system used for georeferencing e.g. OSTN02 / OSTN15 |
| **Scale factor included** | Yes/No |
| **TotalStation** | Yes/No. If Yes then complete fields below |
| **Instrument details (TotalStation)** | Specify the name, serial number, firmware version and last calibration date of instrument(s) used in the project, e.g. Leica Nova MS50 - Serial: 368276 |
| **Traverse (mis-closure) error** | Specify angular error and distance error |
| **Traverse Adjusted?** | Y/N. Specify what method of adjustment was used, the error ratio e.g. 1/10000, 1/100000 etc. |
| **Traverse Accuracy** | Specify the accuracy of the control traverse |

### Registration Alignment

| Field Name | Description |
|---|---|
| **Dataset name** | Specify file name for registered dataset, e.g. Cyclone IMP of Faro Scene project |
| **Software (including version)** | e.g. Leica Cyclone 9.1.5 |
| **Scans/images imported as native format?** | Y / N (If no, specify exchange format) |
| **RGB information included?** | Y / N |
| **Scans cleaned?** | Y / N. Specify method/filtering |
| **Cleaned scans used for registration?** | Y / N |
| **Control data used for georeferencing** | Specify file name (control) or list of points |
| **Method** | Describe the registration method, including use of targets, cloud constraints, survey control and georeferencing method and nesting |
| **Scan/Image Details** | List of raw scans (filenames) and number of points-per-scan used in registered dataset |
| **Total Number of Points in File** | Total number of points in registered file |
| **Max Registration Error (mm)** | Max RMS error - in case of nested registrations, specify max RMS error for each registration |
| **Global Registration Error** | Total Mean Absolute Error - in case of nested registrations, specify MAE for each registration |
| **Max Georeferencing Error (mm)** | Max RMS error for georeferencing the registered dataset (registering final registered point cloud to GNSS data or existing PSMs) |
| **Registration Diagnostics** | List diagnostics.txt file(s) - in case of nested registrations, specify diagnostics file for each one |
| **Overlap Reduction** | Y/N (optional) |
| **Smoothing** | Y/N (optional) |
| **Subsampling** | Y/N (optional) |
| **Colour Editions** | Y/N (optional) |
| **Point Editing Summary** | Description of major editing operations (e.g. overlap reduction, point deletion, etc.) that have been performed on the dataset |
| **Dataset Description** | General description or purpose of dataset |

---

## Light Detection and Ranging (LiDAR)

[Download the 3D Technical Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx)

Please note that this template is utilised by multiple data categories including Laser Scanning, Photogrammetric Survey and Virtual Reality and Visualisation.

This template contains several worksheets that should be completed. The headings below relate to the names of the specific worksheets that should be completed for this Data Category.

### Datasets - Components

| Field Name | Description |
|---|---|
| **File/Group Name** | The name of the file or group of files e.g. model1.obj; /source_images/; /raw_scans/; registered_point_cloud.e57 |
| **Title** | e.g. Landscape Surrounding Site 1 (Reduced Model) |
| **Description** | e.g. Decimated model created from model1 |
| **Software Used** | Specify software and version used for meshing, e.g. 3DReshaper 11.1.4.24994 |
| **Source File(s) / Relationships** | Specify file names/locations of source files e.g. point cloud source data for meshing (laser scan) or list of photos (photogrammetry). Large lists of e.g. images can be stored in a separate file (include name here) |
| **Point Cloud Decimation (pre-meshing)** | Yes or No. If yes, specify amount/level |
| **Hole Filling** | Yes or No |
| **Smoothing** | Yes or No |
| **Data Reduction** | Yes or No. If yes, specify level of decimation |
| **RGB Colour or Texture Included** | Yes or No. If Yes then provide details |
| **Number of Triangles or Polygons** | Total number of triangles in the mesh file where applicable |
| **Number of Vertices** | Number of vertices in data where applicable |
| **Validated as Watertight** | Yes or No |
| **Additional Processing Notes** | Notes on any additional processing |
| **Healing/Despiking** | Yes or No |
| **Coordinate System Used / Adjusted** | Yes or No. If yes and adjusted then provide details (e.g. transformation matrix) |
| **Scale** | If scale used, what is represented by 1 unit |
| **Creators** | Creators for this data |
| **Copyright Holders** | Copyright holders for this data |
| **Creation Date** | Date file was created |

### Laser Scan - Capture

| Field Name | Description |
|---|---|
| **Scanner details** | Specify the name, technology, serial number, firmware version and last calibration date of scanner(s) used in the project |
| **Scan Resolution** | Resolution settings on scanner |
| **Noise/Quality Settings** | Noise settings on scanner |
| **Lens or FOV details** *(optional)* | Triangulation scanners only. Indicate which lens or FOV was used during scan |
| **Number of points per scan** *(optional)* | Specify number of points per scan |
| **Measurement Technology** | Specify technology used: TOF (first or last return), Phase (frequency settings), Waveform |
| **Onboard photography?** | Whether the scanner captures images. Y/N |

### Survey Control

| Field Name | Description |
|---|---|
| **Control Data** | Yes/No. Specify if control data has been collected |
| **Related Control Files** | Specify filenames if related control files (e.g. software exports) or witness diagrams are included |
| **Permanent Survey Markers (PSM)** | Yes/No. Where used, specify when PSM coordinates were obtained (preferably within 12 months of survey) |
| **Scale Used** | Yes/No. Specify type e.g. measurement, scale bar, 3D reference, etc. |
| **Additional Notes** | Additional notes on survey control and reference information. Describe any existing reference information available to the surveyors, including paper plans or digital spatial data |
| **GNSS** | Yes/No. If yes complete fields below |
| **Instrument details (GNSS)** | Specify the name, serial number, firmware version and last calibration date of instrument(s) used in the project |
| **GNSS method** | Fixed base station / virtual reference system |
| **Transformation system used for georeferencing** | Transformation system used for georeferencing e.g. OSTN02 / OSTN15 |
| **Scale factor included** | Yes/No |
| **TotalStation** | Yes/No. If Yes then complete fields below |
| **Instrument details (TotalStation)** | Specify the name, serial number, firmware version and last calibration date of instrument(s) used in the project, e.g. Leica Nova MS50 - Serial: 368276 |
| **Traverse (mis-closure) error** | Specify angular error and distance error |
| **Traverse Adjusted?** | Y/N. Specify what method of adjustment was used, the error ratio e.g. 1/10000, 1/100000 etc. |
| **Traverse Accuracy** | Specify the accuracy of the control traverse |

### Registration Alignment

| Field Name | Description |
|---|---|
| **Dataset name** | Specify file name for registered dataset, e.g. Cyclone IMP of Faro Scene project |
| **Software (including version)** | e.g. Leica Cyclone 9.1.5 |
| **Scans/images imported as native format?** | Y / N (If no, specify exchange format) |
| **RGB information included?** | Y / N |
| **Scans cleaned?** | Y / N. Specify method/filtering |
| **Cleaned scans used for registration?** | Y / N |
| **Control data used for georeferencing** | Specify file name (control) or list of points |
| **Method** | Describe the registration method, including use of targets, cloud constraints, survey control and georeferencing method and nesting |
| **Scan/Image Details** | List of raw scans (filenames) and number of points-per-scan used in registered dataset |
| **Total Number of Points in File** | Total number of points in registered file |
| **Max Registration Error (mm)** | Max RMS error - in case of nested registrations, specify max RMS error for each registration |
| **Global Registration Error** | Total Mean Absolute Error - in case of nested registrations, specify MAE for each registration |
| **Max Georeferencing Error (mm)** | Max RMS error for georeferencing the registered dataset (registering final registered point cloud to GNSS data or existing PSMs) |
| **Registration Diagnostics** | List diagnostics.txt file(s) - in case of nested registrations, specify diagnostics file for each one |
| **Overlap Reduction** | Y/N (optional) |
| **Smoothing** | Y/N (optional) |
| **Subsampling** | Y/N (optional) |
| **Colour Editions** | Y/N (optional) |
| **Point Editing Summary** | Description of major editing operations (e.g. overlap reduction, point deletion, etc.) that have been performed on the dataset |
| **Dataset Description** | General description or purpose of dataset |

---

## Photogrammetric Survey

[Download the 3D Technical Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx)

Please note that this template is utilised by multiple data categories including Laser Scanning, LIDAR and Virtual Reality and Visualisation.

This template contains several worksheets that should be completed. The headings below relate to the names of the specific worksheets that should be completed for this Data Category.

### Datasets - Components

| Field Name | Description |
|---|---|
| **File/Group Name** | The name of the file or group of files e.g. model1.obj; /source_images/; /raw_scans/; registered_point_cloud.e57 |
| **Title** | e.g. Landscape Surrounding Site 1 (Reduced Model) |
| **Description** | e.g. Decimated model created from model1 |
| **Software Used** | Specify software and version used for meshing, e.g. 3DReshaper 11.1.4.24994 |
| **Source File(s) / Relationships** | Specify file names/locations of source files e.g. point cloud source data for meshing (laser scan) or list of photos (photogrammetry). Large lists of e.g. images can be stored in a separate file (include name here) |
| **Point Cloud Decimation (pre-meshing)** | Yes or No. If yes, specify amount/level |
| **Hole Filling** | Yes or No |
| **Smoothing** | Yes or No |
| **Data Reduction** | Yes or No. If yes, specify level of decimation |
| **RGB Colour or Texture Included** | Yes or No. If Yes then provide details |
| **Number of Triangles or Polygons** | Total number of triangles in the mesh file where applicable |
| **Number of Vertices** | Number of vertices in data where applicable |
| **Validated as Watertight** | Yes or No |
| **Additional Processing Notes** | Notes on any additional process

---

## Tabular Data

[Download the Tabular Data Technical Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/tabular_data_metadata_template.xlsx)

Please ensure that you have also deposited an Entity Relationship Diagram for databases.

| Field name | Description |
|---|---|
| **Filename** | Filename of each separate spreadsheet or database file including file extension |
| **Sheet/table name** | Name of each sheet or table within the specified spreadsheet or database |
| **Sheet/table description** | A brief description of the sheet/table and the data it contains |
| **Primary key** *(databases only)* | Name of the field used to uniquely identify every record in database |
| **Foreign key** *(databases only)* | Name of the field used to provide link between other tables |
| **Row count** | The number of rows containing data in the sheet/table |
| **Field name** | Name of each field heading within the specified sheet or table |
| **Field description** | Brief description of the field, including units of measurements and descriptions of codes or abbreviations used where applicable |
| **Field data type** *(databases only)* | The kind of data the field contains, i.e string, boolean |
| **Field length** *(databases only)* | The maximum number of units allowed within the field |

---

## Vector Graphics

[Download the Vector Graphics Technical Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/vector_graphic_metadata_template.xlsx)

Please note that where layers are coded or abbreviated, please provide fuller descriptions using the technical metadata template. Where layers are self-explanatory i.e layer name is ‘Trenches’, technical metadata is not required.

| Field Name | Description |
|---|---|
| **Filename** | The filename of each separate vector file including file extension |
| **Layer name** | The name of each layer component |
| **Layer description** | A description of each layer component including use of styles, line weights, colour where significant |

----

## Virtual Reality and Visualisation

[Download the 3D Technical Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx)

Please note that this template is utilised by multiple data categories including Laser Scanning, LIDAR and Photogrammetric Survey.

This template contains several worksheets that should be completed. The headings below relate to the names of the specific worksheets that should be completed for this Data Category.

### Datasets - Components

| Field Name | Description |
|---|---|
| **File/Group Name** | The name of the file or group of files e.g. model1.obj; /source_images/; /raw_scans/; registered_point_cloud.e57 |
| **Title** | e.g. Landscape Surrounding Site 1 (Reduced Model) |
| **Description** | e.g. Decimated model created from model1 |
| **Software Used** | Specify software and version used for meshing, e.g. 3DReshaper 11.1.4.24994 |
| **Source File(s) / Relationships** | Specify file names/locations of source files e.g. point cloud source data for meshing (laser scan) or list of photos (photogrammetry). Large lists of e.g. images can be stored in a separate file (include name here) |
| **Point Cloud Decimation (pre-meshing)** | Yes or No. If yes, specify amount/level |
| **Hole Filling** | Yes or No |
| **Smoothing** | Yes or No |
| **Data Reduction** | Yes or No. If yes, specify level of decimation |
| **RGB Colour or Texture Included** | Yes or No. If Yes then provide details |
| **Number of Triangles or Polygons** | Total number of triangles in the mesh file where applicable |
| **Number of Vertices** | Number of vertices in data where applicable |
| **Validated as Watertight** | Yes or No |
| **Additional Processing Notes** | Notes on any additional processing |
| **Healing/Despiking** | Yes or No |
| **Coordinate System Used / Adjusted** | Yes or No. If yes and adjusted then provide details (e.g. transformation matrix) |
| **Scale** | If scale used, what is represented by 1 unit |
| **Creators** | Creators for this data |
| **Copyright Holders** | Copyright holders for this data |
| **Creation Date** | Date file was created |

----