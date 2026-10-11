The first three on our checklist have already been completed automatically:
- My developer account has been created
- We are currently logged into the PDI
- We will log into it regularly by default, as I will be doing this lab daily

![[Pasted image 20261002120717.png]]

You'll notice above, the only thing we have yet to tick off is `Learn to impersonate a test user and switch back`. Let's try accomplishing that!

---

## Learn to Impersonate Test User and Switch Back

To impersonate people, we have to create them first! This is located on the top left panel, known as the "Navigation Filter":

![[Pasted image 20261002121214.png|292]]

You'll notice that it's under "User Administration". We currently have the rights/permissions to do this as the PDI has automatically logged us in as an admin. A regular user will not be allowed to manipulate any accounts in the system. You'll notice the top right panel shows a dummy system administrator account, with the option we want below: `Impersonate User`. 

![[Pasted image 20261002121308.png]]

Before we impersonate anyone, let's make two accounts we can see the system through:
- **End User** - A testing role for an employee. They will have no roles.
- **Agent** - This will be the role I want to be employed in - the standard role that works with these incidents. 

Let's make both of these roles right now.

Upon clicking on the "Users" page in the "User Administration" category within the navigation filter, we are met with over 600 dummy users. I won't be using any of these and simply making my own:

![[Pasted image 20261002121656.png]]

You'll notice a very inviting blue button on the top right with the text "New". Upon clicking that, we can make our own users, with their specific qualities and roles:

![[Pasted image 20261002121750.png]]

Next to the "Title" box, there's a lightbulb icon. This is a useful feature for determining what to name the title you want this user to have. By title, we mean job and NOT "Mr." or "Miss."

![[Pasted image 20261002122006.png]]

Let's type out both users' credentials. Here they are below:

![[Pasted image 20261002122259.png]]

As of right now, our Agent does not currently have a role that can allow them to perform their job's actions. This is done AFTER creating an account.

If we scroll down from Isaac's page, our testing agent, we will see a "Roles" tab:

![[Pasted image 20261002122813.png]]

Like how we created our two users, let's click the blue button and add the role we desire:

![[Pasted image 20261002122853.png]]

The role Isaac needs is "ITIL", which you would remember is that global framework for businesses in IT related fields. Anyway, he has that role now. By adding "ITIL" to Isaac, he will automatically get all of the roles listed here:

![[Pasted image 20261002123030.png]]

With this done, we can finally impersonate him and fool around in the system as Isaac.

![[Pasted image 20261002123056.png]]

Upon clicking "Impersonate User", we are in!

![[Pasted image 20261002123141.png]]

You'll notice that our dashboard contains an overview, filled with widgets that would be very useful for someone in a Helpdesk job; SLA timers, Incidents assigned to you, Unassigned incidents and more.

On the right, you'll notice a calendar of sorts. This will let you know of things coming up, so you won't have to go chasing deadlines..

Anyway, that's our `Learn to impersonate a test user and switch back` skill checked off! We can end today's lab by ending our impersonation of Isaac

This can be done by clicking our profile picture on the top right and then "End Impersonation":

![[Pasted image 20261002123414.png|243]]


---

## Post Lab Thoughts

Things are a lot more complex when you choose to learn them as you go along, but man is it satisfying? This was very fun to do and I'm looking forward to doing more of it!

I've noticed a lot of similarities/overlap between this and the Active Directory labs I was doing a little bit ago. I suppose I like the aspect of managing users and finding the root causes of issues.

One of the items on the checklist is under "Admin" and it's to create a user. We did technically make two users, so I've preemptively ticked that off:

![[Pasted image 20261002123707.png]]

I'll see you tomorrow.