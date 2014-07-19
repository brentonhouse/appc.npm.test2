This is a project created for testing using a locally installed npm package inside of alloy.jmk


Normally, I would not checkin the node_modules folder, but I did so in this case for demonstration purposes.

----------------------------------

The following is the command that is executed and the error that follows:

```
ti build -p mobileweb


module.js:340
    throw err;
          ^
Error: Cannot find module 'fs-extra'


```
