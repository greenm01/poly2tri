## Since there are no Input validation of the data given for triangulation you need to think about this. ##

  * Poly2tri was developed for use with simple polygons supporting simple holes and refinement points(steiner points).

  * Does not support repeat points within epsilon.

  * Points to close to an edge(constraint) can cause floating point issues due to the three points forming a degenerate triangle.

  * If you have a cyclic function that generates random points make sure you don't add the same coordinate twice.

  * If you are given input and aren't sure same point exist twice you need to check for this yourself.

  * Interior holes must not touch other holes, nor touch the polyline boundary

  * Use the C++ library in this order:
    1. Initialize CDT with a simple polyline (this defines the constrained edges)
    1. Add holes if necessary (also simple polylines)
    1. Add Steiner points if necessary
    1. Triangulate

Make sure you understand the preceding notice before posting an issue. If you have an issue not covered by the above, include your data-set with the problem.

If you need to make your polygons simple for use with poly2tri take a look at the clipper lib.

**The only easy day was yesterday; have a nice day.**