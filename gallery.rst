.. title:: Glump gallery

.. role:: header
   :class: h4


Gallery
=======

.. container:: lead

   Some screenshots from the glumpy examples directory.


.. container:: row

   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/fireworks.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/fireworks.png

         .. container:: caption

            :header:`Fireworks`

            This example demonstrates simulation of fireworks using point
            sprites and has been adapted from the `OpenGL ES 2.0 Programming
            Guide <http://opengles-book.com/es2/index.html>`_.

            .. raw:: html

               <a type="button" class="btn btn-primary btn-xs"
               href="https://github.com/rougier/glumpy/blob/master/examples/fireworks.py"/>
               <span class="fa fa-github"></span> Sources </a>

               <button type="button" class="btn btn-danger btn-xs">
               <span class="glyphicon glyphicon-film"></span> Movie</button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/galaxy.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/galaxy.png

         .. container:: caption

            :header:`Spiral galaxy`

            This is a simulation of a galaxy using the density wave theory as
            explained by Ingo Berg. All simulation details can be found on `his
            site <http://beltoforion.de/galaxy/galaxy_en.html>`_.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources
               </button>

               <button type="button" class="btn btn-danger btn-xs">
               <span class="glyphicon glyphicon-film"></span> Movie</button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/voronoi.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/voronoi.png

         .. container:: caption

            :header:`Voronoi diagrams`

            This example shows dynamic voronoi based on an `old technique
            <https://wwwx.cs.unc.edu/~geom/papers/documents/technicalreports/tr99011.pdf>`_
            where the hardware is used to compute the diagram using 3D occluded cones.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources
               </button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/high-frequency.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/high-frequency.png

         .. container:: caption

            :header:`High-frequency signal`

            This example explains how to plot high-frequency functions by
            resampling the signal. More details on the `Syntopia
            <http://blog.hvidtfeldts.net/>`_ website and `Shadertoy
            <https://www.shadertoy.com/view/4sB3zz>`_

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources </button>

               <button type="button" class="btn btn-danger btn-xs">
               <span class="glyphicon glyphicon-film"></span> Movie</button>



   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/geometry-surface.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/geometry-surface.png

         .. container:: caption

            :header:`Surface elevation`

            This example shows a 10x10 numpy array represented as a heightfield
            that is generated entirely on the GPU (using a default mesh).

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources
               </button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/gloo-cloud.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/gloo-cloud.png

         .. container:: caption

            :header:`Point cloud`

            This example shows a 3D cloud of a million anti-aliased and stroked
            points animated in real-time. Most of them are hidden though !

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources
               </button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/mandelbrot.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/mandelbrot.png

         .. container:: caption

            :header:`Mandelbrot set`

            The mandatory Mandelbrot set computed in the GPU with single float
            precision even tough `double precision emulation
            <https://www.thasler.org/blog/?p=93>`_ is possible.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources
               </button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/geometry-parametric.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/geometry-parametric.png

         .. container:: caption

            :header:`Klein bottle`

            Just because we can ! This example demonstrates parametric surface
            generation and visualization with uv mapping.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources
               </button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/quiver.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/quiver.png

         .. container:: caption

            :header:`Quiver plot`

            Using GPU power, we can litteraly draw a quiver plot using a
            single quad. Adapted from Morgan McGuire `original idea on
            shadertoy <https://www.shadertoy.com/view/4s23DG>`_

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources
               </button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/polar-frame.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/polar-frame.png

         .. container:: caption

            :header:`Projected frame`

            Pixel perfect anti-aliased projected frame drawn by the GPU using a
            single quad. This can be adapted to any projection actually.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources</button>
               <button type="button" class="btn btn-danger btn-xs">
               <span class="fa fa-spinner fa-spin"></span> WIP</button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/grayscott.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/grayscott.png

         .. container:: caption

            :header:`Reaction Diffusion`

            This example simulates a Reaction diffusion using Gray-Scott model
            largely inspired from this `great site
            <http://mrob.com/pub/comp/xmorphia/>`_ that gives all the details.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources
               </button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/text.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/text.png

         .. container:: caption

            :header:`Hello world !`

            Text rendering uses both `regular textured glyph
            <http://jcgt.org/published/0002/01/04/>`_ with higher quality and
            `signed distance fields
            <http://www.valvesoftware.com/publications/2007/SIGGRAPH2007_AlphaTestedMagnification.pdf>`_.
            `Glyphy <https://code.google.com/p/glyphy/>`_ to follow soon (hopefully).

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources</button>
               <button type="button" class="btn btn-danger btn-xs">
               <span class="fa fa-spinner fa-spin"></span> WIP</button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/filter-blur.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/filter-blur.png

         .. container:: caption

            :header:`Post processing filters`

            Post-processing is applied through python context manager. This
            example combines two filters to produce Gaussian blur.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources</button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/shadertoy-colormaps.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/shadertoy-colormaps.png

         .. container:: caption

            :header:`Colormaps`

            Most colormaps can be computed just in time within GPU. But color
            lookup tables are also available through 1D textures.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources</button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/gloo-terminal.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/gloo-terminal.png

         .. container:: caption

            :header:`UTF8 Terminal`

            This is a fast & failsafe terminal that allows to quickly display
            information on screen. It uses the UCS 6x13 bitmap character sets.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources</button>


   .. container:: col-sm-6 col-md-3

      .. container:: thumbnail

         .. image:: _static/screenshots/thumbnails/collection-custom-lines.png
            :width: 100%
            :class: img-rounded
            :target: _static/screenshots/collection-custom-lines.png

         .. container:: caption

            :header:`Realtime signals`

            From an idea by Cyrille Rossant, this example shows 320 signals
            with 10,000 points each. Each signal can be zoomed in/out
            individually.

            .. raw:: html

               <button type="button" class="btn btn-primary btn-xs">
               <span class="fa fa-github"></span> Sources</button>
