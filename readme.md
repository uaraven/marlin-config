# Marlin Configuration Files for Ender 5

## Ender5/SKR-MiniE3-V2.0

Configuration files for [SKR Mini E3 V2.0](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3)

Copy files over to `firmware/V2.0/Marlin/2.0.x-SKR-mini-E3-V2.0` folder.

Things to change before compiling:

 - Z Probe offsets

 - PID coefficients for hot end and the bed.  
   Defaults for Ender 5 are:

        #define DEFAULT_Kp 21.73
        #define DEFAULT_Ki 1.54
        #define DEFAULT_Kd 76.55

        #define DEFAULT_bedKp 50.71
        #define DEFAULT_bedKi 9.88
        #define DEFAULT_bedKd 173.43

