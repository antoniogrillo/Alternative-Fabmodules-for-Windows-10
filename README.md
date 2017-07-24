# Alternative-Fabmodules-for-Windows-10
@ ntngrillo

## Step_1
Navigate to ````Settings````. You can get there by clicking the gear icon on the Start menu.

Click ````Update & security```` and go to ````Select For Developers```` in the left column.

Select ````Developer Mode```` under ````Use developer features```` if it's not already enabled.

![Image of DEVMODE](/img\devmode-pc-options.png)

## Step_2
Navigate to the ````Control Panel```` (the old Windows control panel). You can get there by hitting ````Windows Key + X```` and selecting Control panel from the pop-up menu that appears.

Select ````Programs and Features````. If it's not visible, make sure you select "Large icons" from the "View by" menu.


Click ````Turn Windows features on or off.````

Toggle ````Windows Subsystem for Linux (Beta)```` to on and click Ok and reboot your computer.

![](img\turn-features-on.png)

## Step_3
You can install all of the dependencies with the command:

    sudo apt-get install python python-wxgtk2.8 python-dev python-pip gcc g++ libpng12-dev libgif-dev make bash okular libboost-thread-dev libboost-system-dev cmake    
