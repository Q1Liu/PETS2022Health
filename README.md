# PETS2022Health Code
This is the code for PETS 2022: Health Information Exposed: Privacy Risks in Bluetooth Traffic from Wearable Devices.
Data Folder contains all the data we collected. Our dataset contains a wide range of health wearable devices from different brands. Devices we collected are: Apple Watch, Fitbit inspire, Mi band, Withings BPM, Withings Sleep Analyzer, Withings Body Scale, iHealth Blood Pressure, SonoHealth EKG Monitor, HealthTree Blood Oxygen Monitor, Govee Thermometer Hygrometer, Pip Stress level monitor, Fitdays Weight scale, FitIndex Body fat Scale. 

Besides various functionality and brands, we also collected data for different activities. We collected different running speeds for Mi Band and Fitbit, breath, and different cycles for Apple watch. 

All_Data: contains all collected data
Processed_CSV: contains processed csv files with aggregated action
Apple_Breath, Apple_Cycle, Fitbit_Speed, Mi_Speed folder names speak for the folder. 

========================================== <br>  
The goal of the code is to identify Health Wearable device brands, devices, actions, and fine-grained device actions. 
Health Device Classification.ipynb contains the code for brand, device, action identification.
Speed Regression.ipynb contains the code for running speed regression for Mi and Fitbit.
