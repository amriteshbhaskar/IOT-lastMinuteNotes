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





# IoT levels:- 🤪 
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
> It is same as Level-2 😒 but you have got big data, which means u need more computational power


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
# M2M (machine-to-machine) 🤖 
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


# IoT design methodology:- 🧐 
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
## building block of IOT device: 🚔 
1. **sending**
2. **actuation**
3. **communication**
1. **analysis and processin**g


## block diagram of Iot:
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588838290429_image.png)

# Raspberry Pi
> taking it as an example for IOT device, sometime called as **“Perfect IOT device” 😇** 
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588838317958_image.png)

## Raspberry Pi GPIO
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588839140463_image.png)

## Raspberry Pi interfaces
> interfaces means the modes of operations, every mode is for different purposes.
> multiple modes can be used .
- **Serial** : uses Rx and Tx (receive and transmit resp.) pins for communication with serial peripherals
****- **SPI:** It is used for communication between one or more peripheral device
****- **I2C:** i2c pins help to connect hardware modules. it uses two pins SDA(data), SDL(clock)


##  One example 😎 
    from time import sleep
    import RPi.GPIO as GPIO
    GPIO.setmode(GPIO.BCM)
    #Switch Pin
    GPIO.setup(25, GPIO.IN)
    #LED Pin
    GPIO.setup(18, GPIO.OUT)
    state=false
    def toggleLED(pin):
    state = not state
    GPIO.output(pin, state)
    while True:
    try:
    if (GPIO.input(25) == True):
    toggleLED(pin)
    sleep(.01)
    except KeyboardInterrupt:
    exit()

**how to connect:-  🤩** 

![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588839830092_image.png)

----------
# Big Data
>  It is high- volume, -velocity and -variety information assets that demands cost-effective and innovating forms of information processing
## Three V’s ✌️ 
- **Volume:** too much of data
****- **Velocity:** speed at which data is generated, processing should be faster than generation
****- **Variety:** there are different types of data

some additional 😫 :

- **veracity:** depicts messiness, or trustworthiness
- **value:** getting value out of big data( sort of searching)


## How to store Huge Files?? 🤷‍♂️ 
- efficient access
- effective utilization of space
- redundancy or failsafe


## HDFS:
> It  is basically a file system. Just like a well-organized book, a HDFS  helps navigate data that is stored in your storage.
> It divides data in equal chunks of 128 MB 
> 
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588842614934_image.png)


**DataNode:-**
A DataNode stores data in HDFS.

**NameNOde:-** 

- keeps directory tree of all files in the file system.
- it tracks where file is stored among clusters
- Does not store the data of these files itself.
- two states: active & stand-by

**Secondary NameNode:-**

- helper for namenode
- puts a check point in file system for namenode to function better

**architecture of HDFS:-**

![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588842665367_image.png)



> **to ensure data is not lost, data can typically be replicated on :**
- local rack
- remote rack
- remote node
- randomly
> Default replication rate is 3 😍 

**Benefits of HDFS**

- **HDFS supports the concept of blocks:** When uploading a file into HDFS, the file is divided into fixed-size blocks to support distributed computation. HDFS keeps track of all the blocks in the cluster.
- **HDFS maintains data integrity:** Data failures or data corruption are inevitable in any big data environment. So, it maintains data integrity and helps recover from data loss by replicating the blocks and more than the node.
- **HDFS supports scaling:** If you like to expand your cluster by adding more nodes, it’s very easy to do with HDFS.
- **No particular hardware required:** There is no need for any specialized hardware to run or operate HDFS. It is basically built up to work with commodity computers.


----------
# Hadoop
> framework for distributed processing of large data sets.
> it  is designed to scale up from single servers to thousand of machines
> It is designed to handle failures

**Modules:-**

- Hdfs: file system
- Yarn: framework for job scheduling and resource management
- MapReduce: used for parallel processing of large data sets



## Map reduce:
> It is a powerful paradigm for parallel computation

Example:-

![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588843685196_image.png)

![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588843699379_image.png)


**Architecture:**

![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588844432282_image.png)

![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588843787296_image.png)


**Resource Manager(YARN):**

- **Scheduler**: Schedulers’ task is to distribute resources to the running applications
- **Application Manager:** manages applications running in the cluster.
![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588844169706_image.png)


**How does it work:-**

![](https://paper-attachments.dropbox.com/s_C5973B4F468A8D5F8B1A98367C70AA1D386A2E1DA402B128C7EFCA2135252821_1588844195897_image.png)

