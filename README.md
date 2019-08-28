#youtube video showing on of the features of the board to switch modes https://youtu.be/DYlisqvXOyg

# Pimoroni Enviro+ Sensor Board 
<p class="body-copy mk-paragraph" ><img src="https://cdn.shopify.com/s/files/1/0174/1800/products/enviro-plus-shop-1_1024x1024.progressive.jpg?v=1565439541"
   class="attempt-right print-hide" style="max-width:800px" /> 
   
 




<p class="body-copy mk-paragraph" ><img src="https://cdn.shopify.com/s/files/1/0174/1800/products/Enviro-Plus-pHAT-on-white-2_256x256.progressive.jpg?v=1565439541"
   class="attempt-right print-hide" style="max-width:430px" /> 
<p class="body-copy mk-paragraph" ><img src="https://cdn.shopify.com/s/files/1/0174/1800/products/Enviro-Plus-pHAT-on-white-3_256x256.progressive.jpg?v=1565439541"
   class="attempt-right print-hide" style="max-width:430px" />
<p class="body-copy mk-paragraph" ><img src="https://cdn.shopify.com/s/files/1/0174/1800/products/Enviro_Plus_pHAT_2_of_4_256x256.progressive.JPG?v=1565439541"
   class="attempt-right print-hide" style="max-width:430px" />


</div>


    
<p>Designed for environmental monitoring, Enviro+ lets you measure air quality (pollutant gases and particulates*), temperature, pressure, humidity, light, and noise level. When combined with a <a href="/products/pms5003-particulate-matter-sensor-with-cable" target="_blank" rel="noopener noreferrer">particulate matter sensor</a>*, it's great for monitoring air quality just outside your house (more information below), or without the particulate sensor you can use it to monitor indoor conditions.</p>
<p>Enviro+ is an affordable alternative to environmental monitoring stations that can cost tens of thousands of pounds and, best of all, it's small and hackable and lets you contribute your data to citizen science efforts to monitor air quality via projects like <a href="https://united-kingdom.maps.luftdaten.info" target="_blank" rel="noopener noreferrer">Luftdaten</a>.</p>
<h2>Features</h2>
<ul>
<li>BME280 temperature, pressure, humidity sensor (<a href="https://ae-bst.resource.bosch.com/media/_tech/media/datasheets/BST-BME280-DS002.pdf" target="_blank" rel="noopener noreferrer">datasheet</a>)</li>
<li>LTR-559 light and proximity sensor (<a href="http://optoelectronics.liteon.com/upload/download/ds86-2013-0003/ltr-559als-01_ds_v1.pdf" target="_blank" rel="noopener noreferrer">datasheet</a>)</li>
<li>MICS6814 analog gas sensor (<a href="https://www.sgxsensortech.com/content/uploads/2015/02/1143_Datasheet-MiCS-6814-rev-8.pdf" target="_blank" rel="noopener noreferrer">datasheet</a>)</li>
<li>ADS1015 analog to digital converter (ADC) (<a href="http://www.ti.com/lit/ds/symlink/ads1015.pdf" target="_blank" rel="noopener noreferrer">datasheet</a>)</li>
<li>MEMS microphone (<a href="https://media.digikey.com/pdf/Data%20Sheets/Knowles%20Acoustics%20PDFs/SPH0645LM4H-B.pdf" target="_blank" rel="noopener noreferrer">datasheet</a>)</li>
<li>0.96" colour LCD (160x80)</li>
<li>Connector for <a href="/products/pms5003-particulate-matter-sensor-with-cable" target="_blank" rel="noopener noreferrer">particulate matter (PM) sensor</a>*</li>
<li>pHAT-format board</li>
<li><strong>Fully-assembled</strong></li>
<li>Compatible with all 40-pin header Raspberry Pi models</li>
<li><a href="https://pinout.xyz/pinout/enviro_plus">Pinout</a></li>
<li><a href="https://github.com/pimoroni/enviroplus-python" target="_blank" rel="noopener noreferrer">Python library</a></li>
</ul>
<p><a href="/products/pms5003-particulate-matter-sensor-with-cable" target="_blank" rel="noopener noreferrer"><em>*particulate matter sensor available separately</em></a></p>
<p>A couple of nice little extras... there's a spare ADC channel broken out on a header if you want to connect another analog sensor, along with I2C pins in the right configuration for plugging one of our <a href="https://shop.pimoroni.com/collections/pimoroni-breakouts">Pimoroni I2C breakouts</a> onto!</p>  
<h2>Citizen science air quality monitoring</h2>

<p> <p class="body-copy mk-paragraph" ><img src="  https://cdn.shopify.com/s/files/1/0174/1800/products/PMS5003_particulate_matter_sensor_with_cable_1_of_4_1024x1024.progressive.JPG?v=1560514915"
   class="attempt-right print-hide" style="max-width:800px" /> </p>



<p>We've developed this board in collaboration with the University of Sheffield, with the aim of letting you contribute real-time air quality data from your local area to open data projects like <a href="https://united-kingdom.maps.luftdaten.info" target="_blank" rel="noopener noreferrer">Luftdaten</a>.</p>
<p>The alarming drop in our air quality is something that's really important to understand. Devices like Enviro+ allow fine-grained, detailed datasets that let us see shifts in air quality through time and across different areas of cities. The more devices that contribute data, the better quality the dataset becomes.</p>
<p>Particulate matter (PM) is made up of tiny particles that are a mix of sizes and types, like dust, pollen, mould spores, smoke particles, organic particles and metal ions, and more. Particulates are much of what we think of as air pollution. They can be measured, in size and quantity, by particulate matter sensors like the <a href="https://shop.pimoroni.com/products/pms5003-particulate-matter-sensor-with-cable" target="_blank" rel="noopener noreferrer">PMS5003</a> that you can connect to Enviro+.</p>


   
<p>The analog gas sensor can be used to make <strong>qualitative</strong> measurements of changes in gas concentrations, so you can tell broadly if the three groups of gases are increasing or decreasing in abundance. Without laboratory conditions or calibration, you won't be able to say <em>"the concentration of carbon monoxide is n parts per million"</em>, for example.</p>
<p>Temperature, air pressure and humidity can all affect particulate levels (and the gas sensor readings) too, so the BME280 sensor on Enviro+ is really important to understanding the other data that Enviro+ outputs.</p>
<p>We've got a tutorial (coming soon) that shows you how to use Enviro+ and a few easily-available bits to build the board into a weather-proof housing that you can mount outside your house to monitor local air quality.</p>
<h2>Indoor monitoring</h2>
<p>As well as outdoor air quality monitoring, Enviro+ is really good for indoor monitoring too. The temperature, humidity, light, and noise readings can be used to keep track of conditions in your home and, combined with the LCD to display the data and the proximity sensor for interaction, it makes an ideal headless monitoring device.</p>
<p>Why not combine it with some IoT smarts like an Alexa skill so that you can ask what the temperature or humidity is? Or you could set up a trigger action with IFTTT that turns your Philips Hue lights on when the light level drops below a certain level. There's loads of possibilities!</p>
<h2>Software</h2>
<p>We've put together a <a href="https://github.com/pimoroni/enviroplus-python" target="_blank" rel="noopener noreferrer">Python library</a> to control all the parts of your Enviro+. There's a <a href="https://github.com/pimoroni/enviroplus-python/tree/master/examples" target="_blank" rel="noopener noreferrer">bunch of examples</a> for each of the individual parts, an all-in-one example that shows you the data from Enviro+'s sensors in a visual way. There's also an <a href="https://github.com/pimoroni/enviroplus-python/tree/master/examples" target="_blank" rel="noopener noreferrer">example</a> that shows you how to contribute data to Luftdaten (requires <a href="https://shop.pimoroni.com/products/pms5003-particulate-matter-sensor-with-cable" target="_blank" rel="noopener noreferrer">particulate matter sensor</a>).</p>
<h2>Getting started</h2>
<p>Have a read through our (exhaustive!) <a href="https://learn.pimoroni.com/tutorial/sandyj/getting-started-with-enviro-plus" target="_blank" rel="noopener noreferrer">Getting Started with Enviro+ tutorial</a> that walks you through how to install the software, how to run the code examples, and how to use the <a href="https://github.com/pimoroni/enviroplus-python/" target="_blank" rel="noopener noreferrer">Enviro+ Python library</a>.</p>
    </article>

















Designed for environmental monitoring, Enviro+ lets you measure air quality (pollutant gases and particulates), temperature, pressure, humidity, light, and noise level. Learn more - https://shop.pimoroni.com/products/enviro-plus

[![Build Status](https://travis-ci.com/pimoroni/enviroplus-python.svg?branch=master)](https://travis-ci.com/pimoroni/enviroplus-python)
[![Coverage Status](https://coveralls.io/repos/github/pimoroni/enviroplus-python/badge.svg?branch=master)](https://coveralls.io/github/pimoroni/enviroplus-python?branch=master)
[![PyPi Package](https://img.shields.io/pypi/v/enviroplus.svg)](https://pypi.python.org/pypi/enviroplus)
[![Python Versions](https://img.shields.io/pypi/pyversions/enviroplus.svg)](https://pypi.python.org/pypi/enviroplus)

# Installing

You're best using the "One-line" install method if you want all of the UART serial configuration for the PMS5003 particulate matter sensor to run automatically.

## One-line (Installs from GitHub)

```
curl -sSL https://get.pimoroni.com/enviroplus | bash
```

**Note** report issues with one-line installer here: https://github.com/pimoroni/get

## Or... Install and configure dependencies from GitHub:

* `git clone https://github.com/pimoroni/enviroplus-python`
* `cd enviroplus-python`
* `sudo ./install.sh`

**Note** Raspbian Lite users may first need to install git: `sudo apt install git`

## Or... Install from PyPi and configure manually:

* Run `sudo pip install enviroplus`

**Note** this wont perform any of the required configuration changes on your Pi, you may additionally need to:

* Enable i2c: `raspi-config nonint do_i2c 0`
* Enable SPI: `raspi-config nonint do_spi 0`

And if you're using a PMS5003 sensor you will need to:

* Enable serial: `raspi-config nonint set_config_var enable_uart 1 /boot/config.txt`
* Disable serial terminal: `sudo raspi-config nonint do_serial 1`
* Add `dtoverlay=pi3-miniuart-bt` to your `/boot/config.txt`

And install additional dependencies:

```
sudo apt install python-numpy python-smbus python-pil python-setuptools
```

## Help & Support

* GPIO Pinout - https://pinout.xyz/pinout/enviro_plus
* Support forums - http://forums.pimoroni.com/c/support
* Discord - https://discord.gg/hr93ByC
