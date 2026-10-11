## Priority

To calculate the priority of tickets, I should use this formula:

`Priority = Impact x Urgency`:
- **Impact** - How much of the business is hit (e.g., a user, team or the WHOLE company?)
- **Urgency** - How quickly the ticket needs fixing

This is NOT a mathematical equation, but rather a matrix lookup, wherein impact and urgency are mapped to a priority. ServiceNow, (the service I will be learning!) apparently has this built in!

Here's the matrix below:

| **Impact ↓ / Urgency →** | Low             | Medium            | High              |
| ------------------------ | --------------- | ----------------- | ----------------- |
| **Low Impact**           | **P4 – Low**    | **P3 – Medium**   | **P2 – High**     |
| ** Medium Impact**       | **P3 – Medium** | **P2 – High**     | **P1 – Critical** |
| **High Impact**          | **P2 – High**   | **P1 – Critical** | **P1 – Critical** |

------

## P1 to P4

Within the matrix above, you'll notice "Ps". These of course mean the level of priority. Remember that P1 is the most critical, NOT P4:

**P1 (Critical)** - Email is down for company!:
- This affects EVERYONE and the impact/urgency is high because the business has stopped!

**P2 (High)** - A team cannot access a shared drive during month-end:
- The impact is high, but the urgency is medium due to it being a month-end deadline!

**P3 (Moderate)** - A user cannot log-into the database:
- The impact here would be low, due to it only being ONE user. 

**P4 (Low)** - Request to install a PDF application on a laptop.:
- Nothing is broken and alternatives/workarounds exist, meaning both the impact and urgency is low.

**P5 (Planning)** - Only some companies use this:
- Just planning. No deadline, no pressure.

----

It's important to note that a good ticket will have these aspects:
- A clear summary
- The affected groups/individuals
- What's been attempted to try fix it
- Any workarouds