# IF to KML
IF to KML is a Python script that retrieves the flight information from Infinite Flight flight simulator and writes it to a KML file that can be viewed in Google Earth.

Usage: Generate 3D Flight Plans/Previews that can be viewed in Google Earth. 

<p align="center">
<img src="https://chauhansai.github.io/Script-Projects/files/IFtoKMLcolormatch.png" width="80%"/>
</p>

## Downloading the script
Download the executable file attached to the GitHub release found [here](https://github.com/ChauhanSai/Script-Projects/releases/tag/r3) or download the source python files to run in CMD

Just run it! Running the script will connect to a running instance of Infinite Flight on your WiFi. It will ask you to input a interval for sending and receiving data from the sim. For slower aircraft and/or slower internet connection aim for a higher value(ex. 5 seconds) while 1 second will provide the best model. It will then prompt you to enter a starting point. Enter this point when and only when you are ready to start tracking. The script will then receive information from the sim every interval. When the flight is complete and you have parked, just press space a couple times to end the flight tracking and enter a stop point. The file will be saved to the directory of the script, named with the date and time of start. 

### Required modules (CMD Version)
Please be sure to have all the required python modules installed for the CMD:
- IFConnectOld
- datetime
- pytz
- keyboard

This is a tracked flight(KLGB-KNUC) previously recorded and opened in [Google Earth Pro](https://www.google.com/earth/versions/):
<img src="https://i.imgur.com/vchi2C0.png" alt="KLGB-KNUC"/>