---
layout: post
title:  "Don’t let feature requests from your customers drive your product roadmap!"
date:   2020-05-30 01:03:29 +0200
categories: Product-Management
comments: true
---
Yes, you read it right! Don’t let the feature requests you receive from your customers drive your product roadmap. Instead, let the real problems they are facing do.

Nearly 4 years ago, when I had just transitioned from engineering to product management here is how I used to respond to one of the most important questions that you get asked as asked as a product manager.
<!--more-->

<div style="padding:20px;background-color:#333;border-radius:5px;font-family:monospace;font-size:15px;font-style:italic;color:white;">
<span style="background-color:#ff7a59;padding:3px;border-radius:3px">Question</span> - Why do you think this feature should be on the roadmap? <br>
<span style="background-color:#5469d4a3;padding:3px;border-radius:3px">Answer</span> - Because customers XYZ and ABC have asked for it
</div>
It sounds naive in the hindsight but I’ve cut myself some slack given it was my first time as a product manager. 

Sometimes, we as product managers consider the number of customers that have asked for a particular feature as a parameter to add weight to the decision of adding it to the roadmap. However, it is easy to fall prey to this vanity metric by right away acknowledging the feature request as a gap in your offering that needs to be filled without analysing the feature request thoroughly. Analysing your customers’ feature requests in a proper manner will help you identify the right set of problems your customers are facing. Many times, you will realize that the problem does not have to be solved by the exact feature the customers are suggesting. 

While there are numerous ways in which one could dissect the feature request , the <a href="https://hbr.org/2012/02/the-5-whys.html"><b>FIVE WHYS framework</b></a> provides a simple and effective way of getting to the core of the problem.  The 5 Whys framework is an iterative interrogation technique to determine the root cause of the problem by repeatedly asking the question -  “Why” . Here is an example of my recent experience of using this framework to address a customer’s feature request. 

<div style="padding:20px;background-color:#333;border-radius:5px;font-family:monospace;font-size:15px;color:white;">
<span style="background-color:#ff7a59;padding:3px;border-radius:3px">Customer</span> : We’d like an API endpoint to fetch the loyalty information of users. <br><br>
<span style="background-color:#5469d4a3;padding:3px;border-radius:3px">Me</span>: Could you please let us know why you would want an API endpoint since you already have this information in the members’ report? <br><br>
<span style="background-color:#ff7a59;padding:3px;border-radius:3px">Customer</span> :   We’d like to build an automated process of getting the information via an API every night and dump that information at an FTP location ?<br><br>
<span style="background-color:#5469d4a3;padding:3px;border-radius:3px">Me</span> : Alright, sounds good. Could you please tell me why you would want to dump this information at an FTP location ?  What happens after you dump it to FTP location.<br><br> 
<span style="background-color:#ff7a59;padding:3px;border-radius:3px">Customer</span> : We have crons that would read the information and sync the information with the contacts in Hubspot CRM . <br><br>
<span style="background-color:#5469d4a3;padding:3px;border-radius:3px">Me</span> : Okay. Why do you sync the loyalty information in Hubspot ? <br><br>
<span style="background-color:#ff7a59;padding:3px;border-radius:3px">Customer</span> :  We want to use the loyalty information to be included in the marketing emails that we send.<br><br>
<span style="background-color:#5469d4a3;padding:3px;border-radius:3px">Me</span> : We already have Hubspot integration underway exactly for this use case. Every time the loyalty information of the user changes, the change will be synced with the Hubspot user profile automatically with the integration. You could then set triggers in Hubspot to send out emails with the loyalty information. 
</div>

In the above example, although it seemed like a feature request for a new API endpoint, the ultimate job that the customer was looking to get done with this API was to include the loyalty information in the marketing emails sent via Hubspot. The actual problem was unearthed by repeatedly asking the question "Why". Evidently, the plethora of information this framework gives you as you go deeper layer by layer not only helps you reach to the core of the problem but also gives you holistic insights about it. You may choose any other framework that helps with problem analysis. The bottomline is to ensure that you thoroughly understand the rationale behind the feature request. 

Customers will often ask you the world. More often than not, the feature requests your customers raise if considered verbatim, have the potential to derail your product strategy. Tending to such feature requests without peeling the layers of the onion may help you pacify a couple of customers but will harm your product in the long run. For a winning product strategy , it is very imperative to choose solving those problems that align with your product and company goals.

After all , effective product management is not just about solving problems but about choosing  the right set of problems to solve.

[Read-More]: http://localhost:4000/2020/05/30/Don-t-let-feature-requests-from-your-customers-drive-your-product-roadmap!/

