# Traffic-flow-Analysis

Forecast the spatio-temporal traffic volume based on the historical traffic volume and other features in neighbouring locations. Specifically, the traffic volume is measured every 15 minutes at 36 sensor locations along two major highways in Northern Virginia/Washington D.C. capital region. The 47 features include: 1) the historical sequence of traffic volume sensed during the 10 most recent sample points (10 features), 2) weekday (7 features), 3) hour of day (24 features), 4) road direction (4 features), 5) number of lanes (1 feature), and 6) name of the road (1 feature). The goal is to predict the traffic volume 15 minutes into the future for all sensor locations. With a given road network, we know the spatial connectivity between sensor locations.

Data
Data (in .mat format) to be used for this problem can be found in below link:

mason.gmu.edu/~lzhao9/pages/dataset_pages/datasets/spatial/traffic_dataset.mat
