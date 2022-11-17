---
title: "How to Embed App Store Reviews on Your Website"
description: "Displaying App Store reviews on your website helps you get more downloads for your app. Create a reviews carousel widget to display app reviews on your website"
date: 2022-11-09T19:54:04-04:00
draft: false
author: "Tyler Kennedy"
cover:
    image: "assets/images/blog-covers/embed-app-store-reviews-on-your-website.png"
    alt: "How to Embed App Store Reviews on Your Website"
    relative: false 
---

App Store reviews will make or break the success of your app. Apple makes it no secret that [ratings and reviews are highly impactful](https://developer.apple.com/app-store/ratings-and-reviews/) on app increasing installs. 

Reviews are one of the leading factors that help determine your ranking in App Store search and your conversion rates. Getting more 5 star reviews will help you get more traffic, more downloads, and more sales.

## Why You Should Display App Reviews on Your Website

After launching my first app, I was looking for more ways to increase installs of my app. I wanted to promote my app outside of the App Store, so I focused on driving installs from the web using the website I created for my app. 

I knew how important reviews were for getting users to install my app. Data shows that users are [twice as likely to download an app with 4 or more stars](https://www.marketingprofs.com/charts/2015/27665/how-influential-are-mobile-app-star-ratings) compared to 3 or less stars!

I wanted to display the 5 star reviews of my app on the website I had created. I searched for an easy way to show off my app reviews but I could not find one.

I needed a tool that could:

1. Fetch and display reviews of my app from the App Store
2. Automatically update when new reviews get added
3. Embed easily on any website and be responsive on mobile
4. Only show the latest 5 star reviews
5. Display reviews in a nicely designed auto-scrolling carousel

Since I could not find a tool to do this, I built my own.

What I made is a tool to create an embeddable carousel of your app reviews that looks like this:

<script src="https://tylerkennedy.co/assets/js/iframeResizer.js"></script>
<iframe src="https://tylerkennedy.co/embed-app-store-reviews/widget/?id=1540836811&rating=5" frameborder="0" width="100%"></iframe>
<script>iFrameResize({ log: true })</script>

The widget can be embedded on any website and is responsive on all screen sizes. The carousel automatically scrolls, showing only your latest 5 star reviews from the App Store and the reviews are updated automatically. 

## How to Add App Store Reviews to your Website

To get started, [go to this page](/embed-app-store-reviews/) to generate your reviews carousel. Then, grab the URL of your app from the App Store.

### Finding Your App's URL from the App Store

This is usually the link that you would share for users to download your app. However, if you don't have that on hand, there are two ways to find the URL:

1. From your phone, go to your app on the App Store and click the 'Share' icon near the top. Then click 'Copy Link' to get the App Store URL for your app. 

2. In a web browser, find the webpage for your app on the App Store and copy the URL of the page.

Now that you have the URL, copy it from the App Store and paste it into the tool and click **Create Widget**.

This will generate a few lines of code that look like this:

    <script src="https://tylerkennedy.co/assets/js/iframeResizer.js"></script>
    <iframe src="https://tylerkennedy.co/embed-app-store-reviews/widget/?id=1540836811&rating=5" frameborder="0" width="100%"></iframe>
    <script>iFrameResize({ log: true })</script>

This is the code for the carousel widget. Paste this code into any website to display your new carousel of App Store reviews!

## How to Embed App Store Reviews on Carrd.co Websites

![Carrd Website Builder](/assets/images/blog-covers/carrd.png#center "Carrd Website Builder")

[Carrd.co](https://try.carrd.co/1zf1rsmd) is one of my favorite tools to quickly build a website. Their interface is intuitive and easy to use for creating single page websites without writing a single line of code. I can't think of a single other tool that allows you to go from nothing to a published website faster.

This tool is especially useful for quickly [creating a website for your iOS app](/blog/how-to-build-a-website-for-your-ios-app-with-carrd/). Using Carrd.co will save you tons of time designing and you don't have to worry about writing any more code or learning HTML/CSS/JS if you are coming from Swift. 

I'll show you how you can add app reviews to an existing Carrd.co website or quickly build a new site from scratch and embed your reviews.

### Create a Free Account on Carrd.co

The first step is to make sure you have an account on Carrd.co. If you don't have one already, you can[ create one for free](https://try.carrd.co/1zf1rsmd).

Once you've got your Carrd.co account setup, you are ready to go. Next, either navigate to an existing website in your account dashboard, or create a new website. Follow along with[ this guide for more help](/blog/how-to-build-a-website-for-your-ios-app-with-carrd/) creating your website with Carrd.co.

### Create App Reviews Carousel Widget

If you didn't already do this [above](/blog/how-to-embed-app-store-reviews-on-your-website/#how-to-add-app-store-reviews-to-your-website), you need to generate your reviews carousel widget.

Grab your app's URL from the App Store and paste it into the [widget generator tool](/embed-app-store-reviews/) and click **Create Widget**. This will create the widget embed code you need.

For now, save this code and we will use it in the next step to show your app reviews on a Carrd.co website.

### Add an Embed Element

On your Carrd.co website, you will only need to create one element to add your reviews. 

At the menu bar to the top right of the screen, click the 'plus' icon to create a new element. 

![Carrd.co Menu Bar](/assets/images/carrd-menu-bar.jpg#center "Carrd.co Menu Bar")

From the dropdown menu, select the 'Embed' element and place it where you would like on your website.

Next, click on the embed element so that you can edit its properties, then do the following:

1. Select 'Code' for **Type**
2. Select 'Inline' for **Style**
3. Paste the code generated from the widget tool into the **Code** box

**Note: Don't worry if you can't see your reviews right away, the reviews carousel will not display in the Carrd.co editor. The embedded reviews will be shown when you publish your website.**

Once these steps are complete, your app reviews widget is ready to show off your 5 star app reviews on your website.

### Publish Your Website with Embedded App Store Reviews ⭐️

![Carrd.co Website with Embedded App Reviews Carousel Widget](/assets/images/embed-app-store-reviews-carousel-on-carrd-website.png#center "Carrd.co Website with Embedded App Reviews Carousel Widget")

When your website is ready, hit the publish button on the menu bar so your site can go live. When you visit your now published site, you should see the app reviews carousel. 

You can checkout this [demo website](https://app-reviews-carousel.carrd.co) I put together to show off the app reviews carousel widget in action.