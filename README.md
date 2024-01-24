# Failure-Managment-system
The system is designed to acquire the raw data of a sensor, filter it and diagnose the data.
# Requirments:
  1- Sensor raw values are acquired every 20ms and KeyOn enabled 
  2- Diagnostic system is triggered every 100ms.
  3- Sensor value will be filtered using a median filter and averaged every 5 readings, the average filter is triggered every 20ms.
  4- Diagnostic system will start working if the voltage is greater than 16V or less than 6V +-1%.
  5- If failure is confirmed, the sensor value will be set to a specific constant (Max=14 V and Min=10 V).
  6- Sensor averaged values above 14 and under 10 will be clamped and reported. 
  7- KeyOFF enabled will reset all the outputs by specific values.
  
