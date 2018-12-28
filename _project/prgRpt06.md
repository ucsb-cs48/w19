---
layout: lab
num: prgRpt06
ready: false
desc: "TBD"
assigned: 2019-01-09 16:00
due: 2019-02-20 14:00
prgRptDue: 2019-02-20 21:00
presOrder: "start with 2nd to last, descending"
---

{{ page.due | date: "%a %-d %b" }}

{{ page.prgRptDue | date: "%I:%M%P" }} on {{ page.prgRptDue | date: "%a %-d %b" }}. 

# Progress Report 6

<h3>Oral report</h3>

Present some details of one of your (most interesting) interaction
diagrams. Interaction in this case means the way objects internal to your system interact
with one another (by sending messages in the form of function calls) to complete an
operation. It does NOT mean interaction between the system and an actor - that is the
subject of a use case diagram, and you already presented one of those in Progress Report 3.

It would be most entertaining, and probably most informative to
have one (or more) of your classmates help you present the interaction. Each speaker
would represent a different object, and the speakers would alternate their responses
as if they were executing the interaction, something like the following imaginary case:

<dt>You (representing a TargetButton)</dt>
<dd>I detect the user clicked me, so I call the respondToClick method of all
objects in my list of ClickListeners, and pass them each a reference to myself.</dd>
<dt>Helper1 (representing a ButtonMonitor)</dt>
<dd>My respondToClick method is called by a TargetButton, so I tell the Game package
about it by passing a code that identifies the target to the TargetRecorder's
recordTarget method.</dd>
<dt>Helper2 (representing a TargetRecorder)</dt>
<dd>My recordTarget method is passed a target code, so I update the score for the target
by calling the GameData's updateScore method.</dd>
<dt>... and so on until the interaction is complete (hopefully a bit longer and more
interesting than this one).</dt>
</dl>

It is okay if you just want to present it alone too, but please don't skip this step.

Be sure to leave time for telling us your general progress, to-do items and problems as well.

# Written report

Please do not include the interaction diagram in your written report. We can
see that and much more in your Draft Project document.
Just tell us your progress, to-do items, and problems as usual.</p>

