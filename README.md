# node-red-contrib-function-inject

A inject node which gets it's data from a function call.

E.g.

Add custom data to a message outside of payload (normal inject adds all json data to payload).

```
return {
    payload:"home",
    data: {
        old_state: {
            state:"not_home"
        }
    }
};
```
