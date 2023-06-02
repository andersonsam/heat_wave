# Modelling the streamflow response to heatwaves across glacierized basins in southwestern Canada

Code associated with the paper "Modelling the streamflow response to heatwaves across glacierized basins in southwestern Canada" by Sam Anderson and Valentina Radic (2023).

This study applies previously trained deep learning hydrological models ([code](https://github.com/andersonsam/cnn_lstm_era) / [paper 1](https://hess.copernicus.org/articles/26/795/2022/hess-26-795-2022.html) / [paper 2](https://www.frontiersin.org/articles/10.3389/frwa.2022.934709/full)) to simulate the streamflow response to heatwaves at 111 basins in southwestern Canada.  

For detailed information about the results and their implications, please see the associated paper.  See below for a brief overview of context and results of this study.
___  

## Running the Code  

This code runs best using a GPU in Google Colab, in order for fastest application of the deep learning models.  The code starts by cloning in this heatwave repo (where the code and requirements are stored), as well as [this model development repo](https://github.com/andersonsam/cnn_lstm_era) (where the deep learning models are stored).  All required datasets are stored and explained in the model development repo.  All data generated in this code is saved and accessed in Google Drive for ease of access within Google Colab.
___

## Study Region

![alt text](https://github.com/andersonsam/heat_wave/blob/main/Figures/study_region%20(1).png)
___  

## Simulation Results: Individual basins

The streamflow response to heatwaves can be characterized by two features: an initial streamflow surplus ($\Delta Q_{max}$), and a delayed streamflow deficit ($\Delta Q_{min}$).  

![alt text](https://github.com/andersonsam/heat_wave/blob/main/Figures/Qhw_Q%20(7).png)
___  

## Simulation Results: Regional scale

$\Delta Q_{max}$ and $\Delta Q_{min}$ vary by the timing of heatwave onset and by glacier coverage ($G$).

![alt text](https://github.com/andersonsam/heat_wave/blob/main/Figures/deltaQmax_deltaQmin_variability%20(2).png)
