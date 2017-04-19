# camera_slider
Arduino sketch for a camera slider based on a NEMA17 stepper motor, ardiuno Nano and A4988 stepper driver.

This sketch is based on Great Scott's camera slider circut, but I've modified it for use with buttons as the control input rather then a rotery encoder. See Great Scott's origional camera slider and ardiuno sketch here: http://www.instructables.com/id/Make-Your-Own-Motorized-Camera-Slider/

TODO: Post link to cameras slider video

# Circut diagram
https://easyeda.com/andii/MotorizedCameraSlider_copy-0b79a2839ec5450099360a282db9948a

# Setup
First current limit your stepper driver http://howtomechatronics.com/tutorials/arduino/how-to-control-stepper-motor-with-a4988-driver-and-arduino/

Download and install the new-liquidcrystal library https://bitbucket.org/fmalpartida/new-liquidcrystal/wiki/Home 

You need to find the LCDs i2c address with a i2c scanner like http://playground.arduino.cc/Main/I2cScanner Once found add it to the 
  define I2C_ADDR <LCDs ADDRESS>
  
