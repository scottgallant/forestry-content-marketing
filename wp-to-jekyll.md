# Why I Switched from WordPress to Jekyll

**Intro**  
While this article focuses specifically on my switch from WordPress to Jekyll as my primary blogging and  
web development platform, I believe my experience is a reflection of the growing migration - particularly among developers - away from dynamic, database-driven CMSs to a static web environment.

### My Background with WordPress and Why I Started Looking for Something New
Professionally, I've been working in the digital marketing realm since 2007. I can remember the glory days of stuffing hundreds of hidden keywords in a site's footer and buying links from Digital Point forums (shhh, don't tell Google). The first digital agency I worked focused on Drupal development, before quickly pivoting to an all-WordPress shop. Each agency I've worked with since then has positioned itself as a "WordPress Specialist" in some shape or form.  

Working in those WordPress-centric environment, I gained firsthand experience of the pros and cons of a dynamic CMS, particularly from the client's perspective. It wasn't until a year ago, when I started looking to transition from a purely digital marketing role to something more involved in front end development, that the annoying WordPress "quirks" that would make me scratch my head before sending the dev team a support ticket became cause for all night hair-tearing sessions of epic frustration.  

My gripes with dynamic CMSs in general, and WordPress in particular, are the same that many developer share:  

1. **Security**

   This is probably the most frequent - and most damning - knock on WordPress. The platform is notorious for being a primary, oftentimes easy target for hackers. In 2014, it was determined that [nearly 74% of WordPress installs were vulnerable to hacker attacks](https://www.wpwhitesecurity.com/wordpress-security-news-updates/statistics-70-percent-wordpress-installations-vulnerable/). Some of this can be attributed to WordPress's popularity ([26% of all websites globally use WordPress](https://wordpress.com/about/)). Still, the alarming amount of security holes caused by outdated WordPress versions, cut rate plugins, MySQL databases, login interfaces, images, malicious search queries, and more are a major reason why some developers are looking for alternatives.  

2. **Speed**

   Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.  

3. **Simplicity**

   Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.  

4. **Scalability**

   Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Bringing Static Back
I'm a pretty basic, "no-frills" kind of guy. I enjoy minimalist design. My favorite ice cream is vanilla. And I like when things work the way I expect - the first time, and every time after. So as I dove deeper down the rabbit hole of front end development, it was the simplicity and stability of being able to create things with nothing more than a little markup and JavaScript that got me wondering, "Is it feasible to develop full-scale websites this way today?"  

Enter Static Site Generators (or SSGs). Simply put, an SSG is a templating engine that takes text, assets, and various other data files and spits out static html webpages. Because many modern SSGs utilize templates (e.g. includes, layaouts, etc.), support the use of Markdown and Meta Data, and include an asset pipeline (among many other features), they facilitate the rapid development of simple, easy to maintain websites without having to rely on a dynamic CMS like WordPress.  

For the same reasons that WordPress gets a bad rap, I've found static sites to shine:  

1. **Security**

   When it comes to security, static sites look like Fort Know compared to your average WordPress install.   

2. **Speed**

   Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.  

3. **Simplicity**

   Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.  

4. **Scalability**

   Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

There are currently [437 Static Site Generators](https://staticsitegenerators.net/) available for folks looking to ditch their dynamic CMS in favor of something more manageable. So why Jekyll? For me, it came down to popularity, documentation, and longevity. _list out specifics for each of those 3 reasons here_

**Wrapping Up**  


**Other Notes / Possible Things to Add**
* Is this regression, or a return to "simpler times?" Maybe a bit of both...  
* Multiple reasons for going static / leaving WP:  
 1. **Security** (see Scott's email for ideas)  
  * _LOTS_ of vulnerability's when it comes to WP (and other dynamic CMSs like Drupal, etc.)
   * Security holes come from plugins, MySQL databases, login interface, images, malicious search queries, etc.  
    * Constant updates, security plugins, anti-virus programs, etc. are often necessary to keep WP secure  
 2. **Speed** (see Scott's email for ideas)  
  * Database queries, code bloat, the need for multiple plugins, etc.
 3. **Simplicity** (cite some stuff from 'Static Sites go all Hollywood' by Phil Hawksworth)  
  * Constant need to update plugins, themes, etc.   
  * For many projects, all of WP's bells and whistles are _WAY_ too much    
  * Out of the box WP install almost always require further configuration and customization  
 4. **Scalability**  
  * Free (or low cost) hosting options  
  * Can handle _LOTS_ of traffic without skipping a beat  
  * Templated approach to site creation allows for faster, more modular design / development  
  * With tools like Forestry, Jekyll and other SSGs can go from a "blogging platform for hackers" to production-level software implemented by agencies and maintained by non-technical end users.

 **Helpful Links / Other Resources**
* https://www.sitepoint.com/wordpress-vs-jekyll-might-want-make-switch/  
* http://www.spiderwriting.co.uk/static-dynamic.php
* https://premium.wpmudev.org/blog/wordpress-security-exploits/
