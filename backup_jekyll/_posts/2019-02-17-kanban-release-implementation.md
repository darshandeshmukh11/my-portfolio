---
layout: post
published: true
title: Kanban implementation
subtitle: How we implemented Kanban for a software delivery
date: '2016-01-26'
tags:
  - agile
---
Recently I worked with a team with –
- No formal QA process (I was the first QA person in team)
- Inconsistencies in testing environments i.e. sandbox. environment was not a replica of dev. env
- Client was relying on third party vendors for their UI/UX requirements 
- No release plan in place and the team was forced to follow tight unrealistic deadlines 🙂 with say please fix these all 32 issues + 4 high priority features before 28th Jan.  
- Long feedback loop and customer complained, well we need something different than what you have built as our requirements have changed now! 
- There was no one to blame for as the problems were not visible early.
- Lot of micromanagement and no ownership from the team members 

### The typical path for release looked like this – 
![Release-cycle](/img/release-path.png)

### As a team we decided to breakdown the current workflow and we created this Kanban board – 
![Kanban-borad](/img/kanban-board.png)

The best thing about Kanban is it doesn’t require any additional role (like a Scrum Master 🙂 )
and it doesn’t require any major changes in your current processes.

### How it helped us – 
- **Better visibility** – WIP limits made the blockers visible and people took ownership for swarming if someone is lagging and if the client wants something urgent to be pushed to production
- **No blame game** – As every step was clearly visible on board the team ensured that they are removing the blockers for each other and it resulted in good team spirit.
- **Early feedback and stable good quality release** – The team worked with consistent pace and client was happy as they were able to play with the product increment on a weekly basis. It was much easier for the team to work on any last minute changes.
- **Building what customer really cares about** – Continuous feedback, time boxed sprints and flexibility to re-prioritize sprints helped the team to only focus on features user really need and not the features that are no longer required (due to change in business/scope etc.) 
- **No burn out for team** – As we were delivering at a sustainable pace the overtime was reduced to 7% which was close to 20% earlier resulting in better job satisfaction and motivation for everyone contributing in a team.
