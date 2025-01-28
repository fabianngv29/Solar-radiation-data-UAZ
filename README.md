# Solar-radiation-data-UAZ
As part of this study to monitor and evaluate solar irradiance in agricultural applications, data was collected using two sensors: a BH1750 sensor and a Davis Instruments 6450 solar radiation sensor. Both sensors were integrated into a custom PCB and operated for a period of 30 days, resulting in the acquisition of 10,000 data points. To ensure accuracy, the Davis Instruments 6450 sensor installed on the PCB was calibrated using a reference Davis Instruments 6450 sensor mounted on a professional weather station.

# Data
The data acquisition involved continuous monitoring of solar irradiance levels, with measurements taken at regular intervals throughout the day. The BH1750 and the 6450 sensors were mounted on the PCB at fixed angles and positions to ensure consistent and reliable irradiance readings. The PCB-mounted 6450 sensor was calibrated by comparing its output with the reference 6450 sensor on the professional weather station, which was installed at the same height and angle as the PCB-mounted sensors.

Data from both sensors were transmitted in real time to the ThingSpeak application using an ESP32 microcontroller for processing and storage. The collected data, totaling 10,000 readings, was stored and managed using the ThingSpeak platform, which allowed for real-time data visualization, analysis, and cloud-based storage. Each data entry includes a timestamp, irradiance measurements from both sensors,ThingSpeak's analytics and visualization tools facilitated effective monitoring and comparison of data trends throughout the study period.

# Paper related and citation
Link to paper: 

# Acknowledgements
The authors want to thank the Mexican National Council of Humanities, Science and Technology CONAHCYT for its support to the National Laboratory of Embedded Systems, Advanced Electronics Design and Micro systems (LN-SEDEAM by its initials in Spanish), project numbers 282357, 293384, 299061, 314841, 315947, and 321128, also for the scholarship number 1301325