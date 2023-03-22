Copyright 2022 Silvan Teufel / Teufel-Engineering.com All Rights Reserved.

This Repository contains the configs for all of my Plugins.



# RTS Unit Template - Readme - 2022
### Create your own RTS Units !

- CTRL + E -- Rotate Cam Right (works also when Cam is locked to Unit )
- CTRL + Q - Rotate Cam Left (works also when Cam is locked to Unit )
- CTRL + Left Mouse Click -- Move Cam to Mouse Position
- CTRL + W -- Zoom Cam In
- CTRL + S -- Zoom Cam Out
- CTRL + HOLD SPACE -- Fast Zoom Out to Position
- CTRL + SPACE + Left Mouse - Move Cam to Mouse Position
- Mouse to Screen Edges -- Move Cam to Mouse Position
- Right Click when Unit Selected -- Move Unit
- Shift + Right Click when Char. Sel. -- Move Unit through Waypoints
- CTRL + G when Unit Selected -- Lock Unit on Character
- CTRL + T when Unit Selected -- Switch to Third Person Mode
- Press A when Character Selected - toggle Attack
- Press A + Left Click when Character Selected - Move to Position and Attack
- Press A + Left Click on Enemy - Focus this Enemy
- HOLD TAB -- Show Control-Widget

Gameplay Preview: https://www.youtube.com/watch?v=ESS5PYtr9mU

For Questions you can write to info@teufel-engineering.com
If you find any Issues or Bugs i appreciate your Mail.
I will fix any Bugs as soon as i can and update the Product.

## Download the Plugin

https://www.unrealengine.com/marketplace/en-US/profile/Silvan+Teufel?count=20&sortBy=effectiveDate&sortDir=DESC&start=0

If you have downloaded the plugin it can be found in your Unreal Engine folder:
C:\Program Files\Epic Games\UE_5.0\Engine\Plugins\RTSUnitTemplate (for example).
or
C:\Program Files\Epic Games\UE_5.0\Engine\Plugins\Marketplace\RTSUnitTemplate

If you can find this folder in your enginge plugins folder the download was successful.
If the plugin is in another folder, you should copy it here.

## Install the Plugin

Open Unreal Editor. Click Edit -> Plugins to open the plugin window.
Search for SwarmSimulator and put a check mark at it.

## Import Settings

RTSUnitTemplate/Document/Description_Backup_2022-11-14_102425_RTSUnitTemplate.ini
RTSUnitTemplate/Document/Gameplay_Debugger_Backup_2022-11-14_102535_RTSUnitTemplate.ini
RTSUnitTemplate/Document/Input_Backup_2022-11-14_102458_RTSUnitTemplate.ini (Deprecated, use Enhanced Keyboard Settings)
RTSUnitTemplate/Document/Maps_&_Modes_Backup_2022-11-14_102333_RTSUnitTemplate.ini

__You can download these files also here from github by clicking on top left Code->Download Zip__

Open Unreal Editor. Go to Edit -> Project Settings -> Search for the Specific Input Section: Gameplay Debugger, Input, Maps & Modes, Settings (For Description)
and import the .ini file

You can also find the .ini files in the Plugin Folder "All\Engine\Plugins\SwarmSimulator\Document\Input

## Enhanced Keyboard Settings

You can Change Inputs at: All\Engine\Plugins\TopDownRTSCamLib\Content\Blueprints\Controls

For GameplayTags you have to set AssetMangerClass in ProjectSettings (Restart Project after change):

![image](https://user-images.githubusercontent.com/45244380/211891213-c16b45c3-25d7-4af2-bb5c-d4aeb124ceec.png)

Go to ProjectSettings->Input and set EnhancedIputComponentBase:

![image](https://user-images.githubusercontent.com/45244380/211891263-032cfbc6-120c-40f3-82f6-b1d7cff938a3.png)

YOu can set MappingContext and ControlAsset in the BP_CameraBase:

![image](https://user-images.githubusercontent.com/45244380/212332329-42eaec24-7096-4728-8c8a-ede7846c0efc.png)

![image](https://user-images.githubusercontent.com/45244380/212332385-9137f8ed-212e-4c99-bcb5-def35dd7160b.png)

## Test Example Map

Open Unreal Editor. Open folder (In Unreal Editor folder tab):
All\Engine\Plugins\RTSUnitTemplate\Content\RTSUnitTemplate\Level\levelOne

## Example Blueprints

Your can find example Blueprints in the Unreal Editor as well:
All\Engine\Plugins\RTSUnitTemplate\Content\RTSUnitTemplate\Blueprints

This Blueprints use the Parent Classes from RTSUnitTemplate Plugin, which you can use for your Blueprints.
	
## Parent Classes

If RTSUnitTemplate is installed the Classes can be used as Parent Class in Blueprint, so all functions from this Class are available.
Just use one of the following Classes as Parent Class and or just choose them in your GameMode Blueprint. Category = RTSUnitTemplate. 


