Paweła Knap,
sample rate: 11 025 Hz
length: 1. 600 seconds 2. 300 seconds

The measurement was taken with piezoelectric accelerometer and Raspberry Pi 4.  
Three bearings were analyzed: first with inner race fault, second with outter race fault and 
third bearing with no fault for reference. The speed varies from 700 rpm to 1000 rpm and back to 
700 rpm. The whole cycle is 1 minute long, 30 seconds for the speed up and 30 seconds for the slow down.
One of the measurements is 600 seconds long and the rest is 300 seconds long. 

There are two datasets:
The data were standarized to mean equal 0 and stanard deviation equal 1, also the sensivity rate adjustment 
was performed (it is specified for the sensor).

1. Spectrogram images created from every one second of measurement.
2. Data in timeseries form splitted in 500 samples long batches (saves as .csv files).