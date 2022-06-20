---
title: Express JS - Set Up 404 Error Page
description: Here is the Code to Setup 404 Error page in Express.js.
date: 2022-05-27
tags: 
  - NodeJS
  - Tech
---

Here is the Code to Setup 404 Error page in Express.js.

```js
app.use('/', function(req, res) {
    res.status(404).json({
        error: 1,
        message: '404 Not Found'
    });
});
```
