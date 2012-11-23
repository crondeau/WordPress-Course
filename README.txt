WordPress-Course
================

Slides to accompany WordPress Course: WordPress as a CMS

Created originally for students enrolled in the Electronic Media Design Program at Langara College, 
the goal of the class is to educate web developers on how WordPress can be used to create an online portfolio.

These slides are aimed at Teachers teaching WordPress to designers. 

Released under a creative commons license, anyone can download them and do whatever they want with them. 

Goals of the Course
====================

Once completed, students should know:
- How to install WordPress locally and on hosting provider
- How to make a child theme
- Understand the making of a WordPress and the function of each template
- How to create a WordPress site


Curriculum 30 hours
====================

LESSON 1: INTRODUCTION TO WORDPRESS
What is WordPress
WordPress.com vs .org
Advantages/disadvantages of WordPress
Installing WordPress
The WordPress dashboard

LESSON 2: THEMES, TEMPLATES & CHILD THEMES
WordPress developer theming options
Overview of WordPress themes
In Depth look at TwentyTwelve
Child Theme

LESSON 3: CUSTOM THEMES
What's a theme?
What's a template?
Choosing the right starting base for you theme
Templates needed
Step by step theming

LESSON 4: ADVANCED THEMING TECHNIQUES
The body_class() function
Custom fields

LESSON 5: TEMPLATE CUSTOMIZATION
Post thumbnails (feature images)
Page, category, custom templates
Mastering the loop

LESSON 6: CUSTOM POST TYPES
What are CPTs
Adding CPTs
Using Plugins to create CPTs
Querying CPTs

Teachers Notes
===============

LESSON 1: INTRODUCTION TO WORDPRESS
Students may be already have Xamp or Mamp installed on their machine, or hosting set up. 
If hosting is required, then a discussion about choosing domain names might also be needed.  
Once installed, students should be given a walk through of the dashboard and all the various sections. 
Students should also be given the time to write a few posts, pages, upload images, etc...

It’s important to walk them through:
- The wp-config file
- Post vs pages
- Wysiwyg/HTML editor
- Categories and tags
- Page parents
- Media library
- Uploading a gallery of images
- Cropping and editing images in WordPress
- Comments
- Themes
- Installing themes
- Theme customizer
- Theme editor
- Widgets
- Menus
- Plugins
- Users, user roles and the importance of a stong password
- Modifying user profile
- Tools – import (install the test data)
- Settings

You should also explain the difference between wp-admin, wp-includes and wp-content folders.
If time permits, you may want to introduce them to a few of your favourite plugins.


LESSON 2: THEMES, TEMPLATES & CHILD THEMES

The goal of this class is to look at our options when working with WordPress and comparing child themes, 
commercial themes and custom built. Students will be required to build a child theme.

Child theming is a skill that is good to know, but most web developers spend more time custom theming 
thus only one lesson is devoted to this. Depending on the needs of your class you may wish allocated 
more time to child and commercial themes. You may also choose a different parent theme. 
I've used both TwentyTen and Responsive during this class.

The child theme tutorial (using TwentyTen) can be found at: 
http://www.wpyogi.com/2011/04/step-by-step-guide-to-making-a-twentyten-child-theme/


LESSON 3: CUSTOM THEMES

In this class, students will be introduced to the concept of building a custom theme based on a PSD 
and a starter theme. What templates need to be included and what theme should they start with will be discussed. 
A PSD of a simple website will be provided and converted into a WordPress site.

The PSD used is - Web_vs1.psd 
I normally use my starter HTML5 theme: https://github.com/crondeau/BLM-Basic-Starter-WordPress-Theme-HTML5 
but feel free to use whatever you want.

The speed at which a PSD can be converted into WordPress will depend on class size and level of CSS/HTML expertise. 
Advanced students may be encouraged to move at their own pace and alter the design while others will need more hands on. 
Converting the whole design into a working site will more than likely take two classes. 

You may also want to introduce a few plugins if you feel that there would be useful.

The tutorial to accompany this class is here:
http://www.wpyogi.com/2011/04/build-a-simple-custom-theme/

The final theme can be viewed here:
http://simple.wpyogi.com/


LESSON 4: ADVANCED THEMING TECHNIQUES
In this class, students will continue building on the custom theme created in Lesson 3.
The PSD used is - Web_vs2.psd 

Custom fields are not used as much as they once were, but are still worth looking at. 
The drawbacks of using them for client work is worth mentioning as well as looking at some plugins 
that utilize their features.

The tutorial to accompany this class is here:
http://www.wpyogi.com/2011/09/enhance-your-custom-theme/

The final theme can be viewed here:
http://enhanced.wpyogi.com/


LESSON 5: TEMPLATE CUSTOMIZATION

In this class, students will continue their custom theme enhancement by looking at creating custom templates.
The PSD used is - Web_vs3.psd 

The different WordPress loops can be a bit complicated for students to grasp especially if they lack PHP knowledge. 
The Digging into WordPress article “4 Ways to Loop With WordPress” is a must read for all students wanting to 
learn more about the various loops. 

It’s a good idea to introduce students to code snippets and get them to start their own snippet library.

The tutorial to accompany this class is here:
http://www.wpyogi.com/2011/10/make-your-custom-theme-fancy/

The final theme can be viewed here:
http://fancy.wpyogi.com/


LESSON 6: CUSTOM POST TYPES
In this class, students will continue their custom theme enhancement by looking at using Custom Post Types.

CPTs provide so many options, it’s hard to create themes to hand out. 
Providing code snippets instead and breaking the code down in simpler steps make it easier to digest. 
This content is also very advanced and may not be appropriate to all students.






Thank you
=============== 

These slides were created using Reveal.js by Hakimel - https://github.com/hakimel/reveal.js
