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
