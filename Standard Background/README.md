## Readme for StandardBackground.mls

1. Set up mAirlist to run StandardBackground.mls as background script. <br/>
![Alt text](images/ControlPanel.png)

2. Set up event in Mairlist triggering TOTH_CHECK<br/>
![Alt text](images/TOTHCheckEvent.png)

3. Add buttons in both of your studios for the script to trigger. <br/>
3-1. GO LIVE AT TOTH/Change at TOTH<br/>
Please add the below to your "main studio"<br/>
![Alt text](images/TOTHChanger.png)<br/>
![Alt text](images/TOTHChangerActionList.png)<br/>
For the External Commands via REST:<br/>
When activated: Send "GO_OFFAIR TRUE" to pc going off air<br/>
When deactivated: Send "VIRTUALSTUDIO_TOTH PRESS"<br/>

3-1. Add Button at your "virtual studio" or secondary studio. <br/>
![Alt text](images/VirtGoLive.png)
![Alt text](images/VirtGoLiveList.png)