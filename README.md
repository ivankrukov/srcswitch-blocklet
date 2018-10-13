# srcswitch-blocklet
An i3bar blocklet that shows the currently running pulseaudio audio sink and allows dynamic switching on blocklet click
## Configuration
To use this blocklet, add the following lines to your i3blocks.conf file:

```bash
[sourceswitch]
command=/path/to/srcswitch "$BLOCK_BUTTON"
interval=5
```
