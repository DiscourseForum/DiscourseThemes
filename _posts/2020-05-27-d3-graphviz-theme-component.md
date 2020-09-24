---
title: D3 Graphviz Theme Component
author: Magnus Jacobsson
homepage: https://github.com/magjac/discourse-d3-graphviz
download: https://github.com/magjac/discourse-d3-graphviz
demo: 
thumbnail: 
license: MIT License
license_link: https://github.com/magjac/discourse-d3-graphviz/blob/master/LICENSE
category: Theme Components
meta_topic_id: 153031

---
The [D3 Graphviz Theme Component](https://github.com/magjac/discourse-d3-graphviz) allows you to add animated [Graphviz](https://www.graphviz.org/) graphs to your post using the [DOT](https://www.graphviz.org/doc/info/lang.html) language. Based on [d3-graphviz](https://github.com/magjac/d3-graphviz).

**Repository:** https://github.com/magjac/discourse-d3-graphviz

### Installation
See [How do I install a Theme or Theme Component?](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682)

### Usage

#### Static graphs

This is just a brief introduction. You may want to read the detailed https://forum.graphviz.org/t/render-graphviz-graphs-directly-in-your-posts/125 which shows the theme component in action or join the [Graphviz fourm](https://forum.graphviz.org/) where you can use it yourself.

To render a graph inline in your post, wrap the graph definition in `dot` tags like this:

```
[dot] digraph {a -> b} [/dot]
```

The block form is also supported:

```
[dot]
digraph {
  a -> b
}
[/dot]
```

#### Animated transitions between graphs

An animated transition between multiple graphs is shown when more than one graph is added to the same paragraph of a post and there is only whitespace between them:

```
[dot] digraph {bgcolor=lightblue a -> b} [/dot]
[dot] digraph {bgcolor=lightblue a -> b; a -> c} [/dot]
[dot] digraph {bgcolor=lightblue a -> b; a -> c; b -> c} [/dot]
```

or

```
[dot]
digraph {
  a -> b
}
[/dot]
[dot]
digraph {
  a -> b
  a -> c
}
[/dot]
[dot]
digraph {
  a -> b
  a -> c
  b -> c
}
[/dot]
```

Paragraphs are separated by blank lines, so this will generate three separate graphs:

```
[dot] digraph {bgcolor=lightblue a -> b} [/dot]

[dot] digraph {bgcolor=lightblue a -> b; a -> c} [/dot]

[dot] digraph {bgcolor=lightblue a -> b; a -> c; b -> c} [/dot]
```

### Options

The graphs and the animated transitions are highly customizable by options that you can add to the `dot` tag. See https://forum.graphviz.org/t/render-graphviz-graphs-directly-in-your-posts/125.