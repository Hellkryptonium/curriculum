+++
title="Backlog"
emoji="📝"
time= 30
vocabulary="Backlog"
hide_from_overview=true
[tasks]
    1="Find the backlog"
    2="Copy your tickets to your own backlog"
    3="Manage your tickets on your board"

[build]
  render = 'never'
  list = 'local'
  publishResources = false

+++

In software development, we break down complex projects into smaller, manageable parts, which we work on for a week or two. These periods are called "sprints."

A sprint backlog is like a to-do list. It lists what the team has decided to work on this sprint. It's chosen from a larger list, usually called the "product backlog," which holds the entire project to-do list.

In this course, the backlog is a set of work designed to build understanding beyond the concepts introduced in the course prep. For your course, we have prepared a backlog of mandatory work for each sprint. You will copy these tasks into your own backlog. You can also add any other tickets you want to work on to your backlog, and schedule all of the tasks according to your own goals and capacity. Use your planning board to do this.

You will find the backlog in the **Backlog** view on every sprint.

Copy the tickets you are working on to your own backlog. Organise your tickets on your board and move them to the right column as you work through them. Here's a flowchart showing the stages a ticket goes through:

flowchart TD
    subgraph Remote["Remote (GitHub)"]
        A["CodeYourFuture/education-blog"] -->|fork| B["EagerLearner/education-blog"]
    end
    
    B -->|clone| C
    
    subgraph Local["Local (your computer)"]
        C["YOUR_CYF_FOLDER/education-blog"]
    end
    
    %% Style definitions
    classDef container stroke-dasharray:5 5,fill:#f8f9fa,stroke:#495057
    classDef rounded rx:10,ry:10,fill:#e9ecef,stroke:#495057
    classDef arrow color:#0d6efd,stroke-width:2px
    
    %% Apply styles
    class Remote,Local container
    class A,B,C rounded
    linkStyle 0,1 stroke:#0d6efd,stroke-width:2px

{{<note title="Backlog (30 minutes)" type="activity">}}

1. Find the sprint backlog
2. Copy your tickets to your own backlog
3. Organise your tickets on your board

{{</note>}}
