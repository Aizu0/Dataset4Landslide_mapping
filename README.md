# Dataset4Landslide_mapping
## Overview

Welcome to the CAS Landslide dataset! This repository contains a large-scale and multimodal dataset developed by the Artificial Intelligence Group at the Institute of Mountain Hazards and Environment, Chinese Academy of Sciences. The dataset is designed to address the challenges posed by landslides recognition and provides researchers with a comprehensive resource to support fast and efficient landslide identification.



## About the Dataset

The CAS Landslide dataset has been created to meet the growing need for a precise and comprehensive dataset in light of increasing landslide occurrences due to climate change and earthquakes. Unlike existing datasets with limitations in coverage, dataset size, and resolution, the CAS Landslide dataset offers the following key features:

- **Scale**: The dataset comprises a total of 20,865 RGB images, making it one of the largest resources for landslide recognition.
- **Multimodal**: It integrates both satellite and unmanned aerial vehicle (UAV) data from nine different regions, providing diverse perspectives and aiding in better understanding landslides.
- **Quality Assurance**: To ensure reliability and applicability, a robust methodology has been established to evaluate the dataset's quality, reducing the possibility of biases and errors.



## Detailed Information

The CAS Landslide dataset includes the following detailed information:

- **Image Format**: RGB images in TIF format.
- **Regions**: Data from nine different regions are included in the dataset. These regions are [Palu,Hokkaido Iburi-Tobu,Lombok,Tiburon Peninsula(Haiti),Mengdong Township,Moxitaidi,Moxi town,Longxi River,Wenchuan and Online].
- **Annotations**: The dataset provides ground truth annotations for each image, indicating the presence or absence of landslides.


**For more detailed information, please refer to the table below:**

| Subdataset                  | Amount | Acquisition Time  | Source                                         | Sensor             | Ground Resolution (m) | Authorization                           |
|-----------------------------|--------|-------------------|------------------------------------------------|--------------------|------------------------|------------------------------------------|
| Palu                        | 817    | 2021.01-2021.11  | Digital Globe Open Data Program               | WorldView2/3        | 5                      | CC-BY-NC 4.0                              |
| Lombok                      | 436    | 2019.05-2019.12  | Digital Globe Open Data Program               | WorldView2/3        | 5                      | CC-BY-NC 4.0                              |
| Hokkaido Iburi-Tobu         | 1484   | 2018.09-2018.10  | Geospatial information Authority of Japan     | SAT                | 3                      | BY 4.0                                   |
| Tiburon Peninsula (Sentinel)| 606    | 2020.03-2020.06  | European Space Agency                         | Sentinel-2          | 5                      | Non-commercial use                       |
| Tiburon Peninsula (Planet)  | 325    | 2021.09-2021.12  | Planet                                         | Planet             | 4                      | Planet education and research program    |
| Mengdong                    | 1155   | 2018.11.04        | Beijing Lanyu Fangyuan Technology Co., Ltd.  | SuperView-1        | 0.5                    | Image Licence                            |
| Moxitaidi (SAT)             | 652    | 2022.09-2022.10  | European Space Agency                         | Sentinel-2          | 0.6                    | Non-commercial use                       |
| Moxitaidi (UAV-0.6 m)       | 984    | 2022.09-2022.10  | Sichuan Geomatics Center                      | UAV                | 0.6                    | Derivative Works Licence                  |
| Moxitaidi (UAV-1 m)         | 483    | 2022.09-2022.10  | Sichuan Geomatics Center                      | UAV                | 1                      | Derivative Works Licence                  |
| Moxi town (0.2 m)           | 1635   | 2022.09-2022.10  | Sichuan Geomatics Center                      | UAV                | 0.2                    | Derivative Works Licence                  |
| Moxi town (1 m)             | 160    | 2022.09-2022.10  | Sichuan Geomatics Center                      | UAV                | 1                      | Derivative Works Licence                  |
| Longxi River (SAT)          | 1769   | 2015.03-2015.12  | China Centre for Resources Satellite Data and Application | GF-1               | 0.5                    | Image Licence                            |
| Longxi River (UAV)          | 2504   | 2011.03-2011.05  | Sichuan Geomatics Center                      | UAV                | 0.5                    | Derivative Works Licence                  |
| Jiuzhai valley (0.2 m)      | 5925   | 2017.08-2017.09  | Sichuan Geomatics Center                      | UAV                | 0.2                    | Derivative Works Licence                  |
| Jiuzhai valley (0.5 m)      | 1752   | 2017.08-2017.09  | Sichuan Geomatics Center                      | UAV                | 0.5                    | Derivative Works Licence                  |
| Wenchuan                    | 178    | 2008.11-2008.12  | U.S. Geological Survey                        | Landsat            | 5                      | Follow the terms and guidelines by LP DAAC|


## How to Use the Dataset

Researchers and practitioners can leverage the CAS Landslide dataset to advance the development of deep learning techniques for landslide identification models. The dataset serves as a valuable baseline for training and evaluating these models. Here are some potential applications:

1. **Landslide Prediction**: The dataset can be used to train predictive models that aid in anticipating potential landslide events, contributing to disaster preparedness and response planning.

2. **Landslide Monitoring**: Researchers can develop algorithms that use real-time data to monitor landslide-prone areas and provide timely alerts for mitigation measures.

3. **Landslide Analysis**: With access to a vast collection of images, the dataset supports in-depth analysis of various landslide characteristics, enabling better understanding and insights into the phenomenon.

## Citation

If you want to use the CAS Landslide dataset in your research or project, please cite the following work:

Xu, Y., Ouyang, C., Xu, Q. et al. CAS Landslide Dataset: A Large-Scale and Multisensor Dataset for Deep Learning-Based Landslide Detection. Sci Data 11, 12 (2024). https://doi.org/10.1038/s41597-023-02847-z

## License

This work is licensed under theCreative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0 Deed | Attribution-NonCommercial 4.0 International | Creative Commons).


## Feedback and Contributions

We welcome feedback and contributions from the community to improve the dataset and its usability. If you encounter any issues or have suggestions, please open an issue or submit a pull request in this repository.

## Contact

For any further inquiries or collaboration opportunities, please contact:

**Institute of Mountain Hazards and Environment, Chinese Academy of Sciences***
**Email:** cjouyang@imde.ac.cn

Thank you for using the CAS Landslide dataset! Happy researching! 🚀
