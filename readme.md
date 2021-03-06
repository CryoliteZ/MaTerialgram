
<img src="images/banner.png" >

*Experience Telegram with the new Material Design, dark and light, clean and simple*

![](https://img.shields.io/chrome-web-store/users/aebgckccbkgbeigkkdglihleeipanoan?label=Chrome%20users&style=flat-square) ![](https://img.shields.io/amo/users/{12f08274-4477-477c-8482-9d7ed0cc6987}?color=FF6611&label=Firefox%20users&style=flat-square) ![](https://img.shields.io/chrome-web-store/rating/aebgckccbkgbeigkkdglihleeipanoan?label=Rating&style=flat-square) 
## Install Extensions

|Platform|Link|
|:-:|:-:|
|[<img src = "https://i.imgur.com/zv5G8Ly.png" width="30px">](https://chrome.google.com/webstore/detail/aebgckccbkgbeigkkdglihleeipanoan)| [Chrome Extension](https://chrome.google.com/webstore/detail/aebgckccbkgbeigkkdglihleeipanoan)|
|[<img src = "https://i.imgur.com/M6KOVju.png" width="25px">](https://addons.mozilla.org/en-US/firefox/addon/materialgram/)| [Firefox Extension](https://addons.mozilla.org/en-US/firefox/addon/materialgram/)|

## Demo
<img src="images/demo.gif">

## About MaTerialgram
This project is inspired by the recently redesign of [Android Messages Web](https://messages.android.com/). Aims to redesign Telegram web while following the new Material design guideline (or so-called Material Design 2). 

You can simply toggle between the dark and light theme by clicking the switch from the extension.

If you want to make some tweaks, you can modify and build the css by

```
sass material-theme.scss:material-theme.css --no-source-map 
```

Feel free to open issues or pull requests!

## Screenshots

### <img src="icons/icon-dark.png" height="20px"> Dark Theme
<img src="images/dark-theme.png">

### <img src="icons/icon-white.png" height="20px"> Light Theme
<img src="images/light-theme.png">

### Switch
<img src="https://i.imgur.com/Qdy9nuv.pngg">

## Privacy
This extension **DO NOT** read or save any of your conversations 

This extension is built with mainly pure CSS, the only scripts([script.js](script.js) & [popup.js](popup/popup.js)) are for toggling between themes

## License
[MIT](LICENSE)
