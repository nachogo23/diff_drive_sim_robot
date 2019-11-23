# diff_drive_sim_robot

Repositori clonat de: https://gitlab.com/beta-robots/diff_drive_sim_robot

En aquest repositori trobem els elements necessaris per simular un robot movil fent servir ROS i Gazebo. 
Es troba organitzat en 3 paquetes diferents:

ddsr_description: Inclou la descripció del robot en urdf i si executem el launch obtindrem una represntació del model fent servir rviz.

ddsr_gazebo: Afegeix un mon virtual amb Gazebo on poder simular el model previament descrit.

ddsr_control: L'arxiu .launch d'aqquest paquet inclou el paquet mouse_teleop que permet controlar el robot amb el mouse pel mon virtual creat a Gazebo.






