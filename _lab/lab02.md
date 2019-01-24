---
layout: lab
num: lab02
ready: false
desc: "First Project Increment"
assigned: 2019-01-24 16:00
due: 2018-01-31 19:00
github_org: "ucsb-cs48-w19"
---


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

# Checking over your deliverables for [lab01]({{'/lab/lab01/' | relative_url }}) 

The following deliverables are due for [lab01]({{'/lab/lab01/' | relative_url }}) .   Check over them and make sure these are complete.

Also look at the green "Graded" boxes in the instructions for [lab01]({{'/lab/lab01/' | relative_url }}) 

* There should be a Kanban board (a Github Project associated with your repo) for your team
   (Check that the 
* That Kanban board should have a complete set of user stories on it, that, when complete, results in a minium viable product for
   your app; one that clearly delivers value to the user.  
* There should be a complete set of issues for each of those user stories; a set of issue that are specific TODO's that a individual, pair, or 
   sub-group of your project team can pick up and start coding from.  Each of those issues should have a clear set of criteria for
   what it means to be "done" with that issue.
* In addition, there should be set of issues for creating "Hello World" apps;  There should be one per each team member or pair of team
   members, and each team member or pair should be *assigned* to that issue on the Kanban board.


# Deliverables for lab02

By the due date of this assignment (i.e. {{ page.due }} ), you should have completed your first project increment.   

That increment includes all of the following:
* Each team member has participated either as a solo programmer, or as part of a pair, in producing a "Hello World" type app for the
   framework you are using for your project.   You will get two grades for this: one as part of your team grade, and another as
   an individual grade, as explained below.
   
<div class="grade" markdown="1">

**Graded (lab02-I) **: (lab02-I) is your individual grade for lab02.  Your mentor will do a code review against a rubric of items including all of the instructions in this lab, as well as conventional notions of good coding practice that you should have learned in CS16/24/32.   Your TA or instructor will then do an independent assessment, informed by the mentors code review, and assign a grade. If you are unsure about your code follows good practice, you are encouraged to complete it early and meet with your mentor, your TA, or another mentor/TA during [open lab hours]({{ '/info/open_lab_hours/' | relative_url }}) to go over it in advance.
The components of this grade are listed below.

**Graded (lab02-T)**: (30 pts) (lab02-T) is your Team grade for lab02.  As part of this grade, each teem member should have contributed to a hello world assignment as an individual or as part of a pair by the due date/time of this lab, i.e.  ({{page.due |  date: "%a, %b %d at %l:%M%p"}})

For teams of 6, this part of your grade is 5 points per team member.  For teams of 5, it is 6 points per team member.  Those 5/6 points are all or nothing; if you've made a reasonable attempt, even if you didn't earn 100% on lab02, your team will earn 5 or 6 points for your contribution towards the whole.

This component of your team grade is designed to encourage each team member to reach out to all the other members of the team, and be aware of the progress they are making towards the goal of having every team member complete a hello world assignment as an individual or as part of a pair.   The most important learning goal of the course is to learn to work as a team, supporting one another.

</div>  
   
# What *each* "Hello World" branch/pull-request must contain for full credit.
   
* Each individual or pair should have built a hello world app suitable for your framework.
* You should have instructions in your read me on what software must be installed in order to deploy your app. 
   A TA, Mentor, or another class member should be able to follow these instructions and successfully deploy your app.
* The app does not have to have any particular functionality other than what is normal for the framework.  It should display
   either the text "Hello, World", or something similar such as "Welcome to the foobar app" (where "foobar" is the name of your
   team's app.)
* By functionality normal to the framework, I mean for example:
   * If it a "game", there should be a "start game" button, and then after a moment, it displays "game over" with a "play again" button.
   * If it is a mobile app, it should have the most basic UI feature that are expected for the app to be "well-behaved" on the iOS or Android platform.  
   * If it is a webapp, it should be formatted as an HTML page, not just a plain text page with the words "Hello World". (Full navigation can come later, though it's nice if you can include it at this stage.)
* In no case should there be a "crash" if/when users interact with the app in a reasonable fashion.  

# Hello World app in a branch, and a pull request is performed

<div class="grade" markdown="1">

**Graded**: (lab02-I) (25 pts) You earn these points if/when you:
* Have a branch and a pull request for your hello world app (the one that you did as an individual or as part of a pair)

</div>

# Hello World app Deployed or Demoed

As explained below, each 

<div class="grade" markdown="1">

**Graded**: (lab02-I) (25 pts) You earn these points if/when by the due date for this lab,  (i.e. {{page.due |  date: "%a, %b %d at %l:%M%p"}}) you have, as explained below, either:

* deployed your app live on the public web (if it is a webapp) through Heroku, or another provider, or
* demoed your app to your mentor during open lab hours, or another mentor if that doesn't work for your schedule.

</div>

## *Each* webapp "Hello, World" branch/pull-request should be deployed

If your app is being deployed as a webapp: you should have have DEPLOYED it so that it runs on a service such as Heroku, 
Google App Engine, Amazon Web Services, etc. at a stable URL.    The easist platform on which to do this
for Java Spring Boot, and Python Flask is Heroku.   If you don't know how, ask on the slack channel (well in advance, not at the last minute), 
and mentors and other students can point you to the resources to get started with this.

Put the URL of your running app in the README in your branch.

## *Each* non-webapp "Hello, World" branch/pull-request should be demoed

If you are NOT doing a webapp, you must set up a time with your mentor, or your TA, to demo your app to them.  You are strongly encouraged to do 
this BEFORE the lab next Thursday.   The mentors and TAs hold 
[open lab hours]({{'/info/open_lab_hours/' | relative_url }}) during which you can schedule this demo.    The last opportunity to do this demo
is during lab on the due date for this assignment, but it may not be possible to fit all of those in, and in that case, regrettably, you may lose the opportunity to do so (and earn the points.)  Please coordinate with your team to
get as many of these demos done *before* lab on the due date of this assignment.

If working in a pair, *each* member of the pair should demo the app, to show that they understand how to run it.

NOTE: If you cannot schedule with your own mentor, you may coordinate on slack between your mentor and another mentor/TA holding open lab hours that better fit your schedule.  Please use the slack to coordinate this.  
