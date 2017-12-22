
![logo](https://avatars0.githubusercontent.com/u/7002937?v=3&s=200) 
# [PulseSensor.com](https://pulsesensor.com) Playground
```
This Playground is a collection of code of the most popular uses of PulseSensor and Arduino.  

- The playgroud includes a number of projects, with the code already written-out and commented! 🤘 
- Use this code to get started quickly, or do advanced stuff. 👍
- Switch between projects right in the Arduino IDE (software). 💻
- Contritube your projects code back to the GitHub hive-mind. 🐝
```
---
## Installing the PulseSensor Playground
 <details><summary><code>Install the Playground in Arduino to get quick and easy access to popular projects.</code> </code> 🤓</summary>

1.  On the main page of this repository, on the right side is a green button. Click on the green `Clone or Download ZIP` button and then select `Download ZIP`. Save the `.zip` file somewhere on your computer.

  <img src="https://cdn.shopify.com/s/files/1/0100/6632/files/Download_Playground_ZIP_1024x1024.png?v=1510864702" width="400">

2. Open up the Arduino IDE.

	(**NOTE** If you do not have Arduino, you can download it [here](https://www.arduino.cc/en/Main/Software))

3. Select `Sketch > Include Library > Add .ZIP Library...`

	<img src="https://cdn.shopify.com/s/files/1/0100/6632/files/Add_ZIP_LIbrary_1024x1024.png?v=1510865023" width="400">

5. Navigate to the location where you downloded the `.zip` file previously and select it to install this library. (**NOTE** you may need to restart Arduino after this step)
6. Hurray!  Once this library is installed you will see our examples in Arduino's dropdown! To select an example sketch, go to 
	`File > Examples > PulseSensor Playground`

	<img src="https://github.com/yury-g/PulseSensorPlayground/blob/master/menupulldown.png?raw=true2" width="400">
	

  More Info On Libraries 👉    [https://www.arduino.cc/en/Guide/Libraries](https://www.arduino.cc/en/Guide/Libraries).

  
</div>
  </details>

---
## PulseSensor Playground Tools

We put together a [HANDY GUIDE](https://github.com/biomurph/PulseSensorPlayground/blob/master/resources/PulseSenaor%20Playground%20Tools.md) to the function-ality of our library. Check it out if you want to dive into the inner workings!
 
---
## Playground Project Descriptions: 


### Getting Started Project:  
  Plug your sensor in for the first time!  Blink an LED with your pulse, live. 
  
- [**Project Page**](https://pulsesensor.com/pages/code-and-guide)
  
  <img src="https://cdn.shopify.com/s/files/1/0100/6632/files/PulseSensor_GettingStarted_bb_1024x1024.png?v=1511986616" width="400">
---

### Calculate BPM:  
  Focus-in on the code that calculates a user's HeartRate Beats Per Minute, "BPM".    
  See the best practises to get the best signal.  
  
- [**Project Page**](https://pulsesensor.com/pages/getting-advanced)
  
  <img src="https://cdn.shopify.com/s/files/1/0100/6632/files/PulseSensor_GettingAdvanced_bb_1024x1024.png?v=1511986194" width="400">
---
  
### Make A Sound to a live Heartbeat:  
  Transform the heartbeat into a live "beep" with a speaker.  
   
- [**Project Page**](https://pulsesensor.com/pages/pulse-sensor-speaker-tutorial)
  
  <img src="https://cdn.shopify.com/s/files/1/0100/6632/files/PulseSensor_Speaker_bb_61a0333f-e868-4123-961d-7456a31fa928_1024x1024.png?v=1510863829" width="400">
---  
  
### Move a Motor to a live Heartbeat:  
  Make a servo motor pulse to your live heartbeat.  
  
- [**Project Page**](https://pulsesensor.com/pages/pulse-sensor-servo-tutorial)

  <img src="https://cdn.shopify.com/s/files/1/0100/6632/files/PulseSensor_Servo_bb_87fce9fc-dc47-4208-b708-a7edb6df58a2_1024x1024.png?v=1510863990" width="400">
 ---

 
### Processing Visualizer:
  
  Get detailed visulization of the heart's pulse and behavior. Send the PulseSensor data into Processing! 
  
- [**Project Page**](https://pulsesensor.com/pages/getting-advanced)
  
  <img src="https://cdn.shopify.com/s/files/1/0100/6632/files/ScreenShot_1024x1024.png?v=1491857113" width="400">
---  

### TroubleShoot Your Signal:  
  If you're having trouble seeing a heartbeat, make sure that you are using 'Goldilocks' pressure on the Pulse Sensor: Not too hard, not too soft. Squeezing the Pulse Sensor too hard against your skin will make the heartbeat go away, and not enough pressure will cause too much noise to creep in!
  
If you are seeing way too many Beats Per Minute, or you are getting lots of noise, try adjusting the Threshold setting. The Threshold variable tells Arduino when to find a pulse that is legit. Adjust this number (noted below with arrows) up for less sensitivity and down for more sensitivity. In the [**StarterProject**](https://pulsesensor.com/pages/code-and-guide) you can find the Threshold variable as shown in the pic below:
  
  ![StarterThreshold](https://github.com/biomurph/PulseSensorPlayground/blob/master/Images/screenshot-threshold-arrows.png)
  
In the other examples, the `THRESHOLD` is defined at the top of the code.

---
## Connecting the Harware 😎
1. Prepare the sensor, with the Kit parts.

<img src="https://cdn.shopify.com/s/files/1/0100/6632/products/PulseSensorKit-Labeled-Contents_1_2048x2048.jpg?v=1348506345" width="400"><img src="https://github.com/WorldFamousElectronics/PulseSensorStarterProject/raw/master/Arduino-LEDonPin13-PulseSensor-Pic.jpg" width="400">

2. See the recommended wiring for your specific project

<img src="https://github.com/WorldFamousElectronics/PulseSensorStarterProject/blob/master/connections.png" width="400">    

---
## Give and Get Feedback
The [Issues Tab](https://github.com/WorldFamousElectronics/PulseSensorStarterProject/issues
) will get you the quickest answers to common techinal questions. 


---
#####  Legal:  PulseSensor.com® World Famous Electronics llc. in Brooklyn, NY. USA
Made Something Awesome With the PulseSensor Code?   Send Us Some PayPal Love. ♥︎  
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg?style=plastic)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KE4DZA5E9AJQ4) 


