1. [Hello, IoT World!]({{ site.url }}/workshop/thingy-4-windows/hello-windows-iot/)<br/>In this lab, you will build a simple single-circuit device that blinks an LED on and off (this is the ‘Hello, World! of the maker/IoT space).
2. [Nightlight]({{ site.url }}/workshop/thingy-4-windows/nightlight/)<br/>In this lab, you will capture analog input using a light-dependent resistor (photocell) and turn on or off an LED based on the amount of light detected.
3. [ThingLabs Thingy&trade;]({{ site.ur }}/workshop/thingy-4-windows/thingy/)<br/>In this lab, you will use multiple Grove sensors and actuators to build a device with multiple inputs and outputs. You will use this device for the rest of the labs in this series.
4. [Setting Up and Azure IoT Hub]({{ site.url }}/workshop/thingy-4-windows/setup-azure-iot-hub/)<br/>In this lab, you will provision a new Azure IoT Hub. Once you have the IoT Hub created, you will be able to create a new Azure IoT device (a software reference to your physical device) that you will use to send telemetry to Azure.
5. [Sending Device to Cloud (D2C) Messages]({{ site.url }}/workshop/thingy-4-windows/sending-d2c-messages/)<br/>In this lab, you will use the ThingLabs Thingy™ device that you built to capture and send messages to Azure IoT Hub.
6. [Displaying IoT Data]({{ site.url }}/workshop/thingy-4-windows/storing-displaying-data/)<br/>In this lab, you will build a data pipeline that captures the data coming into IoT Hub, processes it with Azure Stream Analytics, then routes it to downstream services. The first service you’ll build will consume the data and present it through an Azure Web App where it is rendered as a real-time graph.
7. [Sending Cloud-to-Device (C2D) Messages]({{ site.url }}/workshop/thingy-4-windows/sending-c2d-messages/)<br/>In this lab, you will use the Azure Web App to control the ThingLabs Thingy™ remotely. The Web App will send messages to the Thingy via Azure, which the Thingy will receive, procees, and act on.