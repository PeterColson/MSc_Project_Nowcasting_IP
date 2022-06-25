# MSc_Project_Nowcasting_IP

This github repository contains all the files used for my MSc Data Science Project - Nowcasting US Industrial Production Using Machine Learning.

The files listed are as follows:
Data_pull_no_vintages.ipynb – Accesses the FRED database via the API to download all higher frequency series
IP_Benchmark_V3.ipynb – Creates the benchmark AR model of IP
PIPELINE_V5_Linear.ipynb – contains the hyperparameter tuning and rolling nowcasts for the linear regularised regression models 
PIPELINE_V5_NN.ipynb – contains the hyperparameter tuning and rolling nowcasts for the neural network models
PIPELINE_V5_LSTM.ipynb - – contains the hyperparameter tuning and rolling nowcasts for the LSTM models
Project_library.ipynb – contains the functions and dictionaries frequently used across all of the above notebooks
Current.zip – contains the vintage of the FRED MD database used to train the models for the report
Daily_2021_7_26.zip – contains the vintage of the daily series used to train the models for the report
Weekly_2021_7_26.zip – contains the vintage of the weekly series used to train the models for the report
Ip_release_dates.csv – contains historic IP release dates used for vintagisation
Nn_all_final.h5 – saved model values of the optimal neural network for all features
Nn_f_final.h5 – saved model values of the optimal neural network for F features
NN_mi_final.h5 – saved model values of the optimal neural network for MI features
Lstm_all_w1_v2.h5 – saved model values of the optimal LSTM network for all features
Lstm_f_w1_v2.h5 – saved model values of the optimal LSTM network for F features
Mi_lstm_w1.h5 – saved model values of the optimal LSTM network for MI features
MSc_Project_Report_PColson_13186931.pdf - The project report outlining the process and model results

To run the program, save to your local directory and unzip the data files, and run each of the IP_Benchmark_V3 and Pipeline_V5 files in turn.
If you want to update the higher frequency data first, run Data_pull_no_vintages.ipynb first and then update all path names to the latest data in the other files.


