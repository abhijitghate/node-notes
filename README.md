# node-notes
Handy notes and code fragments related to NodeJS and other JavaScript stuss



For updating node to the latest version [ found here ](https://askubuntu.com/questions/426750/how-can-i-update-my-nodejs-to-the-latest-version)
```
sudo npm cache clean -f
sudo npm install -g n
sudo n stable

```

Restart the terminal to see the version upgrade


## Global objects 

`setTimeout()`, `clearTimeout()`, `setInterval()`, `clearInterval()` are global objects in JavaScript

`window` object is defined for global scope for a browser. We can access all these objects via `window` object.

Similarly in node, we have an object named `global` that gives us the access to global objects of node.


## Loading a `module`

We should always use `const` with `require(...)` method and not `var`

