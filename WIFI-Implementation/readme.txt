The testProject zip file is the code on the ESP32 from the receiving end. Make sure first to get the MAC address of the device by running the following script
//////////////////////////////////////////////////
#include "WiFi.h"
 
void setup(){
  Serial.begin(115200);
  WiFi.mode(WIFI_MODE_STA);
  Serial.println(WiFi.macAddress());
}
 
void loop(){

}


////////////////////////////////////////////////////////


Save the MAC address and place it in the transmitter script which is in the zebra finch bird zip file
