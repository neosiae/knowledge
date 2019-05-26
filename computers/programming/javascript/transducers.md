# Transducers

> Transduce: to convert/transform (something, such as energy, data or a message) into another form.

Transducers are composable higher order reducers which can reduce over any underlying data type.

Transducers produce code that can be orders of magnitude more efficient than dot chaining with arrays, and handle potentially infinite data sets without creating intermediate aggregations.

Transducers aren’t always faster than built-in array methods. The performance benefits tend to kick in when the data set is very large (hundreds of thousands of items), or pipelines are quite large (adding significantly to the number of iterations required using method chains).

In production, we can use transducers from [Ramda](https://ramdajs.com/), [RxJS](https://github.com/ReactiveX/rxjs) or [transducers-js](https://github.com/cognitect-labs/transducers-js).

## See Also

- [Transducers: Efficient Data Processing Pipelines in JavaScript](https://medium.com/javascript-scene/transducers-efficient-data-processing-pipelines-in-javascript-7985330fe73d)
