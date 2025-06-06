Parameters
=====

.. _installation:

Format
------------

These parameters appear under [format], and control where to save the file and how the file shows.

.. code-block:: console

  [format]
  output = 'movie.nml'
  indent = 4
  pad_eq = true

output
  This parameter specifies the path to the output namelist file. Currently, it generates only the movie-related parameters, but appending them to the given file will be realized in future.

indent
  This parameter adds a white space in front of each parameter to improve the visibility. The default is 0 (no indentation).

pad_eq
  This parameter adds white spaces to both side of an equal sign (=) to improve the visiblity. The default is false (no padding).


General
----------------

These parameters are under [general] and controls the number of outputs, size, and properties common to all movie sets (projections).

.. code-block:: console

  [general]
  imov = 0
  astartmov = 0.05
  aendmov = 1.00
  imovout = 2000
  nw_frame = 1920
  nh_frame = 1080
  levelmax_frame = 19
  movie_vars_txt = ['dm', 'dens', 'temp', 'stars', 'var6']

imov
  blablabla

astartmov
  blablabla

imovout
  blablabla

nw_frame
  blablabla

nh_frame
  blablabla

levelmax_frame
  blablabla

movie_vars_txt
  blablabla
