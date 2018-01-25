# Instructions to modify visonic contact sensor to wired smoke detector

If your house have wired smoke detector, you can modify the visonic sensor into a smoke detector. 
  - depend on the brand, purchase the smoke alarm relay corresponding to your brand
  
  <p align="center">
    <img src = "https://github.com/pakmanwg/smartthings-visonic-sensor/blob/master/rm4-relay.jpg" width=300 hspace=10/>
  </p>  
  
  - modify the visonic similar to what we did with water/leak sensor
  - usually the relay should have 6 wires, see the diagram below.
  
  
  <p align="center">
    <img src = "https://github.com/pakmanwg/smartthings-visonic-sensor/blob/master/firex-501-diagram2-large.jpg" width=600 hspace=10/>
  </p>  
  
   - what we want to do is to connect or solder the two wires coming out the sensor to the common and normally open terminal of the relay. Leave the normally closed terminal open. And connect the hot, neutral and interconnect terminals to the alarm. The device handler is code for the normally open terminal and common connection. If you want to use the normally closed terminal instead, you will need to change the logic in the device handler.
   - once you wire up everything, you can pair the sensor with smartthings. After pairing, go to settings menu for the device and select smoke detector in sensor function, then you are done.
