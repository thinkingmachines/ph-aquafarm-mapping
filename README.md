# Philippine Aquafarm Mapping
This repository accompanies our [technical note](https://docs.google.com/document/d/1WYm-KH0TaujAS3Cw6FD8V3TNrUxQnjIwY6QUh8Ly5Ac/edit?usp=sharing), *"Using Computer Vision and Open Geospatial Data in Mapping Aquaculture Farms"*.
    
The goal for this project is to drive progress in computer vision-based mapping using open-source datasets which can be easily replicated and scaled to other areas in need of aquaculture mapping. 
    
    
# Set-up
To get started, locate and run the jupyter notebook `notebooks/Aquafarm Mapping Using Pytorch.ipynb`, which goes through the whole process from downloading the Aquafarm Image dataset to training and evaluating the aquafarm mapping computer vision model. 

This notebook is written to run in the cloud using Google Colab. Google Colab provides free access to computing resources including GPUs, allowing you to run the notebooks in your internet browser at no cost. To run the notebook in Colab, follow these steps:
1. Open webpage to Google Colaboratory: https://colab.research.google.com/
2. On the top of the prompt, click `GitHub`.
3. In the URL field, enter the URL of this repo: `https://github.com/thinkingmachines/ph-aquafarm-mapping`
4. Click on `Aquafarm Mapping Using Pytorch.ipynb` in the search results below

If you would like to run the notebook in your local repository, clone this repository using `git clone`. When running the notebook, skip the **Mount Drive** section of the notebook and edit the local paths in **File Locations** accordingly.

 
# Data Sources
**Aquafarm Image dataset**: This dataset comprises 2021 annual median Sentinel-2 RGB composite images of selected areas in the Philippines. The images are classified as aquaculture or non-aquaculture and were annotated through manual visual inspection using a tagging web application. This dataset is publicly available, and can be  downloaded this dataset by running the notebook or direct download from [Google Drive](https://drive.google.com/file/d/1o7eWWIbEDPSgjP5CwEFi9GQsmz6cEyp1/view?usp=sharing).
    
# Citation

Use this bibtex to cite this repository:
 
 ```
 @misc{ph_poverty_prediction_2018,
  title={Using Computer Vision and Open Geospatial Data in Mapping Aquaculture Farms in the Philippines},
  author={Flores, Ren Avell and Cortez, Joshua and ???},
  year={2022},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/thinkingmachines/ph-aquafarm-mapping}},
}
 ```
    
 # Acknowledgements
 
