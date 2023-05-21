### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry) {
    if (availableTime < 20) {
      console.log("Eat it in the lab");
    } else if (availableTime < 30) {
      console.log("Try a place nearby");
    } else {
      console.log(
        "You're in a bootcamp so reconsider how much time you actually have to spare"
      );
    }
  } else {
    console.log("Get back to work");
  }
};
```
