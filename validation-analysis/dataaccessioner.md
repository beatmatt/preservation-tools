# DataAccessioner

| Category | Evaluation |
| --- | --- |
| **Description** | This simple tool creates and validates checksums for a selected data set, stores them in the metadata of the individual files, collects various technical metadata (file name, file size, file format with PRONOM ID, hash value - via FITS) and compiles an XML metadata file from it (PREMIS - optionally with Dublin Core v 1.0, with manual addition). |
| **Operation System** | Windows, Mac, Unix  |
| **File Format** | - |
| **Experience** | Rather slow (3.5 GB in approx. 15 min. - operate always locally and not via network!). Result very good and structured. Thanks to assignment to PREMIS elements also usable for a later ingest. But rather machine-readable than person-readable. Can only be used for further use in everyday development/evaluation via detours (conversion from XML to CSV?). |
| **Licence** | Open Source |
| **Source** | http://dataaccessioner.org/ or https://github.com/seth-shaw/DataAccessioner/ |
