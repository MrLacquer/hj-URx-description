# urx_description 
for backup repository


### update
- 2019.06.05 1st backup
    - common_sensors original [common_sensors](https://github.com/JenniferBuehler/common-sensors.git)

    - gripper_ur3: my ur3 and d435 urdf model:
    ```
    $ roslaunch gripper_ur3 ur3d435.launch
    ```

### update
- 2019.06.20 2nd backup
    - update the ur3_hand_d435.xacro:
        - which is include the hj Hand.
        - change the shoulder pan joint limit, which is pi/2 → pi
    
    ```
    $ roslaunch gripper_ur3 ur3_hand.launch
    ```
    - how to collision check?
        - take a look ur3_d435.launch file, and editing:
        ```
        $ roslaunch ur3_hj3_moveit ur3_d435.launch
        ```

### update
- 2019.07.15 3nd backup
    - update the hj_hand.urdf.xacro:
        - write the full hj_hand urdf        
    
    ```
    $ roslaunch gripper_ur3 hj_hand_display.launch

    check-up the collisions:
    $ roslaunch gripper_ur3 gazebo_collision_check.launch
    ```

### update
- 2019.08.01 4th backup
    - update the hj_hand.urdf.xacro:
        - editing and updata        
        