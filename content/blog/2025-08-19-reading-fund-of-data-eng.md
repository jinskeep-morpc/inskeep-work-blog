---
title: Reading Fundamentals of Data Engineering
date: 2025-08-19
tags:
    - data-engineering
    - notes
    - books
---

# Chapter 1

## Defining Data Engineering

Their definition:

> Data engineering is the development, implementation, and maintenance of systems
> and processes that take in raw data and produce high-quality, consistent information
> that supports downstream use cases, such as analysis and machine learning. Data engi‐
> neering is the intersection of security, data management, DataOps, data architecture,
> orchestration, and software engineering. A data engineer manages the data engineering
> lifecycle, beginning with getting data from source systems and ending with serving
> data for use cases, such as analysis or machine learning.

## Data Engineering Lifecycle

![The data engineering lifecycle as presented in the book.](../assets/data-engineering-lifecycle.jpeg)

## The History of Data Engineering

They document a history which moved through Big Data into the modern data architectures. Focusing on the role of the Data Engineering (DE) as the process of creating the foundation from which data analysis (DA) and data science (DS) rest.

## The Relationship between DE, DS, and DA

![Data Hierarchy of Need](../assets/data-hierarchy-of-needs.jpeg)

[SOURCE](https://hackernoon.com/the-ai-hierarchy-of-needs-18f111fcc007)

They argue that DEs will spend most of their time working in the lower half of the pyramid. 

> [!NOTE]
> I wonder to what degree these types of diagrams are useful. In reality the relationships between these different actions is more complex than a pyramid. 
> This critique has been leveled against many overtly hierarchical relationships in favor of more "networked" or web-like relational mappings.
> How would this change the way we thinking about dependencies in decisions regarding data architectures?

## DE skills and activities

Across the DE lifecycle decisions need to be made regard how to balance diverse values.

Axes of value:
- cost
- agility
- scalability
- simplicity
- reuse
- interoperability

## Fostering Data Maturity

>**Data Maturity:** is the progression toward higher data utilization, capabilities, and integration across the organization.

Their data maturity model is similar to many others. 

```mermaid
graph LR;
    A[Starting with Data] ==> B[Scaling with Data]
    B ==> C[Leading with Data]
```

### Starting with Data

Getting started with data should focus on:
- Getting buy-in from stakeholders, ideally higher level management.
    - Look for a sponsor
- Defining the right architecture
    - Define the value add first, then find the right tool
- Find the data
- Build the foundation
    - This requires structure and process

Potential Pitfalls:
- Getting quick wins is important for building buy-in, but may incur technical debt. Have a plan for addressing it.
- Focusing on the nitty-gritty of data foundation can lead to tunnel vision. Maintain connections with domain leaders and subject experts. Make tools that people with use.
- At this point, use off-the-shelf solutions. Avoid technical complexity. 
- Custom builds only when necessary. 

GOAL: Move beyond adhoc data requests to formalized data practices.

### Scaling with Data

Scaling with data should focus on:
- Document and formalize processes. 
- Establish data architecture.
- Integrate DevOps and DataOps.
- Begin laying groundwork for ML.
- Continue to resist the desire for custom builds

Potential Pitfalls:
- Avoid the desire to be technologically driven instead of value driven.
- Focus on solutions managing the team. The main barrier is not technology at this point, it is the data team. 
- Educate domain leaders and subject matter experts on the practical uses of data. Avoid over promising.
    - Do the work of bringing people into the data world through outreach and education.

GOAL: Self-service analytics and automated pipelines.

### Leading with Data

Leading with Data should focus on:
- Increasing automation and introduction of new data.
- Building custom tools to create value.
- Better data governance and DataOps
- Increasing use of data through deploying tools that expose data and metadata
- Increased collaboration with analysis, science, and ML process.
- Building community around leveraging data. Inspire creativity. 

Pitfalls:
- Fight complacency. Establish continuous improvement plans.
- Avoid hobby projects. Create value. 

> [!NOTE]
> Overall, a few things stand out in their data maturity model. 
> 1. The focus on avoid custom build is throughout, even in stage 3. 
> 2. The human-work is central, and a potential source of problems throughout the model. 
>    - Getting buy-in early
>    - Working with people to find where you can create value.
>    - Spurring use through education.
>    - Maintain growth through continued creative use of data.

## Skills of a DE

Required knowledge for DE:

- "Data Aware"
- Data Management best practices
- Technical tools and software, including the benefits of each
- DataOps
- Software engineering
- Data architecture
- DA and DS requirements
- Understand needs from business (organizational) and technical lense

### Business Responsibilities

> A successful data engineer always zooms out to understand the big picture and
> how to achieve outsized value for the business. Communication is vital, both for
> technical and nontechnical people. We often see data teams succeed based on their
> communication with other stakeholders; success or failure is rarely a technology
> issue.

- Know how to communicate with nontechnical and technical people.
- Understand how to scope and gather business and product requirements.
- Understand the cultural foundations of Agile, DevOps, and DataOps.
- Control costs.
- Learn continuously.

> [!NOTE]
> I wonder what difference would be included if this section was written not for private business
> but for public sector and non-profit DE. Cost still matter but working within a grant funded and
> highly regulated environment may be different. 

### Technical Responsibilities

- Proficiency in at least SQL, Python, bash, and probably some others. 
- Knowledge of available tools and their benefits

### Type A and Type B DEs

Type A for Abstraction. These engineers focus on building data infrastructure at an abstract level using off-the-shelf tools and software. 

Type B for Build. These engineers are focused on building custom tools and software for leveraging a companies key advantages. 

## Working in Organizations

### Internal-facing and External-facing DEs

DEs interface with both internal and external data users, and need to consider the needs of both. 

> An external-facing data engineer typically aligns with the users of external-facing
> applications, such as social media apps, Internet of Things (IoT) devices, and ecom‐
> merce platforms.

> An internal-facing data engineer typically focuses on activities crucial to the needs of
> the business and internal stakeholders (Figure 1-11). Examples include creating and
> maintaining data pipelines and data warehouses for BI dashboards, reports, business
> processes, data science, and ML models.


### Interfacing with other technical roles

> The data engineer is a hub between **data producers**, such as software engineers, data
> architects, and DevOps or site-reliability engineers (SREs), and **data consumers**, such
> as data analysts, data scientists, and ML engineers.

#### Upstream Data Stakeholders

Data architects

Software engineers

DevOps



#### Downstream Data Stakeholders

