# Philippine Aquafarm Mapping
![image](https://user-images.githubusercontent.com/61814579/166631451-33b35e4a-949b-4593-a5b3-7bda10e26ce4.png)

Shrimp farming industries across different countries are rapidly upscaling operations to meet the increasing demand for shrimp. However, this growth often comes at the expense of wetland ecosystems such as mangroves. As such, monitoring and mapping the continued development of aquafarms is essential in mitigating its impact in wetland ecosystems and ensuring a safe and responsible way of meeting the increasing demand for shrimp. However, on the ground monitoring of aquaculture farms can be slow and expensive, and timely information is often scarce or inaccurate.

Luckily, unprecedented growth in computer vision technology and open-source geospatial data leads to a scalable and cost effective alternative to mapping and monitoring aquafarms. Open data from satellite earth observation missions partnered with computer vision allows for rapid and up-to-date monitoring through automated satellite image interpretation. It also enables high-resolution mapping of aquaculture ponds, facilitating inventory analyses to support sustainable development of the planet’s valuable coastal ecosystems.

To this end, we developed the Aquafarm Image dataset for training a computer vision model to detect aquafarms. The dataset comprises 2021 annual median Sentinel-2  RGB images of selected areas in the Philippines, classified as aquaculture or non-aquaculture through manual visual inspection. Our goal is to drive progress in computer vision-based mapping using open-source datasets which can be easily replicated and scaled in other areas in need of aquaculture mapping.

In this repo, we demonstrate how the Aquafarm Image dataset can be used to train a computer vision model to identify if an image contains aquafarms using publicly available satellite imagery. 

This repository accompanies our [technical note](https://docs.google.com/document/d/1WYm-KH0TaujAS3Cw6FD8V3TNrUxQnjIwY6QUh8Ly5Ac/edit?usp=sharing), *"Using Computer Vision and Open Geospatial Data in Mapping Aquaculture Farms"*.
    
    
## Set-up
This repo contains the jupyter notebook `notebooks/Aquafarm Mapping Using Pytorch.ipynb`, which trains and runs an image classification model on the Aquafarm Image dataset. 

This notebook is written to run on Google Colab. Google Colab provides free access to computing resources including GPUs, allowing you to run the notebook from your internet browser at no cost. To run the notebook in Colab, follow these steps:
1. Open webpage to Google Colaboratory: https://colab.research.google.com/
2. On the top of the prompt, click `GitHub`.
3. In the URL field, enter the URL of this repo: `https://github.com/thinkingmachines/ph-aquafarm-mapping`
4. Click on `Aquafarm Mapping Using Pytorch.ipynb` in the search results below

To run the notebook locally, clone this repository using `git clone`. When running the notebook, skip the **Mount Drive** section of the notebook and edit the local paths in **File Locations** accordingly.

 
## Data Sources
**Aquafarm Image dataset**: This dataset comprises 2021 annual median Sentinel-2 RGB composite images of selected areas in the Philippines. The images are classified as aquaculture or non-aquaculture and were annotated through manual visual inspection using a tagging web application. The dataset has an individual directory for aquaculture areas and another for non-aquaculture areas which contain Sentinel-2 images. It also comes with the vector polygons of 320x320 m grids used to define the boundaries of an area during the labeling process.

This dataset is publicly available, and can be  downloaded this dataset by running the notebook or direct download from [Google Drive](https://drive.google.com/drive/folders/1lrelthAFUf1dzbC1r9DCehY8613M4jyv).

    
    
## Citation

Use this bibtex to cite this repository:
 
 ```
 @misc{ph_poverty_prediction_2018,
  title={Using Computer Vision and Open Geospatial Data in Mapping Aquaculture Farms in the Philippines},
  author={Flores, Ren Avell and Cortez, Joshua and Nacpil, John Christian and Garonita, Oshean Lee and Miclat, Jt and Araneta, Anica and Faustino, Pia and Tingzon, Isabelle and Sy, Stephanie and Klinger, Dane and Goto, Garrett and Casado, Ana Plana},
  year={2022},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/thinkingmachines/ph-aquafarm-mapping}},
}
 ```
    
  
 # Acknowledgements
 
 This work was supported by [Conservation International](https://conservation.org) and [Thinking Machines](https://thinkingmachin.es)
