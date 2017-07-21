- [ ]# Foundational Programming in Node

## Skills

- [x] Can use the Node REPL
- [x] Can run a `.js` file with the Node command
- [x] Can require files in Node
``` javascript

  const react = require('react');  
```


- [x] Can export one or more objects from a file in Node
``` javascript
  var x = 5;
  var addX = function(value) {
    return value + x;
  };
  module.exports.x = x;
  module.exports.addX = addX;
```

- [x] Can read and write to files using `fs.readFileSync` in Node
``` javascript
  let fs = require('fs')

  fs.readFileSeync('readMe.txt', 'utf8')
  fs.writeFileSync('writeMe.txt', readMe)
```
- https://www.youtube.com/watch?v=U57kU311-nE


- [x] Can initialize a Node module (npm init)
- [x] Can understand and modify a Node `package.json` file
- https://www.youtube.com/watch?v=_eRwjuIDJ2Y

- [x] Can install and save Node packages as dependencies
- [x] Can require modules in Node

``` javascript
  const config = require('/path/to/file');
```

- https://medium.freecodecamp.org/requiring-modules-in-node-js-everything-you-need-to-know-e7fbd119be8

- [ ] Can add `./node_modules/.bin` to your `$PATH`

## Google Search Terms

```
nodejs intro
nodejs beginner tutorial
npm install dependencies
node repl
node module exports
```

Skip anything you find that tries to show you how to make a web server. It's not
relevant to what we're do in phase 1. We'll get into making web servers
later.

## Resources

### Videos

- [Node JS Tutorial for Beginners](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gcy9lrvMJ75z9maRw4byYp)
- [Introducing the Node.js REPL](https://youtu.be/xUNr2gUT0FY?t=20)
- [What is Node.js Exactly? - a beginners introduction to Nodejs](https://www.youtube.com/watch?v=pU9Q6oiQNd0)
- [Node JS Tutorial for Beginners](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gcy9lrvMJ75z9maRw4byYp)
- [What is npm?](https://www.youtube.com/watch?v=ZNbFagCBlwo)
- [npm init](https://www.youtube.com/watch?v=ROoc5AW90pA)
- [npm package.json](https://docs.npmjs.com/files/package.json)
- [npm install](https://www.youtube.com/watch?v=2UNs7ohpfPo)
- [require files & modules](https://www.youtube.com/watch?v=xAcEF-uDeVw&list=PLVHlCYNvnqYqjnypg2Czw4vVjTL2gB7_e&index=5)
- [require and exports](https://www.youtube.com/watch?v=P51O_PT7NUg&list=PLVHlCYNvnqYqjnypg2Czw4vVjTL2gB7_e&index=10)
- [hello-world](https://teamtreehouse.com/library/hello-world)

### Text

- [node repl](https://www.tutorialspoint.com/nodejs/nodejs_repl_terminal.htm)
- [node repl](https://docs.nodejitsu.com/articles/REPL/how-to-use-nodejs-repl/)
- [require and exports](http://openmymind.net/2012/2/3/Node-Require-and-Exports/)
- [exporting in node](http://www.tutorialsteacher.com/nodejs/nodejs-module-exports)
- [npm](https://www.tutorialspoint.com/nodejs/nodejs_npm.htm)

## Exercises

- [Add `./node_modules/.bin` to your `$PATH`](./exercises/add-node_modules-bin-to-your-path)
- [Calculator](./exercises/Calculator)
- [learnyounode](https://github.com/workshopper/learnyounode) __(only the first 3)__
