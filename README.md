markdown+mathjax
================
Live markdown editor based on MathJax and Marked


## How it works?

text → Escape tags → MathJax → Markdown (only for each text node) → preview


## Demo

http://kerzol.github.io/markdown-mathjax/editor.html



## Dependencies

- https://github.com/chjj/marked
- http://cdn.mathjax.org/mathjax/latest/MathJax.js


## Install

You should initialize and fetch
[marked](https://github.com/chjj/marked) into _lib/_.
Just type in the terminal:

```bash
    cd lib
    git submodule init
    git submodule update
```

We use MathJax from http://cdn.mathjax.org/. 
If you don't like that you need to read and modify _editor.html_

