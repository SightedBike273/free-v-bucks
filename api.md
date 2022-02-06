---
description: goPAPI
---

# API

Welcome to the docs for goPAPI!

{% hint style="success" %}
The base URL for our API is [`api.gopbot.xyz`](https://api.gopbot.xyz)``
{% endhint %}

Example get request in JavaScript (Using node-fetch)

```js
// Request data from the goPAPI in javascript using node-fetch
// don't forget to require and install node fetch https://www.npmjs.com/package/node-fetch
fetch('https://api.gopbot.xyz/player?username=example_change_me')
    .then(res => res.text())
    .then(text => console.log(text));
```
