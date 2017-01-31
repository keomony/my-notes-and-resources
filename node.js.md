# node.js

##Links
- [How do I get started with node.js - stack overflow](!https://stackoverflow.com/questions/2353818/how-do-i-get-started-with-node-js/9629682#9629682)
- [Art of node - callbacks](!https://github.com/maxogden/art-of-node#callbacks)
- [nodeschool](!https://nodeschool.io/#workshoppers)
- [nodegirls express workshop](!https://github.com/node-girls/express-workshop)

##Code snippets

Single function module export

```javascript
// module.js
module.exports = function (args) { /* ... */ }

// main.js
var mymodule = require('./mymodule.js')
```

Idiomatic node.js callbacks

```javascript
function callback (err, data) { /* ... */ }
```