# 😃 IoT Notes


# Characteristics of IoT
- • Dynamic & Self-Adapting 
- Self-Configuring 
- Interoperable Communication Protocols 
-  Unique Identity 
- Integrated into Information Network
# IoT devices can:
- Exchange data with other connected devices and applications (directly or
- indirectly), or
- • Collect data from other devices and process the data locally or
- • Send the data to centralized servers or cloud-based application back-ends for
- processing the data, or
- • Perform some tasks locally and other tasks within the IoT infrastructure,
- based on temporal and space constraints



# Block Diagram of IoT device:
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588788137564_image.png)



# IOT protocols:
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588788089935_image.png)

# Request-Response communication model
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588788257366_image.png)



# Publish-Subscribe communication model
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588788378726_image.png)

# Push-Pull communication model
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588788420870_image.png)



# Exclusive Pair communication model
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588788464382_image.png)



# REST-based Communication APIs
> It is based on server-client model  where http packets are transferred between client and server with some basic command including GET, POST, PUT… and server returns the value after fetching it from resources.
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588788850904_image.png)



# WebSocket-based Communication APIs
> It follows the full-duplex communication between clients and servers, where first two and last two are connection setup and close requests and responses, and between them there is bidirectional trading of data frame.
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588788993469_image.png)





# IoT levels:-
> first lets know about the blocks that completes up your level
1. **Database:**  it stores the data generated by iot devices and sensors. it can be stored either locally or in the cloud depending upon the size and connectivity.
2. **Webservices:** It is a link between IOT devices and analysis components. they can be either implemented as http/rest or using websockets.
3. **Analysis components:** it is responsible for analyzing the IoT data and generate results out of them
4. **Applications:** user interface for control and monitor aspects of iot system


## level-1:
> Room temperature is monitored using temperature sensor and data is stored/analysed locally. Based on analysis made, control action is triggered using mobile app or it can just help in status monitoring.
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588790120172_image.png)

## level-2:
>  Agriculture applications, room freshening solutions based on odour sensors etc.
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588790194395_image.png)

## level-3:
> It is same as Level-2 but you have got big data, which means u need more computational power


![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588790419709_image.png)



## level-4:
> This level contains multiple nodes with the help of multiple sensors and they perform local analysis and then send their data to cloud
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588790601354_image.png)



## level-5:
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588790695502_image.png)

> It also contains the multiple nodes but has one coordinator nodes which takes the input from all the end nodes and then perform local analysis and then send it to cloud for further processing.
> 
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588790716952_image.png)

> example for level-5 is forest fire detection where multiple sensors are used for detection of fire in wide area
## level-6:
> It has multiple independent end nodes that perform sensing and actuation and then sends data to cloud.
> the centralised controller is aware of status of all the end nodes and sends command to all the controllers.
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588791150920_image.png)



----------
# M2M (machine-to-machine)
> it refers to networking of machines for the purpose of remote monitoring and control and data exchange.
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588795308956_image.png)

- It comprises of machines (or M2M nodes) which have embedded hardware modules for sensing, actuation and communication.
- many communication protocols can be used such as Zigbee, Bluetooth, ModBus
- the communication network provides connectivity to remote m2m area networks.
- can be wired or wireless
- network can either use proprietary or non-IP based
## m2m gateway:
> since there is non-ip based protocol, m2m nodes within the single network cannot communicate with nodes of other network.
> for communicating remote m2m network m2m gateways are used.
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588796302495_image.png)



## difference between M2M and IoT:
## 
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588797129300_image.png)

| Topic                     | M2M                                                     | IOT                                                                                                 |
| ------------------------- | ------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| C**ommunication -→**      | proprietary or non-ip based                             | ip based                                                                                            |
| **machine vs thing→**     | homogeneous machine types                               | physical object that have unique identifier and can sense and communicate with external environment |
| **hardware vs software→** | emphasis more on hardware                               | emphasis more on software                                                                           |
| data collection**→**      | point-solution or on-premise storage                    | is collected in cloud                                                                               |
| application**→**          | diagnosis applications, service management applications | analytics applications, enterprise applications, remote diagnosis                                   |

## communicatio in iot vs m2m
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588796925382_image.png)



# SDN (software defined networking)


https://www.youtube.com/watch?v=Z5Gi2Bpd82M


for deep understanding watch this video:

https://www.youtube.com/watch?v=TQVl5-G3u2U&

    sdn → trafic
    nfv → devices


----------


# IoT design methodology:-
## steps:-
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588834749777_image.png)



- Purpose & Requirements:
- process specification
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588834874007_image.png)

- domain model specification
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588835214612_image.png)

- Information model specification
- service specification
- iot level specification
- 


----------
## building block of IOT device:
1. **sending**
2. **actuation**
3. **communication**
1. **analysis and processin**g


## block diagram of Iot:
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588838290429_image.png)

# Raspberry Pi
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588838317958_image.png)

