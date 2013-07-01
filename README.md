DEPRECATED!
===========

This project is deprecated! All activity has moved to a much-more usable Python library called [PyWavefront](https://github.com/greenmoss/PyWavefront).

pyglet obj test
===============

Test importing .obj files into pyglet. Derived from `contrib/model/examples/obj_test.py` in the pyglet directory. I'm making a git repository to figure out how to make this work generically with [NotOrion](https://github.com/greenmoss/NotOrion)

Usage
=====
Install python, then `pip install hg+https://pyglet.googlecode.com/hg/`. As of December 30, 2012, that is version 1.2alpha1.

- To see an example: `./display.py rabbit.obj`

## Texture Example

The following presumes you are using [Blender](http://www.blender.org/) to generate your mesh:

 - Using Blender, create a mesh with a UV-mapped texture. The UV-mapping is important! If it is working properly, you will see the texture applied within Blender's 3d view.
 - Export the mesh from Blender using the Wavefront format, including normals.
 - Run `display.py your_exported_mesh.obj`
