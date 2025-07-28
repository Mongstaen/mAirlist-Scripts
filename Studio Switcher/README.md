# Studio Switcher mAirlist

Script to move broadcasting from one computer to another in mAirlist

! TODO, write readme. Current notes to be considered

1. Create node.txt in C:/Program Files (x86)/mAirlist containing node name.
   Please use uppercase letters, ie: STUDIO1 or SERVER
   This script is only aware of STUDIO1 or SERVER.. Other studios may be implemented

2. Create extended button in your main studio.
   On Activate: Execute Command ACTIVATE_TOTH_BUTTON
   On Dectivate: Execute Command DEACTIVATE_TOTH_BUTTON

3. For this script to run as intended, your mAirlist must be set up to start in OFF AIR mode, and the ON/OFF Air to change based on Encoder Connect/Disconnect status.
   You can do this in Control Panel > Options > Untick "Start in ON AIR mode", and Control Panel > Encoder > Options > tick "Connect/disconnect encoder when switching ON AIR mode", and "Switch ON AIR mode when connecting/disconnecting encoder".

If needed.. if HTTPPost is not working
// ShellExecuteHidden('curl', 'http://username:password@127.0.0.1:9300/execute?command='+Command);

## Current Status

This script is currently running successfully in two radio stations, providing a seamless transition between studios. The basic functionality works well, allowing broadcasters to switch between STUDIO1 and SERVER configurations.

## Future Improvements

While the script is functional, there are several potential improvements that could be made:

1. More flexible studio naming - currently limited to STUDIO1 and SERVER
2. Better error handling and user feedback
3. Configuration through a settings file rather than hardcoded values
4. Logging of switch operations for troubleshooting
5. Web interface for status monitoring

If you're using this script and would like additional features or have suggestions for improvement, please open an issue or submit a pull request.
