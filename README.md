# vis_track
Intelligent Visual Tracking

Package List:
usb_cam
basler_camera
swiftnav_ros
  
    
    Instructions:
    1. Clone repo to workspace
    2. Use wstool to update package list.
    3. (If you get a error with usb_cam not being identical to remote, go with the (d)elete and update option, then pull repo again to replace deleted file.)
    4. For the swiftnav_ros package, we need to install the libsbp library separately. FOllow instructions 3.1 and 3.2 to do so from the following link. http://wiki.ros.org/swiftnav_ros
    
    
   Use usb_cam-test2.launch to un the Insta360 Air
    
   Use the basler_camera_uc155.launch to run the Basler ac1920-155uc Camera.
