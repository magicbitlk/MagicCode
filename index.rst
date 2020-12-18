******************
What is MagicCode?
******************

**MagicCode** is a Scratch 3.0 based graphical programming software that makes you learn to code super-fast. If you are new to the world of programming, MagicCode is one of the best companions that makes coding fun and easy. The user-friendly interface and drag and drop functionality makes coding more interesting because of no need to worry about traditional programming rules. You can create your interactive games, animations, or program robots and projects with MagicCode. You can directly connect your Magicbit, Arduino, or Microbit boards with MagicCode and control generic sensors and actuators or It also has an upload mode where you can upload your code inside boards.

***************
Getting Started
***************

MagicCode interface and tools
=============================

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/interface.PNG

- **Blocks**

A **block** is like a jigsaw puzzle piece that is used to write programs by simply dragging and dropping them below one another in the scripting area. Blocks are often easier to work with than text-based programming, as one has to memorize the commands typed and syntax errors may occur.There are ten categories of blocks: Motion, Looks, Sound, Event, Control, Sensing, Operators, Variables, List, and My Blocks. The list blocks are shown under the Variables Blocks.

- **Block palette**

The **block palette** is under the Code tab. It consists of different palettes such as Motion, Sound, and Control. Each palette has different blocks that perform functions specified by the palette name.There are other varieties of block palettes that can be loaded from the Add Extension button located at the left bottom.

- **Script**

A **script** is a program or code in MagicCode which is a collection or stack of blocks that all interlock with one another. The blocks and their order are very important, as they determine how sprites interact with each other and the backdrop. Sometimes, comments are attached to scripts to explain what certain blocks do and what the script's purpose is. You can write multiple scripts all of which can then run simultaneously

- **Connect Devices**

Connect Devices is used to connect devices (Magicbit, Arduino, or Microbit) with MagicCode.

- **Add Extensions**

Add Extensions is used to add new palettes to the block palette.

- **Sprite**

Sprites, either user-created, uploaded, or found in the MagicCode Sprites library, are the objects that perform actions in a project. Most projects have at least one sprite as well because only sprites can move.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/sprite.PNG

Users can **give instructions** to a sprite (such as telling the sprite to move) by snapping blocks together in the script area. Clicking on the block(s) in the script area will cause the sprite to react based on the function of the block(s) clicked. Clicking on a sprite's thumbnail in the sprite pane will bring up the script area of that sprite.

The **look of a sprite can also be changed by using costumes**. The current costume of a sprite can be changed by clicking on the "costumes" tab and clicking on the desired costume of choice, or by using Looks blocks to select the sprite's costume. New costumes for the sprite can be imported, created, and edited in the MagicCode Paint Editor.

Some sprites additionally have at least one sound. Unlike costumes, sounds are an optional field, so you can have a sprite with no sounds. **The sounds tab** allows you to add, delete, and edit sounds. Sounds can be played in the sound editor or with blocks that play a specific sound.
Sprites (with all of their scripts, costumes, and sounds) can be exported, and then imported into another project if desired. This is achieved by right-clicking on a sprite's thumbnail in the sprite pane and then selecting "save to local file" in the pop-up menu. A sprite can also be dragged into the backpack and dragged out into another project for transporting. However, this will not save the sprite to one's computer.

- **Stage**

The **stage** is the background of the project where your sprites perform their actions,but it can have scripts, backdrops (costumes), and sounds, similar to a sprite and it has its own scripts and sounds.But the stage has some restrictions on sprite functions such as motion and size blocks.
 
The stage is 480 pixels wide and 360 pixels tall.All sprites have a particular position on the stage. However, no sprites can move behind the stage and it is always at the back layer.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/Stage.PNG
   
   Devices
=======

The **Device** tab is the place where you can connect your boards with MagicCode. MagicCode provides facilities to connect five boards. You can connect your Magicbit, Arduino Uno, Arduino Mega, Arduino Nano, or Microbit Boards with MagicCode. You can program your board either in live mode or Upload mode.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/device.PNG

**Live mode**

In the **Live** mode, you can view the program execution effect in real-time, which facilitates the commissioning of the program.

.. admonition:: Note
  
  In this mode, you must keep the board connected to MagicCode. If it is disconnected, then the program cannot be executed.

**Upload mode**

In the **Upload** mode, you need to upload the compiled program to the device. After being successfully uploaded, the program can still run properly on the device when the device is disconnected from MagicCode.

.. _connect:

Connecting devices  with USB connector
--------------------------------------

**1.	Connect your device to the pc with USB Connector**

**2.	Go to  the Device tab at the down right corner of MagicCode interface**

**3.	Select Live Mode or Upload Mode**

**4.	Select your Device by clicking the Select button.**

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/d2.PNG

The above Devices library is displayed after clicking the select button and select your devices from the library.

**5.	Select the Serial port where the device is connected.**

If you don’t see any port in the select port menu, then click the refresh button. Following figure dispays the select port menu.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/port.PNG


**6.	Click the connect button and connect your device to MagicCode**

After the device has connected, "Connect" button changes to “Disconnect” button and |newbutton1| is turned into |newbutton2|.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/dconnect.PNG

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/connect.PNG

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/d1.PNG

   
.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/afterconnect.PNG

   Device tab, after connecting to the device  

Now you can create and execute your program with your board.

MagicCode Extensions
====================

Magicbit extension
------------------

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/ext1.png

Magicbit Blocks
~~~~~~~~~~~~~~~

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb1.png

The block sets the digital state of the specified digital pin to either “High” or “Low”. If the output is High, the pin will be at 3.3V and if the output is Low the pin will be at 0V.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb2.png

The block sets PWM output on Magicbit PWM pins. The user can select the output from a range of 0 to 100.  If the PWM output is 50, then half the time output will be high and for the rest, the output will be Low.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb3.png

The block rotates the servo connected to the selected PWM pin on Magicbit with the selected angle(0,45,90,135,180) in degrees.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb4.png

The block reads the state of the digital pin on Magicbit(“High” or “Low”). If the state of the pin is “High”, it returns True, else False.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb5.png

The blocks output the status(“HIGH “or “LOW”) of the selected button(“left” or “right”).

Left button – Connected to D35 pin of Magicbit

Right button – Connected to D34 pin of Magicbit

when the button has not been pressed the status of the button is 1(HIGH), & when the button has pressed the status of the button is 0(LOW). 

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb6.png

The block returns the value of analog pins available in the connected hardware between the value range 0 to 4096. This range is mapped to the voltage of the pin (normally 0 to 3.3V). 

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb7.png

The block returns the value of the pin D39, which is the potentiometer connected pin on the Magicbit. It generates a voltage between 0 and 3.3V according to the angle of the potentiometer and returns an integer value(0v= 0 analog value, 3.3v =  analog value).

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb8.png

The block returns the value of the pin D36, which is the LDR(Light Depend Resistor) connected pin on the Magicbit. It generates a voltage between 0 and 3.3V according to the angle of the potentiometer and returns an integer value(0v = 0 analog value, 3.3v = 1024 analog value).

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb9.png

The block generates a tone in the Piezo buzzer connected to the D25 pin on the Magicbit with Selected frequency and selected Duration.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb10.png

The block generates selected note(C,D,E,F,G,A,B) for selected number of beats.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb11.png

The block rotates the selected DC motor(motor 1 or motor 2) at the selected speed.

Motor 1 – connected to  M1A and M1B pins on the Magicbit

Motor 2 – connected to  M2A and M2B pins on the Magicbit

Speed – should be at the range of -100 to 100.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb12.png

The block displays the text you entered at the selected starting position on the OLED display.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb13.png

The block displays the selected shape(circle, triangle, square)  at the selected starting position on the OLED display on Magicbit.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb14.png

The block sets the font size(supports sizes from 2 to 5) of the text displayed on the OLED display on Magicbit

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb15.png

The block sets the shape size(supports sizes: small, medium, large) of the shape displayed on the OLED display on Magicbit.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb16.png

The block clears the OLED display which means all pixels are off.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb17.png

The block returns the distance by reading the analog pin where the ultrasonic sensor is connected.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb18.png

The block returns the temperature by reading the analog pin where the DHT11 sensor is connected.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb19.png

The block returns the humidity by reading the analog pin where the DHT11 sensor is connected.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb20.png

The block sets the color of the RGB module to the selected RGB value. These R, G, B values should be an integer between 1-255. ‘Pin’ variable is the Microbit pin where the RGB module is connected and the ‘index’ variable represents the number of LEDs that module has.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/mb21.png

The Block sets the color of the RGB LED to the selected color at the selected pin on Magicbit.





