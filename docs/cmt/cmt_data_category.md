The table below lists all of the Data Categories currently accepted through the Ingest system. These categories are listed in the [Core Metadata Template](../cmt/cmt_template_download.md). This table below provides a description of each data type as well as accepted file extensions and links to Technical Metadata templates, where required.

!!! note "**Templates**"

    Please note that it is not mandatory to use the templates listed in the table below. You can create and use your own templates when depositing Technical Metadata. For a full list of information required please see the [Technical Metadata Requirements page](cmt_tech_metadata_require.md).

| Data Category | Accepted File Extensions | Description | Technical Metadata Template |
| :---- | :---- | :---- | :---- |
| **Audiovisual** | acc, aif, au, avi, bwf, flack, mkv, mp3, mp4, mpg, avg, wav, mpeg | Audio or video files. |  [Audiovisual technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/audiovisual_metadata_template.xlsx){target="_blank"} |
| **Computed Tomography (CT) Scanning** | bmp, dcm, gif, jpg, png, tif | Images, models, or data from CT scanning including micro CT. CT video files should be categorised as Audiovisual. | None Required.  |
| **Geographic Information System (GIS) Data** | adf, asc, csv, e00, geojson, gml, img, jpg, kml, mid, png, shp, tif | Files commonly used in GIS software including raster or vector datasets, and linked tabular data. | [GIS technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/gis_metadata_template.xlsx) |
| **Geophysics** | csv, dat, mgr, rep, sgy, txt, xcp | Instrument data from geophysical survey equipment. Processed raster or vector data (e.g. geotiff or DXF files) should be deposited as GIS Data. | [Geophysical Survey technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/main/technical_metadata/geophysical_survey_metadata_template.xlsx) |
| **Geophysics (Proprietary)** | Any file types. | Instrument data from geophysical survey in proprietary (or exclusive) formats. Please note that these datasets must be deposited with a version of the data in an accepted (i.e. non-proprietary) deposit format. | [Geophysical Survey technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/main/technical_metadata/geophysical_survey_metadata_template.xlsx) |
| **Harris Matrix** | csv, dxf, lst, pdf, txt [any raster image files - See Photograph and Other Raster Image] | Harris matrices that describe the stratigraphic sequence of an archaeological investigation. |  None required. |
| **Laser Scanning** | tif, txt, e57, las, obj, pts | Point data from terrestrial laser scanning equipment. Please note that LiDAR derived data should be listed under the Data Category ‘LiDAR’. | [3D technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx)  |
|  **Light Detection and Ranging (LiDAR)** | tif, txt, e57, las, obj, pts | Raw point data captured from aerial or mobile LiDAR systems. Processed raster or vector data (e.g. geotiff or DXF files) should be deposited as GIS Data. |  [3D technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx)  |
| **Magnetic Resonance Imaging (MRI)** | bmp, dcm, gif, jpg, png, tif [any video files - see Audiovisual] | Data produced from MRI scanning of artefacts and human remains. |  None required. |
| **Marked Up Text** | html, sgml, xhtml, md | Text and documents formatted using markup or markdown languages. |  None required. |
| **Mass Spectroscopy**  | .jdx, mzdata, mzml, mzxml, txt, xml [any database files  - See Tabular Data] | Data resulting from Mass Spectroscopy techniques. | None required. |
| **Other Document**  | doc, docx, odt, pdf, rtf, txt, md | Other Text documents that are not categorised as ‘Publication’, ‘Report’, or ‘Site Records’. |  None required. |
| **Other Raster Image** | bmp, dng, gif, jp2, jpg, pdf, png, tiff  | Other Raster images that are not categorised as ‘Photograph’  |  None required. |
| **Photogrammetric Survey** | dng, jpg, obj, pts, tiff, wrl | Data, images and 3d models resulting from photogrammetric surveys. | [3D technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx) |
| **Photograph** | bmp, dng, gif, jp2, jpg, pdf, png, tiff | Digitally captured or scanned photographs. | None required.  |
| **Publication** | doc, docx, odt, pdf, rtf, txt, md | Text files that represent a digital version of a formal publication, whether online or in print. | None required. |
| **Radiocarbon** | xml, svg, oxcal, 14c,prior, js, log, txt, pdf, [any database files - See Tabular Data] | Data and dates from radiocarbon dating. |  None required. |
| **Reflectance Transformation Imaging (RTI)** | dng, jpg, obj, ptm, rti, wrl, tif,   | Data (images and outputs) derived from the photographic method of RTI. | None required. |
| **Report** | doc, docx, odt, pdf, rtf, txt, md | Text files that are formal reports Text files that represent a digital version of a formal publication, whether online or in print. | None required. |
| **Site Record** | doc, docx, odt, pdf, rtf, txt, md [any raster image files - See Photograph and Other Raster Image] | Scanned physical site records such as context and other recording sheets, site registers, site plans and section drawings. | None required. |
| **Tabular Data** | accdb, csv, dbf, json, mdb, odb, ods, rdf, sql, tsv, txt, xls, xlsx, xml | Tabular datasets such as databases and spreadsheets. | [Tabular Data technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/tabular_data_metadata_template.xlsx) |
| **Vector Graphic** | dwg, dxf, svg | Graphical vector datasets such as CAD (computer assisted design) models. | [Vector Graphic technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/vector_graphic_metadata_template.xlsx) |
| **Virtual Reality and Visualisation** | obj, stl, wrl  | Other 3D models and visualisation including virtual reality. This data should not include datasets derived from ‘Photogrammetry’. ‘Laser scanning’, ‘LIDAR’ or derived from specific medical imaging techniques such as CT Scanning. | [3D technical metadata template](https://raw.githubusercontent.com/uoy-ads/ads-ingest-documentation/master/technical_metadata/3D_technical_metadata.xlsx) |
| **X-radiography (X-ray) Scanning** | bmp, dcm, gif, jpg, png, tif  | Images and data produced by X-ray scanning. | None required. |
| **X-ray Fluorescence** | txt, xml  | Data resulting from X-ray fluorescence (XRF) spectroscopy | None required. |


## Categories not listed

If the data category you require is not listed above, or you are unsure as to what category your data should fall under, please contact the [Helpdesk](https://archaeologydataservice.ac.uk/contact/) with the subject line *'Ingest'* for advice. 