# torrent2googledrive
Download torren to you google drive
Open in colabr

Don`t sleep, use script in console browser:

```javascript
function ConnectButton(){
    console.log("Connect pushed"); 
    document.querySelector("#top-toolbar > colab-connect-button").shadowRoot.querySelector("#connect").click() 
}

var colab = setInterval(ConnectButton,60000);
```
