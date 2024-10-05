<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see useful information and inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 15

Conversion time: 4.037 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β39
* Fri Oct 04 2024 23:04:23 GMT-0700 (PDT)
* Source doc: Blueprint for Platform Product Roadmaps
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!


WARNING:
You have 13 H1 headings. You may want to use the "H1 -> H2" option to demote all headings by one level.

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 1; ALERTS: 15.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>
<a href="#gdcalert5">alert5</a>
<a href="#gdcalert6">alert6</a>
<a href="#gdcalert7">alert7</a>
<a href="#gdcalert8">alert8</a>
<a href="#gdcalert9">alert9</a>
<a href="#gdcalert10">alert10</a>
<a href="#gdcalert11">alert11</a>
<a href="#gdcalert12">alert12</a>
<a href="#gdcalert13">alert13</a>
<a href="#gdcalert14">alert14</a>
<a href="#gdcalert15">alert15</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



# Blueprint for Platform Product Roadmaps


## A practical guide for people building platforms in 2024.

By [Vik Chaudhary](https://www.linkedin.com/in/vikchaudhary) and [Sid Palani](https://www.linkedin.com/in/sidpalani)

Published on Tue  on [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7216475133052432388?updateEntityUrn=urn%3Ali%3Afs_feedUpdate%3A%28V2%2Curn%3Ali%3Aactivity%3A7216475133052432388%29), [Neuronn on LinkedIn](https://www.linkedin.com/posts/neuronn_there-are-many-resources-for-product-managers-activity-7216440984052588545-Bko6?utm_source=share&utm_medium=member_desktop), [Substack](https://neuronn.substack.com/p/blueprint-for-platform-product-roadmaps?r=hhsh6&utm_campaign=post&utm_medium=web&triedRedirect=true) and [Google Slides](https://docs.google.com/presentation/d/113AWG-9jQnw_atpwovsRDxFco6JSIVHcN-h8qhk8DOI/edit?usp=sharing)



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.jpg "image_tooltip")



# Our Motivation

There are many resources for product managers of consumer apps or B2B applications. However, we see a gap in PM resources for the unique challenges of building platforms, which serve as foundational tools for developers (e.g., AWS, Cohere, GitHub, Google Vertex AI, OpenAI GPT, Shopify, Stripe, and Twilio) and are becoming increasingly common in the AI era. This article aims to bridge that gap by providing a framework to outline a platform roadmap. It is intended for product managers, engineering leaders, CIOs, and CEOs thinking about building platforms, and uses an example framework to create strategy, articulate benefits, prioritize features, and deliver a roadmap for a platform product.

Our experience with developer and ML platform teams at Meta is that roadmaps often begin with goals like collaboration, code reuse, and efficiency. However, teams easily become fragmented, leading to frequent software updates, numerous API versions, legacy code use cases, incoherent user experiences, and growing technical debt. The problems that compound over time include:



* **Fragmented User Experience**. Developer experience is spread across many UX surfaces, which users struggle to navigate, relying on word-of-mouth guidance, and incomplete documentation hampers onboarding. At Meta, engineers encountered dozens of applications throughout the software lifecycle, when perhaps ten might have sufficed.
* **Software Management. **There is often no comprehensive view of all application dependencies like libraries, data stores, or clusters. Tracking signals such as QA status, deployments, alerts, and open tasks are done ad hoc. This raises a developer’s cognitive load and inefficiencies.
* **Unreliable Systems.** Automated dependency updates cause more production errors, leading to time-consuming debugging, crucial downtime incidents, and slow root cause analysis. 


# What Are Platform Products?

A software platform provides a foundation (e.g., environment, tools) that developers, either internal or external, use to build applications more easily than building and maintaining everything themselves.

Some renowned platforms for developers include **Stripe**, which powers website payments through easy-to-use APIs in familiar languages like JavaScript or Python. **Kubernetes** helps scale websites during peak times, such as Black Friday sales, by automatically adjusting resources, like servers, to meet demand without overpaying for unused resources. **Hugging Face** is an AI platform offering tools and models for natural language processing (NLP). For example, it can help a news service generate brief summaries from long articles, saving users time while keeping them informed.



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")



# Framework

In our examples, we will address developers' workflow using a platform to build front-end applications, back-end services, or data management services. In doing so, we plan to answer the following questions:

1. How do you set a platform's vision, strategy, and guiding principles?

2. How do you measure success? 

3. How do you prioritize a platform roadmap?

4. How do you create a timeline for the roadmap?

5. What is the Go-to-Market plan that ensures adoption?




# 1. How do you set a platform's vision, strategy, and guiding principles?


## Product Vision

A product vision is a statement that outlines a product's purpose, value, and long-term goals. Here’s an example of an internal developer platform at Meta that helps developers build and operate consumer apps like Facebook:



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")





## Principles for Internal Platforms

When building a Platform for internal use, be driven by deep discovery, 10x problem-solving, adoption, and impact. Our guiding principles are:



1. Adopt a product mindset
2. Focus on customers critical to growth
3. Provide self-service capabilities


#### 1. Adopt a product mindset



* Internal developer tools should solve the most painful problems first.
* Have an opinionated point of view on the tools offered and reduce UX surfaces.
* Measure the success of accelerating software delivery and reducing time spent on incidents.


#### 2. Focus on customers critical to growth



* Segment developers to understand their impact on future growth: e.g. ML vs software engineers.
* Understand each segment’s critical needs to build the platform roadmap.
* Prioritize features based on requirements, effort, and measurable impact on business.


#### 3. Provide self-service capabilities



* Hide complexity: automate feature delivery, testing, performance, and security requirements in a simple UX.
* Simplify deployment: Clear documentation, fewer services, common configuration templates / smart defaults, and standardized libraries for observability and workload deployment.
* Deploy customized onboarding tools based on developer personas.




## Benefits of a Developer Platform

What is the rationale for building a developer platform? A platform allows a company to provide its core offerings in a way that can easily adapt and scale into a large ecosystem of customers and partners. It benefits the ecosystem because it creates a common language for building and adopting core features, making development easier and increasing velocity, leverage, and impact for the business. 



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")


The best-in-class tooling from each development team can be centralized in the engineering platform for all other teams to benefit from. In addition, having a robust, well-documented engineering platform can expedite the time from hire to first pull request, increasing the productivity of new or transferred developers.




## Evergreen Priorities

While every platform is unique, it shares a set of “always-on” priorities that ground a roadmap: developer experience, delivery, and reliability. Developers are not only the core users but also the force multipliers for the platform’s impact and scale. These priorities address core needs regardless of specific use cases and provide helpful constraints to manage the numerous possible directions platforms can take.



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")



## Considerations for AI / ML Platforms

Platforms that employ artificial intelligence and machine learning features have specific important nuances worth highlighting. It is important that priorities account for these elements:



1. **Data Management.** Data is the lifeblood of AI models–it drives the training, fine-tuning, and evaluation of models put into use. Therefore, a scalable ML platform needs to consider specifically how developers can easily and securely store, retrieve, and label training and evaluation data that is used in model development. 
2. **Cost (Compute) Management.** As developers are given more control over training and fine-tuning models for specific use cases, the platform needs to account for how to share and allocate training costs and provide control to the developers to manage within their budgets. This is especially true today while computation cost is a major barrier to leveraging AI.
3. **Steerability.** As use cases for ML continue to expand beyond largely creative use cases into regulated industries (e.g. healthcare, finance) with a greater degree for harm, the ability for developers to understand and interrogate why models make predictions they do becomes imperative–both for rapid product improvement and societal trust. A long-term consideration for ML platforms will be investment in features that provide transparency to developers, with interpretability and explainability.
4. **Success Measures. **A measurement framework (discussed below) will need to integrate common ML model performance metrics such as accuracy, precision, and recall that are often upstream of core product metrics but offer another area that can either help or hurt a developer’s experience of the platform.




# 2. How do you measure success?


## Setting Goals

Measuring success for platform products is especially challenging because they are removed from end use cases. As such, we focus on the primary developer users and use a broad set of dimensions to encompass how well the platform delivers the value promised. A framework commonly used at Google is the QUANTS framework, which we describe below.



<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")





## Example: Code Search metrics using QUANTS

For example, we’ll describe a hypothetical feature called code search (a search engine dedicated to finding specific sections of program code) and break down how we measure success using the QUANTS framework.



<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")


Once developers adopt and use your platform tools, they will depend on their reliability. Within a company, this responsibility would fall to a developer operations organization. We recommend measuring reliability with a separate framework to minimize conflicts with other priorities.



<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")





# 3. How do you prioritize a platform roadmap?


## Common Pitfalls of Platform PM

A Platform PM will encounter challenges when creating and evangelizing a product roadmap. These include convincing product teams to migrate from ad-hoc tooling to centralized engineering platforms, introducing new tools to avoid further fragmentation and complexity, and setting proxy metrics when top-line metrics can be costly or difficult to measure regularly.

When platform teams are first formed, PMs face particularly large challenges in convincing client teams to adopt a new platform over the ad-hoc solutions they have developed. The latter often leads to tool fragmentation and dependencies on multiple versions of software libraries, which result in more reliability issues. When this happens, more time is lost to debugging problems, often during a time-sensitive phase when a severe event like downtime occurs. Collecting data on reliability incidents and their root causes, and doing qualitative research to understand the technical factors that reduce developer productivity are ways that PMs can build a business case for a more robust platform. Some ways that PMs can address adoption if your platform is new and not feature-rich: \




1. In a metric-driven culture, a PM could define a clear and convincing narrative about how the platform will be accretive to one of the client team's goal metrics.
2. For early adopters, the platform team can consider supporting the implementation alongside the client team and should plan resources appropriately.
3. When possible, the platform team can propose experiments to demonstrably prove success stories instead of testimonials only.
4. Assess whether we can reuse, extend, and deprecate existing tooling to minimize additional fragmentation.


## Technique: Overlay Industry Research

Over twenty years in the developer platform space have shown us that developers face many problems, including change management due to multiple software versions, fragmented user experience from too many tools, and hard-to-find or outdated documentation. Creating a roadmap to address these issues relies on judgment from product management and engineering leaders. Our experience indicates that these decisions are often subjective and influenced by the most prominent voices or arbitrary consensus-building.

Products and platforms share a common challenge: there are usually more problems than time to address them all, making prioritization crucial. However, with a diverse developer user base and specific feedback, prioritizing becomes particularly challenging and often relies on qualitative judgment by product and engineering leaders. To stay data-driven, mapping credible industry research against user problems provides an objective prioritization filter (see below). 

In this example, we highlight (in yellow) specific problems to solve. To narrow down the many potential issues, we mapped them to findings from industry research, using Harness’ [State of the Developer Experience Report 2024](https://www.harness.io/state-of-developer-experience).



<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.png "image_tooltip")



## Theme by Priority Problems

By anchoring on problems sized by research, we can then embark on the standard product exercise of brainstorming solutions and grouping them in themes against each problem.



<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.png "image_tooltip")



## What new directions should we explore?

In addition to using data to create a roadmap, it’s useful to use our experience and judgment to explore new long-term directions and/or new business expansion initiatives. This typically requires combining company-level strategy and important market trends that the company must address in order to succeed.

For example, Meta’s strategic directions are to (a) transform its products from mobile and web to virtual reality (VR) headsets, (b) optimize the delivery of advertising and reverse ad revenue loss from systems issues, and (c) make its 50,000+ developers more productive. With these objectives in mind, we might suggest some new directions for Meta’s developer platforms, below.


# 

<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")



# 4. How do you create a timeline for the roadmap?

Recall that **Leverage**, **Velocity**, and **Impact** are the benefits of a Platform. An effective way to create a roadmap timeline is to map features on a 2x2 matrix. Here we use Leverage and Velocity as the X and Y coordinates, placing features into four quadrants. Features in the top right quadrant are prioritized for early delivery, while those in the bottom left are delivered last.

There may be exceptions to the ordering. Features that deliver substantial business impact (Impact being our third benefit), might be accelerated in the timeline. Additionally, use judgment when necessary. For example, improving documentation for internal tools may have low Leverage and moderate Velocity but it could still be prioritized for earlier delivery due to its common-sense value.



<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.png "image_tooltip")





# 5. What is the Go-to-Market plan that ensures adoption?

We usually conclude a Platform roadmap with specific steps to ensure the adoption of new capabilities. It is crucial that the teams responsible for execution—usually sales, marketing, and customer service—explicitly agree on this plan.



<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image13.png "image_tooltip")



# Conclusion

This article assumes that the product leader has a strong understanding of the product roadmap process. It is meant to highlight the main differences in building platforms as compared to products. We hope this article will be a helpful starting resource for building platforms and we would love to hear your feedback and suggestions on it, other resources, and future articles.

Finally, many thanks to our Neuronn AI colleagues and [Alanna Viega](https://www.linkedin.com/in/alanna-veiga/) for reviewing and providing feedback on this article.


# About Neuronn AI

Neuronn AI is a professional advisory group rooted in prominent Artificial Intelligence companies such as Meta. Leveraging extensive expertise in Data Science & Data Engineering, AI Product Management, Market Research, and Strategic and Brand Marketing, we offer fractional assistance to startups looking to launch AI-driven product ideas and provide consulting services to enterprises seeking to implement AI to accelerate their outcomes. Neuronn AI's advisors include [Alex Kalinin](https://www.linkedin.com/in/alex-kalinin-seattle), [Carlos Romero](https://www.linkedin.com/in/carlos-f-romero/), [Enrique Ortiz](https://www.linkedin.com/in/enriqueortiz), [Lacey Olsen](https://www.linkedin.com/in/laceyolsen), [Norman Lee](https://www.linkedin.com/in/normanhlee/), [Owen Nwanze-Obaseki](https://www.linkedin.com/in/thebritishtexan/), [Rick Gupta](https://www.linkedin.com/in/rickgupta/), [Seda Palaz Pazarbasi](https://www.linkedin.com/in/sedapalazpazarbasi/), [Sid Palani](https://www.linkedin.com/in/sidpalani) and [Vik Chaudhary](https://www.linkedin.com/in/vikchaudhary).


# Summary post on LinkedIn

There are many resources for product managers managing consumer apps or B2B applications. However, there is a gap in PM’ing platforms–services, APIs  and tools that developers use to build applications–that are increasingly common in the AI era (e.g. OpenAI GPT, Cohere, and Google Vertex AI)  With Sid Palani’s and my experience PM’ing developer and ML platforms at Meta, we wrote an article on the challenges that people building platforms need to consider. We use 3 principles: Velocity, Leverage, and Impact to guide platform development.

The article uses an example framework to create strategy, articulate benefits, prioritize features, and deliver a roadmap for a platform product.

**🎯**How do you set a platform's vision, strategy, and guiding principles?



<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image14.png "image_tooltip")
How do you measure success? 

**⚖️ **How do you prioritize a developer platform roadmap?



<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image15.png "image_tooltip")
How do you create a timeline for the roadmap?

**💰**What is the Go-to-Market plan that ensures adoption?

Read on Substack: &lt;link> 

Read on LinkedIn: &lt;link>

This article is the sixth in a series from [Neuronn AI](https://www.linkedin.com/company/99416807/admin/feed/posts/), an advisory group of experienced AI practitioners from companies such as Meta offering fractional support to businesses launching AI-driven products. 

#platform #developer #devex #MLPlatform #productmanagement

**Comment:**

[Alanna Viega](https://www.linkedin.com/in/alanna-veiga/) and Neuronn AI team: [Alex Kalinin](https://www.linkedin.com/in/alex-kalinin-seattle), [Carlos Romero](https://www.linkedin.com/in/carlos-f-romero/), [Enrique Ortiz](https://www.linkedin.com/in/enriqueortiz/),[ Lacey Olsen](https://www.linkedin.com/in/sidpalani/),[ Norman Lee](https://www.linkedin.com/in/enriqueortiz/),[ Owen Nwanze-Obaseki](https://www.linkedin.com/in/obaono/),[ Rick Gupta](https://www.linkedin.com/in/laceyolsen/),[ Seda Palaz Pazarbasi](https://www.linkedin.com/in/normanhlee/), [Sid Palani](https://www.linkedin.com/in/sidpalani), and [Vik Chaudhary](https://www.linkedin.com/in/vikchaudhary).




# Archive


## Notes

Saving some notes in case we need them later: \


There is significant literature and resources on Platform Engineering–a search on Apple Podcasts shows many results. Platform Engineering teams, sometimes called Infrastructure Engineering, or Internal Engineering, are software-only engineering teams that have been around at technology companies for decades. Our experience with Platform engineering teams is that roadmaps are often defined by engineers for engineers, with objectives being collaboration, reuse of code, and efficiency. 

When done well, engineers are quick to collaborate with other engineering teams, often quickly delivering updates as requested by their customers. There is also a high focus on deliverability, so these Platform teams also have Technical Program Managers (TPMs) or Technical Leads (individual engineers) whose goal is to streamline output, i.e. delivering capabilities, rolling out releases, and providing customer support. 

Over time, Platform teams either become more crucial to their upstream customers, or more fragmented with many, smaller component teams. This results in frequent updates, many versions of software APIs, legacy use cases for outdated code, fragmented user experiences with many UX surfaces, and growing technical debt. The responsiveness ethos that worked well in the early days is no longer sufficient. The problems that compound over time include:



* **User Experience**–Developer experience is fragmented across many UX surfaces and configuration experiences. Users find it hard to navigate recommended solutions, with too much time spent on word-of-mouth guidance. Incomplete documentation makes it hard to onboard new users. At Meta, our engineers experienced dozens of applications across the workflow of the software lifecycle. Many alternatives flourished, leading to hundreds of tools when perhaps 10 might have been sufficient.
* **Software Management**–There is often no view into all the dependencies of an application such as libraries, data stores, or clusters. Tracking signals such as QA status, deployments, alerts and open tasks are done ad-hoc. This increases a developer’s cognitive load and increases inefficiencies.
* **Inefficient Error Workflows**–Automated dependency updates result in more production errors with time-consuming debugging practices. Production errors can lead to crucial downtime incidents, and root cause analysis is often slow.

Before Platform teams are beset by these egregious problems hindering developer productivity, they turn to Product Managers to help bring strategic order to product priorities and execution that becomes impactful. However, the challenge is that the Product Management industry mostly has PMs who are well-versed in managing the workflow of products, i.e. applications or tools, but rarely with platform PM experience. This is the gap that this article aims to address, by providing a framework to answer standard questions that outline a Platform strategy. 


## Resources

[5 more myths about platform engineering: how it’s built, what it does, and what it doesn’t](https://cloud.google.com/blog/products/application-development/another-five-myths-about-platform-engineering)
