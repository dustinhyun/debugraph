# debugraph
Simple graph data visualization tool for debugging.

Had been frustrated in debugging a graph?

```
$ git clone THIS_REPOSITORY
$ cd debugraph
$ python -m SimpleHTTPServer 1234
```

Open http://localhost:1234/debugraph.html in your browser to see below.

![Snapshot](https://raw.githubusercontent.com/wiki/dustinhyun/debugraph/images/debugraph0.png)

Remember, the first line is for nodes seperated with space and the second line is for edges denoted as node-node.

You can also set a color for node as below.

![Snapshot](https://raw.githubusercontent.com/wiki/dustinhyun/debugraph/images/debugraph1.png)

Also with label.

![Snapshot](https://raw.githubusercontent.com/wiki/dustinhyun/debugraph/images/debugraph2.png)

Use (,labelName) if only label is to be added without color(Don't use space in label name).

![Snapshot](https://raw.githubusercontent.com/wiki/dustinhyun/debugraph/images/debugraph3.png)

Same for edges.

![Snapshot](https://raw.githubusercontent.com/wiki/dustinhyun/debugraph/images/debugraph4.png)

Edge with color and label:

![Snapshot](https://raw.githubusercontent.com/wiki/dustinhyun/debugraph/images/debugraph5.png)
