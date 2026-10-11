## Incident vs request (RITM) vs problem vs change

*Let's go over some definitions that we must know for ticketing and assigning specific issues under:*

**Incident (INC)** - Something is broken and the service needs to be restored to how it was before. E.g., "Outlook won't open."

**Request (REQ/RITM)** - Someone desires something, from the service catalog. A **REQ** is the order, whereas a **RITM** is each item in it, and **SCTASKs** are the fulfilment tasks.

**Problem (PRB)** - The root cause behind one or more incidents. Fixing it will mean incidents relating to it will stop. 

**Change (CHG)** - A planned modification to the environment. Please remember the three types from before:
- **Standard** - Pre-approved changes
- **Normal** - Requires approval
- **Emergency** - Critical changes that are absolutely required.

Quick Rule of Thumb:
- **Broken?** - Incident
- **Want?** - Request
- **Why does it keep breaking?** - Problem
- **Changing something?** - Change

All of the ticket types from above can be searched via the filter navigator. For example "Change":

![[Pasted image 20261011141323.png|220]]

-----------

## Priority from Impact and Urgency

Remember this?

| **Impact ↓ / Urgency →** | Low             | Medium            | High              |
| ------------------------ | --------------- | ----------------- | ----------------- |
| **Low Impact**           | **P4 – Low**    | **P3 – Medium**   | **P2 – High**     |
| ** Medium Impact**       | **P3 – Medium** | **P2 – High**     | **P1 – Critical** |
| **High Impact**          | **P2 – High**   | **P1 – Critical** | **P1 – Critical** |

-----------

## SLA Timer on a Ticket

**SLA (Service Level Agreements)** are formal commitments that defines how quickly a support team must respond to and resolve a customer/internal support ticket. 

Let's click on a random ticket and see if we can view the timer. We can do this by pressing the gear icon on the top right on the Incidents page and adding "Made SLA" so we can filter by incidents with SLAs:

![[Pasted image 20261011143749.png]]

Perfect! Now by scrolling down from a random ticket after we refresh the list, we can view the task SLAs:

![[Pasted image 20261011143849.png]]

------

## Understand Pause and Breach

In the Task SLAs section of the previous section, we're able to see a "Stages" column, which states the stages of the SLAs:

![[Pasted image 20261011144002.png]]

We can see that one of them has breached, meaning it has exceeded the SLA. SLAs will only attach when a definition's conditions match. You can see said definitions through the SLA page via the filter navigator:

![[Pasted image 20261011144111.png]]

-------

## Searching the Knowledge Base

The knowledge base can be accessed through the filter navigator:

![[Pasted image 20261011144209.png|221]]

From here, we can view articles on previous issues that have been resolved. This is very handy for when you need to remember how you fixed a problem from before:

![[Pasted image 20261011144638.png|348]]

-----

## Attaching Knowledge Base to Tickets

![[Pasted image 20261011145001.png]]

A Knowledge-Base article can be attached to a ticket by linking the problem and/or parent incident.

----

## Creating a KB Article

Within the article page, you can click "New" to add a new article.

![[Pasted image 20261011145140.png]]

We have to select a knowledge base first. Let's do that right away:

![[Pasted image 20261011145158.png]]

I have selected "IT". Let's proceed by entering a knowledge base article of our choosing. We can then enter all of the information about how to fix this specific issue:

![[Pasted image 20261011145427.png]]

Upon clicking save, it is now done!:

![[Pasted image 20261011145510.png]]


-------

## Users, groups and roles basics

**User** - A person
**Group** - A team of "persons", e.g., "Service Desk" is a team
**Role** - A bundle of permissions that allow a user to perform their job

Remember from Day 1 that we can access the filter navigator to edit any users and groups:

![[Pasted image 20261011145644.png]]

--------


