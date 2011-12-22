Example: Wired.com Clone
========================

[Here's the live demo](http://www.ryankinal.com/wired/)

I was looking around the web for a good layout to recreate using haGrid, some OOCSS concepts, and separation of container and content. I didn't expect to tackle something quite as complex as [Wired.com](http://www.wired.com).

Wired's code, well, it kind of sucks (sorry, Wired, I still love you). It's fixed-width, there are IDs all over the place, there are needlessly overridden styles, and it's just overly complex. 

They layout, though, is great. It's based on a grid (though it may not seem like it at first), it uses the divine ratio all over the place (or something very very close to it), and it's very functional. It also has a lot of repetition in terms of visual elements. It turned out to be the perfect candidate.

Now, I may not have the fonts exactly correct, but it even amazed *me* how quickly this came together. I wrote very little CSS, and came up with something that is *very close* to the original.

There are a few things that need added, though:

* Footer content
* Sticky footer
* Right column item separators

Those things should be simple enough, and actually, the sticky footer represents one of those one-off items that might have very little to do with the grid, or with OOCSS at all.

Files:

* layout.html - shows just the layout, without any real content
* index.html - shows the entire page, layout and content combined
* skin.css - the content styles (as opposed to layout styles)