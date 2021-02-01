### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry) {
    if (availableTime < 20) {
      console.log('You need to grab something quick and eat at your desk!');
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log('You deserve a break pre-order from that new local street food spot and quickly pick it up, remember your mask!');
    } else if (availableTime > 30) {
      console.log('You are in bootcamp I doubt you have more than 30 minutes for lunch eat quickly and get back to it!');
    }
  } else {
    console.log('You are not hungry and don\'t need a break! Get back to work!');
  }
};
```
