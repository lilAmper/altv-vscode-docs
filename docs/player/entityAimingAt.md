Get the vehicle, player, etc. that the player is aiming at.

**Example Usage**

```js
const target = player.entityAimingAt;

if (target !== someOtherPlayer) {
    // not aiming at the player we are looking for
    return;
}

// is aiming at the player we are looking for
```
