# the-log

*The Log is dead. Long live the Log!*

### Usage

```javascript
require('the-log');

console.log('echo'); // [2022-02-16T22:06:42.566Z] echo
```

### To-do

require('the-log')({ timestamp: true, stringify: true });

require('the-log')('{timestamp} {id} {log}');

require('the-log')((name, ...arr) => (arr.map(log =>({ timestamp, name, log })));
