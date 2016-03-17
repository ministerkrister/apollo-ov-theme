#OnlineVideos and Games Theme
This is a theme/mod for the excellent [Apollo](http://forum.team-mediaportal.com/forums/apollo.692/) skin for [Mediaportal](http://www.team-mediaportal.com/) and it comes with two OnlineVideos tab layouts and one Games tab layout that replaces the TV tab if enabled.

##Modes/Layouts
The OnlineVideos tab comes in two different modes, Normal and Alternative.
Configure in OnlineVideosThemeSettings.xml set the value #ovtheme.alt.mode to True for alternative mode.
You can also enable Games mode that replaces the livetv tab. Set the value of #ovtheme.games.mode to True for games mode
###Preview "Normal" mode
![Play BasicHome Preview](https://raw.githubusercontent.com/ministerkrister/apollo-ov-theme/master/OnlineVideos%20and%20Games%20Theme/Media/preview.png)
###Preview "Alt" mode
![Play BasicHome Preview](https://raw.githubusercontent.com/ministerkrister/apollo-ov-theme/master/OnlineVideos%20and%20Games%20Theme/Media/PreviewAlt.png)
###Preview "Games" mode
![Play BasicHome Preview](https://raw.githubusercontent.com/ministerkrister/apollo-ov-theme/master/OnlineVideos%20and%20Games%20Theme/Media/PreviewGames.png)

##Versions of Apollo supported:
* [v1.1.0.0](https://github.com/ministerkrister/apollo-ov-theme/releases/tag/v1.1.0.0)
* [v1.0.0.8](https://github.com/ministerkrister/apollo-ov-theme/releases/tag/v1.0.0.8.1) Also for Apollo v1.0.0.9
* [v1.0.0.7](https://github.com/ministerkrister/apollo-ov-theme/releases/tag/v1.0.0.7) 
* Older versions see [Apollo mods](http://forum.team-mediaportal.com/threads/mods.131153/) 

##Installation and configuration
Since v1.1.0.0: Download the [Apollo OnlineVideos and Games Theme_v1.1.0.0.mpe1](https://github.com/ministerkrister/apollo-ov-theme/releases/download/v1.1.0.0/Apollo OnlineVideos and Games Theme_v1.1.0.0.mpe1) file on the release page. 

When istalling you can choose to install:
* BasicHome tabs and tiles (basic functionality of the theme)
* Fanart and now playing in Rockstar (fanart available if fanart is enabled for all screens in Apollo skin settings)
* Thumb format in list views in Trakt 
* Some custom/alternative tile images
* LatestGames process plugin. Showing latest MyEmulators games in BasicHome. Install this if you are planning to use Games mode.

You can configure some properties by editing the OnlineVideosThemeSettings.xml file located in the theme folder.
* Name of the tab in BasicHome (default: play)
* Name of the OnlineVideos tile (default: OnlineVideos)
* Sites for the sites tiles. Defaults (Normal mode):
  * TV4Play
  * SVTPlay
  * Netflix
  * URPlay
  * Viaplay.se
* Sites for tiles. Defaults (Alternative mode):
  * YouTube
  * Netflix
  * SVTPlay
  * URPlay
  * Viaplay.se
  * Viasat
  * TV4Play
  * Dplay.se
* Change the image for each tile

##Features
* livetv is available in BasicHome if enabled in Apollo skin settings (new in v1.0.0.8)
* games tab is available in BasicHome instead of livetv if enabled in theme OnlineVideosThemeSettings file (new in v1.1.0.0)
  * Big tile opening MyEmulators
  * Tile starting Steam
  * A Custom tile
  * Two tiles with latest games, with hyperlinks to the game
  * Latest Games in the footer
  * You can configure all tiles except the latest tiles
* BasicHome configuration in OnlineVideosThemeSettings.xml (new in v1.0.0.8)
* Tile images for following sites:
  * TV4Play
  * SVTPlay
  * Netflix
  * URPlay
  * Viaplay
  * YouTube
* Latest online videos in footer
Rockstar (fanart available if fanart is enabled for all screens in Apollo skin settings)
