---
title: How to Resize Images on Mac Like a Pro
date: 2018-02-27 23:00:58 +0000
layout: post
current: post
cover: "/uploads/resize-images-on-mac-cover.png"
navigation: true
tags:
- productivity
class: post-template
subclass: post tag-productivity
author: zavrelj
---
Resizing images is very handy, especially with all those megapixels thrown at us from the latest and greatest smartphones.

I don't know how about you, but I don't really need 10MB photos of some reference materials. There are a lot of third-party apps and online services for shrinking photos or images to some meaningful (sane) size, but if you're using Mac, you can just select all the images you need to shrink and use one simple shortcut, like **⇧ ⌘** **S** to do the job for you.

Of course, you need to set this up first, because it's not a built-in feature, and in this article, I will show you how!

### **Meet Automator**

Automator is a great app. You can find it on any Mac with Mac OS X v10.4 (Tiger) or newer. It's very powerful, and it's pretty sad that most Mac users don't even know about its existence.

Fire up the Spotlight with the **⌘ SPACE** combo and type **automator**.

![](/uploads/resize-images-on-mac-img01.png)

Once it appears, just hit **ENTER** to run it. You should be greeted with similar window as seen below. If not, just select **File** -> **New** (or hit **⌘ N**).

![](/uploads/resize-images-on-mac-img02.png)

### **Create a New Service**

You can do a lot with Automator, but let's not get too excited here. We just need to create a new Service to move on, so select **Service** instead of default **Workflow** and hit the **Choose** button:

![](/uploads/resize-images-on-mac-img03.png)

You'll get this empty window and the fun can begin!

![](/uploads/resize-images-on-mac-img04.png)

First, make sure to select the **Image files** option from the top row, so it looks like this:

![](/uploads/resize-images-on-mac-img05.png)

Next, go to **Files & Folders** in the left pane and double-click the **Copy Finder Items**:

![](/uploads/resize-images-on-mac-img06.png)

This will allow you to keep the original images for whatever reason and place the resized versions in a specific folder. I suggest you create a new folder in **Documents** and name it **resized_720p** for example. Next, you will simply select this folder instead of the default **Desktop** option in the drop-down menu:

![](/uploads/resize-images-on-mac-img07.png)

Next, double-click the **Rename Finder Items** option and select **Add Text** from the drop-down menu. Type the **_720p** postfix:

![](/uploads/resize-images-on-mac-img08.png)

Next, go to **Photos** and double-click the **Scale Images** option. When asked, click the **Don't Add** button:

![](/uploads/resize-images-on-mac-img09.png)

Type **1280** as the new size, so you'll get most of the time the resolution of 1280x720 pixels, also known as 720p, hence the name of the folder :)

Make sure your settings look like this now:

![](/uploads/resize-images-on-mac-img10.png)

Save the changes with **⌘ S** combo and name this service **resize_720p**:

![](/uploads/resize-images-on-mac-img11.png)

Once the file is saved, you can quit Automator.

### Let's test this!

Right-click the image of your choice and select **resize_720p** from the list of services. Resized copy of the image should appear in the **resized_720p** folder. And by the way, this works even with multiple images selected!

![](/uploads/resize-images-on-mac-img12.png)

### **Like a Pro!**

This is already pretty good, but let's take it a step further by creating a shortcut to run this service so you don't have to select it from the drop-down menu.

Go to **System Preferences**, select **Keyboard** and locate your **resize_720p** service in the list of **Services:**

![](/uploads/resize-images-on-mac-img13.png)

Click the **Add Shortcut** button and type the shortcut, make sure it's not taken by any other application. I chose **⇧** **⌘** **S** (S for “size” to remember it easily) and should work for you as well:

![](/uploads/resize-images-on-mac-img14.png)

Now back to your images. Select as many as you like and use this shortcut to let the magic happen! :-)

![](/uploads/resize-images-on-mac-img15.png)