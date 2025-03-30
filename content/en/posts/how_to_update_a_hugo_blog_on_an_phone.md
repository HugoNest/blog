+++
title = 'How to Update a Hugo Blog on a  Phone'
description = 'Explore different methods for updating your Hugo blog on Android or iOS,  from dedicated apps like HugoNest to using tools like Weblog and Mgit.  Discover the pros and cons of each approach.'
tags = ['Hugo', 'Android', 'Blog Development', 'Static Site Generators', 'HugoNest']
date = '2025-03-31T00:18:42.820927'
draft = false
categories = ['Development', 'Content Management', 'Hugo']
series = ['Hugo Blog Optimization']
keywords = ['Hugo', 'Android', 'blog update', 'HugoNest', 'static site', 'mobile development']
aliases = []
lastmod = '2025-03-31T00:18:42.820927'

+++

It is well-known that the process of publishing a blog has always been cumbersome due to the absence of backend solutions in static blog programs like HUGO, HEXO, and Jekyll. Previously, I used various methods to update my blog, but all of them required a PC.

## PC Method
VSCODE+Github
My initial approach was to edit in VSCODE, generate static files in the Public directory locally using the Hugo command, and then submit them to Github Pages for direct publication. Later, I found the Hugo generation process too cumbersome, so I switched to editing and directly submitting to Github, then using Github Actions to generate blog files and publish them to Github Pages.

Since all images on this site are hosted on Github, and due to the well-known issues with the speed of accessing Github Pages, I eventually abandoned the Github Actions + Github Pages solution in favor of automatic deployment through Vercel or Cloudflare Pages.

## Obsidian+Github
Obsidian is an excellent note-taking software with a very large plugin library. With Obsidian + quickadd plugin + Git plugin, it’s very convenient to directly submit blog posts to Github from Obsidian. However, the issue is that Obsidian can only publish article content and cannot modify other site settings. Managing the Posts directory of Hugo directly with Obsidian feels odd, and unless a dedicated blog repository is created, there’s a constant risk of confusing note content with blog content during the management process.

## Joplin+Github
Joplin is also a very good open-source note-taking software. Although Joplin has fewer plugins, there is one that can directly publish to Github Pages, called Pages Publisher Pages Publisher. However, this plugin is used by fewer people and currently only offers a very basic blog theme.

Nevertheless, all these methods inevitably require the use of a PC.

## Mobile Method
Github Code
Github repositories allow for direct creation and modification of files. However, the inconvenience with this method is that direct access to Github from within China is not always reliable. The worst scenario is editing halfway through, only to have the page reset due to network issues. Github Codespaces faces the same issue.

![](a.png)

## Weblog App
Weblog is an Android app that supports managing Hugo and HEXO blogs on mobile devices. It includes built-in Hugo and Hexo environments and Git, allowing for convenient blog setup, static file generation, and webpage previews on the phone. It can easily publish to Github via Git. However, due to Hexo’s lower efficiency, it is recommended to use it with Hugo. The main issue with this solution is that it only supports creating MD files and does not allow uploading photos within the app. To upload photos, one must use the Android’s native file manager or a third-party file management tool.

![](b.jpg)


## Mgit App
Mgit is an Android Git application that easily pulls Github repositories to the local device, allowing for blog writing with a third-party Markdown editor. Many people use Obsidian as their blog editor and sync between their phone and computer using Mgit. The downside is that Mgit seems to have not been updated for a long time, and I encountered an issue on my Vivo X100 phone where I couldn’t edit files directly within Mgit.

![](c.jpg)


## StackEdit
Stackedit is an excellent online Markdown editor that can be privately deployed and linked to Github repositories, with information stored in browser Cookies. I’ve tried editing simple information on my phone through Stackedit and submitting updates to Github. The main drawback of this method is that it cannot submit images, making it suitable only for situations where no images are needed or when using a third-party image library.

![](d.png)
Having suffered significant setbacks with image libraries since 2008, and upon cleaning up my Wordpress blog in 2018, I found that nearly 500 out of 900 images on the site had been lost due to issues with external image libraries. Even self-built image libraries have left me lacking confidence. Managing them separately always feels prone to problems.

## HugoNest
Finally, the current best choice is HugoNest. It's a cross-platform app (Android, iOS, Linux, macOS, Windows) that lets you update your Hugo blog anytime, anywhere. 
![](https://hugonest.github.io/static/media/dashboard.png)
