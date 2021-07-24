<b/>**Release Notes**</b>

This branch is only for GM Chevolet Bolt EV based on latest released version from comma ai

# Features

  - Add target speed setting by long press (thanks to neokii님)
  - New panda code supports comma/custom made harness for black panda
  - Update panda and DBC for Comma Pedal
  - Toggle Switch for enabling prebuilt (thanks to 양민님)
  - Add Battery Charging Logic (thanks to 양민님)
  - Add UI Recording (thanks to neokii님)
  - Add auto shut down from dragonpilot
  - Toggle Switch for selection lateral control function with LQR or INDI
  - <b>Support Comma pedal for longitudinal control but this does not guarantee fully to provide the Stop & Go </b>
    1) Only Lateral control by OP
       - Engage : main switch on
       - Disengage : Driver braking or main switch off
    2) Only Longitudinal control by OP (comma pedal shall be installed)
       - Engage : accel(resume) button but main switch must be kept off
       - Speed control : accel or decel button (short : +/- 1 km/h, long : +/- 10 km/h)
       - Disengage : Driver braking or cancel button
       - If main switch is on, only lateral control will be enabled
       - If you operate the regen paddle, the target speed will be decreased depending on vehicle speed
    3) Both Lateral and Longitudinal control by OP (comma pedal shall be installed)
       - Engage : set(decel) button but main switch must be kept off
       - Speed control : accel or decel button (short : +/- 1 km/h, long : +/- 10 km/h)
       - Disengage : Driver braking or cancel button
       - If main switch is on, only lateral control will be enabled
       - If you operate the regen paddle, the target speed will be decreased depending on vehicle speed
