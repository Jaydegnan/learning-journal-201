Today I learned about constructer functions and their benefits. They can be used used multiple times without having to redefine the object every time.
For example:

function Hat(style, color) {
  this.style = style;
  this.color = color;
  hats.push(this);
}

new Hat('baseball', 'blue');
new Hat ('trucker', 'orange/brown');
new Hat ('fedora', 'straw');
new Hat ('fez', 'velvet red');
}
