Get the player's seat if they are in a vehicle.
_Note: Driver seat starts at -1 on client-side._

**Example Usage**

```js
const seat = player.seat;
if (seat === 1) {
    console.log('They are the driver');
    return;
}
```
