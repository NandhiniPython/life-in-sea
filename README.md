# life-in-sea Image Classification dataset

Photographs of Life in sea as jpg images

`sealife_annotated.csv` file contains the following features:
1. `file_name`: str [unique values] - image file name
2. `land_visible`: bool [True,False] - `True` if land is visible, `False` otherwise
3. `seabed_visible`: bool [True,False] - `True` if seabed is visible, `False` otherwise
4. `tentacles`: str ['present', 'not present'] - `present` if tectacles are there, `not present` otherwise
5. `legs`: str ['present', 'not present'] - `present` if legs are there, `not present` otherwise
6. `shell`: str ['present', 'not present'] - `present` if shell is there, `not present` otherwise

Annotations are made manually.

This dataset can be used for multi-target image classification. 

Once targets are defined, all other features can be used as metadata to help improve the model.

`sealife_labels.jpg` explores class distribution among features.

![image](https://raw.githubusercontent.com/NandhiniPython/life-in-sea/main/sealife_labels.jpg)
