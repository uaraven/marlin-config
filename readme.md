# Marlin Configuration Files for Ender 5

## Ender5/SKR-MiniE3-V2.0

Configuration files for [SKR Mini E3 V2.0](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3)

## What's in there?

Settings for Ender 5. Following options are enabled, change them in accordance with you configuration:

- BL Touch is enabled and configured to be used as a Z endstop.
- PID coefficients for the hot end and the bed are configured **for my Ender 5** - uncomment the ones marked as SAFE and delete current.
  In any way I recommend running PID autotune to find the values for your printer.
- Filament runout sensor is enabled 
- Extruder steps/mm is set to 135 instead of usual 93 - change value in DEFAULT_AXIS_STEPS_PER_UNIT
- Linear advance is enabled (but K value is not calibrated)

## How to use

Copy files over to `firmware/V2.0/Marlin/2.0.x-SKR-mini-E3-V2.0` folder.

**Things to change before compiling**:

 - Z Probe offsets

 - PID coefficients for hot end and the bed.  
   Defaults for Ender 5 are:

        #define DEFAULT_Kp 21.73
        #define DEFAULT_Ki 1.54
        #define DEFAULT_Kd 76.55

        #define DEFAULT_bedKp 50.71
        #define DEFAULT_bedKi 9.88
        #define DEFAULT_bedKd 173.43

