###What is iOS-SSL-KILLER ?

iOS-SSL-KILLER does the same thing as [iOS SSL Kill Switch](https://github.com/iSECPartners/ios-ssl-kill-switch), and core codes comes from `iOS SSL Kill Switch`. 

Introduction of `iOS SSL Kill Switch`: 
> Blackbox tool to disable SSL certificate validation - including certificate pinning - within iOS Apps

###What's the difference with `iOS SSL Kill Switch`？

`iOS-SSL-KILLER` do not require jailbreaked devices, hook SSL-related functions with [fishhook](https://github.com/facebook/fishhook)

###How to use?

Clone the code, build with your dylib project, inject the dylib into your app!
