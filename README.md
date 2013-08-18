oj-namespace
============

The Namespace constructor for OJ creates safe, automated set of interfaces to build a JavaScript Object which can manage the scope of your application's variables.

This standalone class is a self-executing anonymous function (an immediately invoked function expression, to be precise). Simply include it in your app (preferably first), and the OJ nameSpace will init. 

nameSpace.js takes a single argument, nameSpaceName, which defaults to 'OJ'. When included in an application, this will register an instance of 'OJ' (or your own name) on the global object. OJ also registers a $nameSpace$ member on the global object, which can be used to reference your nameSpace without needed to know its name. 

A more detailed API will follow.
