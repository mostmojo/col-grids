# Col Grids

Col Grids - a 12-column, lightweight CSS grid to help you quickly build responsive websites. Basically, bootstrap, but without the steroids.

Download the CSS stylesheet, add the appropriate classes to your markup, and you're kicking butt. It’s that simple.

Each column is contained within rows, which are contained within a container.

The container is set to a maximum width of 960px, but you can edit without having to break stuff.

State the number of columns you want your content to occupy in the `.col` class. For example, if you want your content to take up 8 columns (out of 12), simply give your content the class `.col-8.`

Col grids is built mobile-first, so all columns will expand to the full container width on smaller screens. If you don’t want columns to expand on mobile devices and small screens, simply add `-sm` to the end of your column class name. For example, if you want to have two blocks of content floating side-by-side on small screens, each would be given the class name `.col-6-sm`.

Be sure to nest columns within a `.row` class. You may also choose to nest rows within a `.container` class.