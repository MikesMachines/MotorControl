# MotorControl
<P>
<img src="https://github.com/MikesMachines/MotorControl/blob/main/media/BlynkScreens/PumpWithMarkup.JPG" align="right" alt="App Screenshot" height="400">
<p>
    I was building a lot of machines and spending too much time trying to build physical controls for each. Now everything is just a drag and drop app based on a standard design. I can plug the outs of the control box into any of the machines - even hacking commercial machines I want to run by app. 
  <p>
    The control box contains up to four 400w / 15A MOSFET boards. Each mosfet runs independently for driving brushed motors, solenoids, heaters, etc and typicaly have a DC barrel jack out for the load. An ESP32 provides pins for stepper control, sensors, like temp or pressure sensor, displays, and also includes WIFI and BT. Blync allows no-code app design with drag and drop widgets so anyone can customize it. Virtual pins from Blync tie the app and hardware together.
<P>
  

<P>
This goes into a 3d printed enclosure based off the Ultimate Box Creator on Thingverse (https://www.thingiverse.com/thing:1264391) I've added parametric options specific to this design. Just simple things - optional OLED display, number of mosfet boards, power switch in the front or back, use DC barrel jacks or aviation connector as outputs.
<P>
Not including sensors, the parts are under $30.  
<P>
The MOSFET boards are 10 for $14 - https://www.amazon.com/gp/product/B07XJSRY6B
I've been buying the S2 mini and S3 versions to get full USB support (some of them end up as MIDI controllers) but the old version works just fine. The S2 mini is great for space constrained installations, but doesn't have bluetooth. 

The ESP32 is available for $6 with expansion that has a 12v barrel input for power in an UNO footprint:
https://www.aliexpress.us/item/3256804150863583

The MOSFET boards have pass thought positives and horrible screw terminals, so I hook it up like this (don't power VIN if USB is connected):
![ESP32_Controller](https://user-images.githubusercontent.com/105053125/224486164-d9a4f0c3-a946-4ceb-97e2-df432a89146d.JPG)

<p>
  <hr>
  <P>

    Boxes with DC barrel and aviation outs:
    <P>
<table>
  <tr>
    <th><img src="https://github.com/MikesMachines/MotorControl/blob/main/media/3chanController.jpg" alt="3chan controller" ></th>
    <th><img src="https://github.com/MikesMachines/MotorControl/blob/main/media/3chanController_Back.jpg" alt="3chan controller back" ></th>
    <th colspan="2"><img src="https://github.com/MikesMachines/MotorControl/blob/main/media/4chanControllerBackPanel.jpg" alt="4chan back panel" ></th>
  </tr> 

</table>
  
<p>
  <hr>
  <P>
    Some screen shots:
    <P>
  <table padding = 15 border = 5 align = center>
  <tr >
    <td ><img src="https://github.com/MikesMachines/MotorControl/blob/main/media/BlynkScreens/MilkerCombo.JPG"  alt="App Screenshot"></td>
    <td border = 15 ><img src="https://github.com/MikesMachines/MotorControl/blob/main/media/BlynkScreens/PumpOralSim.PNG"  alt="App Screenshot" > </td>
    <td border = 5 ><img src="https://github.com/MikesMachines/MotorControl/blob/main/media/BlynkScreens/Templates.JPG"  alt="App Screenshot" >  </td>
  </tr>
</table>
