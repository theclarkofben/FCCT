# FCCT
Hosted page: http://www.clarkben.com/fcct/index.html

I only allowed myself two hours of working time and as you can see I ran out of time. In the time provided I:
- Assessed the design and chose appropriate technologies (Bootstrap and Isotope + Packery extension)
- Used Photoshop to extract the images from the mockup as they were not provided (cropped them out individually and measured and noted down pixel dimensions of each and removed text from them).
- Created the page skeleton in HTML.
- Used CSS to roughly match mockup (pixel perfect precision to be done towards end)
- Added images and styled with CSS to ensure centred.
- Added script.js, HTML elements with .grid and .grid-item classes to implement the Isotope solution for products that need a masonry style layout. Used Packery setting to achieve desired layout which included ensuring a manually add Packery extension js. Clearfix also needed for layout to work.

If I had more time I would have:
- Added css to declare Arial as global font
- Added all text to page using appropriate, semantic elements i.e. < h1 > for main heading, < p > or < span > for paragraphs/sentences, and being sure to include to nest text inside < a > elements for those that will act as links.
- Positioned all text appropriately using CSS
- Used jQuery to fade in text in top image with use of $(document).ready() and $(‘#thetext’).fadeIn();
- Wrapped the images on the page in <a> tags to make them clickable – presumably “clickable” was indicative of them being links. I might be wrong about that assumption?
- Use Bootstrap’s ScrollSpy plugin to update the DOM when user scrolls to xmas jumper image. Thinking off top of my head I would get ScrollSpy to add trigger event when user scrolls to xmas jumper, I would write the event JS to ensure that the image is loaded only then. Presumably you didn’t mean hide/visible – you meant load. If it was a simple case of hide/visible then I could of just updated the style from display:none to display:block.
- I would have investigated the 1 or 2 pixel of feathering I think I can see on the images in the mockup and implemented the same. That would have led to more precise dimensions for the images. At the moment they all have slightly different dimensions that could be more standard once feathering known properly.
- I would have gone over all my code and grouped and commented it all properly. If you look at my other GitHub repos you will see the code is well commented e.g. Feed The Plant Game. It’s something I think is important.
- I would have experimented with Bootstrap’s CSS to ensure that mobile and tablet had a respectable layout to the best of my abilities. I would do my absolute best in the absence of a design. See my clarkben.com website for how I’ve implemented a mobile layout.


Thank you for your time. I hope to hear from you soon. Any feedback would be very welcomed.

Ben

PS: Below I have included the git log for the commits that I did for this code test for your ease of viewing.

commit 12d0da311db5f3f1783453c66091dab4e9a01af1
Author: Ben Clark <ben@clarkben.com>
Date:   Tue Oct 20 13:44:15 2015 +0100

    Initial commit

commit 791377666c73d37c8f44f03e66d07a022b2bae5f
Author: Ben Clark <ben@clarkben.com>
Date:   Tue Oct 20 14:02:27 2015 +0100

    Images not provided so cropped out and saved each image in mockup using Photoshop. Applied naming convention to images when saving based on grouping together ones of similar dimensions.

commit 164a8b22adabaad685851fd74634d07901f60427
Author: Ben Clark <ben@clarkben.com>
Date:   Tue Oct 20 14:06:18 2015 +0100

    Bootstrap seems like a good framework for this design. Creating page with Bootstrap.

commit 557f2a914a415afdb8ee11d8bd69556edf1e807e
Author: Ben Clark <ben@clarkben.com>
Date:   Tue Oct 20 14:38:38 2015 +0100

    Noted masonry type layout used for some product listings. Researched good way to implement masonry with Bootstrap: Isotope.js with packery extension. Added scripts to page.

commit 904fffccbbf391a78790ccf67c15fd232b19fabd
Author: Ben Clark <ben@clarkben.com>
Date:   Tue Oct 20 15:04:29 2015 +0100

    Created the skeleton of the main pages, containers and images. Used a placeholder for now for the masonry layout product listings.

commit fb15f5701814285df4c516d4f646dae1c94a1290
Author: Ben Clark <ben@clarkben.com>
Date:   Tue Oct 20 15:38:05 2015 +0100

    Implemented Isotope Packery on first set of masonry layout products

commit a91ecf380ecc224af862bff05e63092222efe8af
Author: Ben Clark <ben@clarkben.com>
Date:   Tue Oct 20 15:54:21 2015 +0100

    Second Isotope masonry product listing done. Text removed from images.

commit e9fe5d6f38989b5046dab7fcf793c235ab3f478f
Author: Ben Clark <ben@clarkben.com>
Date:   Tue Oct 20 15:59:50 2015 +0100

    Updated typo in img src urls
