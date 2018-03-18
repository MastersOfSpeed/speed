
[Using Scrum, what is a good method to calculate Story Points on the planning?](https://www.quora.com/Using-Scrum-what-is-a-good-method-to-calculate-Story-Points-on-the-planning)

Great example from Damien Filiatrault, Founder, Scalable Path [Premium Developers & Designers On-Demand]

"Common Story Point estimating methods include t-shirt sizes (S, M, L, XL), powers of 2 (1, 2, 4, 8) or the Fibonacci sequence (1, 2, 3, 5, 8, etc). We (here at Scalable Path) personally favor the Fibonacci Sequence – 0, 1, 2, 3, 5, 8, 13, 21, etc – as an exponential complexity scale (good discussion on why, other than the cool name). It best suits our needs of providing visibility into timelines, complexity, budget, and staffing for clients.

This is how we use the Fibonacci Sequence as Story Points:

POINTS & MEANING

0 – VERY QUICK TO DELIVER AND NO COMPLEXITY; ON THE ORDER OF MINUTES

One should be able to deliver many 0’s in a day
I know exactly what needs to be done, and it’s going to take me very little time
Example: Change color in CSS, fix simple query
### 1 – QUICK TO DELIVER AND MINIMAL COMPLEXITY; ON THE ORDER OF A AN HOUR+

One should be able to deliver a handful of 1’s in a day
I know exactly what needs to be done, and it’s going to take me little time
Example: add field to a form

### 2 – QUICK TO DELIVER AND SOME COMPLEXITY; ON THE ORDER OF MULTIPLE HOURS/HALF-DAY+

One should be able to deliver one 2 comfortably in a day
I mostly know what needs to be done, where improvements/changes need to be implemented, and it’s going to take me some time
Example: Add parameter to form, validation, storage

### 3 – MODERATE TIME TO DELIVER, MODERATE COMPLEXITY, AND POSSIBLY SOME UNCERTAINTY/UNKNOWNS

On the order of about a day or more to deliver
I have a good idea what needs to be done, and it’s going to take me a bit of time
Example: Migrate somewhat complex static CSS into a CSS pre-processor

### 5 – LONGER TIME TO DELIVER, HIGH COMPLEXITY, AND LIKELY UNKNOWNS

On the order of about a week or more to deliver
I know what needs to be done at a high level, but there is a good amount of work due to complexity/amount of development, and there are big unknowns we’ll discover as we get into the work.
Example: Integrate with third-party API for pushing/pulling data, and link to user profiles in platform

### 8 – LONG TIME TO DELIVER, HIGH COMPLEXITY, CRITICAL UNKNOWNS

On the order of a couple weeks+
I understand the concept and the goals, but it will take a while to deliver due to amount of work, complexity, and unknowns
If we have an 8, we should breaking them into smaller tasks/issues with smaller point values and minimize the complexity
This might require a Spike to architect/remove uncertainty, or be created as an epic with more granular stories within it
Example: Overhaul the layout/HTML/CSS/JS of a web application

### 13 – LONG TIME TO DELIVERY, HIGH COMPLEXITY, MANY CRITICAL UNKNOWNS

On the order of many weeks/month
Similar to an 8; this should definitely be an epic, and requires discussions around how to accomplish
Example: Migrate application from outdated data store to new DB technology and ORM

### 21 – YOU’RE DOING THIS WRONG…

As you can see, this is not clear cut, and leaves much room for interpretation. Estimating software development is difficult, and there are many factors to consider, including complexity to develop given existing architecture, team availability, business priorities, unforeseen third party complexity, use of CD (Continuous Delivery)/automated testing, etc. What teams should strive to do is build a culture where there is a good grasp on the solution, and all agree on definitions for the level of effort required to deliver each piece of functionality, task, bug fix, etc."

