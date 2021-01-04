# Day-4
__12/17/2020__

## What problems does the Obeserver Pattern seek to solve?

The observer pattern helps to keep a bunch of elements synced with the same data. It enables one to many data binding between elements that allows you to build reusable code.

## What are the three mechanisms of the observer pattern?

The subscribe method adds observable events.
The unsubscribe method removes observable events.
The broadcast method executes all events with the data.

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

The proxystate is a proxy of the appstate. If you are getting data from it, it will run through isValidProp() first to determine if it is a valid property. If it is not, it returns an error. If it is, it returns the target[property]. If you are setting new data, it will fist run isValidProp. It will return an error if it is not a valid property. Then it sets the property's value in the object. From there it will run it through the event emitter. The event emitter broadcasts the data to any functions that have access to it.