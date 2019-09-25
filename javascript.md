# JavaScript

## Call & Apply
They both try to run a function in different object, eg.

```
InstanceA.call/apply(InstanceB, args);
```

the only different is taht call accept serial of arguments, but apply use array as arugment.


```
InstanceA.call(InstanceB, arg1, arg2);
InstanceA.apply(InstanceB, [arg1, arg2]);
```

## Synchronous/Async

JavaScript is Async, eg, when we create a request call, it will continue run the next statement,
instead of waiting for the return from the server.

## let/var

Let create the scope control by curly block, while var controled by function block. eg.

```
// will trigger hoisting machanism
console.log(x);
var x=5;
console.log(x);
```

```
// will throw reference error
console.log(x);
let x=5;
console.log(x);
```

## Event Bubbling
