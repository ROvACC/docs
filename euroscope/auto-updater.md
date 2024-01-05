## [Guide] How to add auto updater in EuroScope

1. Go to ```./Documents/EuroScope``` and create a new folder named ```LRBB AUTO GNG```.
2. Open this folder and unzip both the Install and Update packs from [GNG](https://files.aero-nav.com/LRBB).
3. Access the [URL link](https://files.aero-nav.com/AeroNav_LRBB_by_Aerosoft_NavDataPro.txt), copy the content and paste it to a new txt file. Save the file as ```AeroNav_LRBB_by_Aerosoft_NavDataPro.txt``` to ```./Documents/EuroScope/LRBB AUTO GNG/```
4. Run EuroScope and open the profile from ```LRBB AUTO GNG```. 
5. Push the ```OPEN SCT``` button, then on Download Sector Files
![image][first]
6. You'll see this window
![image][before]
7. Complete it as follows:
> Name: ```LRBB AUTO GNG```
> URL: ```https://files.aero-nav.com/AeroNav_LRBB_by_Aerosoft_NavDataPro.txt```
8. Push the ```NEW``` button
9. Now, look up this new entry in the above list and select it. (It's blue when selected.)
10. Now complete the menu with the location of the before created file (You can use the Browse button)
> Filename: ```[location-to]/Documents/EuroScope/LRBB AUTO GNG/AeroNav_LRBB_by_Aerosoft_NavDataPro.txt```
![image][after]
11. Push the ```Update``` button
12. Push the ```Download``` button
13. Wait a few seconds... You'll see the available packs updating in the bottom part of the window. 
14. Tick the ```A``` column for both packs (A - auto).

**JOB DONE**

#### How it works?

Every 12 hours, if EuroScope runs, it automatically checks if there is any difference between your sector file version and the sector file published from GNG.

If it finds any difference regarding version you'll see a window where the EuroScope will inform you about the availability of a new sector file. It's important to keep your sector file up to date at any time, so push YES. 

Thereafter, a new window will appear asking if you want to change the sector file through all ASR files. It's mandatory to select YES.

A third window might ask if you want to delete the old sector file. It's your decision whether you want to keep all .sct and .ese files from the previous versions. (You don't need them to control.)

#### Might want to update manually?

1. Push the ```OPEN SCT``` button, then on Download Sector Files
2. Lookup for your provider (```AeroNav GNG LRBB VATSIM ROMANIA```)
3. In the bottom list select which pack you want to *manually* update and then push the ```DOWNLOAD``` button
![image][manual]

[first]: ../../images/euroscope-download-sector-files-menu.png
[before]: ../../images/euroscope-dsfp.png
[after]: ../../images/euroscope-auto-updater-completed.png
[manual]: ../../images/euroscope-auto-but-manual.png