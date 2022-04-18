# What is Scrum?

Scrum is an agile methodology - this means it is a recipe for a way of working that is based on the principles of agile. The idea is that this gives you a ready-made + proven way of adopting agile. Importantly though, the team needs to understand the principles behind it for it to be truly effective.

This is the methodology that I have used most during my career, to varying degrees of success. I saw most success when the team collectively owns the project, rather than a top down approach where tickets are written and assigned to people on their behalf. The most effective Scrum teams have a sense of collective commitment that comes from being given the ownership + authority to make decisions about how to plan / design / implement software.

## Scrum Roles

Scrum identifies 3 roles:

### 1) Product Owner

*someone from the business, the key stakeholder*
- work with the team to maintain a prioritized backlog
- help the team understand the value of the software they create
- understands what tasks are important and when a task is truly done
- works with the team everyday to answer detailed questions
- makes lots of small decisions about how the product should work
    - empowered to do this by the business
- collects information + requirements from other stakeholders

### 2) Scrum Master

*the person that guides the team in using Scrum*
- gathers the team for the Scrum meetings (see below)
- helps team get past bockers identified
- importantly this person doesn't own or dictate a plan 
    - the full team owns the plan
- helps the team to understand the agile principles behind the practices of scrum

### 3) Team Member

*a member of the team that works on the project*
- attends the various Scrum meetings (see below)
- works with the rest of the team to break requirements down into a plan
- estimates how long pieces of work will take
- plans each sprint with the rest of the team
    - empowered to say what is or isn't possible in the timeframe
- works with team to design software
- works with team to implement software


## Basic outline of Scrum process

### Sprints
The team work in timeboxed iterations called *sprints*.

At the start of each iteration, the team does sprint planning together. Here they decide together what work will be done in this sprint. It is then up to the team how and by whom this work is done during the sprint. 

There is a collective commitment from the team to finish the work planned for the sprint.

**Tips for running an effective sprint**

1. **Start from the backlog.** Product Owner should be working with the team to prioritize the backlog. They should understand and communicate what is most valuable in the backlog. During planning, try to add those tasks first.
2. **Be Realistic.** Developers tend to underestimate complexity, so don't cram things into the sprint. The Scrum Master should try to help determine what is possible.
3. **Change the plan if you need to.** Daily standups are there to adapt what we are doing in order to complete the sprint. If it becomes clear that some things won't be finished, then move work out of the sprint and back to the backlog (start with lowest value tasks). The Scrum Master should make sure everyone understands the change, the Product Owner can communicate to other stakeholders.
4. **Get the whole team talking about value.** The whole team should be encouraged to discuss the value of each item in the sprint. This promotes understanding of the value of what the team is working on.

### Daily Scrum / Standup
Each day the full team (including Product Owner) meet face-to-face for a daily scrum (I've mostly seen this called "a standup").

**The purpose of this meeting is not to get status updates from the whole team!**

The purpose of this meeting is for the full team to understand the work that is being done, and adapt the working as needed to complete the sprint.

e.g. the goal is to uncover things like:
- an engineer is blocked because they don't have access to a database
    - => the scrum master works with them to get access
- an engineer is finished with their current tasks
    - => the team decides together what they should work on next
- an engineer has identified an ambiguous requirement
    - => the team talk together to decide how to implement the feature

To uncover these things + start these discussions, typically each person answers 3 questions:
- what did I do yesterday?
- what will I do today?
- is anything blocking me?

In general, the standup should be timeboxed to 15 min, and any discussion that goes more than a minute or 2 should be tabled + the team members that need to can meet right after to have the discussion. This keeps the daily meeting from eating up too much of the team's time.

**Tips for running a better standup**

1. **Take turns going first.** This de-emphasises 1 person being the *owner* of the meeting. Gets the team out of status update mindset and encourages everyone to feel like they own the meeting.
2. **Don't treat it like a ritual.** It's easy to fall into patterns and switch off your brain. Stay attentive + be on the lookout for issues that need to be solved to complete the sprint.
3. **Everyone participates.** Including the Product Owner + Scrum Master who should also answer the prompts. The meeting is not meant as a status update from team members, but for the full team to understand and inspect the work being done (including what the Product Owner is doing!).
4. **Inspect every task.** Don't just look at what is being worked on, also consider tasks in the *To Do* column and look for potential roadblocks there.
5. **Change the plan if you need to.** Use this meeting to adapt. This could mean adapting the approach to completing a piece of work or who will work on it. It could also mean removing work that is no longer needed or that you realize isn't going to be completed in time.



### Demos

At the end of each sprint, a demo of the work is given to stakeholders. This is meant to be given by the whole team and is the deliverable that the team are accountable for.

In my experience, it is hard to give a compelling sprint demo working in data and ML because often the work is hard to see (e.g. improving an algorithm). But I think something like this is still valuable if done right since it puts the focus on iterative progress with something to show or talk about at the end of each sprint.

### Retros

At the end of each sprint, the whole team holds a retrospective where they talk about the work done. 

The goal here is to collectively find ways to improve the Scrum process.

In some teams the retro can get bogged down in technical details, but really the goal is not to discuss technical designs but *anything we can do to improve the effectiveness of the team*.

e.g. it could be things like:
- we need to stop under-estimating complexity
- we should rearrange our desks
- we should hold retros 1 hour later
- etc

The idea is to empower the team to decide how to improve.

Often the way we try to come up with these improvments is to prompt each team member:
- what went well this sprint?
- what went not so well?

and then the team tries to dig into the answers and come up with improvements.


# Commitment - the magic ingredient!

The key idea behind Scrum is that *the team collectively owns the project*. The idea of having the Scrum meetings is that the full team participates in planning and adapting to change. This is very different to traditional teams where 1 person typically owns the plan.

It can be hard sometimes for a team to take on this mindset, both team members and managers want to revert to either:
- team members just write code, if things go wrong, then the plan was at fault
- managers want to be gatekeepers and feel important by owning a plan

Ideally, we want everyone on the team to be *commited* to the project.

This means, simply, that rather than working towards their own goals + covering their own butt, they are working to make the project successful. Their success is the project's success.

If we can get the team into this state then everyone begins to contribute ideas + is invested in reacting to changes and fixing problems.

The key to encouraging this mindset is to do 2 things:

1. **give everyone on the team the power to make decisions.** e.g.
    - by planning together, everyone owns the plan
        - a team member should be encouraged to push back when a task is too long or badly defined
    - in a retro, everyone can suggest improvements
        - these should always be taken seriously and adopted if the team agrees
2. **help the team understand the value of the software they are producing.**
    - this is the key for motivation, people want to understand the impact their work will have and see that impact play out.
    - the Product Owner should be able to bring this understanding
    - this is not a one-off explanation, it is a continuous process of understanding changing needs + how the team is meeting them

The benefits of a commited team are huge:
1. **Happiness** - a commited team is invested and it feels good to own something
2. **Better Planning** - team will estimate realistically and less likely to overload themselves, since they are responsible for the plan
3. **Flexibility** - empowered team can adapt to change based on skills and availability, they can achieve the sprint goal however they like
4. **Productivity** - being responsible for the project's success means the team chooses to work on the most valuable tasks




