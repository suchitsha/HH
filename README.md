Notes for vision processing for the robot





----------------------------------
Video streaming node and its usage:

source code and documentation:
http://wiki.ros.org/video_stream_opencv


commands:
Only publishes image on a ros topic:

    roslaunch video_stream_opencv camera.launch

verify using:
    rostopic list
    rostopic echo <topic_name>    
        
To view image published on any topic of ros:
    rosrun image_view image_view image:=<topic_name>
 example
    rosrun image_view image_view image:=/camera/image_raw


    
To publish and show image in a opencv window:

    roslaunch video_stream_opencv webcam.launch


-----------------------------------------

