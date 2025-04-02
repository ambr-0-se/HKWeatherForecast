![HK Night](photos/GettyImages-188076795-crop.webp?height=100)
# Graph Neural Networks for Weather Forecasting in Hong Kong

## Introduction
Weather forecast has been playing a critical role in contemporary society, and improving the accuracy of temperature forecast could bring numerous social and economic benefits. In this project, our objective is to leverage meteorological, spectral and temporal features to predict the weather in Hong Kong. 

I retrieved data from [Hong Kong Observatory](https://www.hko.gov.hk/en/index.html) (HKO), which provide dataset and API to extract data.

We experimented with different machine learning models and graph neural networks, and compared the performance with baseline methods.

## To-Do
- Concatenate multiple datasets
- Select stations, timeframe and features
- Store the data as a PyG object and build a graph dataset 
- Build a simple pipeline (consists of data preprocessing, train-test split, model training, model evaluation)
- Start writing the paper (Objective of the paper, structure, section title, introduction)
### Bonus
- Cross validation to find the best hyperparameter set
- Using more advanced GNN architecture
- Using time-series method to preprocess features/ kernels good at dealing with time-series data
- Encode geographical feature of each station to the representation 
    - lat and lon
    - coastal areas, urban centers, and hilly regions
- Adding more relevant attributes (time, other accessible weather features)
## Data source
[HK Observatory Open data](https://www.hko.gov.hk/en/abouthko/opendata_intro.htm)
[HKO API Documentation](https://www.hko.gov.hk/en/weatherAPI/doc/files/HKO_Open_Data_API_Documentation.pdf)
[HK Gov Open Data](https://data.gov.hk/en-datasets/category/climate-and-weather)



## Explanation of the file structure

## To run the code

## References
