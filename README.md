Montage Notebooks: Jupyter notebooks illustrating the use of the Python version of Montage
==========================================================================================

Montage is a general astronomical image toolkit with facilities for reprojection, background matching, mosaicking and 
visualization. It can be used as a set of command-line tools (Linux, OS X and Windows), C library calls (Linux and 
OS X) and as Python binary extension modules.  These use cases are all covered by the Jupyter notebooks.

All of the core Montage functionality is available through a Python binary extension ("<i>pip install MontagePy</i>") 
and can be used from within Jupyter notebooks.  Most of the notebooks shown here are focused on illustrating the use
of a single Montage function but there are a couple that illustrate end-to-end Montage processing.


The Montage source distribution is available through GitHub at
<a href="https://github.com/Caltech-IPAC/Montage">https://github.com/Caltech-IPAC/Montage</a>
but you don't need this if you are just running the Python version of Montage.

This document set (notebooks and HTML pages) is a available through GitHub at
<a href="https://github.com/Caltech-IPAC/MontageNotebooks">https://github.com/Caltech-IPAC/MontageNotebooks</a>.
If you just want to view the notebook pages without downloading, go to 
<a href="http://montage.ipac.caltech.edu/MontageNotebooks">
http://montage.ipac.caltech.edu/MontageNotebooks</a>.


The data needed to actually run the notebooks comes in two files.

<a href="http://montage.ipac.caltech.edu/data/montage_datacubes.tar.gz">
http://montage.ipac.caltech.edu/data/montage_datacubes.tar.gz</a> (3 GByte uncompressed)
has the data for the datacube examples (because of the third dimension,
datacubes tend to be large files).  If you are not interested in datacubes
you can save time and space by not downloading this file.

<a href="http://montage.ipac.caltech.edu/data/montage_data.tar.gz">
http://montage.ipac.caltech.edu/data/montage_data.tar.gz</a> (1 GByte uncompressed)
has the data for all the other notebooks.<p/>

Both of these tarballs should be taken apart in the same directories as the
Montage (http://montage.ipac.caltech.edu) is an Open Source toolkit,
distributed with a BSD 3-clause license, for assembling Flexible
Image Transport System (FITS) images into mosaics according to
the user's custom specifications of coordinates, projection,
spatial sampling and rotation.

The Montage toolkit contains utilities for reprojecting and background
matching images, assembling them into mosaics, visualizing the
results, and discovering, analyzing and understanding image metadata
from archives or the user's images.

Montage is written in ANSI-C and is portable across all common
Unix-like platforms, including Linux, Solaris, Mac OSX and Cygwin on
Windows.  The package provides both stand-alone executables and
the same functionality in library form.  It has been cross-compiled
to provide native Windows executables and packaged as a binary Python
extension (available via "pip install MontagePy").

The source distribution contains all libraries needed to build the toolkit
from a single simple "make" command, including CFITSIO and the WCS
library (which has been extended to support HEALPix and World-Wide
Telescope TOAST projections. The toolkit is in wide use in astronomy
to support research projects, and to support pipeline development,
product generation and image visualization for major projects and
missions; e.g. Spitzer Space Telescope, Herschel, Kepler, AKARI and
others. Montage is used as an exemplar application by the computer
science community in developing next-generation cyberinfrastructure,
especially workflow frameworks on distributed platforms, including
multiple clouds.

Montage provides multiple reprojection algorithms optimized for
different needs, maximizing alternately flux conservation, range of
projections, and speed.

The visualization module supports full (three-color) display of FITS
images and publication quality overlays of catalogs (scaled symbols),
image metadata, and coordinate grids.  It fits in equally well in
pipelines or as the basis for interactive image exploration and there
is Python support for the latter (It has also been used in web/Javascript
applications).

Montage is funded by the National Science Foundation under Grant Numbers 
ACI-1440620 and ACI-1642453., and was previously funded by the National 
Aeronautics and Space Administration's Earth Science Technology Office, 
Computation Technologies Project, under Cooperative Agreement Number NCC5-626 
between NASA and the California Institute of Technology.
