# JHOVE

| Category | Evaluation |
| --- | --- |
| **Description**  | JHOVE is one of the standard file format identification, validation and characterisation tool. It is implemented as a Java application and is usable on any Unix, Windows, or OS X platform with appropriate Java installation. |
| **Operation System**  | Windows, Mac, Unix  |
| **Application**  | Fileformat identification, validation |
| **File Format** | - |
| **Experience** | Information from KLA Workshop 2018: Question whether the validation tool JHOVE is still the only validator for standard PDF. The answer is "yes", because veraPDF is not suitable for the validation of standard PDF. In addition to JHOVE, pdfaPilot can be used to check the structure of the PDF file. With regard to the validation of JPEGs by JHOVE, defective JPEGs are sometimes not recognized (use "Bad Peggy" as a supplement). In TIFF validation, however, no significant defects were overlooked (DPF Manager is more user-friendly here, however). During the validation of GIF files, false alarms were occasionally issued, but JHOVE and ImageMagick could be seen on the same level. Further tips and hints for using recognition tools can be found in the Wiki of nestor working group Format Recognition. Furthermore, the own experience shows some issues for fileformat identification of audio files. While WAVE is not a problem, other audio formats are partly not recognized as such, but only as BYTESTREAM. |
| **Licence** | Open Source |
| **Source** | http://jhove.openpreservation.org/ |
