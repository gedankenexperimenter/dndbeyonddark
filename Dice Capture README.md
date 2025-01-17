_Note:_ If you are having problems with dice not rendering behind the window see <a href="https://github.com/Azmoria/dndbeyonddark/blob/master/Dice%20Capture%20README.md#:~:text=You%20can%20put,hidden%20behind%20others.">This section</a> for a work around.

[![Capture Dice from DNDBeyond for Streaming/OBS](https://user-images.githubusercontent.com/65363489/150996224-001f9634-2a69-435b-8a70-a2190cb8d500.png)](https://youtu.be/mpB4d-lpnRU")


This requires the character sheet theme to work. Follow instructions in <a href="https://github.com/Azmoria/dndbeyonddark/blob/master/README.md">README.md</a> to install that first. The background color is set in this theme at the bottom of the options. 

For how to set up character specific themes and apply your dice customization per character see: <a href="https://github.com/Azmoria/dndbeyonddark/blob/master/Character%20Specific%20Themes.md">Character Specific Themes.md</a>



Then you will need an extention that allows you to install user.js.

 I recommend Tampermonkey. You can get it for <a href="https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en">Chrome</a> or <a href="https://addons.mozilla.org/en-CA/firefox/addon/tampermonkey/">Firefox</a>


Then install the javascript by going here: <a href="https://github.com/Azmoria/dndbeyonddark/raw/master/Dice%20Tray%20Stream%20Window.user.js">Dice Tray Stream Window.user.js</a>

It will popup with the below. Click install.

![image](https://user-images.githubusercontent.com/65363489/150918125-1e9cd2a0-b1ae-4ec5-acd1-1bbc727c04f9.png)

Once installed when you load into various parts of the site where dice are enabled it will pop up another window. If it doesn't make sure you are **allowing popups on dndbeyond.** 

You can change the background in the character sheet theme options. The options in the image below apply to the dice roll area.

 ![image](https://user-images.githubusercontent.com/65363489/151418937-3e1a7e51-1ed7-49f6-ad6e-166acff479cd.png)


You can put it behind the main window as long as a sliver of it is showing. However it will **not** render in chrome if the whole dice tray is hidden behind another window. Chrome does this to save computer resources. Firefox will be implementing this feature as well at some point. 

If you need to be able to fully hide the dice tray behind the main window you can launch chrome with the --disable-backgrounding-occluded-windows flag in the shortcut target.

To do this create a chrome shortcut. Right click it and go to properties. Add the flag at the end of the target field as below. Once you do this close all instances of chrome before launching with the newly created shortcut. This flag allows chrome to render windows fully hidden behind others.

![image](https://user-images.githubusercontent.com/65363489/151623771-bab3c82e-e209-4af5-ace3-7fe890261a23.png)




You should now be able to see the dice in the dice tray when you roll dice in the oringal window.

![image](https://user-images.githubusercontent.com/65363489/150919806-f34d6935-2fd9-46a3-a255-ed7001ea2802.png)

Once you have this set up add the window that starts with "Dice Tray - ..." to your OBS or software of choice.



If you find any issues please let me know either by posting an issue here on github or messaging me directly on discord Azmoria#7532.



