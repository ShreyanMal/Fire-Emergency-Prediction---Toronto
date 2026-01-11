# Fire Emergency Prediction Using a Spatio-Temporal Transformer

Please find the final report for the project in the files uploaded to the repository. 
My contributions to the project include data collection from the Toronto Open Data Portal. I collected demographic data for each ward. I also worked on data cleaning and data transformation to make the data ready to use to input into the model. This includes linearly interpolating data for missing years in the census data, as well as cleaning the weather dataset and normalizing the final dataset. I also researched the best model architecture to use, as well as implemented the final chosen architecture. During the implementation, I researched and implemented techniques like parallel GPU training and gradient accumulation to run the model at the largest depth possible. I was also responsible for the system flow architecture connecting the data to the model, which supplied the prediction to the UI for the end-user.

My contributions are highlighted on pages 11-15 in the report.

The Jupyter notebook for model implementation and results is available at https://www.kaggle.com/code/dualputu/capstone-model
