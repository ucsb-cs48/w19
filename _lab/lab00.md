---
layout: lab
num: lab00
ready: true
desc: "Getting Started"
assigned: 2019-01-10 16:00
due: 2019-01-18 17:00
signup_app: https://ucsb-cs-github-linker.herokuapp.com/
slack_url: https://ucsb-cs48-w19.slack.com
---


If you find typos or problems with the lab instructions, please report
them on Piazza

## Step 0: Find your assigned seat and locate your mentor

Seating charts are here:

| Row | 4pm | 5pm | 6pm |
|-----|-----|-----|-----|
|1|blue-spotify-queue	|buy-my-clothes|	park-finder|
|2|gold-scheduler	|countries-over-time	|stock-trading-6pm|
|3|gold-spotify-queue	|help-those-in-need|	ucsb-rooms|
|4|sleep-schedule|	ucsb-rideshare|	when-2-meet-6pm|
|5|stock-trading-4pm	| 5pm-when-2-meet	|  | 
{:.table .table-sm .table-striped .table-bordered}


## Step 1: Create a CoE account if you don't have one already

We encourage you to complete all programming assignments by logging in
to the machines in the Computer Science labs, or to connect
remotely. To do this you will need a **College of Engineering
account**. You can create an account online at
<https://accounts.engr.ucsb.edu/create>.

If you are enrolled in <i>any</i> CoE course this quarter (including CS48), you
should be able to create your account immediately.

If you are not able to do so, you will need to contact the ECI Help Desk at <a href="mailto:help@engineering.ucsb.edu">help@engineering.ucsb.edu</a>.

## Step 2: Get setup with github and add yourself to our organization

We will be using github.com in this course. We have created an
organization called {{site.github_org}} on github.com where you can
create repositories (repos) for your assignments in this course.

The advantage of creating private repos under this organization is
that the course staff (your instructors and TAs) will be able to see
your code and provide you with help, without you having to do anything
special.

To join this organization, you need to do three things.

1. If you don't already have a github.com account, create one on the
"free" plan. Visit [https://github.com/](https://github.com/)

2. If you don't already have your @umail.ucsb.edu email address
associated with your github.com account. go to "settings", add that
email, and confirm that email address.

3. Visit our Github Sign Up Tool at <{{page.signup_app}}>.   Navigate to <{{page.signup_app}}>.  Login with your github.com account. Click "Home", find this course ({{site.course}}, {{site.qtr}}), and click the "Join course button".   That will automatically send you an invitation to join the course organization on github.

4. There should be a link to the invitation for the GitHub organization for this course (<https://github.com/{{site.github_org}}>). Click on the invitation link and accept it. You can also go straight to <https://github.com/{{site.github_org}}> and see the invitation there (if you're logged in). Accept the invitation that appears in your browser (from step 3) or log into your account on [https://github.com/](https://github.com/) to accept the invitation.

## Step 3: Slack channel for your team

Find your mentor.  The team list is here, and it will tell you who your mentor is:

* [teams_page]({{ '/teams_page/' | relative_url }})

Then, ask them to add you to the Slack for the course which is:

* <{{page.slack_url}}>

There should be a channel there for your team.   Find that channel and join it.

## Step 4: Ask your mentor to create a repo for your team

First, your team must decide what language you want to use, so your mentor can choose the correct .gitignore. This choice isn't permanent. Once you've communicated your choice to your mentor, they should create a repo under the organization:

* <https://github.com/ucsb-cs48-w19/>

Settings for repo:
* Public or private (your team decides)
* `.gitignore` for whatever language your team decides
* By default, MIT License, unless your team chooses a different one
* The repo name should be the same as the slack channel name.  


Your mentor should then add one team member with admin permission, who will then add all the other team members with admin permission.



## Step 5: Each of you INDIVIDUALLY now makes either a fork or branch of the repo

The next step is done as an individual

You can either:

* Clone the repo and make a branch of the repo that matches your name, e.g.
   ```
   git clone repo-url-goes-here
   cd repo-name-goes-here
   git checkout -b yourname
   ```
OR

* Fork the repo to your own github id

## Step 6a: Inside your fork/branch of the repo, create a file called `team/your_first_name.md`

In your fork or branch, NOT on the master branch of the main repo, please do the following:

Make a directory called `team`. Inside this, create a markdown file named `your_first_name.md` containing a brief description of you and of your ideas for the project. 

* NOTE: Not literally `team/your-first-name.md`, but something like `team/chris.md` or `team/taylor.md`

Each team member should do this individually. Note that this will be publicly displayed on the course site.
   
## Step 6b: Do a pull request from your fork/branch that has your file called `team/your_first_name.md`.

Do a pull request from your fork or branch to the master branch of the repo.  Each team member should have done at least
one pull request from their github id.
   
## Step 7: Create your team/NORMS.md file

This is a list of ideal team behaviors, e.g. everyone arrives to meetings on time or everyone starts things tasks early. You should write this as a team.  Only one student needs to submit a pull request containing this file, however it is ok
if there are multiple pull requests for this file.   You should be careful, however to avoid merge conflicts!

The `team/NORMS.md` file should contain all of the team norms.  It is ok to "suggest" team norms in your individual team/first-name.md files, but the team, ultimately, should consolidate all of these into one `team/NORMS.md` file.

# GRADING

This is a group grade.  Everyone on the team gets the same grade.  HOWEVER, some components of the grade required individual action.   It it suggested that you work together as a team to help and encourage one other to get each part of this done. 

* (60 pts): 
   Points are awarded for each team member that has successfully created their `team/name.md` file, and has done a
   pull request, per the instructions above.   For each team member that does this, points are awarded:
   * For teams with six members, 10 points per team member 
   * For teams with five members, 12 points per team member 
   * For teams with four members, 15 points per team member 
* (30 pts): Completion of the `/team/norms.md` file.
* (10 pts): Ten points for the team when each member of the team has contributed an idea on the Slack channel



