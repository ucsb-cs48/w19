---
title: Draft Project
layout: default
---

# Draft Project Instructions

<p>The object of this assignment is to complete at least one full development iteration,
including a working software system and associated analysis and design documentation.</p>

<a name="analysis"><h3>Domain Analysis</h3></a>
<p>Perform a domain analysis for the current development iteration, and
   prepare the following artifacts:</p>
    <ol type=a>
    <li><em>Begin</em> a <u>static class diagram</u> - similar to this
        <a href="domainmodel.png">Figure 12.9</a> from the Larman text.
        Include <em>domain</em> classes only at this stage.
        Use proper UML notation. Class attributes should be included now, but
        attribute types are optional. You will complete this diagram during the design phase.</li>
    <!--
    <li><u>System sequence diagrams</u> - like this <a href="ssdannotated.png">Figure 9.1</a>
        from Larman (but omit the annotations).
        A separate diagram should be prepared for each use case in this development cycle.
        It is up to you whether you want to include use case text with the diagram like this
        <a href="ssdwithuctext.png">Figure 9.5</a> example from the Larman text.</li>
    -->
    </ol></li>

<a name="design"><h3>System Design</h3></a>
<p>Design a system to satisfy the current iteration requirements, and
    prepare/improve the following design artifacts:</p>
    <ol type=a>
	    <li>Identify two design patterns that work for your project design/implementation and describe how you have implemented them in your project.  Give a link to the github commit(s) that provide the implementation and tests.</li>
    <li>Expanded and upgraded <u>static class diagram(s)</u> - with design features as appropriate.
        First be sure to allocate your classes to meaningful sub-systems (a.k.a. <em>packages</em>).
        <ul type="circle">
        <li>Add operations, showing parameters and types, and return types if not void.</li>
        <li>Show attribute types (e.g., <tt>score : double</tt>) now too.</li>
        <li>Remember to add any new classes introduced during system design.</li>
        <li>Exclude
        details of packages not to be created this quarter by your group - use the UML notation for
        a package to show each such item as a single box in your diagrams. For example, if you use any wxWidgets components, then just show a package named wxWidgets in your diagram.
        </ul></li>
   <li>At least 10 new use cases or user stories, with acceptance tests.  2 of them should be the ones used for your Interaction Diagrams (described below) and all should fit within your system design.</li>
    <li>At least two <u>interaction diagrams</u>. See several example diagrams and explanations
        about interaction diagram notation in Larman's <a href="InteractionLarman.pdf">Chapter 15</a>.
        <ul type="circle">
        <li>Ideally you would create one interaction diagram for each system event. For this
        assignment we want you to choose at least two <em>interesting</em> events - i.e., ones that
        involve multiple steps and objects.</li>
        <li>If a diagram cannot fit neatly on a page, consider splitting it into two diagrams.</li>
        </ul></li>
    <li>One or more <u>state diagram(s)</u> like this <a href="statediagram.png">Figure 29.3</a>
        from the Larman text.
        Focus on <em>external system events</em> in the context of use cases.</li>
    </ol>

<a name="implement"><h3>Implementation, Testing and User Instructions</h3></a>
<ol type="a">
<li>Implement the system for the current development iteration - 
    i.e., write the necessary source code, and get the system working
    well enough to demonstrate <em>all</em> of its current functionality.
    <ul type="circle">
    <li>Each C++ class (except nested ones) must be defined in a separate .h file,
        and implemented in a separate .cpp file, unless the class is so simple
        that all functions are defined inline.</li>
    <li>All .h files must include proper comments for every non-private
        member. Describe parameters and return values, pre- and post-conditions
        and any exceptions thrown by member functions.</li>
    <li>If you are using a different OOP language than C++, then
        follow that language's conventions, but still keep separate classes in separate files.</li>
    </ul></li>
<li>Fully test the system. Do both unit and integration testing, and test
    overall functionality. (Note - any "test drivers" and "stubs" used
    for unit testing must <em>not</em> be included with the system that you turn in.)
<li>Prepare a file called <code>README.txt</code> as follows.
   <ul type=circle>
   <li>List <em>precise</em> instructions to build and execute your system. Be sure
       to tell us about necessary libraries, and about any operating system or other
       restrictions.</li>
   <li>Include any necessary details about where to store data files too.</li>
   <li>Also include any other special information we need to know in order to test
       your system properly (a list of known bugs, for example).</li>
   <li>Finally include brief guidance about how to use the system (e.g., how
       to play the game).</li>
   </ul></li>
</ol>

<h3>Deliverables</h3>
<a name="files"><h4>System</h4></a>
<p>The system includes source code, data, and the read-me file.</p>
<p>All of this must be in your github repo.  Specify the link and branch name (if not master) and source root directory in the document you turn into the TAs. The source root directory/folder must include the following:</p>
    <ol type="a">
    <li><u>Source code</u> in github repo
	    <!--files must be stored separately under a directory named "<tt>src</tt>"--> 
	in subdirectories that correspond to your system's packages.  We must be able to 
	build the project using a makefile or script.  Include the steps (AND TEST THEM ON A CLEAN CLONE TO MAKE SURE THEY WORK) in the README.md.
	<!--Please</em> just turn in <code>.h</code>,
        <code>.cpp</code>, <code>.java</code> and other source files, and <em>not IDE- or
	svn-generated</em> or object files or temporary executables or any other unnecessary files.-->
   </li> <li>All necessary <u>data files</u> must be turned in too -
        any data, graphics, sound, or other files (like libraries) necessary to compile
        and/or execute the system.</li>
    <li>Include <u>README.md</u> in the root of this file structure. This file must include the exact steps (cut/past-able) to build and run your project.</li>
    </ol>
<h4>Documentation</h4>
<p>Text must be typewritten. Hand-drawn diagrams are okay, but we suggest you learn and use a
   UML drawing tool instead. Assemble artifacts into a single PDF document in the following order - 
</p>
   <ol type=a>
   <li>Cover page with group ID, project title, and project team (member names).</li>
   <li>Analysis and design artifacts in this order: 
       static class diagram, interaction diagrams, state diagram(s), 
       and design patterns (as described above).</li>
   <li>Evolved Requirements Analysis document -- with the following extensions:
	<ul><li>Expanded glossary (begun in the Requirements Analysis) - be sure to add names and descriptions of all classes, class attributes, associations, system events/operations, packages, methods, and any other important terms. Also remember to revise or delete any existing faulty glossary entries if necessary.</li>
   <li>10 new use cases or user stories, with acceptance tests.  2 of them should be the ones used for your Interaction Diagrams (described above) and all should fit within your system design.</li>
   </ol>
<h3>Due Friday, Due Friday, Feb 23 before 5:00 pm</h3>
<p>Turn in the PDF via Piazza as described in an earlier Piazza post.</p>

