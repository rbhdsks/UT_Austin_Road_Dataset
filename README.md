# UT Austin Road Dataset

## Overview

This dataset contains annotated images collected at UT Austin. It supports applications such as object detection, traffic monitoring, autonomous driving research, and smart city initiatives.

## Dataset Information

- **Location:** University of Texas, Austin, USA
- **Number of Images:** 606
- **Image Resolution:** 934x474 pixels
- **Annotations:** Bounding boxes and class labels

## Dataset Structure

```
UTAustin_Road_Dataset/
├── IMG_UT_Austin/
│   ├── frame_00000.jpg
│   ├── frame_00001.jpg
│   └── ...
├── annotations/
│   ├── frame_00000.xml
│   ├── frame_00001.xml
│   └── ...
└── README.md
```

## Annotation Classes

The dataset annotations include the following object classes:

- `vehicles`
- `pedestrians`
- `traffic_signs`
- `traffic_signal`
- `car`
- `motorcycle`
- `bus`
- `truck`
- `animal`
- `other_vehicles`
- `auto_rickshaw`
- `cycle`

## Quick Example

Example Python usage:

```python
import cv2

image = cv2.imread('IMG_UT_Austin/frame_00000.jpg')
# Annotation processing from XML file
```

## License

This dataset is licensed under [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). Proper attribution is required.

## Citation

Please cite this dataset as:

```
@misc{UTAustin2025,
  author = {Nitesh Kumar Shah and Chandra Prakash Maurya and Navjot Singh and Kartikeya Gullapalli and Jahnavi Gadde},
  title = {UT Austin Road Dataset},
  year = {2025},
  url = {https://github.com/rbhdsks/UTAustin_Road_Dataset}
}
```

## Contributors

- **Nitesh Kumar Shah**, Student, IIIT Allahabad ([iib2021002@iiita.ac.in](mailto:iib2021002@iiita.ac.in))
- **Jahnavi Gadde**, Student, IIIT Allahabad ([iit2021190@iiita.ac.in](mailto:iit2021190@iiita.ac.in))
- **Kartikeya Gullapalli**, Student, University of Texas, Austin
- **Chandra Prakash Maurya**, Research Scholar, IIIT Allahabad ([prf.cpm@iiita.ac.in](mailto:prf.cpm@iiita.ac.in))
- **Prof. Dr. Navjot Singh**, Assistant Professor, IIIT Allahabad ([navjot@iiita.ac.in](mailto:navjot@iiita.ac.in))

---

Thank you for your interest in our dataset. Feedback and contributions are greatly appreciated!

