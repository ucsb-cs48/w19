---
layout: default
title: rules
ready: true
desc: "Project Rules"

---

# Group formation

This quarter the instructional staff will assist and partly direct the formation of groups.

We will try to minimize the number of groups, subject to the restriction that no group may
have more than 6 nor fewer than 4 members.

Attendance is always important, but it is mandatory during the first week of lectures and
at your first discussion section.  Otherwise, you cannot be assigned to a group, and will
need to drop the course and take it next time it is offered.

All remaining rules apply after the groups are formed.

# Type of project to choose

CS 48 is mostly about analyzing problems and designing systems. It is not primarily
about programming, at least not programming at the method or even class level.
Therefore, what we are looking for in projects are problem domains that
are "interesting" - i.e., have


* around two dozen key concepts, and
* interesting relationships between these concepts.

Suppose you have a choice between two projects, A and B:

<blockquote>
<table border="1" cellpadding=5>
  <tr>
    <th bgcolor="lightgreen">Project A - GOOD Choice
    <th bgcolor="#ff8070">Project B - POOR Choice
  <tr>
    <td bgcolor="lightgreen">Has many concepts with complex relationships between them,
        but each resulting class is simple to implement.
    <td bgcolor="#ff8070">Has fewer concepts, and classes are difficult to implement
        due to tricky algorithms and/or fancy graphics.
</table>
</blockquote>

For CS 48, project A
is a <em>much</em> better choice. A key goal is for you to learn how to analyze
and design, and thus a major portion of your work on the project should
be in that area.

# Good news: you may choose *almost* any type of project you want

Almost, subject to some limitations:


* You must create something that someone will actually use.
   * If it's a game, it should be a game people will actually play, and enjoy playing
   * If it's a tool, it should be a tool people will actually use.

As an example of something that you could build, but that would NOT be acceptable: supposed you built a better interface for a ride sharing service such as Lyft or Uber.   That's clearly useful to someone.  But no-one is actually going to use it, unless you have a bunch of willing drivers ready to start driving people around.

Another example: an airline reservations systems.  Unless you own planes, and have airport slots, and cleararance from the FAA, etc, you aren't going to be able to actually have anyone try out your system for *real*.

So concentrate on something that people can actually use.

# Programming language and other source code requirements

In order to 

As CMPSC 32 is a pre-requisite for this course, every enrolled student is assumed to possess
sufficient C++ programming knowlege to be an effective team member if the project is mostly written
in that language.

CMPSC 56 is another required course for CS majors, many students have
or are gaining experience with the Java programming language and
related libraries.   If all of your team members are comfortable with Java, that's an acceptable choice.


Therefore, heed
the following language requirement.</p>
<blockquote>
<table border="1" cellpadding=5 bgcolor="lightyellow">
   <tr><td><strong>Programming language requirement</strong><br>
      The bulk of your project must be implemented in C++ (2011 standard) or Java
      (SE 1.8). Another object-oriented language may only be used with explicit permission.
      Small, auxiliary parts may be composed in Javascript, Python or another
      scripting language if your TA approves it.
   </td></tr>
</table>
</blockquote>
<p>Additionally:</p>
<ul>
<li>Each non-nested class (and interface) must be in a file by itself. Except for very simple C++
    classes or template classes, you should have separate files for the declarations (.h)
    and definitions (.cpp). Every Java class must be in its own file.</li>
<li>Every public class, method/function or enum must be properly commented (in the .h files if C++,
    or properly formatted Javadoc comments if Java).</li>
<li>The bulk of your code must be <em>original</em> - written by your group <em>this quarter</em>.
    Of course, your source may use any parts of the standard libraries, but please obtain
    permission from your TA to use any non-standard libraries.<br>
    <strong>Note:</strong> your system design must be original too, or it must be properly
    credited. See the special note about plagiarism below.
</ul>


# About technical expertise

The instructor and TAs will <em>not</em> assume responsibility for teaching you how to accomplish every
possible programming task you need to learn - whether or not we are familiar with these tasks
ourselves. A large part of a developer's job is to learn how to do things they have not been
trained to do. You must research any techniques that are novel to you: find examples in books
or by searching the Internet.



# Grading guidelines

The project counts 75 percent of each student's course grade, broken down as follows:


* 50 percent is on the basis of the group grade, awarded equally to all members of a given group
   that remain in good standing in the group.
* 25 percent more is available as a "Teamwork Credit" - to be awarded based on the
    recommendations of other members in each student's group.</li>
</ul>
   <blockquote>
   <table border="1" cellpadding=5 bgcolor="lightyellow">
   <tr><td><strong>About individual accountability</strong><br>
      Near the end of the quarter, every student will be given an opportunity to submit a specific
      recommendation to reduce the Teamwork Credit of another member in their group.
      If a student submits no such recommendation, it means that student effectively
      recommends the full 25 percent be awarded to each other group member.
   </td></tr>
   </table>
   </blockquote>
<p>

## The Group grade, and "good standing"

The group grade is the accumulation of the following components:

* Progress reports (weekly, with both written and oral components)
* Story Mapping and Sprint Planning
* Code Reviews
* System Demonstrations

All project team members in good standing will receive the same grade
for this portion of the project.   To remain in good standing, you should have
* an acceptable level of attendance/participation in standup meetings
* an acceptable level of attendance/participation in group discussions
* an acceptable level of contribution to the teams progess.

# Good Standing on your Team

The initial determination as to what an acceptable level of participation is will
be defined by consensus of each group during the "team norming" activity
at the start of the quarter.

For example, a team might define "acceptable attendance/participation at standups meetings" with some combination of norms like the following:
* A team member should not normally miss a standup 
* The team may occasionally excuse a member from standup attendance by unanimous consensus when there is a legitimate reason to miss it.
* If it is necessarily to miss a standup, the team member should communicate with the team as soon as possible; in advance if possible, or as soon as possible afterwards when not.
* A team member that misses more than k consecutive standups is not in good standing.
* A team member that misses more than n during a quarter is not in good standing.

Course staff will take attendance at standups, but it is up to teams themselves to hold each other accountable to their team norms.  If a team member is not in good standing, or is in danger of not being in good standing, it is the responsibility of the team to reach out to course staff---mentors, TAs, and instructors---early, and often---for help in resolving the situation.  You can't just "vote someone off the island" on the last day of the course.  You have a responsibility to make every effort to resolve the situation early, and successfully, to document your efforts to do so, and to involve staff in those efforts as early as possible.

Ultimately, the decision about whether a team member is in good standing lies with the instructor.  However, the instructor will use the norms, and communication processes established by the team, as well as its own documented efforts to resolve the matter, in making a final determination.

# A special note about plagiarism:

All work that you submit must be entirely your own,
or its origin must be properly credited. In other words, it is okay to borrow an
idea from somewhere, but only if you tell us so. (Of course, if you borrow
a substantial part of your design, your grade may be affected.)

Plagiarism is a very serious offense, and we are obligated to spend some
effort trying to find it. If we detect it, the offending group's grade will be
reduced by at least 40 percent even for minor infractions. For anything
other than a minor infraction, the grade will be zero, and the students' behavior
will be reported to the appropriate university authorities. According to university
guidelines, "any act of academic dishonesty ... is unacceptable and will
be met with disciplinary action".



Credits:
* Updated December 27, 2018, P. Conrad.
* Based on previous CS48 course material provided by C. Michael Costanzo and Chandra Krinz.

