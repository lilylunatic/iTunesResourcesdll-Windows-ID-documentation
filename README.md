
# iTunesResources.dll

Extracting the contents of iTunesresources.dll to edit them and theme the application still works with [iTunes Skin Tools](https://github.com/Apophenic/iTunes-Skins-Windows) or other resource (de-)compilers.

The contents of the dll are a mess since old icons (that are not used in iTunes anymore) are still in there alongside with what looks like darkmode, even though  there is no darkmode on windows.

The Resource IDs in the [documentation](https://htmlpreview.github.io/?https://github.com/Apophenic/iTunes-Skin-Tools/blob/master/Resource%20IDs/ResourceIDs.html) provided for [iTunes Skin Tools](https://github.com/Apophenic/iTunes-Skins-Windows) is outdated for iTunes 12.11.x.

After hours of repeatedly killing iTunes, editing mages injecting them, and starting iTunes again I got this list of IDs.

## ID's:

- 1, 2, 2200, 15001, 15002 // iTunes logos
- 390, 391; 1642, 1643 unused play pause buttons
- 515 - play, 516 - play but reversed, 517 - pause, 518 - stop, 519 - rewind, 520 - forward // taskbar playback controls
- 522 - play, 523 - play but reversed, 524 - pause, 525 - stop, 526 - rewind, 527 - forward // taskbar playback controls when inactive
- 672-969 // small device images, used for devices pre-5th-gen video
- 1277, 1279, 1280, 1281, 1283, 1284, 1286, 1287 // Empty cover art for music movies, audiobooks, radio, genius and CDs
- 15019 // apple logo in the top portion
- 15021 // three dot menu in the top bar
- 15023 // shuffle top bar controls when a song is playing
- 15024 // repeat controls when a song is playing
- 15028 // top bar playback slider
- 15029 // sync progress bar
- 15035 // top bar now playing background
- 15037 // mini player button when no song is playing
- 15038 // miniplayer hover button
- 15044 // eject button on the CD page
- 15045 // blue circle three dot menu
- 15053 // three dot menu on individual tracks
- 15064 // icon used when drag and dropping files in iTunes
- 15080 - rewind, 15081 - forward, 15082 - play, 15083 - genius shuffle, 15084 - pause // play controls
- 15090 // volume slider
- 15116 // genius mix play/pause buttons
- 15119 // battery indicator
- 15244 // buttons used on the song info page, about iTunes, etc...
- 15245 // buttons used for the iPod Sync screen
- 15255 - left, 15256 - middle, 15257 - right // tab selectors (used in the album info screen)
- 15293 // volume adjust slider in the song options menu and in the maximum volume iPod setting
- 15313 // Ipod tab select background
- 15314 // Library-For You-Radio-Store select background
- 15049 // settings button found in the CD screen i.e.
- 15390, 15391 // album play pause buttons
- 15359 - general, 15360 - playback, 15361 - sharing, 15362 - store, 15363 - restrictions, 15365 - devices, 15366 - advanced, 15367 - downloads // Settings tab icons
- 15402 // progress circle
- 15466, 15467, 15468, 15469, 15473, 15474, 15475, 1576 // scrollbar arrows
- 15470 // scrollbar vertical
- 15477 // scrollbar horizontal
- 15567 // ipod setup screen
- 15610 - close, 15611 - minimize, 15612 - reduce down, 15613 - maximize // window controls (on windows 10, I don't kow if iTunes uses other resources on other windwos versions)
- 15663 // storage usage indicator
- 15687-15969 // big device images used in the device dropdown menu & device sync screen
- 16034 // mini player time slider
- 16208 // three dot menu in the album track view
- 17201 // apple logo displayed in about itunes

## Changing the device icon displays
**Mainline iPods**

- 1st/2nd gen // 18x13px
- 3rd/4th gen // 18x14px
- 5th gen // 48x36px
- 6th/7th gen // 50x38px

**Mini**

- 1st/2nd gen 19x14px

**Nanos**

- 1st/2nd gen // 34x24px
- 3rd gen // 62x45px
- 4th gen // 32x43px
- 5th gen // 33x51px
- 6th gen // 49x49px
- 7th gen // 38x68px

## Missing stuff / what I have not found yet

- the icons used in the application sidebar
- the blue song/gategory select background
- a lot of buttons 

## Example images

Custom top bar apple logo and miniplayer button

![Custom top bar apple logo and miniplayer button](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_top_bar_logo_and_miniplayer_button.png)

Custom iPod Video icon

![Custom iPod Video icon](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_iPodvideo_Icon.png)

Custom three dot circle menu

![Custom three dot circle menu](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_three_dot_circle_menu.png)

Custom three dot song menu

![Custom three dot song menu](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_three_dot_menu.png)

Custom about iTunes section (edited logos and buttons)

![Custom about iTunes section (edited logos and buttons)](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_buttons_and_icons_about_itunes.png)

Custom window controls

![Custom window controls](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_Window_Controls.png)

Custom empty CD cover

![Custom empty CD cover](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_Empty_CD_cover.png)

Custom top bar (playback controls and volume control slider)

![Custom top bar (playback controls and volume control slider)](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_top_bar.png)

Custom sync progress bar

![Custom sync progress bar](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_Sync_Progressbar.png)

Custom miniplayer (track slider and tab buttons

![Custom miniplayer (track slider and tab buttons)](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_tab%20buttons_and_track_slider_miniplayer.png)

Custom album play/pause button

![Custom album play/pause button](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_Album_play_button.png)

Custom genius mix play/pause button

![Custom genius mix play/pause button](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_genius_mix_pause_button.png)

Custom taskbar miniplayer controls

![Custom taskbar miniplayer controls](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_taskbarplayer_buttons.png)

Custom battery indicator

![Custom battery indicator](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_Battery_indicator.png)

Custom Settings tab icons

![Custom Settings tab icons](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_settings_tabs.png)

Custom iTunes file drag icon

![Custom iTunes file drag icon](https://raw.githubusercontent.com/Benji7103/iTunesResourcesdll-Windows-ID-documentation/main/screenshots/Custom_drag_file_icon.png)
