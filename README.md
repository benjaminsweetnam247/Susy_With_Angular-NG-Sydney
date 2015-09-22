##My Talk On Using Suzy With Angular.js with examples
Hi I want to talk to you today about layouts.
A bit about me I've recently finished up an internship type arrangement and I'm looking for
a place to work.
this might seem like a strange topic for an angular meetup.
but I feel it is something that effects all of us and we are not currently finding good ways of solving these problems.
I want to get a show of hands.
How many of you are using bootstrap for styling your webpages or apps.
so thats currently ?% of the room.
How many webpages on the internet are currently styled with bootstrap.
using built with .com currently a little under 6 million.
That number is growing by about a million each quarter.
Ok why is this a problem.
bootstrap solves a particular problem and that is styling a webpage
quickly, with very little effort and you get a whole heap of bonuses.
all this quickly adds up and weighing in at 150kb load times quickly become a problem.
Whats the solution
css?
Too verbose and hard to manage
Less?
um.. no thankyou
Sass?
My Preference and alot of others
Stylus?
Great Language just not as much support or frameworks to use.

So Susy makes styling webpages easier just like any other framework and just like
any other framework has some cool features to go with it.
Susy is not a class based frame work but uses imports to define features of selected elements.
I feel this allows for more readable and semantic code. Helps with defining resuable styles.
Which inturn helps with code duplication and minimises the difficulty of changing something down the track.

I think susy is particularly useful in helping you with repeating repeating patterns like gallerys and blogs.

now susy is really easy to start using especially if your already using compass, bower, Grunt or ruby.

if you have ruby installed just add the gem and watch the sass file with the command -r susy.
this will watch your sass file for changes and recompile your css after saving.

now for a demo.

first I'm going to show you two very simple examples a blog layout and a Image Gallery.
I've built both in pure css, css and angular and susy and angular.

So in this first example I'm building an Image gallery in pure css and html
things to note with this example I havn't added any functionality in here
not because it's too hard but just because it was more work.
the other is the images float around the screen and don't have a defined
structure this can be fixed but it's at the cost of some screen flexability.

In this next example I'm using angular.js to aliterate through an array printing out
vertually the same gallery but I'm using susy to handle the layout and angular to handle the
image data and am removing alot of code duplication and making the layout nicer.

Taking this idea one step further
we can add indavidual lightboxes by adding only 4 lines of code to the html
and 26 lines of css.

this is just the start of how susy can help with your layouts and as you can see
it works really well when combined with angular.


Here are some of the reasources that helped me produce these examples.

Any Questions?

Obilitory meem.

Thankyou.

https://www.emaze.com/@ALQZOFFO/susy-with-angular


