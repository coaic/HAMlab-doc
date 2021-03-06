.. _sdr:

Power SDR
######### 

Power SDR Instalation
+++++++++++++++++++++

.. _here: http://downloads.redpitaya.com/hamlab/powersdr/Setup_PowerSDR_Charly_25_HAMlab_Edition.exe

Click here_ to download Power SDR installation package.

1. Start the installation by double clicking on the Setup_PowerSDR_Charly_25_HAMlab_Edition.exe file.

	.. image :: ../quickStart/HamLab_images/PowerSDRinstallation1.PNG

2. If you are asked for extended user access rights during the installation click Yes! Running installer with administration rights will work as well. 
	
	.. image :: ../quickStart/HamLab_images/PowerSDRinstallation2.png
		:scale: 70%
		
On Windows 10 you might get warning of Unknown Publisher you can procede with installation by clicking on "more info" and then "Run anyway".
 
	.. image:: ../quickStart/HamLab_images/PowerSDRinstallation3.PNG
		:scale: 75 %
	
	.. image:: ../quickStart/HamLab_images/PowerSDRinstallation4.PNG
		:scale: 75 %
	

3. Follow the instructions of the setup routine and accept the license agreements if asked for.


4. At the end of the installation you are asked if you want to run PowerSDR Charly 25 / Hamlab Edition software immediately, feel free to do so.


5. After starting the PowerSDR Charly 25 / Hamlab Edition software the first time you will be led through the PowerSDR Charly 25 / Hamlab Edition specific setup wizard which lets you configure the software to use it with your Hamlab.

So please choose Hamlab as your radio model:

.. image :: powersdrsetup01.jpg

6. Confirm the RedPitaya as HPSDR hardware (currently there is no other type of hardware available for the Hamlab).

.. image :: powersdrsetup02.jpg

7. Select the region where you are using your Hamlab, this is important due to the different frequency ranges your are allowed to transmit in the different countries all over the world:

.. image :: powersdrsetup03.jpg

8. Your initial setup is completed:

.. image :: powersdrsetup04.jpg

9.  After clicking the Finish button PowerSDR Charly 25 / HAMlab Edition will start with the calculation of the FFT wisdom file, **which will take a while** depending on the CPU power of your computer.
This is only done once, even after updating the software to a new version in the future:

.. image :: powersdrsetup05.jpg

10. When all calculations are done, PowerSDR Charly 25 / HAMlab Edition will come up with the main window:

.. image :: powersdrsetup06.jpg

11. Click Power to connect Power SDR with HAMlab. On the screen the input singnal should appear.

.. image :: ../quickStart/HamLab_images/SDRconnectepower.PNG




Power SDR configuration
+++++++++++++++++++++++

Audio configuration (only required for HAMlab 80-10 10W model)

.. image :: ../quickStart/HamLab_images/PowerSDRaudiosetup.PNG


.. HAMlab configuration

    
    
Power SDR basic usage
+++++++++++++++++++++   
 
Putting HAMlab into SDR mode
----------------------------


1.) Turn on power supply, HAMlab will start automatically. Next time you can momentary press on the power button to turn it on/off.

2.) Make sure your computer is connected to same local area network as HAMlab.

3.) On your computer start a WEB browser (Chrome recommended).

4.) Type in the HAMlab URL that can be found on the back panel of the HAMlab

.. image:: ../quickStart/HamLab_images/4_Type_in_the_HAMlabURL.jpg

HAMlab application page should appear 
     
.. image:: ../quickStart/hamlab/apps.png


In order to use HAMlab in SDR mode You must run SDR HPSDR web application first. 

.. image :: ../appsFeatures/hpsdr_icon.png
   :alt: icon
   :align: center
   
Click on the SDR icon in order to put HAMlab into SDR mode. While web application is running HAMlab will be in SDR mode and you can connect to it with PowerSDR software to use it as radio.
   
.. image :: ../appsFeatures/webapp.png   


Connecting Power SDR with HAMlab
--------------------------------

.. image :: ../quickStart/HamLab_images/PowerSDRsetupleft.PNG
.. image :: ../quickStart/HamLab_images/PowerSDRsetup2.PNG
.. image :: ../quickStart/HamLab_images/PowerSDRsetup.PNG
	

Receiving
--------- 


Transmitting
------------


Credits
+++++++

Original developer of sdr-transceiver-hpsdr web application is Pavel Demin. 
Original developer of PowerSDR is FlexRadio Systems. 

Repositories used for our builds:

	- https://github.com/RedPitaya/PowerSDR_HPSDR_mRX_PS
	- https://github.com/RedPitaya/red-pitaya-notes

   
