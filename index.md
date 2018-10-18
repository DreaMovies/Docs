# Welcome to DreaMovies App Docs

In this doc you will be able to see what our goals are for the app and what is the status and possibilitys for the app. 

## Idea

The idea for the app is to be able to search, see, listen and share media with your friends without the need to have multiple apps or that the distance between you to prevent from seeing that episode or that movie that you are talking about for so long. 


## Core App

The core app will have the mainly functions so any plugin can require them and work.

 - Torrent content list
 - Torrent download and stream
 - link with video, image, sound or iframe will be displayed
 - Ability to chat with anyone that has the unique ID link
 - API reader by config provider:
   - Videos, Sounds (even Iframes)
   - Chat
   - Torrent
 - Local Library viewer
 - Automatic information finder:
   - Subtitles
   - Movies, Tv Shows and Music

### Plugins System

The plugin system will give the oportunity for anyone with an idea or to anything that already exists, to use the app as a place to the end user and what they want to see.

**Package Folder**
```
  - plugin_folder
    - config.json
    - index.js
    - view.js
    - assets
      - images
        - mini-logo.png
        - logo.png
```
