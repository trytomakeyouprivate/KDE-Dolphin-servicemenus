# KDE: Dolphin appstarters and servicemenus

Dolphin allows service menus for everything! I created a lot, here are they.

## Dolphin extensions
Copy them to `/home/USERNAME/.local/share/kservices5/ServiceMenus` and restart dolphin.

The appstarters for Dolphin extensions hanlde the file, icon, display and what is executed. But the actual command needs to be ran in a different folder, as a shell script.


## Direct appstarters
You can copy them to `/home/USERNAME/.local/share/applications` and they appear as normal Apps. If you want to open a certain file type with them, right click on the file, "open with", and choose the appstarter. This modifies the "Mimetype" tag (open the .desktop file with a text editor to read it), you can use this to find out the correct name for the file you want to open.

---

Note: By focussing only on folders in `~/` (`/home/USERNAME`) this works on every Linux distro without sudo rights.
In general its good practice to use `root` access as little as possible, with ***immutable Operating Systems*** like ***Fedora Silverblue/Kionite*** or ***VanillaOS*** (Ubuntu) being popular ones.
