There are **4** types of tickets we'll primarily be working with in regards to ticketing:

-----------
## Incident

**Incident Tickets** - An unplanned interruption or reduction in quality of a service:
- **Goal** - Restore service ASAP to make it function as intended
- **Example** - "My VPN keeps dropping every 10 minutes!"
- **Sub-Type** - **MAJOR INCIDENT** - A major incident can occur, wherein the impact is huge and affects the revenue, users or critical systems of an organization. (You do NOT want this to happen)*

*In the event of major incidents:
- A "Major Incident Manager" usually takes charge, with their whole job being to co-ordinate the response, rather than fixing it themselves
- Sometimes a **war room** gets spun up with everyone relevant - **Basically, all relevant teams trying to work together and fix the critical issue**
- **Communication With Stakeholders** - Management will often have to communicate with stakeholders to elucidate the problems and give them an ETA
- Once fixed, a **Post-Incident Review** (postmortem) occurs, wherein a formal write-up of what occurred and what happened to stop it from recurring is illustrated.

----
## Service Request

**Service Requests Tickets** - A little less serious. Usually a low-risk, pre-approved ask from a user. Nothing is usually broken:
- **Goal** - A user wants a specific request/addition.
- **Example** - "Can you reset my password, please?"
- This is often handled via a **Service Catalog**; a menu of standard requests with pre-defined approval workflows, preventing techs from reinventing the process each time.

------
## Problem

**Problem Tickets** - The underlying cause of one or more **Incidents** (known or unknown!):
- **Goal** - Let's **permanently fix** the incidents, rather than just use a band-aid fix.
- **Example** - 15 separate **Incident** tickets revolving around the printer not working usually will help shine the light on a bigger problem, e.g., **one bad print server config**

There are two states you'll usually see here:
- **Known Error** - Root cause identified, but no permanent fix deployed yet
- **Problem Record** - Logged, under investigation

It's important to note that a **"Problem"** ticket aims to fix a problem/incidents PERMANENTLY, where's a **"Incident"** ticket is usually a temporary problem that you try to fix as soon as you can.

A lot of **Incident** tickets can indicate a deeper **Problem** within an organization.

------
## Change

**Change Tickets** - Any addition, modification or removal of anything that could affect IT services:
- **Goal** - Safely manage and track modifications to IT systems, infrastructure, or project scope without causing unexpected downtime or risks

There are three sub-types I should know "cold":

**Standard Change** - Pre-approved, low-risk, repeatable (e.g., a routine software patch following a KNOWN procedure). No individual approval needed each time:
- **Example** - Installing a routine monthly Windows security patch on employee laptops, via a patch management tool.

**Normal Change** - Needs assessment and approval (Usually by a **Change Advisory Board**) before any change happens:
- **Example** - Upgrading the company's mail server to a new major version this weekend. To do so, someone has to submit a **Change Ticket** explaining what's happened, as well as the risks, rollback plan and what would change
- (**Above all else, just remember you require PERMISSION here from a board.**)

**Emergency Change** - Urgent changes needed! Needs to happen NOW to prevent a major **Incident**. Approval is often fast-tracked to an emergency version of a **Change Advisory Board** or a single authorized manager:
- **Example** - You have a CRITICAL security vulnerability that's actively being exploited on your public-facing web server right now! You need to patch it ASAP, without waiting for that long CAB meeting every week.

A good way of remembering all of this would be:
- **Standard** - A routine update/change the organization is used to.
- **Normal** - Risky enough to need a proper review
- **Emergency** - Very risky and urgent. No time to wait through that whole process

