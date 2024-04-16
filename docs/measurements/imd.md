# IMD Measurement
This service performs IMD measurement

## Tested Hardware Setup 1

  ![imd](https://github.com/NI-MeasurementLink-Plug-Ins/audio-adc-labview/blob/main/docs/measurements/meas-images/hardware-setup-for-CDB5381.png)

## Tested Hardware Setup 2

  ![imd](https://github.com/NI-MeasurementLink-Plug-Ins/audio-adc-labview/blob/main/docs/measurements/meas-images/hardware-setup-for-TLV320ADC3101-K.png)

## InstrumentStudio Panel

### Usage

1. Select appropriate resource names, data line and channel according to the hardware setup and update other parameters as needed. Ensure the protocol settings are good. Please note that, measurement is working in I2S by default.

   ![imd](https://github.com/NI-MeasurementLink-Plug-Ins/audio-adc-labview/blob/main/docs/measurements/meas-images/IMD.PNG)

2. Run the measurement. The calculated IMD Value displayed in the panel below.

   ![imd](https://github.com/NI-MeasurementLink-Plug-Ins/audio-adc-labview/blob/main/docs/measurements/meas-images/IMD%20Freq.PNG)
3. The generated and acquired signals can be seen from time domain and frequency domain graphs.

   IMD Measurement - Frequency Domain:
   ![imd](https://github.com/NI-MeasurementLink-Plug-Ins/audio-adc-labview/blob/main/docs/measurements/meas-images/IMD%20Freq.PNG)

   IMD Measurement - Time Domain:
   ![imd](https://github.com/NI-MeasurementLink-Plug-Ins/audio-adc-labview/blob/main/docs/measurements/meas-images/IMD%20Time.PNG)

