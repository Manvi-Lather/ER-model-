# 
About Truelancer:

Truelancer is an online platform for employers hire professionals to get their work done. Freelancers, a term used for those who provide services, can sell services, and find projects to work on based on their skills & expertise. Clients can buy freelance services and post project to hire freelancers. Projects – a term used for the task posted by Client – can be placed in various categories like IT & Programming, Graphic Design, Content Writing, Data Entry, Finance, Sales, Marketing, and many more. The URL for the website is https://www.truelancer.com/

Summary:

I have to create a database in MySQL for Truelancer.For that, first I analyzed the business rules, entities, and relationships to form an ERD and then converted it into a database. In this case, I have worked with the snapshots from a functional website (https://www.truelancer.com/) to understand the entities and business rules so that I can reverse engineer the database design. I went through the website to understand the client and freelancer relationship. 

Scope:


The scope of this work is limited to bids and reviews. Like other bidding systems, a client/employer can post projects on the website and freelancers can bid on the project(s). The client selects one of the bids at his/her discretion for the work to start. The design captures the bids received, the selected bid along with the amount and duration of the project. The payment schedule for the selected bid is out of scope for the this work. Similarly, the sales of non-project related tasks (things that do not go through the bidding process) are out of scope. Moreover, we can assume that the employer/client cannot be a freelancer. As for the reviews, we will assume that the client/employer to leave reviews for the selected bidder (freelancer) and the selected bidder (freelancer) can also leave reviews about the client/employer.


