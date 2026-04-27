# Technical Metadata

Technical metadata refers to the descriptive information about data that helps to understand its technical characteristics, structure, and relationships. It is useful to include technical metadata with certain file types to provide more specific information.

The new Ingest system enables depositors to utilise a single [Core Metadata template](cmt_index.md) to upload their files to the system. However, for some data categories additional technical metadata is required. Below is a full list of the [data categories](cmt_data_category.md) that require additional technical metadata file to be deposited alongside your collection.

## How to upload your technical metadata

To upload Technical metadata files, include them in the folder of files that you want to deposit and have uploaded on the [Files](../nc/nc_files.md) page when you submit a new collection. 

It is not required to list these technical metadata files as a separate row in the [Core Metadata Template](./cmt_template_download.md), however, each file (with an appropriate  file extension) should be listed in the *Technical Metadata* column of the Core Metadata template. If you fail to include a required Technical metadata file, or include the file but do not list it in the Core metadata template, then Ingest will produce an [error](../appendix/core_metadata_errors.md).

## Data types that require technical metadata

The table below provides a list of templates that can be used for required Technical metadata. It is not mandatory to use these templates but they provide a useful starting point for the types of information that we would like to collect for some Data Categories.

Each template contains sample data for each field . These templates can be used and amended as necessary to suit the needs of your collection. For a full list of the fields required for each technical metadata template please the [technical metadata field list](../cmt/cmt_tech_metadata_require.md).


| Data Category | File Extensions | Technical Metadata Template |
| :---- | :---- | :---- |
| **Audiovisual** | acc, aif, au, avi, bwf, flack, mkv, mp3, mp4, mpg, avg, wav, mpeg | [Audiovisual metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/audiovisual_metadata_template.xlsx) |
| **Geographic Information System (GIS) Data** | adf, asc, csv, e00, geojson, gml, img, jpg, kml, mid, png, shp, tif | [GIS Metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/gis_metadata_template.xlsx)  |
| **Geophysics** | csv, dat, mgr, rep, sgy, txt, xcp | [Geophysical survey metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/main/technical_metadata/geophysical_survey_metadata_template.xlsx) |
| **Geophysics (Proprietary)** | Any file types | [Geophysical survey metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/main/technical_metadata/geophysical_survey_metadata_template.xlsx) |
| **Laser Scanning** | tif, txt, e57, las, obj, pts | [3D metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx) |
| **Light Detection and Ranging (LiDAR)** | tif, txt, e57, las, obj, pts | [3D metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx)  |
| **Photogrammetric Survey** | dng, jpg, obj, pts, tiff, wrl  | [3D metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx) |
| **Tabular Data** | accdb, csv, dbf, json, mdb, odb, ods, rdf, sql, tsv, txt, xls, xlsx, xml | [Tabular Data  technical metadata](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/tabular_data_metadata_template.xlsx)  |
| **Vector Graphic** | dwg, dxf, svg | Graphical vector datasets such as CAD (computer assisted design) models. | [Vector technical metadata](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/vector_graphic_metadata_template.xlsx)  |
| **Virtual Reality and Visualisation**  | obj, stl, wrl  | Other 3D models and visualisation including virtual reality. This data should not include datasets derived from ‘Photogrammetry’. ‘Laser scanning’, ‘LIDAR’ or derived from specific medical imaging techniques such as CT Scanning. | [3D metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx) |




| :---- | :---- | :---- |
| Audiovisual | acc, aif, au, avi, bwf, flack, mkv, mp3, mp4, mpeg, mpg, avg, wav | [Audiovisual technical metadata]() |
| Computed Tomography (CT) Scanning | bmp, dcm, gif, jpg, png, tif | [CT Scanning technical metadata]() |
| Geophysics | csv, dat, mgr, rep, sgy, txt, xcp | Geophysics Scanning technical metadata |
| Geographic Information System (GIS) Data | adf, asc, csv, e00, geojson, gml, img, jpg, kml, mid, png, shp, tif | [GIS technical metadata]() |
| Laser Scanning | tif, txt, e57, las, obj, pts | [Laser scanning technical metadata]() |
| Light Detection and Ranging (LiDAR) | tif, txt, e57, las, obj, pts | [LiDAR technical metadata]() |
| Magnetic Resonance Imaging (MRI) | bmp, dcm, gif, jpg, png, tif \[video\] | [MRI technical metadata]() |
| Mass Spectrometry | jdx, mzdata, mzml, mzxml, txt, xml | [Mass Spectrometry technical metadata]() |
| Photogrammetric Survey | dng, jpg, obj, pts, tiff, wrl | [Photogrammetric Survey technical metadata]() |
| Reflectance Transformation Imaging (RTI) | dng, jpg, obj, ptm, rti, wrl, tif, | [RTI technical metadata]() |
| Tabular Data | accdb, csv, dbf, json, mdb, odb, ods, rdf, sql, tsv, txt, xls, xlsx, xml | [Tabular data technical metadata]() |
| Vector Graphic | dwg, dxf, svg | Vector Graphic technical metadata |
| Virtual Reality and Visualisation | obj, stl, wrl | [Virtual Reality and Visualisation technical metadata]() |
| X-radiography (X-ray) Scanning | bmp, dcm, gif, jpg, png, tif | [X-Ray technical metadata]() |