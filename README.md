# Fall Detection

In this study, to minimize damage caused by falls, I’ve proposed a model that can achieve real-time fall detection by applying LSTM based deep learning technique on IoT sensor data. 

## The Dataset

The data set used is the "Simulated Falls and Daily Living Activities" dataset, which is created by taking data from the falls and daily activities of 17 male / female volunteers through sensors13. In this data set, there are 36 dierent movements, including 20 falls and 16 daily living activities.
Data set consist of 23 meaningful features such as ‘Counter’, ‘Temperature’, ‘Pressure’, ’VelInc-X’, ’VelInc-Y’, ’VelInc-Z’, ’Acc-X’, ’Acc-Y’,’Acc-Z’, ’OriInc-x’, ’OriInc-y’, ’OriInc-z’, ’ ’OriInc-w’, ’Gyr-X’, ’Gyr-Y’, ’Gyr-Z’, ’Mag-X’, ’Mag-Y’, ’Mag-Z’, ’Roll’, ’RSSI’, ’Pitch’, ’Yaw’. 

## A sample of the daily activity time series change in all columns.
![alt text](https://github.com/HilalKocak/FallDetection/blob/main/adl.png?raw=true)

## A sample of the fall motion change time series change in all columns.
![alt text](https://github.com/HilalKocak/FallDetection/blob/main/fall.png?raw=true)

## Distribution of Activities of Daily Living Activities and Falls
![alt text](https://github.com/HilalKocak/FallDetection/blob/main/distadlandfall.png?raw=true)

## Lengths of Time Series in the Dataset
![alt text](https://github.com/HilalKocak/FallDetection/blob/main/sizeoftimeseries.png?raw=true)

## Result of LSTM 
![alt text](https://github.com/HilalKocak/FallDetection/blob/main/perf.png?raw=true)





