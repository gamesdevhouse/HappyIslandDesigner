# Happy Island Designer (Alpha)


## Features

* autosave
* undo/redo
* zooming
* Choose between flat icons or high quality renders for building icons
* Save an image of a map and load the image back in to recover your map (the map data is encoded in the image)
* Click the tool icon a second time to hide the pop out tool menu
* Brush size selector
* Line toggle buttons
* Mobile - pinch to zoom and two finger swipe to scroll

### Hotkeys

* Hold `SHIFT` to draw straight lines
* Hold `ALT` and click a color to switch to it
* Hold `ALT` and scroll to zoom
* Hold `SPACEBAR` and drag to pan

## Known Issues

**Note that if you edit/compress the saved image, the encoded data will get corrupted.** If you're sharing a map, make sure to use an image host that doesn't compress the image.

The UI isn't really optimal for mobile, but at least it works.

The UI will be cut off if you hold your phone in landscape mode.

## FAQ

### The browser crashes every time I open it!

The autosave file might be corrupted. Open the browser console (hit `F12`) and run this command `editor.clearAutosave()` to remove your autosave file.

## Future Enahancements

* Choose from multiple starting templates
* All the icons
* Island name banner
* Text labels
* UI overhaul
* Isometric view??

## Contribute

Please let me know if something isn't working or if you have any feedback!

### Sprites

I am in dire need of icons for all the buildings/plants. If any of you have nice looking icons and are willing to share, I'd like to use them (and of course give you credit).

### Maps

People could help me by recreating these 24 maps and sending me the map data, either by sending me a non-compressed version of the image file or pressing `/` and grabbing the map data that will be output in the browser console. Then I can offer all of these templates in a menu.

![base maps](/docs/base-nh-maps.png)

