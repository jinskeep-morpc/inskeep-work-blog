---
title: 2025 Ohio GIS Conference Notes
date: 2025-09-15
tags:
    - conference
    - spatial
    - blog
---

# Breakout Session 1: Applying Project Management Principles to Geospatial Projects and Programs

Speaker: Ashley Hitt, Cultivate Geospatial Solutions

## Project Knowledge Areas

1. Integration  
2. Scope  
3. Schedule  
4. Cost  
5. Quality  
6. Resource  
    -  Technology and People  
7. Communications  
    - "Top project managers are 90% focused on communication."  
8. Risk
9. Procurement  
10. Stakeholder  

## Project v. Program

### Project
- Has specific objectives
- Elaborate plans progressively
- Scope defined by objectives

Temporary and Unique

### Projects
- Long-term 
- High-level plans
- Value Driven
- Adaptive

Coordinated between projects

## Product Management
- Product lifecycle
- Create, Maintain, Evolve, Retire

## Project and Product Lifecycle

### Product Lifecycle

1. Concept
2. Delivery
3. Growth
4. Maturation
5. Retirement

## Management Approaches

### Waterfall

Task 1 -> Task 2 -> Task 3

1. Gantt Charts
2. Hierarchical task and activities

### Agile

Plan -> Iterate -> Feedback -> Repeat

1. Product backlog - What are we waiting on
2. Sprint planning, short term planning, think in days
3. Sprint Backlog - What work didn't get done last time
4. The Sprint
5. Stand ups
6. Demos, Feedback, Reviews

#### User Stories

A short description of a feature or ability

1. Tasks to sprints based on the needed task for each user story

### Which is right?

Hybrid and other combinations are options.

Specific start and end dates are constraints

### What causes failure?

1. Inaccurate Requirements
2. Inaccurate vision or goals - What's the why?
3. Inaccurate constraints

### Triangle of Tradeoffs

Scope -> Budget -> Schedule

## Risk Management

What could potentially happen? What is the response?

### Risk Identification

1. Status - Active, Dormant, Retired
2. Type - Threat or Opportunity
3. Category - Organizational, Technical, External, Management

### Risk Statement

If - Then 

### Risk Rating

 - Probability v. Critically

### Response Response

1. Strategies and Action

### Risk Owner

### Risk Register

- Spreadsheet including the above

## Change Management

1. Policies
2. Formal change control and approval
3. Project management approach
4. Tracking changes

## Trainings and Certs

Project Management Institute

- [Agile Practice Guide](https://www.agilealliance.org/wp-content/uploads/2021/02/AgilePracticeGuide.pdf)


# Breakout Session 2: Everywhere, Everywhen: The Geography of Existence

Todd Tuckey, Heartland GIS

## Core Principles

1. Geography is the science of when and where
2. Space and time is inseperable

## Moving away from the Big Bang

- Geography is tied to movement,
- Movement away from big bang
- 380 million years after light began
- Misunderstanding about space

## Geography is atomic

- Everything exists in grids
- Understanding these grids is the base of geography

## The science of where

- Location
- Place
- Scale
- Movement, Can not be left out

## Geography is not fixed

- Often taught as fixed.
- Over emphasize static

## Space/Time

Speed is relative

- We are moving 1675 km/h around the earths surface
- "We are creating a biography of time, history and space"

## Physical Geography

- the material where
- Measuring and documenting the physical world

## Human Geography

- The experiential where
- Sense of place
- The material of our memory
- Culture and place
- an attachment to geography

## Geographic Traditions

- Difference between representation of space

## Landscapes are in flux

- Maps freeze time
- Illusions of permanence
- How do manage the idea of movement?
- We know rivers change, forests expand and contract

## Geography is temporal

- Place = Space and Time
- Space-time fabric



# Hosted Feature Layer Views

Kelly Wright

## HFL 101

- Feature Class in AGO
- includes spatial and non-spatial data

### Benifits 

- Persistent later configurations
- No server (no versioning!)
- Centralized data source for multiple uses

### What it does?

- Filter, Area of interest
- Multiple views, persistent between data and views
- No data duplication
- Views can included ability to limit access, users, etc.

### Why?

- custom perspectives on data
- access
- Control who sees what
- Edit capabilities are different
- No need to share parent feature layer
- streamlines maintainability

### Control Access

- Need to know basis
- Use groups
- Leverage group roles
- Usable for offline sync

### Enforce Data Governance

- Enable editor tracking, Who created or edited a record - a little dicey
- Apply ownership access and editor
- Use backups
- Use HFL views

## Hosted Feature Layer Views

### Creating and Managing

- Creating a view: filter, fields, and permissions
- Assign the access controls: viewers, editors, admins
- Filter based on uses: spatial and attribute filters
- No need for delete ability
- Change views as data changes

### Steps to publish

- a whole bunch of ESRI jargon
- Many warnings about how the software isn't compatible with itself
- Publish on AGO

### Publish in AGO

- From Feature layer overview
- Click create layer view
- Select joined view layer
- Weird GUI problems. Not sure didn't follow
    - All of this can be fixed with Postgis and some SQL queries

### Managing in AGO

- Authoritative and Deletion protection in Settings
- Public Data? 
- Allow export of data for exports from experience builder

### Joined view layers

- Once created, you can not edit underlying feature layer schema or domain

## Pitfalls

## HLV Maps, Dashboard, Apps





