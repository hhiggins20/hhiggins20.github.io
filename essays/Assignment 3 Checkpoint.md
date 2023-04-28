---
layout: essay
type: essay
title: "Assignment 3 Checkpoint"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels: 
 - MIS
 - Assignment 3
 - Checkpoint 
---

# Screencast Link

<a href="https://drive.google.com/file/d/1Jib5kYYrj-tiIZBN1p_td6iN5lkA04u0/view?usp=share_link">Click Here</a>
   
# Show what each page will look like.

My website will have three pages each selling a different category of clothing.  These three categories will be t-shirts, shorts, and socks.  I will have an assortment of colors for sale on each of these pages, which will allow you to put them in your cart once you log into the website.  The login page will have a register button down at the bottom in case the user has not registered yet, and once logged in you will be returned to the homepage.  Once you are ready to make your purchase you can go to your cart and click confirm to load the invoice and send out the email.

# Describe your design for your site’s shopping cart. 

My shopping cart will be on a separate page from the purchasing and home pages.  This is to simplify the website design and prevents bugs from happening.  This will work by POSTing all of the data inside of the quantity textboxes into the shopping cart page when it loads.  On the shopping cart page, you will be able to remove any items that are currently inside your cart.

# Explain specifically how you will use sessions to manage your shopping cart.

The shopping cart data that will be stored in sessions will be the number of items you currently have added to your cart, as well as your username and login info.  Once you are logged in, the data inside your cart will be saved until the website is closed or shut down.  The data format that will be used will be JSON object arrays that are stored inside of the session that is currently active.

# How will you avoid access to your application when the user has not logged in or registered?

I will avoid access to my application when the user is not logged in by using login sessions that prevent certain web pages on my server from being loaded without the user first logging in.  Some security concerns that I must address include people typing in the URL directly, and people attempting to access other's user data.

# Upon successful login, how do you provide personalization in your UI?

I will personalize the UI by showing the user's name in the corner of the screen on the store pages, as well as the shopping cart and invoice.  The best way to do this is to load the user's name in the JSON object and have it rendered on the page using HTML.

# If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible?

I am not working with any partners on this assignment

# How are you approaching Assignment 3 differently than Assignment 2?

I am going to approach Assignment 3 differently than Assignment 2 by making sure I know what I am doing before I begin to change anything inside of my code.  I found out the hard way on Assignment 2 that if you do not have a plan before you begin, you will end up making a mess that is difficult to clean up in the future.
