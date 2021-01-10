# Day-3

__1-6-2021__

## What is the purpose of async / await?

Async / await was built to make callbacks and promises even simpler. They are a combination of promises and generators that get around problems with chaining promises.

## What must you do in order to await a promise inside of a function?

You must define the function as async. This can be done by adding the word async in front of the function.

## What are some of the primary benefits of async / await?

Async / await makes code easier to read vs the chaining of promises. You can also do multiple async funtions in a series. Debugging gets easier because async/await looks like synchronous code to the compiler.