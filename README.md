# gladys-yamaha
Gladys module to control Yamaha Network Receivers.
Requires Gladys > 3.6

# Installation
1. Install the module in Gladys, through modules pannel.
2. Go to "Parameters" => "Parameters" => "Parameters" in the dashboard, and create parameters:
 - YAMAHA_IGNORED_ZONES which will contain the zones, you want to ignore (ex: Zone_2).
 - YAMAHA_IGNORED_FEATURES which will contain the features, you want to ignore (ex: iPod,Bluetooth,UAW,Napster,iPod_USB).
 - YAMAHA_IGNORED_INPUTS which will contain the inputs, you want to ignore (ex: PHONO,HDMI_2,AV_1,AV_2,V_AUX,AUDIO_1,DOCK).
3. Reboot Gladys when it's done.
4. Go to "Modules" => "Installed modules", and click on the configure button (this process takes a few secondes to complete).
5. Your device(s) should be available(s) in devices page, you can update the room of device(s). If they are not, feel free to repeat step 2.
