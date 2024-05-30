---
title: "Why being a Data Architect?"
date: 2024-05-27
summary: 
tags: ["intro", "data architect", "pilot"]
draft: false
---

It is crucial that data is accessible and reusable for society and industry. Nowadays, it is essential that data can be accessed and repurposed not only by professionals but also by regular users, such as those using social media and trying to download their own information.

Tasks such as creating, saving, ingesting, transforming, processing, and visualizing data require time and effort. Additionally, maintaining security, executing administration, performing operations, detailing orchestration, preserving good software engineering practices, and defining data architecture strategy are all critical aspects of the data ecosystem.

Out of all these points, I want to focus on data architecture. There are various data roles in the workforce that can sometimes be overwhelming or difficult to distinguish from one another.

If you have experience working with data, you may have noticed that sometimes a Data Analyst performs tasks typically done by a Data Engineer, or vice versa. Similarly, a Data Scientist may be focused solely on SQL queries and dashboards for a company. This variation in roles often depends on the data maturity of the company, organization, or project.


### What is a Data Architect?

If you search on the internet, in books, or consult someone with experience in data, you may come across different definitions of what a data architect is.

According to the book _"Deciphering Data Architectures"_ by James Serra:
> They are the ones who design the high-level structure of the data architecture (MDW, data fabric, or data lakehouse) and decide which data governance technologies and policies the project should use.

According to _TOGAF_:
> They are responsible for describing the structure and interaction of the main types and sources of data, logical data assets, physical data assets, and data management resources of the enterprise.

According to _DAMA DMBOK_:
> They are the ones who identify the data needs of the company (regardless of structure) and design and maintain master plans to guide data integration, control data assets, and align data investments with business strategy.

According to the book _"Fundamentals of Data Engineering"_ written by Joe Ries & Matt Housley:
> They function as a level of abstraction from data engineers. Data architects design the model for organizational data management, mapping processes and overall data architecture and systems. They also serve as a bridge between the technical and non-technical aspects of an organization.

They also have another definition:
> It is the one who designs systems to support a company's changing data needs, achieved through flexible and reversible decisions reached through careful evaluation of trade-offs.

&nbsp;

Now, which definition should be chosen?

Summarizing all of these definitions, it could be done like this:
- They design the overall structure of how data is stored, organized, and utilized.
- They decide which technologies will be used to manage the data.
- They create rules and policies to ensure that data is of high quality and reliable.
- They ensure that data systems are flexible and can adapt to the changing needs of the company.

They function as designers, developing necessary systems for the entire data lifecycle so that companies can maximize their data.

A data architect analyzes the pros and cons, designs with agility, and adds value to the business.


### And what is NOT a Data Architect?

Everything related to both strategy and tactics can be considered as Data Architecture.

Strategy involves the questions of **what, why, and when**, while tactics involve the **how**. Let's say someone from your company approaches you and expresses the need to integrate information from various sources in order to utilize the data. As a data architect, you must begin by investigating what exactly they are dealing with, understanding why they want that integration and data utilization, and determining when they require this type of solution.

These are not the only questions that a data architect asks, but the point I want to emphasize is that it is not accurate to simply state, _"We have X, Y, and Z tools to extract and analyze data,"_ as this can have negative consequences on the solution design.

In addition to strategy and tactics, data architects must consider three main aspects when developing a new data architecture:
* Completeness
* Accuracy
* Consistency

Often, stakeholders may not have a clear understanding of what they are dealing with, so it is essential to be present when defining those functional requirements. In my opinion, it is an art; sometimes, stakeholders may only know that they need to integrate and utilize data, which can actually be a good starting point.

#### But are these tasks typically performed by a Data Engineer?

It is true that a data engineer is capable of handling all of these tasks, but as previously mentioned, data architects operate at a higher level of abstraction. Additionally, while I am not an expert in construction, I understand that a civil engineer could fulfill the duties of an architect. So why do architects exist? They focus on strategy and tactics, while engineers bring designs to life.

A Data Engineer is tasked with creating, testing, and maintaining data architecture. They write scripts to extract, load, and transform data from various sources to create a data solution, collaborating closely with a data architect to implement the planned architecture.

While an engineer can perform architectural work, it is important to define their limitations, objectives, tasks, and scope. This is crucial because you may have encountered situations in your workplace where an engineer takes on more responsibilities than necessary.

Now, out of all these roles, have you observed any instances where they have been combined?
- Data Analyst
- Data Scientist
- Business Analyst
- Data Engineer
- Database Administrator
- Data Steward
- Data Architect
- Data Governance Manager
- Data Quality Manager
- Project Manager/Scrum Master
- DevOps Engineer
- Product Owner/Manager

It is not uncommon for roles to be combined, but it is essential to remember that one data role may encompass multiple responsibilities.


### Their Role in the Data Engineering Lifecycle

Understanding the data engineering lifecycle is crucial due to its impact on every stage of a project, ultimately bringing business value to stakeholders.

* Generation
* Storage
* Ingestion
* Transformation
* Visualization or delivery

Data holds value at each phase of this cycle, and data that is not consumed or consulted can pose a risk to any company. Many companies, in their pursuit of ambitious projects in the age of big data, have collected massive amounts of data that ultimately went unused.

Projects must be intentional throughout the entire lifecycle, both in engineering and in data. A data engineer is responsible for extracting information in a timely manner, following proper security and integration protocols, and any other necessary tasks.

#### But does a data engineer's job end here?

That's what I want you to understand: A data architect has to evaluate, design, organize, and see the value in the phases of the project. A data engineer might do all of these tasks, but it's not their main job.

For instance, let's think that you go to a hospital and meet a doctor. Probably you know for sure the doctor will:
* Examine your condition
* Make a diagnosis
* Prescribe medications

And surely wouldn't do:
* Clean the hospital
* Make the medicine
* Manage hospital administration

But what about data engineers? Are expectations unclear? Can they:
* Design the data warehouse data model
* Handle application databases
* Create a data pipeline for machine learning
* Manage all big data infrastructures and software installation
* Analyze big data to transform raw data into meaningful insights

As I mentioned before, if companies were more data mature, then there will be better well-defined boundaries. In the end of the day, it also depends on how modern data management tools rise with the increasing complexity of the data.

#### What should a Data Engineer do?

I believe they should have a broad understanding of the entire data lifecycle, distinguishing between essential, beneficial, and/or optional skills.

However, what is considered essential in one company may be seen as optional in another. It ultimately depends on the specific operations and needs of the company and its customers.


### Common Challenges in the Data Realm 
As a Data Architect or in a related role, you will encounter common challenges in the data realm.

If data maturity is low, you may encounter:
* Data Silos
* Limited data literacy
* Inadequate infrastructure
* Cultural resistance
* Security vulnerabilities

On the other hand, if data maturity is high, you may encounter:
* Data Governance and Management issues
* Innovation with emerging technologies
* Development and maintenance of advanced analytics 

In both scenarios, there may be a variety of challenges, but it is important to recognize that a lot of data is not being utilized effectively. This could be due to poor data architecture design, inadequate data governance or management, or low data quality since its creation.

### Conclusion

A Data Architect plays a crucial role in shaping the data landscape of an organization. They are responsible for creating strong data architectures that guarantee data accessibility, reliability, and security.

By addressing both strategic and tactical aspects, Data Architects bridge the gap between business requirements and technical implementation. Their ability to assess trade-offs and develop adaptable systems is essential for meeting changing data needs.

At last, Data Architects empower organizations to effectively utilize their data resources, driving business value and innovation.

### TL;DR

A Data Architect designs the structure of data storage, organization, and utilization to ensure data quality and flexibility. They focus on strategy and tactics, collaborating closely with data engineers to implement the architecture. Understanding the data engineering lifecycle and common challenges is key to adding business value.

