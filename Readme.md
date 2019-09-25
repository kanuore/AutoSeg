# Introduction to AutoSeg -- an image annotation tool

For latest updating information please refer to <ReleaseNotice.txt>

Easy and user friendly annotation tool, it supports area annotation, polygon annotation, rectangle annotation. 

Annotation of landmarks & points are not available yet.



You may extract imagesTest.7z anywhere in your disk and start testing.



Functions overview are given as follows,

![img](OverView.png)



In processing of marking, single click to add points, and double click to finish the polygon or spline areas, etc.

After you finished the marking, you may edit the polygon,

1. double click to add points to the nearest edge
2. right click to delete extra points



When the polygon is acceptable, click the check button (or press the carriage return button on your keyboard) to accept it and convert it to annotation.

![img](01.gif)



![img](02.gif)



The annotation files are saves as json format, mainly coco format, you need a category file for all annotations.



Different from coco format (2 level), Autoseg accepts multiple levels of annotation, you may check the menu category->setup to see the results.

Some functions (left row buttons) are planned but not finished yet, luckily these are functions not frequently used.

You can play with functions of superpixels or cannyedge, these functions are a little bit complicated to use, but easy to understand. I just give the demo of using it.

The "Delete" function is given as follows, you make a selection with polygon, polyspline, or manual draw button, when press the del key on your keyboard, any selected area inside will be marked as background.



![img](03.gif)

You may read the about-> help if you have comments or requirements about these annotation tool.



Categories should be carefully manipulated, so some enabling/disabling functions are added, 

![](categorymanipulation.gif)



## Automatic Saving

This function is specially design to speed up your annotation. 

The annotations will be saved for you when you click next or previous button, so no time will be wasted when you move on to the next image.

Below you can see that the saving box popups only once for the destination folder of the annotations, 

![](autosaving.gif)



## General short key

A/a -- auto smart mode
F/f -- foreground mode
B/b -- background mode

carriage return-- accept/transfer current results to annotation

escape - - reset all conditions



## Donation

We will keep updating this software, any advice are welcome.

如果您熟悉使用QQ群，可以加入我们的服务群SpaceServices (262375262)，我们的工程师会负责解答您的问题。



## About us

SpaceSoftwares is a team focused on high accuracy image annotation and image segmentation, we target and provide the highest accuracy in semantic segmentation to auto-driving, medical imaging, general machine learning, tracking, automation, etc.;

We focusing on accuracy improvements,  our AI models are widely applied to industrial applications such as    precision positioning system, defect detection, classification, etc..

For anything please contact us [tansheng@spacesoftwares.com](mailto:tansheng@spacesoftwares.com)
