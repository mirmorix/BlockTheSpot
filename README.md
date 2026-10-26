chrome_elf.dllchrome_elf.dll<center>
	<h1 align="center">BlockTheSpot</h1> 
	<h4 align="center">A multi-purpose adblocker and skip-bypass for the <strong>Spotify for Windows (64 bit)</strong> </h4>
    <h5 align="center">Please support Spotify by purchasing premium</h5>
    <p align="center">
        <strong>Last updated:</strong> 12 February 2026<br>
        <strong>Last tested version:</strong> see `config.ini`
    </p> 
</center>

### Virus warning on windows defender issue:
* The code is on Github, everyone can check it.
* false positive can happen. but don't trust me on this, try verify by compile your own BTS and compare with the release.

### Features:
* Focus mainly on block listening ads and performance, cosmetic aren't main purpose.

#### Experimental features from developer mode
- Click on the 2 dots in the top left corner of Spotify > Develop > Show debug window. Play around with the options.
- Enable/disable feature by yourself in realtime and on demand.

:warning: This mod is for the [**Desktop Application**](https://www.spotify.com/download/windows/) of Spotify on Windows only and **not the Microsoft Store version**.

#### Fresh installation
1. Browse to your Spotify installation folder `%APPDATA%\Spotify`
2. Rename `chrome_elf.dll` to `chrome_elf_required.dll`
3. Download `chrome_elf.dll` and `blockthespot.dll`from [releases](https://github.com/mrpond/BlockTheSpot/releases)
4. Put downloaded file from 3 to Spotify directory. 
5. Download latest [config.ini](https://github.com/mrpond/BlockTheSpot/blob/master/config.ini) from github to Spotify directory. 

#### Update from spotify
1. Browse to your Spotify installation folder `%APPDATA%\Spotify`
2. Delete `chrome_elf_required.dll` and `blockthespot.dll`
3. Rename `chrome_elf.dll` to `chrome_elf_required.dll`
4. Download `chrome_elf.dll` and `blockthespot.dll`from [releases](https://github.com/mrpond/BlockTheSpot/releases)
5. Put downloaded file from 4 to Spotify directory. 
6. Download latest [config.ini](https://github.com/mrpond/BlockTheSpot/blob/master/config.ini) from github to Spotify directory. 

### Uninstall:
1. Remove `chrome_elf.dll`, `blockthespot.dll` and `config.ini` from Spotify directory.
2. Rename `chrome_elf_required.dll` to `chrome_elf.dll`

or just reinstall Spotify

### Additional Notes:

* For more support and discussions, join our [Discord server](https://discord.gg/eYudMwgYtY).





