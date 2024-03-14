# Setup a Development Environment
If you want to commit changes to the repo, we recommend you use the current versions of application software unless a newer version enables new features. Software should work with newer versions of these dependencies.

## Software dependencies:
Install the below softwares and packages from NIPM

- NI-DAQmx (2022 Q3 or higher)
- NI-Digital Audio Acquisition and Generation Toolkit (2023 Q3 or higher)
- NI-DCPower (As recommended by InstrumentStudio, if SMUs are used for powering up the DUT)
- LabVIEW Sound and Vibration Toolkit (2021 or higher)
- LabVIEW Runtime Engine (2021 SP1 or higher)
- LabVIEW 64-bit (2021 SP1 or higher)
- Measurement Link (2023 Q3 or higher)

## VIPM packages

Download and install the below packages in this [link](https://github.com/ni/measurementlink-labview/releases/tag/v1.0.1).
- LabVIEW Grpc library - 1.0.0.1
- LabVIEW Grpc servicer - 1.0.0.1

Then, Download and install the below packages in this [link](https://github.com/ni/measurementlink-labview/releases/tag/v1.1.0.3).
- MeasurementLink service - 1.1.0.3
- MeasurementLink generator - 1.1.0.3

## Tested with:
- Instrument Studio 2023 Q1
- TestStand 2023 Q4

## Github and LabVIEW Guidelines:
Refer to [this](github-labview-guidelines.md) document for guidelines on github processes and labview development.

## Building NIPM packages
To build NIPM packages for the measurement plugin, refer to the [this](build-plugin.md) document.
