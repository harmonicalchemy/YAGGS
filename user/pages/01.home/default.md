---
title: Home
body_classes: 'title-center title-h1h2'
content:
    items: '@self.children'
    leading: '0'
    columns: '2'
    limit: '5'
    order:
        by: date
        dir: desc
    show_date: '0'
    pagination: '1'
    url_taxonomy_filters: '1'
---

![](Alexander-Andrews-natures-fireworks.jpg)
# Say Hello to Yet Another Grav Skeleton!
## installation successful...

Congratulations! You have installed the [Grav Skeleton Package](https://github.com/harmonicalchemy/grav-base) From Harmonic Alchemy Productions!

This Skeleton is based on the Gantry 5 Framework and uses a customized version of the G5 Hydrogen theme...

### Find out all about Grav and Gantry 5

* Learn about **Grav** by checking out their dedicated [Learn Grav](http://learn.getgrav.org) site.
* Download **plugins**, from [Grav Downloads](http://getgrav.org/downloads)...
* Learn about the [Gantry 5 Framework Docs](http://docs.gantry.org/)...
* Check the [Grav Development Blog](http://getgrav.org/blog) to find out the latest goings on in the Grav-verse.


### Edit this Page

To edit this page, simply navigate to the folder you installed **Grav** into, and then browse to the `user/pages/01.home` folder and open the `default.md` file in your [editor of choice](http://learn.getgrav.org/basics/requirements).  You will see the content of this page in [Markdown format](http://learn.getgrav.org/content/markdown).

### Create a New Page

Creating a new page is a simple affair in **Grav**.  Simply follow these simple steps:

1. Navigate to your pages folder: `user/pages/` and create a new folder.  In this example, we will use [explicit default ordering](http://learn.getgrav.org/content/content-pages) and call the folder `03.mypage`.
2. Launch your text editor and paste in the following sample code:

        ---
        title: My New Page
        ---
        # My New Page!

        This is the body of **my new page** and I can easily use _Markdown_ syntax here.

3. Save this file in the `user/pages/04.mypage/` folder as `default.md`. This will tell **Grav** to render the page using the **default** template.
4. That is it! Reload your browser to see your new page in the menu.

! NOTE: Your page will automatically show up in the Menu after the "blog" menu item. If you wish to change the name that shows up in the Menu, simple add: `menu: My Page` between the dashes in the page content. This is called the YAML front matter, and it is where you configure page-specific options.

#### Banner Image Credit:[Natures fireworks -  by: Alexander Andrews](https://unsplash.com/photos/eNoeWZkO7Zc) Published January 19, 2018 Unsplash.com