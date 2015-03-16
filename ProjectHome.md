**Based on the paper "Sweep-line algorithm for constrained Delaunay triangulation" by
V. Domiter and and B. Zalik**

Officially supported langs: [C++](http://code.google.com/p/poly2tri/source/checkout), [Java](http://code.google.com/p/poly2tri/source/checkout?repo=java)

[BASIC INSTRUCTIONS](http://code.google.com/p/poly2tri/wiki/README?ts=1328629791&updated=README)

![http://poly2tri.googlecode.com/files/dude_cdt.png](http://poly2tri.googlecode.com/files/dude_cdt.png)

Community based langs (unsupported):
  * [AS3](http://code.google.com/p/poly2tri/source/checkout?repo=as3)
  * [C](http://code.google.com/p/poly2tri-c)
  * [C#](http://code.google.com/p/poly2tri/source/checkout?repo=cs), [C#(basic)](https://github.com/MaulingMonkey/poly2tri-cs)
  * [Go](http://code.google.com/p/poly2tri/source/checkout?repo=golang)
  * [Haxe](http://github.com/nerik/poly2trihx)
  * [Javascript](https://github.com/r3mi/poly2tri.js)
  * [Python](http://code.google.com/p/poly2tri/source/checkout?repo=python)
  * [Ruby](http://github.com/mieko/rbpoly2tri)

Try it out online: click [me](http://r3mi.github.io/poly2tri.js/) or [me](http://nerik.github.io/poly2trihx/)!

Image
[01](http://java.poly2tri.googlecode.com/hg/resources/screenshots/quad_screen_01.png)
[02](http://java.poly2tri.googlecode.com/hg/resources/screenshots/quad_screen_02.png)
Video
[poly2tri-java](http://www.youtube.com/watch?v=Bt1TYzzr2Rg)

Seidel's Triangulation Algorithm in [Python](http://code.google.com/p/poly2tri/source/browse/python/seidel.py?repo=archive&r=5ad6efedc1c120ea194bbce2a0d4ed849e6e6903)

If you want to triangulate complex or weak polygons you will need to prepare your data
with a polygon clipping library like:<br>
<a href='http://sourceforge.net/projects/polyclipping/'>Clipper</a>(C++, C#, Delphi)<br>
<a href='http://sourceforge.net/projects/jsclipper/'>Javascript Clipper</a><br>
<a href='https://github.com/dmac100/clipper'>Java Clipper</a>