---
layout: lab
num: lab03
ready: false
desc: "Deliver Hello World, Plan for Retro, MVP"
assigned: 2019-01-31 16:00
due: 2019-02-07 19:00
github_org: "ucsb-cs48-w19"
---

<div style="display:none">
https://ucsb-cs48.github.io/w19/lab/lab03/
</div>

<style>
div.grade { margin: 2em; padding: 1em; border: 2px solid #0c0; background-color: #efe; }   
</style>

<div style="float:right; width: auto;">

<table style="margin-top:1em;">
<tr>
   <th>Points</th>
</tr>
<tr>
   <td class="pointCount"></td>
</tr>
</table>

</div>

# What you need to finish TONIGHT

* Conduct a standup meeting (5-10 minutes)
* Choose a leader for next week's sprint retrospective
   * Put the name of that leader in a card in the "TODO" column of your Kanban board, e.g. "Chris will lead team in first Retro"
   * Note, for full course credit, each of you needs to take a turn taking a leadership role in some activity.  
   * If you don't lead a retro, you'll make a class presentation at some point.
   
* Review your deliverables for [lab02]({{'/lab/lab02/' | relative_url }}) 
* Complete the sprint planning (generating user stories, issues) for a complete MVP that you can fully deliver by two weeks from tonight.
   * That MVP should go beyond a "hello world" and should deliver actual value to the end user

# Choose the right size MVP!

<div style="font-size: 150%; width: 35em; margin-left:auto; margin-right:auto; background-color: #fef; border: 4px solid red; padding:1em;" markdown="1">

* If it doesn't deliver value ⇒ too small
* If you can't finish by due date ⇒ too big

</div>

You main task tonight is to adjust the user stories and issues that you want to include in the MVP.

There is more detail on how to do that below.


# Conduct a standup meeting (5-10 minutes)

You are encouraged to conduct a standup meeting as a team.

Find a space in which to gather, standing in a circle, and answer three questions:
* What have you done since our last team checkin
* What are you working on now?
* Are there any barriers or blocks to your progress?

Direct your comments *to the entire team* (not to your mentor/TA/instructor, or a perceived peer team leader)

Suggestion: Set a timer for six minutes.  
* If six minutes goes by and you are aren't done, you are probably letting each member speak more than is ideal; try to focus just on answering the three questions.  
* If there are issues that need to be discussed outside of standup, you are encouraged to NOTE THEM, and come back to them as a team AFTER standup.

# Choose a leader for next week's retrospective

Choose a leader for next week's sprint retrospective.  That sprint retrospective will take the entire lab period next week.  Attendance at that 
lab is therefore particularly important.  

* Put the name of that leader in a card in the "TODO" column of your Kanban board, e.g. "Chris will lead team in first Retro"

Note, for full course credit, each of you needs to take a turn taking a leadership role in some activity.  
   * If you don't lead a retro, you'll make a class presentation at some point.
   * So you are encouraged to volunteer.  
   * Once you've led one retro, you'll have fulfilled your duty to exercise leadership at least once.
   
# Review committment to attendance and team norms

Note to each individual: If you cannot be at next week's retro in person, discuss this with your team.

Teams generally understand that members may occasionally need to miss a single activity now and then.  It is helpful to balance unavoidable
occasional absences with renewed commmitment to team goals.

Any time you miss a team activity, you may want to consider making a 
special committment to be sure that you are present for other team activities in the future.  Review your team's norms in this regard.


# Checking over your deliverables for [lab02]({{'/lab/lab02/' | relative_url }}) 

Look at the green "Graded" boxes in the instructions for [lab02]({{'/lab/lab02/' | relative_url }}) and review the due
date for that lab.  Tonight is likely your last oppportunity to get things together before the grading of those deliverables
begins.

# MVP Planning

To help your team (as well as your instructional staff) know what you are defining as part of your MVP---which you are delivering two weeks from today
, we are asking you to do things process/tool wise:

* Create a new column on your Kanban board.  
   * Call it MVP, and put everything (in terms of user stories and issues) from the TODO column that is part of MVP into that column.
   * Leave everything that is NOT part of MVP in the TODO column.
   
In addition, issues on Github can have tags.  Github creates some predefined tags, but can edit these and add new ones.

* Add a new tag called MVP.
   * Add that tag to all of the issues that are in the MVP column, as well as any issues that are already in-progress or done
      that are part of your MVP.
 
Finally, while regular cards cannot be given "tags" in the same way that issues are, you can just use the letters `(MVP)` in parens
as a kind of tag on the user stories that are part of your MVP.

In this way, anyone can look at your Kanban board, and see:
* What is, and what is not part of your MVP
* Which user stories and issues are still not started, in progress, or done, with respect to your MVP.

# Deliverables and Grading for {{page.num}}

By the end of due date of this assignment (i.e. {{page.due |  date: "%a, %b %d at %l:%M%p"}}), you should be halfway done
with delivering a significant number of issues towards your MVP.

Here's what we'll be looking for and grading:

<div class="grade" markdown="1">

{{page.num}}


**Graded ({{page.num}}-I)**: (20 pts) towards the individual part of your grade for {{page.num}}.   We will be looking to see that you (as an individual)
are assigned to **at least one issue** that is part of the MVP and that this issue 
is either in-progress or done by {{page.due |  date: "%a, %b %d at %l:%M%p"}}).

**Graded**: ({{page.num}}-I) (20 pts) towards the individual part of your grade for {{page.num}}.   You earn these points if/when you, by the due date of this assignment (i.e. {{page.due |  date: "%a, %b %d at %l:%M%p"}}):

* The issue/issues to which you are assigned have comments on them with a link to the branch or fork where you are working on the issue.
* There is evidence of some commit activity showing progress towards the goal
* There is a discussion in the comments on the issue indicating the progress you are making.  This may include questions, or some boxes on a check
   off list being checked, etc.

</div>


**Graded ({{page.num}}-T)**: (30 pts) towards the team part of your grade for {{page.num}}.  

As part of this grade, each team member 
should be assigned to  **at least one issue** that is part of the MVP and that this issue 
is either in-progress or done by {{page.due |  date: "%a, %b %d at %l:%M%p"}}).

For teams of 6, this part of your grade is 5 points per team member.  For teams of 6, it is 12 points per team member.  

These points are all or nothing; if you've made a reasonable attempt, even if you didn't earn 100% on the individual portion, 
your team will earn the points for your contribution towards the whole.  

The most important learning goal of the course is to learn to work as a team, supporting one another, and building the team's success.

</div>  


**Graded ({{page.num}}-T)**: (30 pts) towards the team part of your grade for {{page.num}}.  

This part of the team grade is for the mechanics of:
* naming a retro leader for the lab04 retro and putting a card in the TODO column with their name
* creating a MVP column on the Kanban board
* tagging issues with a Github custom issue tag MVP
* tagging user story cards with `(MVP)`
</div>  


<div class="grade" markdown="1">

**Graded**: (lab02-I) (20 pts) You earn these points if/when you, by the due date of this assignment (i.e. {{page.due |  date: "%a, %b %d at %l:%M%p"}}):

* The issue/issues to which you are assigned have comments on them with a link to the branch or fork where you are working on the issue.
* There is evidence of some commit activity showing progress towards the goal
* There is a discussion in the comments on the issue indicating the progress you are making.  This may include questions, or some boxes on a check
   off list being checked, etc.

</div>

