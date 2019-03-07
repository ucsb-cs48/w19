---
layout: lab
num: lab06
ready: true
desc: "Mentor review of MVP +1 week"
assigned: 2019-02-07 16:00
due: 2019-02-21 19:00
github_org: "ucsb-cs48-w19"
---

<div style="display:none">
https://ucsb-cs48.github.io/w19/lab/lab06/
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



# What you will do today

1.  (10 minutes) Hold a standup meeting.   Your mentor should observe.
2.  (10 minutes) Decide on a time/place/leader for two out-of-class meetings for your team that should take place
    before your next week's scheduled lab:
    
    * your next retro (45 minutes)
    * your next sprint planning meeting (at least 45 minutes).

    Note that these should be at a time/place that your mentor can attend.

    Record the time/place(s) on cards in the TO-DO column on your Kanban board.
    

3.  (10 minutes) On the slack channel, remind yourselves who took on these four roles, and record
    it on the channel:

    * First presentation 
    * First Retro Leader (lab04)
    * Reviewer (lab05)          
    * Reviewee (lab05)          

    Then, discuss the list of roles below and assign one team member to each of the roles.

    There are more than six total roles now (four old ones and seven new ones), so some people will have
    to be assigned to more than one role.    That's fine, but follow these rules:

    * The product owner and the scrum master *may not* be the same person, and
    * The retro leaders for each of the three retros in the quarter should be different people.
    * No one should take on three roles unless/until each team member has already taken on two.

    If you have a situation where it is impossible to satisfy all of these rules, check with your mentor;
    they are permitted to authorize exceptions where there is a legitimate need to do so.

    Also, on the slack channel, who ever is chosen below as the "Documentation Coordinator"
    will be responsible for copying these roles from the slack into a file in the team's repo
    (see instructions below in the "After Lab" section of these lab instructions.) 

    **Roles to assign**

    * **Retro leader (lab06).** Leads a mid-quarter retro later this week 
    * **Product Owner**.  Together with Scrum Master, leads the Sprint Planning meeting later this week.
      Responsible for making sure that the team comes up with a set of **user stories**
      for the "final" product that your team will deliver, and marking those stories with a label "final" (just
      like the label `MVP` that you used previously.  
    * **Scrum Master**.   Together with Product Owner, leads the sprint planing meeting later this week.
      Responsible for making sure that the team comes up with a set of **issues**
      for the "final" product that your team will deliver, each tied to one of the user stories.
      and marking those stories with a label "final" (just like the label `MVP` that you used previously.
      Also responsible for holding the team accountable for keeping the issues moving through the Kanban board.
    * **Testing/QA Coordinator**. They will be responsible for establishing at least one unit test and at least one
      functional test for your project, and having these running on Travis-CI by next Thursday's lab.
      Ultimately, responsible for making sure that user stories and issues have acceptance criteria, and that
      these are met before pull requests are accepted into master. 
    * **UX Coordinator**.  Responsible for the look and feel of the product, and the way that the user interacts with the
      product.   By next week, will have a set of recommendations for the final UI/UX of the product in support
      of the user stories that emerge from the Sprint Plannig Meeting
    * **Documentation Coordinator **  This person is responsible for the project documentation, chiefly the README.md file.
      By next week (lab07), they should have given it a thorough update, and will be responsible for updating it
      throughout the rest of the quarter.
    * **Final presentation leader (week 9/10).**  This person will give the final class presentation during week 9/10.
    * **Retro leader (lab09).**  This person will lead a retro during week 9.   

4. (20 minutes) Your mentor will now do a review of your product similar to the one that you did last week during
    lab05, but in an accelerated fashion, looking only at the product from a user standpoint, the README.md,
    and the code.

    * Your same "reviewee" from last week should set up the application for the mentor to run themselves.
    * ALL other team members should listen and take
      notes on the slack, with particular emphasis on their respective new roles
      (product owner, scrum master, etc.)

    Mentors, you have discretion to use the 20 minutes as you see fit, focusing on any/all of these.
    * The product from a user standpoint
    * Whether the README.md has clear instructions to configure and run the product from its source codeN
    * The quality of the code itself


# After lab

## ALL STUDENTS

* attend and participate in your retro
* fill out the retro survey (see the #retro channel on the slack for the link)
* fill out the teamwork survey (see the #retro channel on the slack for the link)

## Retro Leader Followup

Before the retro:
* Send Reminders to the team about the retro time/place, 1 day in advance, and earlier on the day of the retro
* Bring supplies to the retro if needed (sticky notes, markers, etc.)
* Choose a retro format/template (see: <https://ucsb-cs48.github.io/topics/retros/> )
* Remind yourself about retro best practices:
   * Facilitate, don't participate
   * Help bring out everyone's point of view
   * Review the last experiment, come up with a new one

During the retro
* Revisit the last experiment (see your team's RETRO repo)
* Gather insights, and choose a new experiment

After the retro
* Post about the experiment on the slack
* Record the experiment in the RETRO repo (same instructions as for the previous retro)
* Remind team to fill out retro survey (the instructor posted the link in the Slack "retros" channel)
* PLUS all team members should fill out the teamwork survey #1

## Product Owner / Scrum Master Followup

The two of you are collectively responsible for facilitating the Sprint Planning meeting.

* The Product Owner is the voice of the customer
* The Scrum Master is the voice of the development team

Before the sprint planning meeting:
* Send Reminders to the team about the sprint planning meeting time/place, 1 day in advance, and earlier on the day of the sprint planning meeting
* Meet as a pair, if possible, and generate some user stories and issues

During the sprint planning meeting
* Review all stories/issues with the team
* As a team, revisit which are going to "make the cut" with the `final` label (i.e. will be in the final product)
* Generate accpetance criteria
* Make sure each team member is assigned to an issue in the in-progress column


After the sprint planning meeting
* Scrum master monitors of the flow of issues through the columns
* Product owner works with testing coordinator on which issue are being completed, with the pull request accepted into master



## Documentation Coordinator Followup

Record the team's decisions about roles in your team's project repo, under a directory called `/team/`
in a file called `/team/ROLES.md`.  

In this case, you may commit this file directly to the master branch without
doing a pull request.

You may use this Markdown template for the contents of `/teams/ROLES.md` to produce a nicely formatted table:

```
| Role                             |   Name              |
|----------------------------------|---------------------|   
| First presentation               |                     |
| First Retro Leader (lab04)       |                     |
| Reviewer (lab05)                 |                     |
| Reviewee (lab05)                 |                     |
| Mid-Course Retro Leader (lab06)  |                     |
| Testing Coordinator (lab06)      |                     |
| Product Owner (lab06)            |                     |
| Scrum Master (lab06)             |                     |
| UX Coordinator (lab06)           |                     |
| Documentation Coordinator (lab06)|                     |
| Final presentation (week 9/10)   |                     |
| Retro Leader (lab09)             |                     |
```

# Reviewer from lab05

See instructions at the end of lab05.   

# Reviewee from lab05

See instructions at the end of lab05.   

# Testing Coordinator

Review this article on Acceptance Criteria: <https://ucsb-cs48.github.io/topics/testing_acceptance/> which includes
the template used in the guest lecture by [Jason, Amir and Heidi from Procore](https://ucsb-cs48.github.io/w19/lectures/lect11/).

Then go through all of your issues for the `final` sprint, and add acceptance criteria.

Then, determine how to:
* Create unit tests within the technology stack you are using (e.g. `unittest` or `pytest` for Python, `mocha` for node, etc.)
* Set up Continuous Integration using Travis-CI

Then:
* Set up at least one unit test by next Thursday night in a branch, and then do a pull request to put that test in your master branch 
* Set up Travis-Ci for the master branch of your repo
* Add a Travis-Ci badge in the README.md of your repo, at the very top.


## Other team members

After lab tasks for the following team members are coming soon.  For now, work on issues for your team!

* UX coordinator
* Final presentation


<div class="grade" markdown="1">

**Graded**: 

* ({{page.num}}) (20 pts) Markdown template with list of roles is posted in `/team/ROLES.md` in Master branch of repo.
* ({{page.num}}) (20 pts) Unit and/or integration tests are present on the master branch of the repo
* ({{page.num}}) (20 pts) A Sprint Planning meeting took place
* ({{page.num}}) (20 pts) A Retro was held, and there is a record of that retro in the teams `_RETRO` repo, with a discussion of the last sprint's experiment, and the current sprint's experiment.
* ({{page.num}}) (20 pts) Team has filled out the second retro follow up survey.
</div>
