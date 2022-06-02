## Setup. 
#### The launch of new casino. Introduction
To launch a new product we have to complete the following steps:
1. Provide the data required for the app config.
2. Refactor, update and extend the default template due to the business & 
design requirements.

The second step includes the full cycle of development process which is
meant to provide a ready to be purchased product as the result. It takes 
weeks to deliver the app to the customer. Such a long and complex kind of 
process requires:
- Carefully designed patterns for every stage
- Structured system of creating every single part of the application.
- Valuable and clear requirements that determine the definition of 
done of every single part.
- The stages of these process should be as flexible, non-related and
  order independent as it's possible.

If the process of a product development is organised in such a predictable 
way the development and management teams (it, designers, leads, 
product/project managers) are able to perform the most efficient level
of cooperation as the focus of the entire product team is not limping from 
one question to another during the whole production cycle but is completely 
on the result that resolves all the customer requests and needs.  
However, there is no key to any lock, and until that we should take about the 
patterns and methods that we use, refactor and maintain all the steps and 
stages to improve the final result. It means, that we have to discuss and fix 
the issues that have been revealed.  

#### Why does that matter?  
Such kind of improvement covers a couple of aspects that are valuable for 
any IT company, and especially, for the company that provides its own 
software as a product:
- The documented and set up from the box development plan as most of the 
higher level modules are shared between the projects.
- Predictable and clear state of the project on any point of the timeline.
- Team members can be easily switched, substituted, removed from or included in team on any 
(or almost any) stage of the development.
- The time and possible issues of the product delivery are reduced and easy 
predictable for most business cases as the most part of the product 
development is already described and arranged.

#### Problem
The setup of the new project is described in a single ticket typed **Setup**. 
In the description of the ticket we have all the data required for the app 
config and links to the designs. Not sure about the average estimation for 
the ticket but obviously it takes at least several weeks to finish the 
task. In `confluence` we have partial information about some basic/shared 
steps that are involved in every dev cycle.  
The **ER** of a ticket is actually a ready to be purchased application. 
Basically we get a ticket that is estimated for several weeks and stands 
for that complex process of product development from the beginning, a 
default template, to the very end, the ready to be used app.  
There is no any description of the plan itself, of the way to get the **ER**.

#### Solution
There are always lots of opportunities for the improvement. But there two 
key points that shouldn't be missed in order to make it really efficient:
- Collecting and handling the issues
- Prioritizing of the collected issues  
  
Let's formulate the issues described above:  
- No structured development plan but just the only requirement to get a 
finished product version
- Constant questions that occur here and there with no determined source of 
truth that leads to non-predictable and non-linear stages of development 
process as the problems are revealed on a go
- No room and time for improvement as nothing is structured and nothing can 
be planned
  
There are definitely more side effects, but we are here in sake of statement 
of some achievable results but not to count the things.

To begin with, I would suggest to destructure the following ticket into the 
parts that might be relevant and understandable to all the members of a 
development team.

https://confluence.softswiss.com/display/SET/Setup  
To do that we should divide the app and extract the independent parts or 
modules which in a combination stand for the entire product. 
Here is the list of such modules:
- Header, Aside, Navigation, Notification Center, Auth panel, 
User Control Panel
- HOME page
- CMS pages
- GAMES page
- GAME page
