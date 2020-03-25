# WebServer_DepthCamera
Depth camera and mobile control through customized ROS webserver 

STEP1:python -m SimpleHTTPServer 7000
STEP2:roslaunch rosbridge_server rosbridge_websocket.launch
STEP3:rosrun web_video_server web_video_server _port:=11315
STEP4:webvideo_address
      https://i-0123456789012345.robotigniteacademy.com/cameras/
