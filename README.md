haGrid
======
Grid-based design has gained a lot of popularity. So has "responsive" or "liquid" design. At first glance, these concepts seem incompatible. However, good grid-based design is based on ratios, so there is no reason we shouldn't be able to use percentage-based layouts and still achieve grid-like aesthetics.

Percentages are notoriously difficult to work with when attempting to implement margins, borders, and padding. These difficulties are easily reconciled using the concept of *separation of container and content*, as described by Nicole Sullivan (and demonstrated in her OOCSS framework).

**haGrid**, unlike OOCSS, does not attempt to normalize or reset defaults. It does not attempt to solve the content problem. It only attempts to solve the container problem, and it attempts to do so in a readable manner.

Grid Sizes
----------
haGrid defines a few different ratios, and encourages combining those to form grids with more granularity:

* tenths
* fifths
* thirds
* quarters
* "divine" ratio

Designing in CSS
----------------
Grid-based design with haGrid requires a lot of planning. In fact, it's most likely best to design outside of CSS, and use haGrid to implement, rather than create your design.

[1]: http://www.stubbornella.org			"Nicole Sullivan"
[2]: https://github.com/stubbornella/oocss	"OOCSS"