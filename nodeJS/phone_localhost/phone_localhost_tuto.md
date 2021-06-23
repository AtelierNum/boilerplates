# How to access to your localhost server on your phone
In order to display your web app on your phone, you'll need to have both devices connected to the same network. You'll have to type your computer ip and the right port on your default phone browser.
To know your computer ip adress, run in your terminal :
```
node ipadress.js
```

You'll see a similar message in your terminal. Change ``[yourlocahost]`` to your port: 
```
Enter 192.168.43.27:[yourlocalhost] on your phone
```

For example, the ``liveserver`` in VSCode use normally the port ``5500`` :
```
192.168.43.27:5500
```