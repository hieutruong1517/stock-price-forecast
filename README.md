# stock-price-forecast
Stock price forecast using data from 2017 - 2020 of FPT, HPG, STB and VIC found on Vietstock - Final Project of Machine Learning subject
# Summary
1. Find and retrieve stock data from 2017 to 2020 of FPT, HPG, STB, VIC.
2. Preprocess the data to train in the model.
3. Put processed data into RNN model, MLP model, LSTM model for training.
4. Process test data for the model.
5. Predict the next 14 days by giving the predict model 1 day, add that date to the dataset for training and continue predicting. Repeat 14 times and we will have 14 days according to the required topic. (To forecast the upcoming 14 days, the approach involves initially predicting just one day. Subsequently, this predicted day is added to the existing dataset by shifting the entire data one step to the right, discarding the first row. The model is then retrained using the updated data, enabling it to forecast the subsequent day. This process is repeated iteratively to forecast the consecutive days.)

The project emphasizes the critical role of input data in machine learning models through the comparison of 4 stock codes: FPT, HPG, STB and VIC.
You can read my report for this subject in "Report_En.docx" file.
