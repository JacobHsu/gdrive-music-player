Music Player for Google Drive
=============================

Music Player for Google Drive is a simple and lightweight online music player for your audio files stored in Google Drive. Its is entirely client side and does not require any server side component.

It's available [in the Chrome Web Store](https://chrome.google.com/webstore/detail/music-player-for-google-d/hnfeekfpnjbdmelcapngdgkjnhgijjkh) or you can simply visit www.driveplayer.com.

It looks like this:

![Music Player for Google Drive](https://github.com/nicolasgarnier/drive-music-player/raw/master/cws/screenshot_small_1.png)

It features open-with functionality from Google Drive:

![Open-with from Google Drive](https://github.com/nicolasgarnier/drive-music-player/raw/master/cws/screenshot_small_2.png)

As well as the following features:

  * Playback of MP3 files, MP4, OGG (Audio), WAV (very partial), ACC (iTune's .m4a files), webm (Audio).
  * Support for ID3 tags v1 and v2as well as AAC file Tags.
  * Automatic display of Album covers.
  * Handles users signed-in multiple Google account elegantly.
  * Open Audio files directly from the Google Drive UI.


> Note: This is not an official Google Product. This is a sample application demonstrating how to build a fully client side Google Drive application. It is currently deployed and running and is supported on a best effort basis.


### Google Developers Console 憑證

* 網路應用程式 用戶端 ID *

用戶端 ID `dmp.auth.CLIENT_ID `

已授權的 JavaScript 來源
http://localhost
http://jacobhsu.github.io

已授權的重新導向 URI
http://localhost/oauth2callback
http://localhost/gdrive-music-player/?oauth
http://jacobhsu.github.io/gdrive-music-player/?oauth

啟用 Google Drive API 

* 設定 *

dmp.auth.js

`dmp.auth.APPLICATION_ID`
`dmp.auth.CLIENT_ID `