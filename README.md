mm-wave DreamHat+ radar

The DreamHat+ radar is a 60 GHz FMCW radar module based on the impressive Infineon BGT60TR13C radar chip.

This PiHat allows direct access to the Infineon chip, via 50 MHz SPI, to unleash the full power of this chip.

A range of example Python applications is available here, as a disk image download, to get you started:

http://www.ee.ucl.ac.uk/~ucee364/DreamRF/mmw-hat.zip (if necessary, copy and paste this link into a new browser window).

The application script above can be installed as a disk image using Raspberry Pi Imager:

https://www.raspberrypi.com/software/

just extract the .zip file above and install on your SD card using 'select a custom .img from your computer'.

The applications provided include:

1. range-Doppler plot, the classic radar visualisation;
2. xy plot with tracking and persistence;
3. Doppler-azimuth plot;
4. Doppler-range plot;
6. Data gathering and storage;
7. Offline processing.

1 to 4, above, produce real-time radar images at c. 5-10 Hz refresh rate.

The example scripts are also available separately in the MMW-HAT.zip file in this repository. If you use these files then make sure to set up the environment as follows:

sudo apt-get update
sudo apt-get install -y python3-numba
sudo apt-get install -y python3-pyqtgraph
sudo apt-get install -y python3-pyfftw

This is more than enough to get you started and on the way to creating your own unique 60 GHz radar project!

![](http://www.ee.ucl.ac.uk/~ucee364/DreamRF/radarpic.jpg "Logo Title Text 1")
