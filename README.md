# devops-ci-cd
What is DevOps and CI/CD Pipeline?

This article contains information about what is DevOps, how CI/CD pipeline works and which companies have adopted DevOps.

What is DevOps?


DevOps is not a tool, it’s an approach/mindset which every company needs to adapt for business productivity otherwise the company won’t survive. DevOps follow practice call “automation” which means everything is handled by system as, system/device work faster than humans. In other words, DevOps is all about automation and unification of processes. Main motive of DevOps is to apply automation practice and increase a company/organization’s ability to deliver products or application and services at faster rate.
Let’s understand DevOps with an example,


Step 1 ::
An organization have an idea (start-up) which contains new features to solve an industry challenge. A developer will be assigned to it and a webapp or application would be created as desire.
Step 2 ::
This product/application needs to be exposed to public world from an production environment which holds deployment configurations, server, cloud, etc. to release the product.
To combine above steps, DevOps act like a bridge, a process or a method to provide fast/agile product delivery to open market. Time to market (TTM) is key part provided by DevOps which means, truly innovative product with short time.

What is CI/CD pipeline?

CI/CD pipeline means to understand what exactly happens between developer and product release(between step1 and step2). A pipeline is series of step that must be performed in order to deliver a new version of software. Continuous integration & continuous deployment, i.e., CI/CD pipeline stages/phases are the pillar to build DevOps architecture. CI/CD approach automates the entire operation process from integration to delivery, testing, and deployment.
Let’s understand CI/CD and different terms involved in it.


Continuous Integration ::

Continuous integration (CI) is kick-off step of CI/CD pipeline. It contains two stages namely “code”, “build and test”. CI is implemented using tools like Jenkins or SaaS services like Gitlab CI, Circle CI, etc.

Code → This stage represents the code or algorithm developed by developer with different programming languages as per requirement. Created code is pushed onto SCM (source code management) products like Github, CodeCommit, etc. to track modification done by developer and resolve conflicts while merging updates from multiple contributors.

Build and Test→ As different programming language might be used to build the product hence, some language code like Java need to compile first and then, run. Here, the role of build come in play. SCM will provide the code to “build” stage which will compile and run the application. Tool like codeBuild, maven, gradle, npm, etc. are used in this stage. After the code is made executable by “build”, it is then, tested with certain test cases to make sure the build is successful.

Continuous Deployment ::

Continuous deployment is the final stage in a CI/CD pipeline process. Continuous deployment is a test-driven approach to validate the application on different parameters and automatically roll out deployments. CD deals to create code deployment configurations by setting up webserver, OS instances, etc. depending on application. It contains two stages namely, Testing environment and Production environment.

Testing Environment → After CI phase, the product is provided to “testing environment”. This environment makes sure to meet all customer requirements before the product is exposed to public world. In this stage, an Quality Assurance (QA) team is assigned for code configuration/deployment. QA team members ensure that the products customers receive consistently meet or exceed expectations, which helps boost brand reputation. QA plays an important role as a key enabler in delivering business value.

Production/Deployment Environment → This is the last phase of CI/CD pipeline in which the final product is provided to public world. After the testing is approved by testing environment, QA team exposes it to clients or customers by providing a public IP. In other words, production environment is set of computers where finished, user-ready software is deployed and executed.

Meaning of “Continuous” in CI/CD ::

None of the product is built perfectly in one go means, lots of changes are made in both Continuous integration and Continuous deployment. Main motive is to create product as per customer/client need hence, making sure code is functioning properly and QA team is providing best of it.
In CI, some test cases might fail and code needs to be modified or rebuild. Same goes for CD, if QA team doesn’t approve or product doesn’t have necessary features, it won’t be deployed and again CI phase need to take care of it. This is an infinite loop until all requirements are satisfied. This loop in DevOps is called “Continuous”. In simple words, Continuous means to keep on visiting previous stage to add or modify features and again pass onto next stage.

Note ::
Continuous Deployment → Everything is automated.
Continuous Delivery → Everything is handled manually.
Mostly in DevOps, whole CI/CD stages are automated rather than validating entire stage or test manually, also, it would be way faster than manual method.

Companies that are doing DevOps well

I} Netflix

When Netflix evolved its business model from shipping DVDs to streaming video over the web, it waded into uncharted waters. Over 100 million users turn to Netflix for a quality streaming experience. Maintaining its place as an industry leader without causing any glitches for their customers requires speed, flexibility, and attention to quality. Netflix has continued its commitment to automation and open source, and today engineers deploy code thousands of times per day. Automated monitoring is in place so that if the deployment of the images fails, the new images are rolled back and traffic is rerouted to the old version.

2} Walmart

While Walmart is the king of big box retailers in the American heartland, online it has always struggled in the shadow of Amazon. WalmartLabs has taken a decidedly DevOps approach to its mission. cloud-based technology, which automates and accelerates application deployment. It has also created several open source tools, including hapi, a Node.js framework for building applications and services that allows developers to focus on writing reusable application logic instead of spending time building infrastructure.

3} Adobe

Adobe’s DevOps transformation began five years ago when the company moved from packaged software to a cloud services model and was suddenly faced with making a continuous series of small software updates rather than big, semi-annual releases. To maintain the required pace, Adobe uses CloudMunch’s end-to-end DevOps platform to automate and manage its deployments.

4} Amazon

Amazon has a reputation for impressive DevOps. The transition to DevOps was a part of the company’s 2010 move from physical servers to the Amazon Web Services (AWS) cloud, a change that allowed them to save resources by scaling capacity up and down in single-serve increments. Amazon also began using a continuous deployment process managed by an internal system called Apollo, which gives developers the ability to deploy code whenever they want to whatever servers they need.

5} Etsy

For its first several years, Etsy struggled with slow, painful site updates that frequently caused the site to go down. With the help of a new technical management team, Etsy transitioned from its waterfall model to more agile approach. Today, it has a fully automated deployment pipeline, and its CD practices have reportedly resulted in more than 50 deployments a day with fewer disruptions. And though Etsy has no DevOps group per se, its commitment to collaboration across teams has made the company a model of the DevOps framework.

Conclusion

DevOps bring a new mindset, agile practices and smart tools which together accomplish that goal. DevOps is not only important to speed up software development, but also improves the quality of the software.
