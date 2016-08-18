# Why I Switched from WordPress to Jekyll

You guys. Dynamic CMSs are like, _soooo_ 2007. I'm pretty sure my grandma still uses Drupal to run her knitting blog. All kidding aside, dynamic CMSs are still extremely popular, and in certain instances are the right tool for the job. But as someone transitioning from "n00b to nerd" (all rights reserved - T-shirts coming soon), it became clear to me that there was a faster, easier, simpler way to build websites for myself and my clients.  

While this article focuses specifically on my switch from WordPress to Jekyll as my primary blogging and  
web development platform, I believe my experience is a reflection of the growing migration - particularly among developers - away from dynamic, database-driven CMSs to a static web environment.

### My Background with WordPress and Why I Started Looking for Something New
Professionally, I've been working in the digital marketing realm since 2007. I can remember the glory days of stuffing hundreds of hidden keywords in a site's footer and buying links from Digital Point forums (shhh, don't tell Google). The first digital agency I worked with focused on Drupal development before becoming an all-WordPress shop. Each agency I've worked with since has positioned itself as a "WordPress Specialist" in some shape or form.  

Working in those WordPress-centric environments, I gained firsthand experience of the pros and cons of a dynamic CMS, particularly from the client's perspective. It wasn't until a year ago, when I started transitioning from a digital marketer to a front end developer, that the annoying WordPress "quirks" that would make me scratch my head before sending out a support ticket became cause for all night hair-tearing sessions of epic frustration.  

My gripes with dynamic CMSs in general, and WordPress in particular, are the same that many developers share:  

1. **Security**

   This is probably the most frequent - and warranted - knock on WordPress. The platform is notorious for being an all too easy target for hackers. In 2014, it was determined that [nearly 74% of WordPress installs were vulnerable to hacker attacks](https://www.wpwhitesecurity.com/wordpress-security-news-updates/statistics-70-percent-wordpress-installations-vulnerable/). Some of this can be attributed to WordPress's popularity ([26% of all websites globally use WordPress](https://wordpress.com/about/)), but even Drupal sites have been the subject of widespread hacking. Back in 2014, Drupal [released a PSA](https://www.drupal.org/PSA-2014-003) that informed platform users they should "proceed under the assumption that every Drupal 7 website was compromised unless updated or patched before Oct 15th, 11pm UTC, that is 7 hours after the announcement." Yikes.  

   The alarming amount of security holes caused by outdated platform versions, cut rate plugins, unsecure databases, login interfaces, images, malicious search queries, and more are a major reason why some developers (myself included) have begun to explore safer alternatives.  

2. **Speed**

   Another major downside to working with WordPress is the painfully slow load times many users experience. On top of a database query occurring _every time_ someone visits a page on your WordPress site, all of those fancy plugins, gigantic slider images, and excess code that accompany so many WordPress installs can really take a toll on page speed and performance. Sure, you can combat this by using caching plugins, optimizing your images, and paying top-dollar for hosting, but all of these seem to be bandaids rather than real solutions.  

   Most of us already know that even a [1 second delay in page response time can cost companies **BIG** money](https://blog.kissmetrics.com/loading-time/). With Google now using [site speed as a ranking factor](https://webmasters.googleblog.com/2010/04/using-site-speed-in-web-search-ranking.html), the need for speed is even greater.  

3. **Simplicity**

   At first, the multitude of bells and whistles that WordPress provides was something I loved. If there was some functionality I wanted that wasn't provided by the currently installed theme, there was a good chance a 3rd party plugin would do the trick. For non-technical users, having the ability to easily extend the functionality of their website without having to creating something from scratch is pretty amazing - but it comes at a price.  

   For starters, these bells and whistles are a major cause of the speed issues mentioned in #2 above. Second, each new add-on or extension can quickly clutter up an already complicated dashboard, making it difficult for even seasoned WordPress users to navigate.  I recently logged into a friend's WordPress site only to find that his dashboard has become an unusable wall of text (even with spammy weight-loss commments)!  Finally, all of these plugins, themes, and other extensions must be constantly updated to avoid security and compatibility issues. Not so simple after all, right?
   
   ![Imgur](http://i.imgur.com/sr9YxAm.jpg)


### Bringing Static Back
I'm a basic, "no-frills" kind of guy. I enjoy minimalist design. My favorite ice cream is vanilla. And I like when things work the way I expect - the first time, and every time after. So as I dove deeper down the rabbit hole of front end development, it was the simplicity and stability of being able to create things with nothing more than a little markup and JavaScript that got me wondering, "Is it feasible to develop full-scale websites this way today?"  

Enter Static Site Generators (or SSGs). Simply put, an SSG is a templating engine that takes markup, assets, and various other data files and spits out static html webpages. Because many modern SSGs utilize templates, Markdown, and include an asset pipeline (among many other features), they facilitate the rapid development of websites. Websites that are easy to maintain and won't just break 6-months down the road (no [code rot](https://en.wikipedia.org/wiki/Software_rot)!).  Need to change your footer across 200 pages? No problem, just edit your footer include file.  Need to loop through the 10 most-recent posts?  No problem, most of the templating langues have a [small learning curve](https://github.com/Shopify/liquid/wiki/liquid-for-designers).

For the same reasons that WordPress gets a bad rap, I've found static sites to shine:  

1. **Security**

   When it comes to security, static sites are like Fort Knox compared to your average WordPress install. The main reason for this is that there isn't a build process occurring for each page request like there is with a dynamic CMS. Instead, the server simply delivers the requested file for that page in a nice, clean, static format (HTML, CSS, and maybe a bit of JavaScript if you're feeling saucy). No build process and fewer moving parts mean less opportunities for security exploits.  

2. **Speed**

   Again, this comes back to how static files are delivered to the user. Imagine that for each visit to a page on your WordPress site, a million tiny worker ants are scrambling to put together all of the text, images, and other resources you want to display. Now imagine those same ants kicking back, sharing some beers, and watching Netflix because they've already built your site's static pages - they're ready to be requested and delivered. Throw in the speed improvements you get from not having all those plugins and code bloat, and it's easy to see why static = _FAST_.  

3. **Simplicity**

   So far, this is my favorite thing about static sites in general, and [Jekyll](https://jekyllrb.com) in particular. Once you learn the basic installation and usage workflow of an SSG, you can build pretty much anything you want using simple markup and programming languages. There's no real framework to fight against, no constant updates to be made, tons of quality (and often free) hosting options, and easy iteration and deployment. Static sites just work - the first time, and every time after.  

**Wrapping Up**  
If you're reading this post, then I'm guessing you're looking for an alternative to WordPress the same way I was not too long ago. Hopefully I've done a good job of pointing out the pain points of dynamic CMSs, which are also the strenghts of SSGs. If you'd like to experiment with static sites, but you're not quite ready to give up your dynamic CMS cold turkey...well my friend, you're in luck. With tools like [Forestry](https://forestry.io/), Jekyll and other SSGs can go from a "blogging platform for hackers" to a user-friendly GUI equipped with some of the same tools you know and love (WYSIWYG for the win!).  

There are currently [437 Static Site Generators](https://staticsitegenerators.net/) available for folks looking to ditch their dynamic CMS in favor of something more manageable. So why did I choose Jekyll? For me, it came down to popularity, documentation, and longevity. Jekyll has been [starred nearly 27,000 times, and forked almost 6,000 times on GitHub](https://www.staticgen.com/). It was developed by GitHub co-founder Tom Preston-Werner, who used Jekyll to build GitHub Pages, which provides a free hosting environment for static web pages. Additionally, Jekyll's [solid documentation](https://jekyllrb.com/docs/home/) and [large support community](https://talk.jekyllrb.com/) made it my SSG of choice for the foreseeable future.
