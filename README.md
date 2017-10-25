apriltags_ros  [![Build Status](https://api.travis-ci.org/RIVeR-Lab/apriltags_ros.png)](https://travis-ci.org/RIVeR-Lab/apriltags_ros)
=============
Build Satus probably incorrect

General Info about Apil Tags [https://april.eecs.umich.edu/wiki/AprilTags](https://april.eecs.umich.edu/wiki/AprilTags)

AprilTags for ROS

## How to Use:
- Clone this repository into the src directory of your catkin_workspace
- Run catkin_make from the root of your workspace
- Change remap parameters in the launch files to match your input topics

## Example With ROSbag from Zed Camera
- Download ros bag from [here](https://drive.google.com/drive/folders/0B1-HWmWqxMxSMzc1UmxKU1dEWUU?usp=sharing)
- Launch corespoing launch file

*Note: Mesurments used in launch file probably do not match rosbags*

## Topics
#####__/apriltag_detector/compressed/parameter_descriptions__
I don't know what this does please add details and submit a pull request
#####__/apriltag_detector/compressed/parameter_updates__
I don't know what this does please add details and submit a pull request
#####__/rosout__
I don't know what this does please add details and submit a pull request
#####__/rosout_agg__
I don't know what this does please add details and submit a pull request
#####__/tag_detections__
This is a custome message type that is an array of poses including the tag id for each pose
#####__/tag_detections_image__
output image marking the found tags
#####__/tag_detections_image/compressed__
I don't know what this does please add details and submit a pull request
#####__/tag_detections_image/compressed/parameter_descriptions__
I don't know what this does please add details and submit a pull request
#####__/tag_detections_image/compressed/parameter_updates__
I don't know what this does please add details and submit a pull request
#####__/tag_detections_image/compressedDepth__
I don't know what this does please add details and submit a pull request
#####__/tag_detections_image/compressedDepth/parameter_descriptions__
I don't know what this does please add details and submit a pull request
#####__/tag_detections_image/compressedDepth/parameter_updates__
I don't know what this does please add details and submit a pull request
#####__/tag_detections_image/theora__
I don't know what this does please add details and submit a pull request
#####__/tag_detections_image/theora/parameter_descriptions__
I don't know what this does please add details and submit a pull request
#####__/tag_detections_image/theora/parameter_updates__
I don't know what this does please add details and submit a pull request
#####__/tag_detections_pose__
This is an output array of April tag poses
#####__/tf__
I don't know what this does please add details and submit a pull request
#####__/zed/rgb/camera_info__
Remap this to the camera info topic for your respective camera
#####__/zed/rgb/image_raw_color/compressed__
Remap this to the image output topic for you respective camera

##Tested With
- 16h5
- 36h11
