[![Build Status](https://travis-ci.org/duereg/no-cliches.svg?branch=master)](https://travis-ci.org/duereg/no-cliches)
[![devDependencies](https://david-dm.org/duereg/no-cliches/dev-status.png)](https://david-dm.org/duereg/no-cliches#info=devDependencies&view=table)
[![NPM version](https://badge.fury.io/js/no-cliches.svg)](http://badge.fury.io/js/no-cliches)

# No Clichés

npm module for checking for clichés in your writing.

## Install

```shell
npm install no-cliches
```

## Use

```javascript
var complexity = require('no-cliches');

var problems = complexity('Writing specs puts me at loose ends.');
// problems -> [{ match: "at loose ends", index: 22, offset: 12 }]
```

##See Also

[Concise Writing](http://grammar.ccc.commnet.edu/grammar/concise.htm)

## License

MIT