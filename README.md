Hale
====

Support for minimalist scientific visualization.

The main purpose of this library is to be a bridge between Teem and OpenGL3,
and to simplify writing programs that use Teem and OpenGL3.

We also want to make it easy to create a window that views a 3D scene,
so we rely on GLFW3 for window creation and event handling.

Describing where things are in 3D is facilitated by a vector math
library, so we go with GLM as a path of least resistance.  With time
and experience we may also include dependencies on AntTweakBar, or
some other GL-based widget toolkit. The hope is that Hale will
gradually subsume code from Gordon's "Deft" project (which is dead
because [FLTK2 is dead](http://www.fltk.org/articles.php?L825)).

To build Hale you'll need to first install:

1. Teem (checkout from source):

   svn co https://svn.code.sf.net/p/teem/code/teem/trunk teem
   and follow info at http://teem.sourceforge.net/build.html
2. GLFW3: http://www.glfw.org
3. GLM: http://glm.g-truc.net


Hale has been written by [Gordon
Kindlmann](http://people.cs.uchicago.edu/~glk/) based in part on code
examples written by [Roman Amici](https://github.com/roman-amici).
