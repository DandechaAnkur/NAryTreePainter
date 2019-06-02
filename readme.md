NAryTreePainter
---------------

One can input array representaion of the tree and
this program will print how the tree would look.

By default, it outputs binary tree.
e.g., Enter "1 2 3 4 5" and hit enter and it will
print,

```
         1
        / \
       /   \
      2     3
     / \   / \
    4   5
```

To create a turnary tree enter "1 2 3 4 5 /b3" and
it will print,

```
          1
         /|\
        / | \
       /  |  \
      2   3   4
     / \ / \ / \
    5
```

In this way, one can use /bN for creating N-ary
trees.

To indicate an absent node just use ".", for
example, for "1 . 2 . . 3 4" and it will print,

```
         1
        / \
       /   \
            2
     / \   / \
          3   4
```

To hide the extra pipes use /h switch.
e.g., "1 . 2 . . 3 4 /h/b2" will print,

```
        1
         \
          2
         / \
        3   4
```

For some hands on please check **[this](https://adandecha.github.io/NAryTreePainter/tree_maker.html)** out!

Enjoy!
