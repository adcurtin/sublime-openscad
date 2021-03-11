I've tweaked the sublime completions a little bit for how I use openscad.
I've converted the language definition to sublime-syntax format

I fixed nested parenthesis so they work a lot better. e.g. `translate([(length + width)/2, 0, 0]);` is now highlighted correctly.


```
ln -s `pwd` ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/OpenSCAD
```







derivative of https://www.thingiverse.com/thing:235558, which itself is a derivative of https://www.thingiverse.com/thing:119350