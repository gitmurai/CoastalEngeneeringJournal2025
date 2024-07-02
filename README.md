### Appendix to the paper
# Title : Field measurements of sedimentary structure of beach gravels using an unmanned aerial vehicles (UAV)-based multi-directional photometric analysis

Author :Ryosuke Muraia and Shinji SATO \
Date : June 30 ,2024

### DOI :


## ABSTRACT
＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊＊（Will post after procedure is completed.）


### KEYWORDS
multi-directional photometric analysis; UAV photogrammetry; gravel structures; morphodynamics of gravel beach

## Appendix
The appendix includes two core programs and multiple input files.
- ForCoastal_00_Tool_Raw2Tiff_Ver202406.ipynb
- ForCoastal_01_dsm-OlPh-PhA-OANomal_Ver202406ipynb.ipynb
- I_InputFiles
    - Kotogahama-20231228-1153-P1_CameraOmegaPhiKappa.txt
    - Kotogahama-20231228-1153-P1_CameraXML.xml
    - Kotogahama-20231228-1153-P1_DSMtliming.csv
    - Kotogahama-20231228-1153-P1_ListImages-INSIDE.csv
    - Kotogahama-20231228-1153-P1_ListImages.csv
    - P1-FlatCofficient.npz
- I_Raw
    - DJI_20231228115449_0106.DNG

The following is a directory containing the output files actually obtained when the program is executed.

- O_Tiff
    - DJI_20231228115449_0106.tif
- O_LuminunceImage
    - OA-Luminunce-DJI_20231228115449_0106-005-015-15.tif
    - VI-DJI_20231228115449_0106-005-015-15.tif
- O_AngleImage
    - OA-HSV-DJI_20231228115449_0106-005-015-15.tif
    - OA-NormalDJI_20231228115449_0106-005-015-15.tif
    - OA-RGB-DJI_20231228115449_0106-005-015-15.tif
    - PA-DJI_20231228115449_0106-005-015-15.tif





### Programming Environment
Python 3.8 \
OS Ubuntu