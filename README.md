<h1 align="center" style="margin-top: 0px;"> OpenMW Enhanced </h1>
<hr>
<p align="center" dir="auto">
  <a href="https://discord.gg/gDDnzsyY9u" rel="nofollow">Discord</a> |
  <a href="https://ko-fi.com/leokhi" rel="nofollow">Ko-fi</a>
</p>
<hr>

OpenMW Enhanced is a Wabbajack version of the [Total Overhaul](https://modding-openmw.com/lists/total-overhaul/) modlist (and credits to Johnnyhostile for that!) and is as close as a 1:1 to that modlist. With some small additions and removals from myself.

OpenMW Enhanced overhauls everything, graphics have been revamped and replaced along with tons of extra content, ranging from Tamriel Rebuilt and Skyrim: Home of the Nords.
## Installation
- Requires Steam version of Morrowind. Releases from GOG are **not supported**
- If you have used 1.0 you may have to do a fresh install if it doesn't work. I'm looking into this.

Before downloading the modlist, make sure you have a folder dedicated for the modlist.
Once you've finished downloading, there are a few things you will want to do before running it for the first time.
1. Download [Wabbajack](https://www.wabbajack.org/)
2. Download the latest .wabbajack file from the [releases page](https://github.com/LeArby/OpenMW-Enhanced/releases)
3. Create a new folder named `mwenhanced` in your OpenMW installation folder. 
4. Run Wabbajack and load the .wabbajack file from #2. This will install all the mods
5. In your root OpenMW folder, run 'openmw-wizard.exe'. Select the 'From existing' option, then point it to `mwenhanced\Stock Game folder\Data Files\morrowind.esm`
6. In your root OpenMW folder, run `openmw-launcher.exe` and press skip installation. In the launcher you can tinker around to your desired settings. Some to note are the resolution, shadows, draw distance and so forth.
7. In your `C:\Users\<YOUR USERNAME>\Documents\My Games\OpenMW` folder, find the `settings.cfg` file and add the following to it:
```
[Groundcover]

enabled = true   
density = 1.0  
stomp mode = 2  
stomp intensity = 2
```
8. In the folder you created during step #3, run `organizer.exe` and click play



Enjoy!
This is the only time you need to do this. I will get a better way to do this eventually.

## Credits

Thank you for johnnyhostile for creating the manual modlist, this wouldn't have happened without you.

Thank you to Salty and Lulzed for being amazing testers and spending time to make sure it's a quality product.

And you.

