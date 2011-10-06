# timeago

A wrapper for John Resig's [Pretty Date function](http://ejohn.org/blog/javascript-pretty-date/).

![timeago](http://i.imgur.com/W1Zwy.png)

#install

    npm install timeago

#usage

    var timeago = require('timeago');

    var pretty = timeago(+new Date());

    console.log(pretty); // just now

You can also use it in Express app templates:

    var app = express.createServer();

    app.helpers({
      timeago: require('timeago')
    });
