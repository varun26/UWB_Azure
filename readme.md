# Send UWB data to Azure using Azure IoT device SDK for Python

This folder contains simple samples showing how to use the various features of the Microsoft Azure IoT Hub service from a device running Python.

## Code

* iothub_client_anchorList.py is the code in python2.7 to display the list of UWB anchors in a network.

## How to run the samples
In order to run the device samples you will first need the following prerequisites:
* [Setup your development environment][devbox-setup]
> Note: On Windows, it is recommended to install the **iothub-client** module package using pip (see link above).
* [Create an Azure IoT Hub instance][lnk-setup-iot-hub]
* [Create a device identity for your device][lnk-manage-iot-hub] and retrieve the primary connection string for this device

* Run the application using the following command to run the simple sample (replacing `<device connection string>` with the one generated previously):
    ```
	python iothub_client_anchorList.py 
    ```

[lnk-setup-iot-hub]: https://aka.ms/howtocreateazureiothub
[lnk-manage-iot-hub]: https://aka.ms/manageiothub
[devbox-setup]: ../../doc/python-devbox-setup.md
