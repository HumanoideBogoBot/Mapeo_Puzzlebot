# Mapeo_Puzzlebot

Aqui realizamos el mapeo de un laboratorio de Gazebo con el uso de un LIDAR.<br>
- Los comandos para poder correr la simulacion son:
- Abrimos el gazebo del carro en el laboratorio:
```
roslaunch puzzlebot_gazebo puzzlebot_room.launch 
```
- Abrimos RVIZ y luego by topic agregamos el topico /map
```
rviz
```
- Iniciamos el codigo seguidor de pared
```
rosrun puzzlebot_nav2d right_hand_rule_template.py 
```

