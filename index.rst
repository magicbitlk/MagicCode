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
   
   Sprite list 

Users can **give instructions** to a sprite (such as telling the sprite to move) by snapping blocks together in the script area. Clicking on the block(s) in the script area will cause the sprite to react based on the function of the block(s) clicked. Clicking on a sprite's thumbnail in the sprite pane will bring up the script area of that sprite.

The **look of a sprite can also be changed by using costumes**. The current costume of a sprite can be changed by clicking on the "costumes" tab and clicking on the desired costume of choice, or by using Looks blocks to select the sprite's costume. New costumes for the sprite can be imported, created, and edited in the MagicCode Paint Editor.

Some sprites additionally have at least one sound. Unlike costumes, sounds are an optional field, so you can have a sprite with no sounds. **The sounds tab** allows you to add, delete, and edit sounds. Sounds can be played in the sound editor or with blocks that play a specific sound.
Sprites (with all of their scripts, costumes, and sounds) can be exported, and then imported into another project if desired. This is achieved by right-clicking on a sprite's thumbnail in the sprite pane and then selecting "save to local file" in the pop-up menu. A sprite can also be dragged into the backpack and dragged out into another project for transporting. However, this will not save the sprite to one's computer.

- **Stage**

The **stage** is the background of the project where your sprites perform their actions,but it can have scripts, backdrops (costumes), and sounds, similar to a sprite and it has its own scripts and sounds.But the stage has some restrictions on sprite functions such as motion and size blocks.
 
The stage is 480 pixels wide and 360 pixels tall.All sprites have a particular position on the stage. However, no sprites can move behind the stage and it is always at the back layer.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/stage.PNG
   
   The Stage list and the Stage with sprite on it
   
   Devices
=======

The **Device** tab is the place where you can connect your boards with MagicCode. MagicCode provides facilities to connect five boards. You can connect your Magicbit, Arduino Uno, Arduino Mega, Arduino Nano, or Microbit Boards with MagicCode. You can program your board either in live mode or Upload mode.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/device.png
   
   Device tab

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

   Devices Library


The above Devices library is displayed after clicking the select button and select your devices from the library.

**5.	Select the Serial port where the device is connected.**

If you don’t see any port in the select port menu, then click the refresh button. Following figure dispays the select port menu.

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/port.PNG
   :scale: 60% 
   
   Select port menu

**6.	Click the connect button and connect your device to MagicCode**

After the device has connected, "Connect" button changes to “Disconnect” button and |newbutton1| is turned into |newbutton2|.

.. |newbutton1| image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/dconnect.png
                :scale: 60%

.. |newbutton2| image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/connect.png
                :scale: 60% 

.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/d1.png
   :scale: 60%

   Device tab, before connecting to the device 
   
.. image:: https://raw.githubusercontent.com/magicbitlk/MagicCode/main/images/afterconnect.png
   :scale: 60%

   Device tab, after connecting to the device  

Now you can create and execute your program with your board.






