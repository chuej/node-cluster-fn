# cluster-fn
Run functions w/ nodejs cluster.

## Usage
```javascript
var clusterFn = require('cluster-fn');
var fn = function (){
  // worker operations
};
var cluster = clusterFn({numWorkers: 5, fn: fn});
cluster.start()
```
