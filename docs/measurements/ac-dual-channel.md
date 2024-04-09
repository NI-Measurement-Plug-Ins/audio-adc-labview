# AC Dual Channel
This service performs AC dual channel measurements: SNR, THD, THD+N, SFDR, Dynamic Range, Gain Error.

## Tested Hardware Setup 1

![alt text](meas-images/hardware-setup-for-CDB5381.png)

## Tested Hardware Setup 2



## InstrumentStudio Panel

### Usage

1. Select appropriate resource names, data line and channels according to the hardware setup and update other parameters as needed. Ensure the protocol settings are good. Please note that, measurement is working in I2S by default.
![alt text](meas-images/ac-dual-channel-config.PNG)

2. Run the measurement. The frequency, amplitude, SNR, THD, THD+N, Dynamic Range, Gain error, SFDR values are calculated and displayed in the panel below.
![alt text](meas-images/ac-dual-channel-meas-results.PNG)

4. The generated and acquired signals can be seen from time domain and frequency domain graphs.

   AC Dual Channel Measurement - Frequency Domain:
   ![alt text](meas-images/ac-dual-channel-freq-domain.PNG)

   AC Dual Channel Measurement - Time Domain:
   ![alt text](docs/measurements/meas-images/ac-dual-channel-time-domain.PNG)
