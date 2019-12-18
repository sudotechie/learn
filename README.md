## **Background**

This project is my attempt at sharing my strategy for building personal relevance in the rapidly changing world of software delivery. 

I am here out of necessity. My role has traditionally been sales "+" for software, SaaS, and even hardware companies. The "+" represents the part of my role where a playbook didn't exist. Having to do this over and over taught me how to quickly learn about the technologies, competitive ecosystems, and the users and companies that adopt them.

I struggle to organize content and specific facts without first establishing a foundation to receive that information. 

An example would be from the first time I "pitched" a site reliability engineer. This was back in 2013. At the time, I distinctly remember having difficulty understanding exactly what he did. I was unable to mentally place his daily tasks and objectives into any of my pre-existing buckets of titles and responsibilities. As you have probably already concluded, the call went nowhere. Because I didn't have the mental dexterity to accept this new input, I wasn't able to adjust my message and build credibility. 

Fast forward to 2019. New titles are birthed weekly. Some companies are flat, classifying all engineers (application, platform, etc) as non-descript "software engineers". There is no enforcement of titles within LinkedIn, allowing individuals the freedom to be ninjas, rockstars, and the like. And from a technology standpoint, every startup with a previous FAANG employee is getting funding. Each has a ground-breaking, disruptive technology that requires a new category to be defined.

How do we make sense of it all?

Through a series of questions, that once answered, will yield a framework for all new information to be received. 

Let's revisit the example with the SRE. My goal in these types of scenarios is to quickly anchor on where this individual fits within the org, what their responsibilities are, an understanding of the potential challenges that they face, and the types of technologies they leverage. Please note that this is a sample; however, any framework does assume a cursory understanding of how companies make money. To accelerate your understanding of these concepts, read a few 10Ks (the annual report filed by publicly-traded companies to the SEC), specifically the "Risks" sections.

With answers to the questions below, I would have been better prepared to engage with this individual. 

1. How does this company make money?

A: SaaS offering, billed monthly

2. How is this company's service delivered?

A: Globally via regional data centers

3. Why would a customer choose this company's service over a competitor?

A: Features, Reliability, Ease of Use, Cost, Branding

     This is where it gets a little more complicated...

4. So what does it take to deliver that differentiation?

A: Features - Ability to ship code faster, collect/visualize data on how code performed, expose for subsets of users, track features, engineering capacity, customer training, and marketing

A: Reliability - Multiple components here: detecting and alerting on failures, ability to withstand multiple types of failures, ability to revert/remediate quickly, means to teach engineers how the system works, robust QA (quality assurance) whether that's through test-driven development, paired programing, or user testing, track bugs and customer impact

A: Ease of Use - Collection and visualization of correlation data: user interactions vs. adoption, conversion, expansion, churn; similar measurements for professional services and impact on customer-lifetime value

A: Cost - Companies have three levers to use to derive pricing - value-based (how much would it cost to solve this otherwise?), competitive (what do our direct competitors charge?), and COGS-based (what does it cost us to deliver this product or service?). Employees can only impact the value they deliver (identifying the right use cases to pursue and delivering the right functionality) and the cost to run their service via organizational and technical decisions.  

     And this is where it all comes together. 
     Answer #5 and you're on the cusp of having real customer empathy 
                    
5. From an organizational perspective, what roles and responsibilities are needed to achieve these outcomes?

...


Had I had this framework in time for the SRE conversation, I would have been able to very quickly relate their daily tasks to one or multiple of the buckets above. Most SREs I work with fit primarily in the "Reliability" bucket, while also providing services that enable "Features" and reduce "Costs".

------

Now that I've shared a primer on how I organize this information, the next section covers some of the content I consume to educate these frameworks.

### __Books__

- [The New Kingmakers](https://thenewkingmakers.com/)

- [The Phoenix Project](https://itrevolution.com/book/the-phoenix-project/)

- [The Unicorn Project](https://itrevolution.com/book/the-unicorn-project/)

- [The DevOps Handbook](https://itrevolution.com/book/the-devops-handbook/)

- [Accelerate](https://itrevolution.com/book/accelerate/)

- [The Manager's Path](http://shop.oreilly.com/product/0636920056843.do) (Eng Leadership)

- [An Elegant Puzzle](https://lethain.com/elegant-puzzle/) (Eng Leadership)

### __Podcasts__ (in no order)

- [Software Engineering Daily](https://softwareengineeringdaily.com/)

- [SE Radio](https://www.se-radio.net/)

- [On-Call Nightmares]

- [Arrested DevOps]

- [Troubleshooting Agile]

- [DevOps Cafe]

- [The Ship Show (retired 2016)]

- [Foodfight Show]

- [DevOps Chat]

- [The New Stack]

- [The Changelog]

- [Maintainable]

- [o11ycast](https://www.heavybit.com/library/podcasts/o11ycast/)

Any cloud vendor podcast episodes (ie Google for Kubernetes, etc)

### __Blogs/Articles__

- [SRE Weekly by Lex Neva]

- [Engineering Impact by Gitprime]

- Dan Luu's Summary of _[Site Reliability Engineering](https://danluu.com/google-sre-book/)_ by Google

### __Reports__

- [State of DevOps] (DORA, previously Puppet)

- [Developer Coefficient by Stripe]


