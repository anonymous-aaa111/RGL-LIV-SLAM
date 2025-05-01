# Real-time Global Localization for LIV-SLAM Using Referenced Image

## Introduction
RGL-LIV-SLAM proposed a real-time global localization method which only relies on a Lidar-initial-visual SLAM (LIV-SLAM) and a referenced image
The proposed method enables long-range navigation without requiring GPS or loop closure, while eliminating accumulated localization errors.

An example on NCLT dataset squence 2012-02-04 is shown below:

raw video_demo can be downloaded from here: [Click to download](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/video_demo.avi)

![Video demo](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/videos/video_demo.gif)



## Adability for initial deviation

We evaluated the robustness of the proposed method under the condition of initial position deviation and heading deviation, examples of which are shown as below:

### Initial position deviation of 50m:
Video demonstration: [Click to download](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/videos/initial_pisition_deviation.avi)
![Initial Position Deviation](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/videos/initial_position_deviation.gif)

### Initial heading deviation of 6 degree:
Video demonstration: [Click to download](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/videos/initial_heading_deviation.avi)
![Initial Heading Deviation](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/videos/initial_heading_deviation.gif)

## Adability for indoor scene

The proposed method can adapt to indoor environment, where the referenced image is not feasible, due to the application of OAGS mechanism.

Video demonstration: [Click to download](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/videos/indoor.avi)

![Indoor Scene Result](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/videos/indoor.gif)


## Results on all test sequences
| sequence           | Image                               |
|--------------------|-------------------------------------|
|2012-02-02           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-02-02.jpg) |
|2012-02-04           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-02-04.jpg) |
|2012-02-05           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-02-05.jpg) |
|2012-02-19           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-02-19.jpg) |
|2012-03-17           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-03-17.jpg) |
|2012-03-25           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-03-25.jpg) |
|2012-04-29           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-04-29.jpg) |
|2012-05-11           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-05-11.jpg) |
|2012-06-15           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-06-15.jpg) |
|2012-08-04           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-08-04.jpg) |
|2012-10-28           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-10-28.jpg)|
|2012-11-17           | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/2012-11-17.jpg)|
|hkust_seq00          | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/hkust_seq00.jpg)|
|hkust_seq01          | ![](https://github.com/yao-yating/RGL-LIV-SLAM/blob/main/supplementary%20material/hkust_seq01.jpg)|
