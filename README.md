Simple work time management (tecnica del pomodoro) script for i3blocks,
To have sound notifications for break and resume add "break.ogg" and 
"towork.ogg" to script directory, install "sox" package for sound playback. 
PLEASE CHANGE line 9 of this script and input path to script and sounds directory.
After first start left click new box to start timer and create time file.
Left click to reset, right click to stop.
Add to i3blocks config:

[timer]  
command=$SCRIPT_DIR/timer  
label=  
interval=60  
DEFAULT_WORKTIME=45  
DEFAULT_BREAKTIME=10  
