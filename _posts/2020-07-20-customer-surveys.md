---
layout: post
title: Customer Surveys

---
In the past few months, I’ve increasingly begun to think more about incorporating qualitative feedback into our processes at Gainful.

The challenge for me has always been figuring out the most efficient process to collect feedback and summarizing those insights to be able to take action on them.

This post contains the exact step-by-step process I use to reach out to customers, collect feedback, and summarize responses for insights.

## Step 1: Draft survey questions

I start by identifying the exact questions to ask customers. The key here is to figure out what information you are trying to collect and how they will be used to improve your work.

For most of my surveys, I focus on open-ended questions instead of multiple-choice responses. I do this to get very specific customer language and prevent my own biases for what buckets of insights these responses may fall under.

These are the top questions I ask and the intention behind each one:

* How would you feel if you could no longer use Gainful?
  * Why? - Leading indicator for Product-Market Fit / Retention
* What made you buy Gainful?
  * Why? - Product Benefits
* What is the main benefit you receive from Gainful?
  * Why? - Product Benefits and Value Proposition
* How often do you use Gainful?
  * Why? - Product Usage
* How are you consuming Gainful protein in your everyday routine?
  * Why? - Product Usage
* What would you use if Gainful were no longer available?
  * Why? - Competition Insights
* What type of people do you think would most benefit from Gainful?
  * Why? - Persona Development
* What would you say about Gainful to persuade a friend to try it?
  * Why? - Voice of Customer Benefits and Value Propositions
* How can we improve Gainful for you?
  * Why? - Product Improvements

## Step 2: Set up the survey tool

Once I’ve identified the key pieces of insights I’m looking to gather and the questions that help me identify them, I then add those questions into a survey tool to collect responses.

**Typeform**

My preferred tool is Typeform as I find the experience to be the simplest to use while also offering a degree of flexibility to “brand” the survey.

**Title Page**

I typically set up a title page prior to the survey questions, a nice little feature Typeform has.

![](/uploads/typeform-title-page.png)

I write one sentence to thank the customer for helping us gather feedback, and set expectations for how long the survey will take them to complete.

**Question Settings**

Aside from the first question in my survey, I use the ‘Long Text’ question type so that customers can expand their responses as much as possible.

![](/uploads/long-text-question-type.png)

For the first survey question I use a multiple choice question type and use the following options:

* Very Disappointed
* Somewhat Disappointed
* Not Disappointed

![](/uploads/multiple-choice-pmf-question.png)

This question has been used as a leading indicator for a company’s product-market fit. Rahul Vohra [wrote a great piece](https://firstround.com/review/how-superhuman-built-an-engine-to-find-product-market-fit/) about using this question as the basis for Superhuman’s engine to achieve product-market fit.

**Hidden Fields**

An important part of the survey setup is adding hidden fields so that you can properly attribute responses to specific customers and segments.

The top of each Typeform survey will have a section for you to input your fields to be populated and will reflect in the URL parameters of your survey link.

_I go into more detail in Step 4 on how to dynamically populate these hidden fields from each customer email response._

## Step 3: Identify customer segments

Next, I’ll identify the exact customer segments I’ll want to reach out to and gather feedback from. For the purposes of the survey questions listed above, I typically aim to reach out to all customers who have retained after their first month of using Gainful.

These specific segments to reach out can vary depending on the outcome I am trying to produce. For example, I may choose to focus on a particular subscription plan for a specific gender if I’ve noticed the retention metrics are lower than the customer average.

I’ll dig up the names and emails for the target customer segments from our internal database and export the list for the next step in the process.

## Step 4: Set up the email outreach tool

A key part of what makes this process so scalable is using an outbound email tool to help automate the process.

The tool I’ve found perfect for this process is Mailshake. What’s great about Mailshake is it allows you to send outbound emails using your personal work email account (as opposed to an ESP like Mailchimp) and use mail merge tags to dynamically personalize the content of the outreach email.

**Template**

Once I connect my email account, I can create a campaign and select the recipients from the customer list exported in the last step. From here I draft up the outreach template and select the appropriate mail merges to insert the customer’s first name.

![](/uploads/mailshake-outreach-template.png)

The template I use above is the exact copy I use to reach out to customers. I like to start off by explaining how important customer feedback is to make the product better for them. In the second line, I’ll introduce myself and reiterate how we aim to keep improving the product and delivering the best customer experience that we can. I’ll end the email with an ask to complete a survey and thank them.

Regarding the survey link here, I’ve found it important to set expectations for how long the survey will take. This has helped ensure an 80%+ response rate once a customer clicks on the link. I also like to extend the survey link to more words instead of just ‘click here’ (this makes it harder for the customer to miss the link).

**Preview**

In the next part, you’ll have the option to preview each customer’s individual email outreach and spot any mistakes. Mailshake will also let you know if any customers have missing mail merge fields.

![](/uploads/mailshake-preview-screenshot.png)

**Schedule**

Finally, I’ll schedule the email to go out starting on a specific date and time. The sending part of this process is crucial to set up. In the first few runs using this system I ended up running into some spam traps and my email account was temporarily suspended.

![](/uploads/mailshake-sending-rules.png)

You can set up the exact sending rules for your email account pictured above. For personal Gmail accounts, the sending limit is 500 emails/day and for GSuite business accounts the sending limit is 2000 emails/day. I personally hit the spam traps at 500 emails/day and ran into fewer issues at 250 emails/day.

I’d personally recommend using an email account on a separate domain from your company’s main domain to avoid hurting your email reputation (which can have downstream consequences on your marketing promotional and transactional campaigns).

## Step 5: Analyze responses

The last step of the process is to collect and analyze responses for insights.

I like to use Airtable to collect each new response as they come in so I can more easily manually bucket each response into appropriate response categories.

![](/uploads/typeform-airtable-integration.png)

Typeform has an easy integration with Airtable that takes less than a few minutes to set up.

![](/uploads/airtable-category-bucket.png)

My process from here once responses start populating is to create a column next to each question to bucket each response into a high-level category. This makes it a lot easier to report off and surface insights.

Once all responses are categorized I’ll export the results and visualize the insights into a pie chart.

## Improvements

This is an evolving process for collecting customer insights and I’m always looking for ways to improve each step.

How do you think this process can be improved? I personally find the bottleneck to be finding time to manually bucket responses the most challenging. Reach out on Twitter or drop me an email if you have any thoughts!