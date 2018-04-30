# Towards an Automated Geometer

Automatic theorem generation in plane geometry is a topic that deserves study.
Some fruitful attempts have already been made by [Bagai, Shanbhogue, Żytkow and Chou (2005)](https://link.springer.com/chapter/10.1007%2F3-540-56804-2_39),
based on a conceptual framework for discovery of theorems in geometry, and a mechanism which
systematically discovers such theorems.

Our present work, similarly to the abovementioned one, has its background in Wu's algebraic
method, but, by contrast, it has a widely disseminated dynamic geometry engine, [GeoGebra](http://www.geogebra.org). In our work
a geometric construction can be opened in a [web page](http://htmlpreview.github.io/?https://github.com/kovzol/ag/blob/master/automated-geometer.html), and can be investigated on having
usual relations like collinear points, parallel or perpendicular lines, isosceles triangles,
and so on, automatically. The relations to observe can be fine-tuned by the user, to avoid explosion of combinatorial complexity. On the other hand, the input construction can be extended by a configurable set
of newly added objects to obtain a wider set of possible results.

GeoGebra's high level user interface (UI) and [JavaScript application programming interface (API)](https://wiki.geogebra.org/en/Reference:GeoGebra_Apps_API) make
it possible to study planar geometry theorems in an automated but still convenient and modern way. Further improvements of our approach, namely, to consider false statements and automatically compute an extension of the hypothesis set, in order to get true statements, are promising horizons towards an Automated Geometer tool, cf. [Guzmán (2002)](https://www.agapea.com/libros/La-experiencia-de-descubrir-en-geometria-9788495599346-i.htm).

All of these efforts are based on GeoGebra's recent improvements, the ["Automated Reasoning Tools"](https://github.com/kovzol/gg-art-doc).

## Authors

* Francisco Botana <fbotana@uvigo.es>
* Zoltán Kovács <zoltan@geogebra.org>
* Tomás Recio <tomas.recio@unican.es>
