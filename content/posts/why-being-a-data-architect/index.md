---
title: "Why being a Data Architect?"
date: 2024-05-07
summary: 
tags: ["intro", "data architect", "pilot"]
draft: false
---

It is very important that data are accessible and reusable for society and industry. Nowadays, it is crucial that data have the capacity to be accessible and reusable not only for the workforce but also for regular users, such as someone using social media and trying to download their own information.

Creating, saving, ingesting, transforming, processing, and visualizing data are tasks that require time and effort. Additionally, maintaining security, executing administration, performing operations, detailing orchestration, preserving good software engineering practices, and defining data architecture strategy are extremely critical aspects of the data ecosystem.

Of all these points I mentioned, I want to focus on what data architecture is. There are several data roles in the workforce that sometimes become overwhelming or even a bit difficult to distinguish from one role to another.

If you're familiar with data roles or rather if you have experience working with data, you'll agree that sometimes a Data Analyst does the work of a Data Engineer, or vice versa. Likewise, a Data Scientist may be working for a company solely doing SQL queries and dashboards. I could continue with countless examples, but to not go into too much detail, this practically depends on the data maturity of the company, organization, or project.


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

Now, which definition to choose?

Summarizing all these definitions, I could do it like this:
* They design the overall structure of how data is stored, organized, and utilized.
* They decide which technologies will be used to manage the data
* They create rules and policies to ensure that data is of high quality and reliable.
* They ensure that data systems are flexible and can adapt to the changing needs of the company.

They are like data engineers (practically functioning as a level of abstraction), who design the necessary systems for the entire data lifecycle so that companies can make the most of their data.

A data architect analyzes the pros and cons, designs with agility, and adds value to the business.


### And what is NOT a Data Architect?
Everything involving both strategy and tactics can be considered as Data Architecture.

Strategy involves the questions of **what, why, and when**, while tactics involve the **how**. Let's suppose someone from your company comes to you and says they need to integrate information from various sources because they want to leverage the data. As a data architect, you have to start investigating what exactly they are dealing with, you have to know why they want that integration and data leveraging, and you have to know when they need this type of solution.

It's not that these are the only questions asked by a data architect, but what I want you to understand is that it's not correct to say, _"We have X, Y, and Z tools to extract and analyze data"_ because that brings negative consequences to the solution design.

Besides strategy and tactics, data architects must be aware of three main aspects when embarking on a new data architecture design:
* Completeness
* Accuracy
* Consistency

Most of the time, the stakeholders don't know what exactly they are dealing with, so it's crucial to be present when making those functional requirements. It's an art in my humble opinion; if you're lucky, they just know that they need to integrate and leverage data. (Believe me, sometimes that's a really good starting point)

#### But these tasks are made by a Data Engineer, right?
It's true that a data engineer can do all of this, but as mentioned earlier, data architects function as a level of abstraction. Furthermore, I'm not an expert in buildings or houses or apartments, but I know that a civil engineer could do the work of an architect. So why do architects exist? Because they focus on strategy and tactics, while engineers turn what is designed into reality.

A Data Engineer is responsible for creating, testing, and maintaining data architecture. They write the corresponding scripts to extract, load, and transform data from one or more sources and turn it into a data solution, working closely with a data architect to implement the designed architecture.

While an engineer can do architecture work, it's important to establish the limits, objectives, tasks, and scope of what they can do. I say this because you have probably encountered job positions or employees in your workplace where an engineer does more tasks than they should.

Now tell me, of all these roles that exist, which ones have you seen end up being "combinined"?
* Data Analyst
* Data Scientist
* Business Analyst
* Data Engineer
* Database Administrator
* Data Steward
* Data Architect
* Data Governance Manager
* Data Quality Manager
* Project Manager/Scrum Master
* DevOps Engineer
* Product Owner/Manager

What I can tell you is that it's "normal" for this to happen, but it's crucial to keep in mind that there is the possibility for one data role to encompass several data roles.


### Their Role in the Data Engineering Lifecycle
It's important to understand the data engineering lifecycle due to its impact in every step of a project. (Basically, bring business value to stakeholders)

* Generation
* Storage
* Ingestion
* Transformation
* Visualization or delivery

Data holds value at every phase of this cycle, and data that isn't consumed or consulted can pose a risk to any company. Many companies, simply by wanting to undertake ambitious projects in this era of big data, ended up (and continue to) collecting massive amounts of data that ultimately weren't used correctly.

Projects must have intention throughout the entire lifecycle, both in engineering and in data. A data engineer will be responsible for extracting information in a timely manner, following correct security and integration protocols, and whatever else you want to add.

#### But does a data engineer's job end here?

That's what I want you to understand: A data architect has to evaluate, design, organize, and see the value in the phases of the project. A data engineer might do all of these tasks, but it's not their main job.

For instance, let's think that you go a hospital and meet a doctor. Probably you know for sure the doctor will:
* Examine your condition
* Make a diagnosis
* Prescribe medications

And surely wouldn't do:
* Clean the hospital
* Make the medicine
* Manage hospital administration

But what about data engineers? Expectations are unclear? They can or can't do:
* Design the data warehouse data model
* Handling application databases
* Creating a data pipeline for machine learning
* Handling all big data infrastructures and software installation
* Analyzing big data to transform raw data into meaningful insights

As I mentioned before, if companies were more data mature, then there'll be better well-defined boundaries. In the end of the day it also depends of how the modern data managament tools rise with the increasing complexity of the data.

#### So what should a Data Engineer do?
I think there is a distribution of knowledge from an end-to-end data lifecycle, and that must clarify what skills/knowledge are a "must", what are "good-to-have", and what are "nice-to-have".

However, a "must" in one company is a "nice-to-have" in another. It really depends on how the company and its customers operate.


### Common Challenges in the Data Realm 
Not only as a Data Architect, but also being as one related role mentioned above you'll encounter common challenges in the data realm.

If data maturity is low, you might encounter:
* Data Silos
* Limited data literacy
* Inadequate infrastructure
* Cultural resistance
* Security vulnerabilities

Now, if you go to the other end where data maturity is high, you may encounter:
* Data Governance and Management issues
* Innovation with emerging technologies
* Development and maintenance of advanced analytics 

I mean, in both ends you might find a little bit of everything, but it's important to keep in mind that there is a lot of data that is not used correctly. When not used correctly, it might be because of a bad data architecture design, or a bad data governance or management, or bad data quality since creation.

### Conclusion
In summary, a Data Architect plays a pivotal role in shaping the data landscape of an organization. They are responsible for designing robust data architectures that ensure data is accessible, reliable, and secure.

By focusing on both strategic and tactical aspects, Data Architects bridge the gap between business needs and technical implementation. Their expertise in evaluating trade-offs and designing flexible systems is crucial for adapting to evolving data requirements.

Ultimately, Data Architects enable organizations to leverage their data assets effectively, driving business value and innovation.

### TL;DR
A Data Architect designs the structure of data storage, organization, and utilization, ensuring data quality and flexibility. They focus on strategy and tactics, working closely with data engineers to implement the designed architecture. Understanding the data engineering lifecycle and common challenges is crucial for adding business value.

