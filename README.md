# Turtlebot3 with SLAM approach

## Steps of Use Turtlebot3 with SLAM approach to create and save a map:


- **Step-1:** PC Setup steps

   1.1 Install Oracle VM VirtualBox from [this link](https://www.virtualbox.org/wiki/Downloads).
            
     ![image](https://user-images.githubusercontent.com/85820553/128093150-99c207d5-3751-4e01-809d-2661c634f070.png)



   1.2 Install Ubuntu 18.04 from [this link](https://releases.ubuntu.com/18.04).
            
   Follow [this video](https://youtu.be/QbmRXJJKsvs) steps to install Ubuntu 18.04 on Oracle VM VirtualBox
   
   
   
   ![image](https://user-images.githubusercontent.com/85820553/128093284-1557b366-e695-40c7-9f92-3767148c40b7.png)
   
   
   
    1.3 Install Install ROS 1 on Remote PC by executing the following next commands:
            
            
   <!-->
         sudo apt install python-rosdep
![image](https://user-images.githubusercontent.com/85820553/128537254-a949b4ab-dbae-46e5-ba6c-6815afd4c8ba.png)



   <!-->
         sudo apt upgrade
         
![image](https://user-images.githubusercontent.com/85820553/128538608-0dd3e21e-1229-4871-961e-e5685343561e.png)


![image](https://user-images.githubusercontent.com/85820553/128538662-d740ea7f-f135-478e-b109-2b061c37d086.png)


![image](https://user-images.githubusercontent.com/85820553/128538700-8667425a-596e-426d-b84c-88fe2339a059.png)



   <!-->
         wget https://raw.githubusercontent.com/ROBOTIS-GIT/robotis_tools/master/install_ros_melodic.sh


![image](https://user-images.githubusercontent.com/85820553/128538814-306c6798-8517-4791-bcb1-43472bc87ffb.png)



   <!-->
         chmod 755 ./install_ros_melodic.sh 
         
         
![image](https://user-images.githubusercontent.com/85820553/128539078-858410b6-8943-4743-be09-4eb3c4057fdb.png)


   <!-->
         bash ./install_ros_melodic.sh


![image](https://user-images.githubusercontent.com/85820553/128544031-2a6df814-54ae-4784-887f-2ac7c88fe05f.png)

sudo apt-get install ros-melodic-joy ros-melodic-teleop-twist-joy \
![image](https://user-images.githubusercontent.com/85820553/128544089-625c3c10-300c-467f-88c6-b77f4e591d5a.png)


![image](https://user-images.githubusercontent.com/85820553/128544108-4c9dd8a9-1b61-46a0-8a58-d7090327e771.png)



  1.4 Install Dependent ROS 1 Packages by executing the following next commands:


   <!-->
         bash ./install_ros_melodic.sh
