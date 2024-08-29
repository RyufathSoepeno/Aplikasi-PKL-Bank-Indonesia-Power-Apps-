# Aplikasi PKL Bank-Indonesia (Power-Apps)

To download the entire app, download the .msapp file which can be found in the Microsoft.PowerApps Folder

To import this to your PowerApps, simply create a blank canvas app in PowerApps, click the triple dots in the header section, select "Open", and navigate to the msapp file

<br><br>

To search for the source code, simply check the "Src" file and you will find the .yaml "fx" files of each screens

To search for the source code for all the elements available, simply check the Pkgs file and you will find the .yaml "fx" files of each elements

<br><br>


To extract the source code with Microsoft Visual Studio
1. Export using PowerApps
2. Download Power Platform Tools
3. Select the .msapp file from the package you exported and put it to visual studio editor
4. use this code pac canvas unpack --msapp AppName.msapp --sources DestinationFolder (a new folder will be created it unavailable in your file explorer)
