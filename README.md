# esp8266-timebased-appliance
this is a an esp8266 project which turn on and off an appliance depending on the time it fetches using the ntp server  the code can also be updated over the air and soon i will also add the soft coding of wifi credentials feature 
so the esp connects to wifi and when connected it asks the ntp server for the current time in india (ie +5:30 hours ahead of international time) then it checks if the time matches our set time if yes then it will turn on the appliance otherwise off

