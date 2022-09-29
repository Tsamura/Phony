# Phony

<h1> What is this project based on? </h1>

This project revolves around the topic of cloud computing and the aim of this project is to showcase how companies/organizations these days should be making use of this technology to host their applications/websites on the cloud instead of relying on on-site/on-premise servers. 


<h1> Why did I decide to start on this project? </h1>

Well, it was actually a module (C300 - FYP, or better known as Final Year Project) that I had to take during the final year of my studies at Republic Polytechnic. 

I had to work together with two other teammates on the given topic to develop an application in PHP and host it on the cloud. We also had to design (and construct) the underlying architecture using features/services from Amazon Web Services (AWS) - one of the top cloud service providers. 


<h1> What made our project stand out from other teams working on the same topic? </h1>

Our solution encompassed several features - a working cart system, multi-factor authentication (MFA), integration with PayPal using its Sandbox API, a forum for users to post feedback, etc. 


<h1> Additional project details </h1>

To assist us on our journey to build a solution, Republic Polytechnic has kindly provided my team with our very own AWS (root) account and we were allowed to use any features/services from AWS as long as we did not exceed the project's budget of $300. 

Upon receiving the AWS account, we decided on a theme of "electronics" for our application. To design the application, we made use of Figma - a popular tool used to construct protoypes/wireframes. I have uploaded the final version of the wireframe in one of the branches in this repository if anyone is interested. 

Afterwards, we had to come up with an architecture diagram to showcase our supervisor in charge of my team. This architecture diagram was used to plan out how exactly are we going to construct the 3-tier architecture on the cloud. For example, we configured 4 EC2 instances - 2 of them were used as jump hosts (in the web tier) while the rest were installed with Apache.

To protect our application, we hardened our application by rewriting our code while keeping mind of OWASP's Top 10 
Vulnerabilities and other security measures were implemented as well - i.e AWS's Web Application Firewall (WAF). 

In conclusion, the project was a success and we all managed to do well for this particular module. 



