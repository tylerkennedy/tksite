---
title: "How to Add Google Analytics or Cloudflare Analytics to Carrd.co"
description: "Learn how to embed analytics from Google or Cloudflare into your website built with Carrd.co"
date: 2022-12-03T18:52:42-05:00
draft: false
author: "Tyler Kennedy"
cover:
    image: "assets/images/blog-covers/add-google-analytics-or-cloudflare-analytics-to-carrd.png"
    alt: "How to Add Google Analytics or Cloudflare Analytics to Carrd.co"
    relative: false 
---

If you've read any of my other posts, you know that I love using [Carrd.co](https://try.carrd.co/1zf1rsmd) to build websites.

Carrd.co is an excellent platform for anyone looking to build a website quickly and easily. It offers a user-friendly drag-and-drop interface that allows anyone to quickly create a professional-looking website without having to learn any coding. 

It is incredibly affordable, offering a free plan and various paid plans so it fits any budget. With its simple yet powerful features, Carrd.co is a great option for anyone wanting to quickly build a website without writing any code.

## Add Google Analytics to Carrd.co

[Carrd.co](https://try.carrd.co/1zf1rsmd) makes it really easy to add Google Analytics to their websites. Here are the steps:

### Log into Google Analytics

First you will want to [sign into Google Analytics](https://analytics.google.com/). 

If you don't already have a Google Analytics account or your website is not added to Google Analytics as a property, here is [how to set it up](https://support.google.com/analytics/answer/9304153).

### Find Measurement ID

Once your account and website property is setup in Google Analytics, you need to [find your **Measurement ID**](https://support.google.com/analytics/answer/9539598)

Go to the **Admin** panel, then choose your property. Click **Data Streams** under that property then click on your website name to open up the panel. 

In the popup panel you should see your **Measurement ID** that starts with 'G-'. Copy the Measurement ID.

### Go to your Carrd.co Website 

Now that you have your website added to Google Analytics and found the Measurement ID, visit [Carrd.co](https://try.carrd.co/1zf1rsmd) and go to your website you want to setup with analytics. 

### Paste Google Analytics ID 

Next, click **Publish** at the top of the page, then click the **Settings** tab.

![Carrd Embed Element Menu Google Analytics](/assets/images/carrd-google-analytics-menu.png#center "Carrd Embed Element Menu Google Analytics")

In the **Google Analytics ID** field, paste your Measurement ID that you got from the Google Analytics dashboard. 

### Publish Website

Your site is now ready to publish and you have successfully setup Google Analytics with your Carrd.co website. When you publish your website and start getting traffic, it will show up in your Google Analytics dashboard.

## Add Cloudflare Analytics to Carrd.co

I use Cloudflare for almost all of my web projects. They have a ton of free tools available for developers. Most people have heard of their [free CDN](https://www.cloudflare.com/plans/free/) and use it to serve their content. 

But, they also make it easy to host a website, deploy serverless code, or store data (all for free!). If you haven't used Cloudflare's developer platform, you should definitely check it out. I can't recommend Cloudflare's [Workers](https://workers.cloudflare.com) and [Pages](https://pages.cloudflare.com) platform enough.

One other free tool that Cloudflare offers is [Web Analytics](https://www.cloudflare.com/web-analytics/). Since I already use so many of Cloudflare's tools for my websites (including this one), I also like to use their analytics.

Adding their analytics to a Carrd.co website is really easy.

### Log into Cloudflare

The first step is to log into your Cloudflare account and go to your [dashboard](https://dash.cloudflare.com/login). If you don't have an account, you can [create one for free](https://dash.cloudflare.com/sign-up). 

### Add a Site

The next step is to add your website to Cloudflare Analytics. In the dashboard menu, click **Analytics** and then click **Web Analytics**. 

Next, click **Add a site**. If your website and its domain are being managed through Cloudflare's name servers and DNS, select your domain from the dropdown. 

If you are not using a custom domain with Carrd.co or don't want to host your DNS with Cloudflare, type your domain name into the input box. 

If you are hosting your website on a Carrd.co subdomain, type in a domain that looks something like this: tylerkennedy.carrd.co

Click **Done** after entering your domain name.

### Copy the Analytics JS Snippet

Now you should see a JavaScript code snippet. This is what you'll be pasting into your Carrd.co website to setup the analytics tracking. 

![Cloudflare Analytics JS Snippet](/assets/images/cloudflare-analytics-js-snippet.png#center "Cloudflare Analytics JS Snippet")

For now, copy this code or keep the webpage open so you can come back to it. 

### Log into Carrd.co

Now that you have the Analytics setup, go to your [Carrd.co](https://try.carrd.co/1zf1rsmd) account and browse to the website you want to add the analytics.

### Create an Embed Element

On your website, add an **Embed** element to the page. It doesn't matter where you add this element to the page because it will be hidden and not shown to users. I usually like to place it at the bottom just so that it is out of the way while I am designing my site. 

![Carrd Embed Element Menu Cloudflare Analytics](/assets/images/carrd-embed-element-menu.png#center "Carrd Embed Element Menu Cloudflare Analytics")


On the **Embed** element, you will want to select **Code** for the **Type**. You can give the element a label, I usually call it 'Analytics'. Then for **Style** choose **Hidden** and **Head**. This will make sure your analytics element is not shown on the page and gets added to the header. 

### Paste JS Snippet

This is the part where you need the JS snippet from the Cloudflare dashboard. Copy the code snippet and paste it into the **Code** box. 

### Publish Website

The only thing left to do is publish your website. Click the **Publish** button to launch your website. When you publish your website, make sure that the domain you publish to matches the domain you setup in Cloudflare.

Once your site goes live, you should start seeing page views and visits in the Cloudflare Analytics dashboard. 

## Add Other Analytics Tools to Carrd.co

There are tons of other options for analytics besides Google or Cloudflare. If you choose to use another analytics tool, the process for adding it to your Carrd.co site is basically the same.

### Generate Analytics JS Code

This step will depend on what analytics platform you are using but you'll need to get the code snippet they use to embed analytics on websites. 

### Create Carrd.co Embed Element

Now that you've got the analytics code copied, you need to embed it in your Carrd.co website. 

Create an **Embed** element on your website. Typically, I place it at the bottom of the page so that it is out of my way while I am working on my website. 

Then on the **Embed** element, select **Code** for the **Type**. Give the element a label, and call it 'Analytics'. For **Style** choose **Hidden** and **Head**. 

The last step is to paste in the analytics code into the **Code** box. Once you complete this step your site is ready to publish and your analytics will be activated. 