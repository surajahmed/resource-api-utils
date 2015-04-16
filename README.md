
Resource Api Utils
============


Installation
------------

```sh
npm install resource-api-utils
```

Uses
----
```sh
var ResourceApiUtils = require('resource-api-utils/lib');

var Api = ResourceApiUtils.create('<route-name>');

```

Requests
--------

#Get:

```sh
Api.get(id).then(function(response) {
  //success 
}, function(error) {
  //error
});
```

#Post: 

```sh
Api.post(data).then(function(response) {
  //success 
}, function(error) {
  //error
});

```

#Put:

```sh
Api.put(id, data).then(function(response) {
  //success
}, function(error) {
  //error
});

