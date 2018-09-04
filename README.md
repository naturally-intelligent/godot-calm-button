# godot-calm-button
A Calm Texture Button for Godot 3+

Included is a scene for a widget that inherits TextureRect.  It's 'calmer' than the regular TextureRect.  It may not be applicable for all usage, and it needs some improvement for touch.

To use, copy or link the "widget" folder and then use the Instance button in Godot to create a new button.  You must set Normal, Pressed, and Hover textures for the button to be of use.  Usually you're going to use this for highly graphical buttons, like a person who turns to look at you when you hover/click, or a door that opens when you hover on it.  Then, the calm button will help make such a button less glitchy.  Regular TextureButtons will be very quick to change when the cursor moves on/off the button, which can ruin the graphical experience of your game/app.  

Once instanced, you can set the "hover_time" inside the "Script Variables" above the regular TextureButton settings to make the calming effect shorter or longer.

TODO:
- Add another delay to make it a bit calmer after returning to unfocused state and user immediately refocuses 
- Improve for touch events (how?)

Feel free to use in any project and also please return any improvements to this repository!

GAMES USING CALM BUTTON:

- Lemkin (www.lemkin.ca).  
