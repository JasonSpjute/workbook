# Day-3
__12/16/2020__

## What are the two common operations that we will set in the handler?

The get operator returns a value stored in a key in an object. The set operator will assign a value to a property in an object.

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?

The value becomes undefined because by default, get is supposed to return the value stored in the object. Since we went around it's default, it returns undefined. We must pass the object and property parameters through the get function. We must then return property of the objec "obj[prop]" in order to make sure the value does not become undefined.

## WHat are some of the benefits of the proxy object that we are using in our structure for applications?

Security is one benefit. If we create a proxy to override the get operator, we can prevent people from accessing certain properties. We can also use it to add custom validation before setting a value. We can throw an error if the value does not meet the validation requirements