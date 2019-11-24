# diff_drive_sim_robot

Repositori clonat de: https://gitlab.com/beta-robots/diff_drive_sim_robot

En aquest repositori trobem els elements necessaris per simular un robot movil fent servir ROS i Gazebo.
Es troba organitzat en 3 paquetes diferents:

ddsr_description: Inclou la descripció del robot en .urdf i si executem el .launch obtindrem una represntació del model fent servir rviz. (roslaunch ddsr_description description.launch)


ddsr_gazebo: Aquest paquet afegeix a la representació gràfica, un món virtual on simular el model amb Gazebo. (roslaunch ddsr_gazebo gazebo.launch)

ddsr_control: L'arxiu .launch d'aquest paquet inclou el paquet "mouse_teleop" que permet controlar el robot amb el mouse pel món virtual creat a Gazebo. (roslaunch ddsr_control control.launch)
