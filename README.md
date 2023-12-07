# DroneDetect


![DroneDetect](https://github.com/innovativethinker/dronedetect/assets/127458338/f6a5331f-364f-42f7-8158-abbf13212152)

Drone Detects Misssion

The goal of the Drone Detect company  is to create a cheap system of drone detection for civilian use. Examples where this is useful will be for people who are concerned for there privacy and have large acreages that are hard to monitor. Florida Fish and Wildlife have no drone zones for hunters using the wildlife management areas (WMA) and this can deter illegal use of drones and help monitor millions of square acres of state conservations, preservations and W.M.A's. Airports around the world can make use if this detection system to keep airspace safe for airlines and there passengers. Drone detect can offer fast response of drone detection invading unauthorized airspace.

SAM

Sampling Prompts: The tool samples single-point input prompts in a grid-like pattern over an image. These prompts are used as input to the SAM system to generate masks.

Predicting Multiple Masks: From each sampled prompt, SAM predicts multiple masks. This suggests that SAM can generate masks with variations or different features based on the same input prompt.

Filtering and Deduplication: After generating multiple masks, the tool applies a filter to select masks of high quality. It may also perform deduplication, ensuring that similar or redundant masks are removed. This step helps in retaining only the most relevant and distinct masks.

![image](https://github.com/innovativethinker/dronedetect/assets/127458338/14464d14-1e86-48fa-8153-69b295bd946b)

https://colab.research.google.com/gist/innovativethinker/f00dd24aedeac0906bf499c03845ef31/hahn-ai-sam-automatic_mask_generator_example.ipynb

YOLO

Real-world Applications: YOLO has been successfully used in various real-world applications, including surveillance, security, and autonomous systems, which are areas where drone detection is crucial.

Multiple Object Detection: YOLO can detect multiple objects in a single frame, which is essential when dealing with scenarios where there may be multiple drones flying simultaneously.

![image](https://github.com/innovativethinker/dronedetect/assets/127458338/9a4ec588-936e-4449-b486-b17ad7b07c57)

A vs B

To keep it simple I chose a blank sky and a drone in the sky to train alexnet to detect the drones. 
From here I can then add other possible detections in the sky such as planes or birds to target the detection of drones only.

![image](https://github.com/innovativethinker/dronedetect/assets/127458338/f0c1aa21-e662-4b3c-a01c-e062fca95c15)

![image](https://github.com/innovativethinker/dronedetect/assets/127458338/aaa9687f-6df0-4cf6-99b0-7dcdfb52eaa4)



Wanb.ai

![image](https://github.com/innovativethinker/dronedetect/assets/127458338/168c1067-78b2-4572-97db-82c57042c935)

https://colab.research.google.com/drive/1mQIAgrmxTHnSeQtXtMso1fmg5StLT1jR#scrollTo=WANJibeUNghZ

Alexnet Slides

https://colab.research.google.com/drive/1mQIAgrmxTHnSeQtXtMso1fmg5StLT1jR#scrollTo=h7MhH8hrR3AE
![birdfeaturemap](https://github.com/innovativethinker/dronedetect/assets/127458338/b2dca792-d205-4f94-8580-3c762f7ab62f)
![birdfeaturemapmulti](https://github.com/innovativethinker/dronedetect/assets/127458338/e892b2c5-d1fe-44d3-b4ad-9437642d6367)

https://colab.research.google.com/drive/1_oQONAXyIiz4Oz3tq800MIdTNESp69Wa
