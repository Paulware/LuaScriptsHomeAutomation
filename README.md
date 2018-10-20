<h1>Home Automation Lua</h1>
This information describes how to configure a wemos sensor with .lua files.<br>
Files:
<ul>
  <li>init.lua: loaded on all wemos devices it will log on to the home network</li>
  <li>sensor.lua: one for each type of wemos device.  It will perform the specific behavior for the sensor</li>
</ul>
Directories:
<ul>
<li>bin
    <ul>
    <li>dContains historical record of .bin files used </li>
    </ul>
</li>
<li>Tools
   <ul>
     <li>ESP8266Flasher.exe: Used to load .bin (os) file on wemos chips</li>
     <li>LuaLoader: Used to load .lua files on wemos chips</li>
   </ul>
<li>dht11: Contains sensor.lua for temperature/humidity sensor</li>
<li>relay: Contains sensor.lua for relay sensor that can also set individual gpio pins</li>
<li>security: Contains sensor.lua for security wire (0-closed, 1-open/tripped)</li>
<li>water: Contains sensor.lua for water temperature sensor</li>
</ul>
