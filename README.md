# Current-Topic
Intro: What is your topic? What will you do?
4 Layers:IOT devices, network, data process, data services.
   - Data processing: 
      + Contains server and IoT device. 
      + Server will the user's IoT device to take a picture then process the image using Object Detection by detecting and counting the number of fruits in the fridge .
      + (insert here database). 
      + It will send the results back to the server together with suggestions.
   - Data service: 
      + Mainly use Microsoft. Azure SQL server is a Microsoft product. 
      + This data server helps to store the data. 
      + Even Azure is out of service, the data can be transferred to another services to handle and maintain the service.
   - Network: 
      + Azure IoT Hub provides communication between Raspberry Pi (Wifi only) and user's device through Internet. 
      + This is easy for small project because of low cost, easy to deploy and expand scalability later.
   - IoT device: 
      + Raspberry Pi has low energy cost, cheaper, larger memory and better clock speed for handling complex tasks. 
      + The biggest advantage over Arduino supports camera and on-board network. 
      + It can be easily connected to Internet using Ethernet port.
