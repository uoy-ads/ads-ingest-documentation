# Technical Metadata

The new Ingest system enables depositors to utilise a single metadata template to upload their files to the system. However, for some data types additional technical metadata is required. Below is a full list of the file types that require an additional metadata file to be included.

## How to upload your technical metadata

The Technical metadata files should be included in the ingest system alongside the other files to be deposited. It is not required to list these additional metadata as a separate row in the template, however, each file (with approproate file extension) should be listed in the __Technical Metadata__ column of the [metadata template](./cmt_template_download.md). If you fail to include  requred additinal metadata file or include the file but do not list it in the metadata template, then the Ingest will produce an [error](/docs/appendix/core_metadata_errors.md).

## Data types that require technical metadata

| Data Category | Affected file extensions |
| :---- | :---- |
| Audiovisual | acc, aif, au, avi, bwf, flack, mkv, mp3, mp4, mpeg, mpg, avg, wav |
| Computed Tomography (CT) Scanning | bmp, dcm, gif, jpg, png, tif |
| Geophysics | csv, dat, mgr, rep, sgy, txt, xcp |
| Geographic Information System (GIS) Data | adf, asc, csv, e00, geojson, gml, img, jpg, kml, mid, png, shp, tif |
| Light Detection and Ranging (LiDAR) | tif, txt, e57, las, obj, pts |
| Laser Scanning | tif, txt, e57, las, obj, pts |
| Magnetic Resonance Imaging (MRI) | bmp, dcm, gif, jpg, png, tif \[video\] |
| Photogrammetric Survey | dng, jpg, obj, pts, tiff, wrl |
| Reflectance Transformation Imaging (RTI) | dng, jpg, obj, ptm, rti, wrl, tif, |
| Spectrometry | jdx, mzdata, mzml, mzxml, txt, xml |
| Tabular Data | accdb, csv, dbf, json, mdb, odb, ods, rdf, sql, tsv, txt, xls, xlsx, xml |
| Vector Graphic | dwg, dxf, svg |
| Virtual Reality and Visualisation | obj, stl, wrl |
| X-radiography (X-ray) Scanning | bmp, dcm, gif, jpg, png, tif |