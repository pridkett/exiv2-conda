Anaconda Build Package for exiv2
================================

Patrick Wagstrom &lt;patrick@wagstrom.net&gt;

April 2017

This is part of a project that got a little out of control. Long story short, I
wanted to modify the EXIF data on some photos. That lead me to Python bindings
for [gexiv2][gexiv2], because none of the existing bindings worked for Python
3. gexiv2, in turn, requires [exiv2][exiv2].

Usage
-----

    conda build .
    conda install exiv2 --use-local

License
-------

This code is licensed under the MIT license. The code for exiv2 is licensed
under the GPLv2 or later.

[exiv2]: http://www.exiv2.org/
[gexiv2]: https://wiki.gnome.org/Projects/gexiv2
