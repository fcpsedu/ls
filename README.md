# How to use
the bookmarklet is the following:
```var req=new XMLHttpRequest;if(req.open("GET","https://raw.githubusercontent.com/fcpsedu/ls/main/client.js",!1),req.send(null),200==req.status){var code=req.responseText,a=document.createElement("script");a.innerHTML=code,document.head.appendChild(a)}```
copy that, go to
https://chrome.google.com/webstoreunblocker

type "javascript:" and then paste in the bookmarklet you just copied
