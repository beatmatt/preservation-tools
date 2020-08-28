# Tika File Identifier

| Category | Evaluation |
| --- | --- |
| **Description** | Identifies file formats in a directory. Recursively run Apache Tika over all files in a specified directory and save output metadata (TikaRunner.py). Then process output metadata and collate into a single CSV file (CSVFormatter.py), and summarise the data in the CSV file (Summariser.py) |
| **Operation/System** | Windows |
| **File Format** | - |
| **Experience** | Input from OPF: A few issues to resolve with odd files, but deals successfully with problematic .psd. Saves lots of manual effort. Deals with unusual file extensions well. Additional metadata is added bonus! |
| **Licence** | Open Source |
| **COPTR** | - |
| **Source** | https://github.com/opf-labs/SPRUCE/tree/master/TikaFileIdentifier bzw. http://wiki.opf-labs.org/display/SPR/Tika+Batch+File+Identification |
