Get if the player is currently using their voice.

**Example Usage**

```js
alt.everyTick(() => {
    if (alt.Player.local.isTalking) {
        alt.log('You are currently talking!');
    }
});
```

_alt.Player.local can also be a **player instance** from server_
