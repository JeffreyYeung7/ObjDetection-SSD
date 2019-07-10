# Multiple Object Detection using Single Shot Detector

Detected multiple objects with a single forward sweep of the network.

Increased mAP of targetted class (bird) by unevenly distributing data and with data augmentation techniques.

Example 1 of before and after:
![alt text](https://github.com/JeffreyYeung7/ObjDetection-SSD/blob/master/bird_demo1.png)
Example 2 of before and after:
![alt text](https://github.com/JeffreyYeung7/ObjDetection-SSD/blob/master/bird_demo2.png)
From above, we can see that performance and bounding boxes are visually improved

However, by the No Free Lunch Theorem, increasing the performance of one class results in the worsening of another. In the following example this is shown in that the plant class's performance decreased.
![alt text](https://github.com/JeffreyYeung7/ObjDetection-SSD/blob/master/sofa_demo.png)
