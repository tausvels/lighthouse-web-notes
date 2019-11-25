### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

``` javascript
const whatToDoForLunch = function(hungry, availableTime) {
  //console.log("I don't know what to do!");
  (hungry) ? (
    (availableTime <= 20) ? (console.log('Pick up something and eat in kictchen.')) :
      (availableTime <= 30) ? (console.log('Try out a place in Gastown.')) :
        (console.log('You are in bootcamp and you should reconsider.'))
  ) : (
    console.log('Go do codeing')
  );
};
```