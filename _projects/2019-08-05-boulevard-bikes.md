---
title: 'Boulevard Bikes'
subtitle: 'An e-commerce site design'
date: 2010-08-05 00:00:00
description: This is a re-design of an e-commerce application for a local business.
featured_image: '/images/boulevard-bikes/banner.jpg'
---

<div class="gallery" data-columns="1" style="max-width: 900px;">
	<img src="/images/boulevard-bikes/high_fidelity/laptop_screen_1.png">
	<img src="/images/boulevard-bikes/high_fidelity/laptop_screen_2.png">
	<img src="/images/boulevard-bikes/high_fidelity/laptop_screen_3.png">
	<img src="/images/boulevard-bikes/high_fidelity/laptop_screen_4.png">	
</div>

# Boulevard Bikes

---

For my second project at General Assembly, I designed and prototyped an e-commerce application for Boulevard Bikes, a local bike store in Logan Square

## User Research

---

I first ran a competetive analysis. This analysis compared the existance of 40 different features on seven different bike store websites spanning all of Chicago. There were a few key takeaways from this, the biggest and broadest being that there are a lot of retailers that have online storefronts. Even local retailers. Secondly, while there is plenty of variety in the features of online bike storefronts, there is a basic, refined formula that goes into a lot of the sites. Following pieces of this formula helped me establish the basic outline of my page.

I then reached out and e-mailed the owner of Boulevard Bikes to see if he had any interest in taking part of my research in exchange for free design. He boldly stated that he had no interest in developing an online store front and believed in the importance of brick and mortar business. I then managed to get two guerilla user interviews outside the storefront before getting kicked out. After that, I found two people I knew who both had shopped at Boulevard Bikes in the past as well as two people who had bought bikes online. I managed to get extensive interviews with all of them.

---

I had a few key takeaways from my user interviews:
* Users want to compare, customize and test bikes.
* Users want to buy used bikes.
* Users want a way to access the store’s policies. (Returns important)
* Users want to see the store’s services.
* Users want competitive prices.
* Users want control over the aesthetics of their bike.

---

From this information, I was able to formulate my problem and solution statements.

##### My problem statement:
As a city biker who is in the market for a new bike but unsure where to shop, I need a way to shop between an online and in-store experience because I will benefit from detailed specifications, access to staff, and a wide selection of bikes.

##### My solution statement:
Create an e-commerce website that allows its users to search for, compare, and buy bikes as well as schedule times to come in and test bikes. It would also allow users to chat with staff directly to receive expert advice on their purchases.

## Synthesis

---

Using this statement and my user research as a guide, I created an affinity map to diagram my progress. It is from this research that I was able to go back and refine the questions from my user interviews for potential future use. From this research, I was able to identify several pain points including:
Users want reviews
Users want social media presence
Users do not want to be upsold.
Users do not want to deal with snobbish employees.
Users do not want bikes that aren’t durable.

I performed an Information Architecture analysis on the existing Boulevard Bikes website by documenting its existing site map. The site map turned out relatively flat, highlighting the original site’s mostly static architecture. The site seemed almost like the shell of an online store, minus the ability to buy bikes. Additionally, I found that since Boulevard Bikes preferred a brick and mortar approach to business, I would have to tailor the online experience to integrate with the in-store experience.

From all of this, I created two user personas: Sarah Norman a 24 year old biker who’s fairly new to riding in the city, but in the market for her second bike, and Tom Mashkovic, a bike messenger from the Chicago south side who is always in the market for a new bike. With these two personas, I identified pain points that they would like to tackle while shopping for a new bike.

<div class="gallery" data-columns="2">
	<img src="/images/boulevard-bikes/personas/persona-sarah.png">
	<img src="/images/boulevard-bikes/personas/persona-tom.png">
</div>

Next came an update to the site map. I included a bike comparison page which convoluted the depth of the site map as it looped around from bike details to bike comparison and back again. I also added in a feature to shop for accessories as well as a cart/checkout function as the key points I would tackle in my prototype.

From here, I created a user flow. The user flow was fairly simple. It introduced the ability to chat with the bike store staff via a small popup window in the corner of the screen as well as a way to view the biography of the last person to service your bike conveniently placed in the product detail page.

<div class="gallery" data-columns="1" style="max-width:900px;">
	<img src="/images/boulevard-bikes/user_flow/user_flow.png">
</div>

It was time to create my initial user sketches. I decided to model my basic site outline by combining the outlines of two online storefronts that were prominent in the area. From this, I included my new features, on top of which were image carousels that highlighted the flaws in the used bikes, thereby solving one of the major pain points with my users which was honesty and transparency from the store staff.

<div class="gallery" data-columns="2" style="max-width:600px;">
	<img src="/images/boulevard-bikes/sketches/sketch_1.JPG">
	<img src="/images/boulevard-bikes/sketches/sketch_2.JPG">
	<img src="/images/boulevard-bikes/sketches/sketch_4.JPG">
	<img src="/images/boulevard-bikes/sketches/sketch_3.JPG">	
</div>

The online checkout would be modeled after Amazon, the current forerunners in the UX shopping experience worldwide. The placement of features and the labeling of forms were both modeled off of the existing Amazon storefront.

## Usability Testing

---

After adapting these sketches into a simple paper prototype, I was ready to begin usability testing. I found three willing participants who gave me feedback on the basic outline as well as the usability of the site’s unique features. From these critiques, I was able to move forward into a digital wireframe.

I admittedly moved a bit too quickly into the design phase of things, increasing the fidelity of my prototype before taking it in for usability testing. Luckily, the design I settled on was simple enough that I was able to make changes quite easily with my second set of testing. 

I ended up getting much more detailed insights from my second round of user testing. I ended up changing the adjusting quite a bit of text to make things more readable. I added a carousel select screen to the comparison page and a search bar to make navigation quicker and easier. The chat button needed to be a good deal brighter. The product detail page was vague in my first draft and needed a good deal of expansion and adjustment. I replaced a lot of hyperlinks with buttons to improve visibility and made my checkout page look a little closer to Amazon’s which I felt was the most refined and convenient example of checkout UX I could find. These changes, among other things smoothed out my user flow substantially.

In my final round of user testing, the changes I made to the UI were considerably less dramatic. I added Paypal and GPay buttons to the checkout for convenience's sake. I adjusted the payment system to limit the amount of names a person could include on their checkout for clarity. I adjusted the text on several buttons to make their functions more obvious at first glance. A huge change was simply adding contact and location information on the front page in a spot where they could easily be found.

## What's Next?
---
So what are my next implementations for this project? The compare feature needs to be more fleshed out. I would like the user to be able to easily find and compare as many bikes as they want and the comparison page needs to be updated accordingly. The bike testing scheduler also needs to be implemented. I would like to add a way for users to schedule appointments to test bikes. A sizing and geometry guide will be helpful to let users fit their bikes before buying. Finally, I would like to make the chat window easier to find. One common pain point on my site that I wasn’t able to address was the findability of the chat window. This was hard to address in invision with the level of fidelity that I was working with.

## Conclusion
---
I’m glad I was able to work with such a complex and personally intriguing subject and I feel like I walked away from this project with a good deal more knowledge in the tools and processes required to be successful in the field. I learned a lot over the course of this project and had a lot of fun in the process.