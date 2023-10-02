# BeagleBone_Black_PRUS
Repository for CCS and Eclipse Beaglebone Black PRU0 amd PRU1 application and support for velocity control of a DC bursh motor equiped with a quadrature encoder.

Zip file "motor_control_msg.tar.xz" Is a Linux app designed to run on the BeagleBone. This app communicates through the "/dev/rpmsg_pru31" messaging interface using shared memory between PRU0 and PRU1. It facilitates the loading of the "MotorControlPru0.out" and "MotorControlPru1.out" app running on the BeagleBone Black using the /dev/remoteproc interface. The PRU apps are contained within the "pru0_motor_control.tar.xz" "pru0_pru1_motor_control.tar.xz"file which is built using Code Composer Studio.

The Linux app was built using Eclipse and Cross Compiled on a Desktop PC using debian 11 uploaded and debugged on the BeagleBone.
