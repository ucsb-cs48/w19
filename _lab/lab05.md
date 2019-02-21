---
layout: lab
num: lab05
ready: true
desc: "Deliver MVP"
assigned: 2019-01-31 16:00
due: 2019-02-14 19:00
github_org: "ucsb-cs48-w19"
---

<div style="display:none">
https://ucsb-cs48.github.io/w19/lab/lab05/
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



#  The most helpful attitude and approach for reviewers: friendly helpfulness, not "gotcha"

First, it is important to have the right approach.  You are engaging in this review to *help the other team improve their code*.  This is not an opportunity for showing off or playing "gotcha".  

On the other hand, don't hold back on sharing what you find.  The grade for this review is not based on how well team B's product performs.  It is based on how much team A is helpful to team B.     

Everything you find that can be perceived as a weakness in team B's product is something that you can help them uncover early, so that they can address it while they still have time, long before the end of the quarter.

Don't mock or criticize---be helpful and constructive.   If you have knowledge of a practice or technique that can help another team, make a note of that, and come back and share it later (e.g. on the slack).

# The most helpful attitude for reviewees: gratitude, not defensiveness.

For reviewees, it can be really tough to be out front represnting your team as another team's representative goes through your product inside and out.  THere is a natural human tendency to become defensive.

It may be helpful to resisit this urge.

## What if we disagree with the reviewer's assesssment?

That's ok.  It's ok to just nod and let it go.

* You do NOT necessarily act on every piece of information or suggestion you receive from the reviewers.  
* Your team may not agree with all of it.  
* Your team has every right to decide, if they judge the advice or suggestions to be incorrect or unwise, to let them go.  It isn't necessary to argue back with the reviewer. 

All I'm asking of you is to listen and consider it carefully, and discuss it as a team.  You might decide to discuss it later after the review is over, on the Slack channel.  With a bit of distance in space and time, you may find parts of it you agree with, or really good reasons to go in a different direction from what was suggested.

# Instructors for Reviewers

As the reviewer, you are from team A, and reviewing the work of team B.

Present, there should be:
* You, lead reviewer from team A
* Someone from team A to take notes on the Slack
* Lead reviewee from team B
* Someone from team B to take notes on the Slack
* The mentor for team B.

1.  Start by making sure that you and your helper from team A are added to the slack for team B.


2.  On the slack, make a note of everyone present at the review from both teams.  Any members of team B that are missing, hopefully are missing becuse they are engaged in the reciprocal review of A's product.)
    
2.  Then, start by sitting at the lead reviewee from team B's computer, where lead reviewee from team B has the product up and running.

3.  Ask the lead reviewee to walk you through the features of the product, as YOU, leader reviewer from team A, control the mouse and keyboard.    You, the lead reviewer should be going through the features of the product, led by an explanation of the reviewee from team B.  

    As you notice things you like, and things that could be improved, say them out loud.  Both the person from team A and the person from team B should be noting these things on the Slack.    The person from Team A should simply make notes about your observations.  The person from team B may go a step further, and note what the team might do in response (e.g. add issues, add user stories, add bug fixes, etc.)
    
4.  When you have gone through the product demo, now go to your OWN computer.   Pull up the Kanban board.

    Go through all of the user stories and issues that you see that are marked as part of MVP in in-progress or done. 
    
    Comment on whatever you see that either in-line with what you experienced in the demo, out out of alignment, in your view as a potential user of the product.  Again, the notetakers should make notes as they did in earlier steps.
    
5.  Now, pull up the README.md for the project in the repo.

    Go through it and make sure it doesn't have any "TODO" items in it.  If it does, comment on those, and note that they should perhaps be addressed.  
    
    Finally, on your OWN computer, try to clone the repo, and follow the steps needed to get the application up and running.
    
    You should NOT need any credentials from the original team---if there is a database setup needed, you should BE ABLE TO DO THAT DATABASE SET UP YOURSELF by following the instructions in the README.md.  If that is not possible, then note this as one of the observations.    At any point that you are stuck and cannot continue, as a last resort, the reviewee can jump in and help, by guiding you through the process, but NOT by providing you database credentials or API credentials--only by walking you through the process of setting up your own.
    
6.  [OPTIONAL IF TIME] If you are successful in setting up the project, and you get this far: start looking through the code for places you can make suggestions for improvement, or offer words of praise.  Most reviewers won't get this far.    
    
7.  Closing the review: to close the review, try to offer a sandwich of praise and helpfulness:
   * One thing you really liked about the project (inside or outside)
   * The most impactful opportunity for improvement
   * One more thing you thought was good
   
There will be additional instructions over the next few days for consolidating this review into a summary, but for tonight this is enough.    

# Instructors for Revieweees

Read through the instructions to reviewers, since most of what you need to know is already there.

Your main job is to be at the service of the reviewer.   

# Other members of the team

For those that are not the lead reviewer or reviewee:

* At least one  member of the team should be with the ambassador of your team to the other team being reviewed as a note taker
* At least one other member of your team should be taking notes during the review of your team's product

The other 1 or 2 members should stay with the team being reviewed, and as notes are taken in the slack, start setting up user stories and/or issues to follow up on the items suggested, or if needed, do emergency bug fixes/edits to code or documentation to address problems found during the review.

# FOLLOW UP instructions for Reviewers

1. Please create a private github repo under the course organization {{site.org}} that follows the following naming convention, with the team name of the team that you reviwed (not your own team).   Create it with a README.md only

   | 4pm-spotify_REVIEWS          | 5pm-buy-my-clothes_REVIEWS	      | 6pm-park-finder_REVIEWS  
   | 4pm-gold-scheduler_REVIEWS   | 5pm-findtheroommate_REVIEWS	      | 6pm-stock-trading_REVIEWS
   | 4pm-turkey-trot_REVIEWS      | 5pm-Help-Those-In-Need_REVIEWS       | 6pm-ucsb-rooms_REVIEWS   
   | 4pm-sleep-scheduler_REVIEWS  | 5pm-ucsb-rideshare_REVIEWS	      | 6pm-when2meet_REVIEWS    
   | 4pm-stock-trading_REVIEWS    | 5pm-pet-life_REVIEWS                 |

   (You may add a .gitignore if it makes things more convenient, but its optional)

2. In that repo, add a file called <tt>{{page.num}}_reviewer.md</tt>. In this file, write a summary of your findings
   during the review.

   Include sections for each of the following:

   1.  Everyone that was present for the review from each of the two teams, and the roles they were in.
   2.  A summary of the features of the product as you understood them, and what you liked or thought could be
       improved about each
   3.  A summary of what you found on the Kanban board in terms of whether the user stories and issues were, or
       were not in alignment with the features of the product.
   4.  A summary of whether the README.md was in good shape according to the criteria outlined in
       the lecture on good README.md practices, and whether you were able to follow the instructions there
       to actually set up the product to compile and run on your own computer.
   5.  Your final closing thoughts: something you liked, the most impactful opportunity for improvement,
       and one more thing you thought was good.


