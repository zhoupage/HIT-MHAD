# HIT-MHAD：A multimodal human action recognition dataset fabricated by using depth cameras and 24-dimensional wearable stretch sensors
# HIT_MHAD: 利用深度相机和24维可穿戴拉伸传感器制作的多模态人体动作识别数据集
In order to facilitate the research of multimodal sensor fusion for human motion recognition, this paper provides a multimodal human motion dataset using Kinect depth camera and wearable stretch sensor, called the Harbin Institute of Technology Multimodal Human Motion Dataset (HIT-MHAD). The dataset includes data from a 24-dimensional wearable stretch sensor and depth data from the Kinect. The HIT-MHAD dataset provides time-synchronized depth video, skeleton joint position, and tension sensor data.  
为了便于多模态传感器融合用于人体动作识别的研究，本文提供了一个使用Kinect深度摄像头和可穿戴拉伸传感器的多模态人体动作数据集，称为哈尔滨工业大学多模态人体动作数据集（HIT-MHAD）。该数据集包含了来自24维可穿戴拉伸传感器的数据，和来自Kinect的深度数据。HIT-MHAD数据集提供了时间同步深度视频、骨架关节位置和拉伸传感器数据。  
### 1.Sensor
The use of sensors includes Kinect.   

<img src="https://github.com/zhoupage/HIT-MHAD/blob/main/kinect.jpg" width="400px">    

and 24-dimensional wearable stretch sensors  

<img src="https://github.com/zhoupage/HIT-MHAD/blob/main/zhinengyi.png" width="400px">    

### 2.、Synchronization
The sensors of different modalities are synchronized with each other by means of timestamps.
### 3.Dataset Introduction
HIT-MHAD collected data from 9 test subjects. Each subject performed 27 types of movements, with each movement repeated 10 to 15 times. The movements included the following: 
 ID | Action Name | ID | Action Name |ID | Action Name
 ---- | ----- | ---- | ---- | ----- | ----
1|arm cross|2| arm curl|3|balling
4| baseball|5| boxing|6| catch
7| clap|8| draw O clockwise|9| draw O counter clockwise
10| draw triangle|11| draw x|12| jog
13| knock|14|  lunge|15| pickup and throw
16| push|17|  sit to stand|18| squat
19| stand to sit|20|  swipe left|21|  swipe right
22|  tennis serve|23|  tennis swing|24|  throw
25| walk|26| wave|
