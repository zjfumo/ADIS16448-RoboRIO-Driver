# LabVIEW Instructions

## NI Package Manager Installation
Installation via the NI Package Manager is the only supported installation method for the 2020 season. 

This library assumes you have a working 2019 LabVIEW Professional installation and 2020.b4 or greater FRC software package already installed on your system. The latest package installer can be found [here](https://github.com/juchong/ADIS16470-RoboRIO-Driver/releases). 

## Installing the Library
Once downloaded, double-click on the `.nipkg` file. The pre-installed NI Package Manager utility will extract the necessary files into the correct folders within your LabVIEW installation. Future updates to the library can be installed over previous installations. **LabVIEW must be closed completely before installing the library package!** 

![ADIS16470 .nipkg Icon](https://raw.githubusercontent.com/juchong/ADIS16470-RoboRIO-Driver/master/docs/nipkg_icon.PNG)

Once you double-click on the installer file, the NI Package Manager will walk you through installing the library. Click `Next` at the window shown below to install the library. *Note: The library version shown in the screenshots on this page may be different than the latest version available on the GitHub page!*

![ADIS16470 Installing Window](https://raw.githubusercontent.com/juchong/ADIS16470-RoboRIO-Driver/master/docs/installing.PNG)

The package manager window should like like below if the library was installed successfully.

![ADIS16470 Install Complete](https://raw.githubusercontent.com/juchong/ADIS16470-RoboRIO-Driver/master/docs/installed.PNG)

## Using the Library
The LabVIEW driver can be used like any other third-party library. All .vi's can be found in the pallet shown below:

![ADIS16470 LabVIEW Pallet](https://raw.githubusercontent.com/juchong/ADIS16470-RoboRIO-Driver/master/docs/menu.PNG)

The example .vi included in this repository should look like below when successfully connected to a RoboRIO:

![ADIS16470 LabVIEW Example Front Panel](https://raw.githubusercontent.com/juchong/ADIS16470-RoboRIO-Driver/master/docs/labview_example.PNG)

## Uninstalling the Library
To uninstall the library, open the NI Package Manager and select `ADIS16470 IMU RoboRIO Driver`. 

![ADIS16470 .nipkg Icon](https://raw.githubusercontent.com/juchong/ADIS16470-RoboRIO-Driver/master/docs/uninstall.PNG)