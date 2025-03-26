# audio controller for rainmeter  

a lightweight and customizable audio controller skin for rainmeter that detects all audio sources and allows control over volume, playback, and media info.  

## features  
- **customizable appearance** – change font, size, color, and position
- **multi-source detection** – detects and controls all audio sources (via [nowplaying](https://docs.rainmeter.net/manual/plugins/nowplaying/) plugin)
- **album art/thumbnail support** – displays media thumbnails (if available)
- **playback controls** – play/pause, next/previous track, and volume slider
- **adjustable window size** – resize via `.ini` settings
- **lightweight** – low system resource usage

## installation  
1. download the `.rmskin` package or clone this repository.  
2. double-click the file to install via rainmeter **or** manually place the skin folder in:   ```Documents\Rainmeter\Skins\```
3. refresh rainmeter and activate the skin.  

### basic settings  
```ini  
[variables]  
fontface=segoe ui          ; font family  
fontsize=12                ; font size  
textcolor=255,255,255,255  ; rgba color  
positionx=100              ; x-axis position  
positiony=100              ; y-axis position  
width=300                  ; skin width  
height=150                 ; skin height  
showthumbnail=1            ; 1=show album art, 0=hide  
