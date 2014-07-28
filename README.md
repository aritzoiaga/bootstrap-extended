bootstrap-extended
==================

```
bower_components/
	|-- bootstrap/
	|-- bootstrap-extended/
less/
	|-- variables/
	|   |-- bootstrap-variables.less
	|		|-- bootstrap-extended-variables.less
	|		|-- variables.less
	|-- mixins/
	|-- |-- mixins.less
	|-- bootstrap.less
	|-- bootstrap-extended.less
	|-- main.less
```


**bootstrap-variables.less**


**bootstrap-extended-variables.less**


**variables.less**

```
@import "bootstrap-variables.less";
@import "bootstrap-extended-variables.less";

// Own variables ...
```


**mixins.less**

```
@import "bower_components/bootstrap/less/mixins.less";
@import "bower_components/bootstrap-extended/less/mixins.less";

// Own mixins ...
```


**bootstrap.less**


**bootstrap-extended.less**

```
@import "variables/variables.less";
@import "mixins/mixins.less";

// Bootstrap-Extended Less files ...
```


**main.less**

```
@import "bootstrap-extended.less";

// Own styles ...
``