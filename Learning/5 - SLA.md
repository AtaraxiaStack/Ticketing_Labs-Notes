**SLA (Service Level Agreement)** - A promise about how fast support will respond to and fix things:
- Usually measured by timers on each ticket.
- The time remaining depends on the priority. A high priority ticket will have a shorter time, due to it being more important

-----

The **TWO MAIN TIMERS**:
- **Response** - Time until someone acknowledges and picks up the ticket.
- **Resolution** - Time until it's actually fixed.

Example/Theoretical Targets:
- **P1** - 15 minute response - 4 hour resolution
- **P2** - 30 minute response - 8 hour resolution
- **P3** - 4 hour response - 3 days resolution
- **P4** - 1 day response - 5 day resolution

-------

## ServiceNow

According to ServiceNow's documentation...:
- SLA Definitions hold the rules; start, pause and stop conditions, duration and schedule.
- When a ticket matches, it receives a Task SLA record attached, which you see on the ticket form with a progress bar.
- Stages are roughly: **In progress, Paused, Achieved and Breached


---

## Breaches/Pending

**SLA Breach** - This occurs when a service provider fails to meet a measurable promise made in the initial SLA. This could be due to:
- **Missed Deadlines** - "We didn't have enough time!"
- **System Downtime** - The system goes offline in an unforeseen way
- **Resource Shortages** - High ticket volumes, staff shortages or bad work routing.

----

When an SLA is about to breach, it's recommended to do the following:
- **Problem Identification** - You should check on WHY the promise can't be met. The fix usually depends on the blocker.
- **Early Escalation** - Do not wait until 95% on the progress bar; escalate issues early and pass it to a more skilled team.
- **Inform User** - Be transparent and tell the user what's happening. Be honest, rather than silent.
- **Document Everything** - Add notes on what's happening, e.g., what you tried, who you contacted, etc. Even if a breach does occur, this will show you actually tried.
- **Keep Working** - A breach doesn't end the ticket. It's imperative you keep trying.

-----

## Pending

This means the ticket is paused because the next move isn't yours. Work cannot continue until something outside your control occurs:
- It's a **WAITING** state, rather than a progress state. Nothing is wrong with the ticket, it's just block.
- The usual reason is waiting on the user for more info, a reply or approval on something

Common pending reasons (Service Now):
- **Awaiting Caller** - I need the user to speak to me
- **Awaiting Change** - Blocked until a change request completes
- **Awaiting Problem** - Waiting on work on the root cause
- **Awaiting Vendor** - Waiting on an outside supplier

It's usually bad practice to use a "pending" status to dodge a breach or to pause when YOU'RE the one who's stuck.