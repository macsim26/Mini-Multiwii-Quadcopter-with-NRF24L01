# UPDATED 20 Dec 2024, Mini-Multiwii-Quadcopter-with-NRF24L01
This is the final arduno project of mini quadcopter (QUADX) using Multiwii 2.3 firmware with NRF24L01 as a single board. Enjoy!

<h2>YOU DO NOT NEED TO CHANGE ANYTHING THE CODE</h2>
<p>Please leave a comment in <b><a href="https://www.youtube.com/@ArduJimmy">Ardujimmy Youtube Channel</a></b> if you have a question or have a problem with it.</p>

<p>
HOW TO MAKE DRONE with NRF24: <a href="https://www.youtube.com/watch?v=wbK7oOLr6PM" target="_blank">Video Here</a><br />
HOW TO MAKE DRONE TRANSMITTER with NRF24: <a href="https://youtu.be/4M9A6sWJjzM" target="_blank">Video Here</a>
</p>

<h3>REQUIREMENTS</h3>
<p>Only works for LADYBIRD Board Types ONLY! (328p 5v Version: Arduino Nano, Arduino Pro mini, Arduino UNO)
Please see our documentation in https://www.youtube.com/@ardujimmy</p>
<p>We also provide the schematic diagram and all needed to build a brushed mini quadcopter.</p>

<h3>RX SCHEMATIC DIAGRAM</h3>

<img src="https://github.com/ArduJimmy/Mini-Multiwii-Quadcopter-with-NRF24L01/blob/main/Wiring.jpg" alt="nrf24l01 multiwii quadcopter" title="Arduino Quadcopter with Multiwii 2.3 and NRF24L01"/>

<h3>TX SCHEMATIC DIAGRAM</h3>

<img src="https://github.com/ArduJimmy/Mini-Multiwii-Quadcopter-with-NRF24L01/blob/main/Schematic-Transmitter.jpg" alt="TX Transmitter for nrf24l01 multiwii quadcopter" title="Arduino Quadcopter with Multiwii 2.3 and NRF24L01"/>

<p>By using this NRF_Multiwii version you agree at your own risk!!!</p>

<h3>MOTORS PIN CONFIGURATION </h3>
<ul style="font-size:17px;">
  
<li>Motors pin: 9,10,6,3</li>

<p><b>Note:</b><br />
Front Right: 10<br />
Front Left: 3<br />
Rear Right: 9<br />
Rear Left: 6</p>

<li><b>CE: 7</b></li>
<li><b>CSN: 5</b></li>
<li><b>SCK: 13</b></li>
<li><b>MOSI: 11</b></li>
<li><b>MISO: 12</b></li>
</ul>

<h3>TRANSMITTER PIN CONFIGURATION </h3>
<ul>
<li>CE: 4</li>
<li>CSN: 3</li>
<li>SCK: 13</li>
<li>MOSI: 11</li>
<li>MISO: 12</li>
<li>Throttle: A1</li>
<li>Yaw: A0</li>
<li>Pitch: A3</li>
<li>Roll: A2</li>
<li>AUX1: 5</li>
<li>AUX2: 6</li>  
</ul>

<h3>ADDITIONAL INFORMATION</h3>
<p>If you use specific joystick, then wiring must be like this follow:</p>

<img src="https://github.com/ArduJimmy/Mini-Multiwii-Quadcopter-with-NRF24L01/blob/main/Specific%20Joystick%20Wiring.jpg" alt="Specific Joystick Wiring" title="Specific Joystick Wiring"/>

<p>All Information above based on common transmitter configuration. For more info, see this pic below.</p>

<img src="https://github.com/ArduJimmy/Mini-Multiwii-Quadcopter-with-NRF24L01/blob/main/common_Config_transmitter.jpg" alt="Common Transmitter Model" title="Common Transmitter Model"/>



WARNING !!!!!
<p><b>ONLY arduino PROMINI 328p 5v FOR MINI QUADX with MOSFET will work!</b></p>

<p>Please subscribe and share our channel for more videos: https://www.youtube.com/@ardujimmy</p>









