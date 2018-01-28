# Instructions to modify visonic contact sensor to wired smoke detector

If your house have wired smoke detector, you can modify the visonic sensor into a smoke detector. 
  - purchase the smoke alarm relay compatible with your smoke alarm
  
  <p align="center">
    <img src = "https://github.com/pakmanwg/smartthings-visonic-sensor/blob/master/Relay.jpg" width=300 hspace=10/>
  </p>  
  
  - modify the visonic similar to what we did with water/leak sensor
  - usually the relay should have 6 wires, see the diagram below.
  
  
  <p align="center">
    <img src = "https://github.com/pakmanwg/smartthings-visonic-sensor/blob/master/Relay1.jpg" width=600 hspace=10/>
  </p>  
  
   - what we want to do is to connect or solder the two wires coming out of the sensor to the common and normally open terminal of the relay. Leave the normally closed terminal open. And connect the hot, neutral and interconnect terminals to the alarm. The device handler is coded for the normally open terminal and common connection. If you want to use the normally closed terminal instead, you can change the logic in the device handler.
   
   - I put the relay and the sensor inside one of the alarm as shown, it is a little bit tight but ok.
   
   <p align="center">
     <img src = "https://github.com/pakmanwg/smartthings-visonic-sensor/blob/master/IMG_2149.JPG" width=300 hspace=10/>
   </p> 
   
   - once you wire up everything, you can pair the sensor with smartthings. After pairing, go to settings menu for the device and select smoke detector in sensor function, then you are done.
