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