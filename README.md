ng-randomid
===========

Generate random id strings as an angular factory - packaged as component

## installation

```
$ component install binocarlos/ng-randomid
```

## usage

```js
angular.module('myApp', [
	require('ng-randomid')
])

.controller('MyAppCtrl', function($scope, $randomid){

	$scope.id = $randomid(12);

	// $scope.id = 'ejeh3n3nm28d';
})

```

## $randomid(char_count)

Return a random id with the given number of characters



## license

MIT