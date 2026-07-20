# Slingshot
A simple and elegant Plymouth theme with OEM logo on top, OS logo below and a bouncing/growing bar at the bottom.


## Note
After installation, you might want to change ```watermark.png``` with an image of your distro's logo, but it needs to have the same name. The default one is CachyOS.

## Installation
Installation is simple:
1. Install Plymouth if you haven't already (command for installation depends on your distro)
2. Copy the ```slingshot``` folder into ```/usr/share/plymouth/themes/```, you can do it with this command:
   
   ```
   sudo cp ./slingshot /usr/share/plymouth/themes
   ```

3. Apply the theme:

   ```
   sudo plymouth-set-default-theme -R slingshot
   ```

   Alternatively, you might be able to do it in your system settings, but it's recommended to use the above command.

---

## Known issues to fix and stuff to be added
- Fade-out could also apply to OEM and OS logos and not only on loading bar
- Shutdown, reboot and all options other tham boot-up should be able to play only the throbber animation and not the final animation

