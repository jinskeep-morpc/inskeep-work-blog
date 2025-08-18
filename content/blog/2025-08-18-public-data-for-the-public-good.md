---
title: Public Data for the Public Good (CURA Seminar)
date: 2025-08-18
tags:
    - write-up
    - data-engineering
    - seminar
---

Notes from a presentation by Joy Bonaguro, former CDO of California. Title: Public Data for the Public Good.
Hosted by CURA. Virtual.

<!--more-->

# Public Data for Public Good

## Introduction: Joy Bongaguro

- Independent Consultant
- Former CDO of California and San Francisco

## Seeking the Data-Driven Organization

## Introduction
<details>
<summary>Raw Notes</summary>
- Evacuation of New Orleans before Hurricane
- Put out an elevation map of New Orleans
- USGS elevation data, Metadata was missing
- Wrong guess in units
</details>

Joy discussed a situation in which she created a map of elevations in New Orleans preceding the potential landfall of a hurricane (potentially Katrina, unclear). She mentioned that the levies broke and that her map quickly became viral over social media and then was shared internationally be at least one organizations. 

when she made the map, the USGS metadata was unavailable due to maintenance and she had to guess at the units. Turns out that she guessed wrong. It was in meters, not feet. I assume that this didn't cause any actually complications.

### The point: 

It seemed like what Joy was emphasizing was the urgency at which some public data is necessary. I believe she used the term, ***Data Fire Drills***. That most government organizations are able to do some basic data retrieval but systematic and structured data queries with persistence is hard to find. 

## Why I did what I did?

### Theory of Change

1. Make data easy to access
2. Better use of data by Governance
3. Better services
4. Better outcomes

**Building a robust data and technology system will result in better public service**

### The point: 

This is probably the working theory of change for most people. I would agree with that. It assumes that the governance and users have the capacity and willingness to put the data and technology to use. This is not the case, and it is pretty clear why. 


## What did I do?

Joy discussed how she used her training as a system designer to address teh real issues. 

- "People assume private is better than public at using data."
- "People assume that the problem is people problem not technology problem."
- "Design thinking as a solution to data problem"

She explained that the primary and initial focus of design thinking is focusing on really defining the problem and applying appropriate tools. She discusses her approach to this using the analogy of "data roads."

## 1. Building the data roads

This is typical data engineering problem, but it doesn't end here. 

- Data is in silos.
- How do we use all kinds of data to see the whole picture
- The actually reality of inter-institutional data.
    - Most data and data requests and updates create is tedious
    - Across many data sources.
    - Using different processes.

## 2. Improve the rules of the roads

### Example: Stop sign standardization

In 1968, there was the [Vienna convention on Road Signs and Signals](https://en.wikipedia.org/wiki/Vienna_Convention_on_Road_Signs_and_Signals) which established consistency across signing countries for essential and critical road signage. Supposedly this created easier travel and better road safety. 


### Example: Vaccine sign-up, Race and ethnicity, 4 options for data collection

During the height of the COVID pandemic, different municipalities were using different question formats on surveys regarding race and ethnicity for vaccine recipients. One of the municipalities used open form, one a scrolling list, one a drop down, and one a select what applies with all options visible. The one that had the select all that apply had the best collection rates. This was because Joy and colleagues had worked with that municipality to develop standards for survey questions.

Default data standards had an impact on implementation and ultimately interoperability. 

## 3. Increase responsible use of roads. 

It is not enough to build it and regulate id, you need to spur data use and ability.

***Use a data maturity model***

> [!NOTE]
> See the data model that was presented by Joy on her blog post, [In search of a practical data maturity model for California](https://medium.com/caldata/in-search-of-a-practical-data-maturity-model-for-california-cd41d8ace046)


### Step 1: Get your data house in order:
- level 1: No data
- level 2: Data fire drill, answers but ad hoc
- level 3: Data on demand, Automated reports

Data teams in the public sector:

Time is consumed by manual processes usually in excel.

Typical workflow:
- Starts with a csv to excel
- Applies horrible unknown process
- Produce pdf or “overly” interactive dashboard

How do we liberate data folks from monotonous, manual data work?

### Step 2: Use data in decision-making

1. Performance management
        
Example: Supply chain issues with PPE

- 3 different departments with different physical data systems
- Different definitions and units across systems
- Lesson: finding common language

Takeaway: Dashboards are not the answer.

2. Evaluation and experiments

The regular pattern is ideas applied without experimentation without control

3. Advanced analytics

Barriers: Truffle pig problem

What are the problems in the public sector that are:
- Signs you have the problem.
- Can you make a dashboard?
- Automate a business process

Develop problem typology. Examples: 
- Needle in the hay stack
- Prioritize your backlog, expounded:
    - Usually FIFO
    - Categorization problem
    - Solution: Reorder cue by prioritizing on criteria

***The important element is the service change!***

4. Ongoing exploration and development. 

Bonus: Ethical Consideration means building in a point in the workflow both before and after development. 

## What should we do now?

***Don’t jump into advanced data analytics (including AI)***    

> [!NOTE]
> Data analytics can trigger the needed change in data management, etc. This is inline with some of the conversations that I have had with people about the real value of transitioning to AI is actually the increased focus on data management. 

### Warnings about data in public sector:

1. [Goodhart’s law](https://en.wikipedia.org/wiki/Goodhart%27s_law)

Definitions:

- "Any observed statistical regularity will tend to collapse once pressure is placed upon it for control purposes."
- "Any statistical relationship will break down when used for policy purposes."
- "a feature of the economy is picked as an indicator of the economy, then it inexorably ceases to function as that indicator because people start to game it."
- "Every measure which becomes a target becomes a bad measure"

Metrics can be countered by Results

***Joy's Public Management Paradox: Public goals are bad performance goals, and vice versa.***    

See [blog post](https://medium.com/@joybonaguro/the-paradox-of-public-performance-management-110363b168b8)

Programs come in different flavors and have different data needs.
- Regulators
- Funders
- Service providers

Storytelling is essential. 

> [!NOTE]
> I think about Dave's Cup. "Nice story, now show me the data." The truth is for data to have any impact it must tell a story. "Show me the data, Whats the story?"

### Do not let technology drive the change

Especially with GenAI. The problem is not purely technological but also social and cultural. New technologies do not change the underlying culture.

### Approach data as ecosystem.

**Data gyms**

Clarify roles and responsibilities:
- IT maintains Gym
- Data Team trainers
- Business and service providers need to commit to getting in shape

The important element is that we understand the human elements and address those from all angles. 

# Q&A

Harvey: What are components of a good data-driven story

- Minimize the data elements
- Highlight the problem and solutions, include data where it matters
- Standard narrative approaches to communication
- Making methods and stories public, make documentation a story
- Why dashboards, why not?
    - UI is not great or useful
    - Look at data journalism
    - Dashboards can be useful in operations with clear metrics and trained staff. 


# Takeaways:

1. For major changes to take hold, an organizations requires integrating data into it's human processes. This is not to say we need to reduce the human practices to the data-able elements, but developing meaningful interfaces between human and tech which is useful to the humans. 

2. If we are going to make technological changes (with or without the changes to the human side of things), it is going to require the real foundational work of data maturity. We will not be able to leverage any AI without having our data in order. 

3. Tell the story. A dashboard with a bunch of graphs is not a meaningful data product. Producing data products maybe shouldn't even be the point. The question is what data products are useful in making change to services? 
