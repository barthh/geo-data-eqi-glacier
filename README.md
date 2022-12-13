# About The Project : Analyzing the evolution of the Eqi glacier with Planetary Computer and Python

Our objective is to observe a trace of global warming. What better way than to go to the North Pole and observe the evolution of the size of a glacier!

We chose Eqi, a glacier located in Greenland. We first observed the facade of the glacier with the Sentinel2 dataset. Having been confronted with problems, we decided to move to the Landsat dataset which allows us to have an observation which goes back more in time (1985 instead of 2018). To finish, we analysed a small part located further back.

## Content

Usefull content table :

| Template name | Description |
| ------------- | ----------- |
| [Sentinel Study](./Facade-sentinel.ipynb/) | The first Analysis with Sentinel |
| [Landsat Study](./Facade-Landsat.ipynb/) | The second Analysis with Landsat |
| [Back of the glacier Study](./Back-glacier-part-sentinel.ipynb/) | The third Analysis on the back of the glacier (Sentinel) |
| [Env file](./conda_env.yml) |  Contains the environment |

# Notebook observations

NB: The links below provide access to the notebooks on [nbviewers](https://nbviewer.org/github/barthh/geo-data-eqi-glacier) for a better rendering.

- Glacier facade (2018 - 2022) : [notebook](https://nbviewer.org/github/barthh/geo-data-eqi-glacier/blob/main/Facade-sentinel.ipynb) </br> Observation of glacier melt with the [Sentinel-2 L2A][Sentinel doc] dataset. This notebook isn't complete.

- Glacier facade (1985 - 2022) : [notebook](https://nbviewer.org/github/barthh/geo-data-eqi-glacier/blob/main/Facade-Landsat.ipynb
) </br> Observation of glacier melt with the [Landsat-C2 L2][Landsat doc] dataset.

- Midland portion of the glacier (2018 - 2022) : [notebook](https://nbviewer.org/github/barthh/geo-data-eqi-glacier/blob/main/Facade-sentinel.ipynb) </br> Observation of a portion of the glacier with the Sentinel-2 L2A dataset.

<!-- MARKDOWN LINKS & IMAGES -->
[Sentinel doc]: https://docs.sentinel-hub.com/api/latest/data/sentinel-2-l2a/
[Landsat doc]: https://www.usgs.gov/landsat-missions/landsat-collection-2-level-2-science-products
