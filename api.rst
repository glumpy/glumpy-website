.. role:: header
   :class: h2

===================================
Application Program Interface (API)
===================================

.. toctree::
   :maxdepth: 2
   :hidden:

   api-gloo
   api-app
   api-graphics
   api-other



.. container:: lead

   Glumpy is organized around three blocks:

   .. container:: small

      * The `app <api-app.html>`_ package is responsible for opening a window and handling
        user events.

      * The `gloo <api-gloo.html>`_ package is responsible for handling shader programs and
        syncing CPU/GPU data.

      * The `graphics <api-graphicshtml>`_ package provides higher-level common objects such as
        text, collections and widgets.

----

.. container:: row

   .. container:: col-md-6

      :header:`App`

      * **clock**         : Clock
      * **console**       : Debug console
      * **options**       : Command line options
      * **configuration** : Default configuration
      * **window**

        * **backends** : Backend specific code
        * **event**    : Event dispatcher
        * **mouse**    : Mouse events
        * **keyboard** : Keyboard events
        * **window**   : Abstract window


   .. container:: col-md-6

      :header:`Gloo`

      * **globject** : Abstract object that lives on both CPU & GPU
      * **gpudata**  : GPU aware numpy array
      * **program**  : GPU Program
      * **parser**   : GLSL parser
      * **shader**   : Programmable shader
      * **snippet**  : Reusable GLSL snippet
      * **variable** : Shader variable (attribute or uniform)
      * **buffer**   : GPU buffer (VertexBuffer/IndexBuffer)
      * **texture**  : GPU texture (1D/2D/3D)
      * **atlas**    : 2D Texture atlas


.. container:: row

   .. container:: col-md-6

      :header:`Graphics`

      * **text**        : Text related objects
      * **widgets**     : Interactive widgets
      * **collections**

        * **points**    : Points collection
        * **lines**     : Lines collection
        * **triangles** : Triangles collection
        * **quads**     : Quads collection

   .. container:: col-md-6

      :header:`Others`

      * **geometry**   : Geometry related functions
      * **transforms** : Interactive transformations
      * **shaders**    : Actual shader code
      * **gl**         : OpenGL access
      * **glm**        : Simple 3D matrix transforms
      * **ext**        : External packages
