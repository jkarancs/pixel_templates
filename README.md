This code produces pixel template and generr db files by uploading template files and associating each detID with a template.

To produce db files, run either /CondTools/SiPixel/test/SiPixelTemplateDBObjectUploader_cfg.py or /CondTools/SiPixel/test/SiPixelGenErrorDBObjectUploader.py using cmsRun

The code requires as input a .csv file that can be made from a spreadsheet listing detector locations and template/generr IDs. File format can be found at the example (/CondTools/SiPixel/data/template_1D_IOV12/IOV12_map.csv)

Both require as input the magnetic field value in Tesla ("MagField" option) and a "version" string ("Version" option, currently set at "v12" with a new versioning scheme in the works). Optional parameters include the directory location of the template/genError files themselves and the run GlobalTag.

Works in progress include integration into CMSSW, and maybe even a visualization.

This code is recognized as part of Johns Hopkins University's contribution to the CMS collaboration in the form of "service work".
