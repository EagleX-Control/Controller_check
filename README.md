
<p style="text-align: center;">
  <img src="_assets/logo_blanco.png" alt="logo" style="width:350px;"/>
  </p>

# joy_tester
Created by [@FerMatute](https://github.com/FerMatute)

## <span style="color: rgb(26, 99, 169);">**Purpose**</span>
This repository was created to check if your controller is being detected on your Computer/Raspberry/Jetson. Below are instructions on how to run it and try it.

## <span style="color: rgb(26, 99, 169);">**Instructions**</span>
1. Clone this repository on your computer
   ```sh
   git clone https://github.com/EagleX-Control/Controller_check/

2. Source your terminal
  ```sh
   source install/setup.bash
  ```

3. Build your package
```sh
   colcon build --packages-select joy_tester
  ```

4. Run the package
```sh
   ros2 run joy_tester test_joy
```
   
## <span style="color: rgb(26, 99, 169);">**Tutorial**</span>
### Check our quick tutorial [here](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
