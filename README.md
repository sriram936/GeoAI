# GeoAI
This repo implements RandLANet with pretrained weights, on point cloud aerial lidar data of villages to classify ground and non ground points and finally generate DTM of the village

## Project Links

[Kaggle Link](https://www.kaggle.com/code/mahik9969/geoai)

[GeoAI custom dataset Link](https://www.kaggle.com/datasets/sriramm932/tera-baap-tera13231)

[GeoAI original dataset Link](https://www.kaggle.com/datasets/sriramm932/tera-baap-tera13231)

[Problem statement - Theme 2](https://github.com/sriram936/GeoAI/blob/main/National_Geo-AI_Hackathon__1.pdf?raw=true)

[Our Approach](https://github.com/sriram936/GeoAI/blob/main/Aerial%20GeoAI1.pdf?raw=true)

[RandLANet paper link](https://arxiv.org/pdf/1911.11236)

## Classified Point Clouds
<figure>
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/e8b55ce0-7e9c-4d26-958c-1f90f04a5607" />
<br>
<figcaption>Figure 1: Original vs Classified point cloud data (Top view).</figcaption>
</figure>
<br><br>
<figure>
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/44cf5764-de84-4eac-b707-7f969d58a0a8" />
<br>
<figcaption>Figure 2: Classified vs Original point cloud data (Side view)</figcaption>
</figure>

## Approach
1) Create classified point cloud data using Cloud Compare software
2) Break 3d data of village into grids
3) Implement RandLANet architecture
4) Use pretrained weights of Dales or Semantic3D data
5) Change the final layer from multi class for the corresponding pretrained weights data to 2 classes namely ground and non ground
6) Train the model with our village data grids
7) Finally do train, validation and test
8) Evaluate the model and analyze the results
