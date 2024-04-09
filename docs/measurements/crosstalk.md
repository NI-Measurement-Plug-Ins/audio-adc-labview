# Crosstalk
This service performs Crosstalk measurement.
## Tested Hardware Setup 1

  ![alt text](meas-images/hardware-setup-for-CDB5381.png)

## Tested Hardware Setup 2

  ![alt text](meas-images/hardware-setup-for-TLV320ADC3101-K.png)

## InstrumentStudio Panel

### Usage

1. Select appropriate resource names, data line and channel according to the hardware setup and update other parameters as needed. Ensure the protocol settings are good. Please note that, measurement is working in I2S by default.

   ![alt text](meas-images/crosstalk-config.PNG)

2. Run the measurement. The crosstalk value is calculated and displayed in the panel below.

   ![alt text](meas-images/crosstalk-meas-results.PNG)
3. The generated and acquired signals can be seen from time domain and frequency domain graphs.

   Crosstalk Measurement - Frequency Domain:


   Crosstalk Measurement - Time Domain:
   ![alt text](meas-images/crosstalk-time-domain.PNG)
