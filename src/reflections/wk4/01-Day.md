# Day-1
__1-4-2021__

## What are some of the signs and causes of Callback Hell?

A couple signs of callback hell are a pyramid shape and several }) at the end of your code. It is caused by code that is written to execute from top to bottom.

## What does the asynchronous mean and how are callbacks involved?

Async means to take some time. Instead of returning a result immediately, these functions will take extra time, usually because they have to download, access databases, or read through files. A callback stores the code that should run after the async function finishes it's task.

## Summaraize the 3 ways to avoid/ fix Callback Hell.

- Keep your code shallow. Naming your functions will make code easier to read. This allows you to reference your functions at the top of the page and declare them at the the bottom.
- Modularize. Break your code up into smaller modules that each do one thing.
-Handle every single error. Make sure that if there is an error, it will alert you to this.