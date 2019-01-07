---
layout: lab
num: lab00
ready: false
desc: "Getting Started"
assigned: 2019-01-10 16:00
due: 2019-01-10 18:50
signup_app: https://ucsb-cs-github-linker.herokuapp.com/
---

STILL A WORK IN PROGRESS--DO NOT START THIS LAB YET.

WE MIGHT CHANGE IT COMPLETELY BEFORE FRIDAY.

If you find typos or problems with the lab instructions, please report
them on Piazza

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

## Step 3: Get setup with gradescope

We will use gradescope to grade all your homeworks, exams and a limited number of programming assignments. I have manually added everyone (using your @umail.ucsb.edu accounts) currently enrolled in the course to the Gradescope system.   N

**IMPORTANT:** Note that even though the university has switched to `@ucsb.edu` addresses, the GOLD and EGrades systems **still use `@umail.ucsb.edu` addresses**.  For this reason, in order to ensure that your work is credited to you, please continue to use your `@umail.ucsb.edu` address (which goes to the same Gmail based inbox) for registering for websites related to the course such as Gradescope, Piazza, etc.

You should have received an email notification with instructions about logging into gradescope. Once you follow the instructions to set your password, you should have access to our course on Gradescope. You should see {{site.course}} in your {{site.qtr}} courses.

The lab assignment {{page.num}} should appear in your Gradescope dashboard in {{site.course}}. You will need to submit your code for {{page.num}} using this page.

## Step 4: Set up your github.ucsb.edu account.
    
Visit <https://github.ucsb.edu> and login with your CSIL account, to establish your github.ucsb.edu account.   We may or may not use that account this quarter, but we want to be sure that you've established that account in case we need it.  Just loggin in and logging out once establishes the account.

## Step 5: Some coding

We are going to do a limited amount of coding in both C++ and Java.  If you've never used Java before, don't worry: the Java coding we'll be doing is straightforward, and does not require Java background&mdash;your C++ background from CS32 will be sufficient.

1.   Login to your CSIL account, and create a <tt>~/{{site.course | downcase }}</tt> subdirectory.

2.  Next, we are all going to make sure we have the basic Hello World skills down in C++, Java, and Python.
   not only to make sure we know what we are doing, but to make sure our CSIL accounts are working
   properly.   This will walk you through "Hello, World" in all three languages.

2. Java first.  In your <tt>~/{{site.course | downcase }}</tt>
   directory, use your favorite text editor (e.g. `vim`, `emacs`) to create a file containing
   the following code.  Call the file `Hello.java`.  Put your name instead of `Your Name Here`.

   (Side note: if you prefer it, two new editors are now available on CSIL staring Summer 2018: [atom](https://ucsb-cs16.github.io/topics/atom/) and [visual studio code](https://ucsb-cs16.github.io/topics/code/).)

   ```java
   /**
     @author Your Name Here
   */

   public class Hello {

     public static void main(String[] args) {
        System.out.println("Hello World!");
     }

   }
   ```

   NOTE: Please don't put literally `Your Name Here` in the code above.  Write your actual name.  Thanks!

   4. Compile the file with the command `javac Hello.java`

   5. Run the file with the command `java Hello`

   6. TODO: Add Python and C++ steps as well.

   6. Navigate to <https://gradescope.com>.   You should have an account invitation in your email.  If you don't, ask an instructor, TA or mentor for assistance.

   7. Upload your work to Gradescope.com for grading.    If you are working from your own machine (i.e. ssh'ing into CSIL), you'll need to transfer the file to your own machine before you can upload it for grading.    
      * If you aren't sure how, there is a link on the CS16 web page that explains [how to copy files between CSIL and your own machine](https://ucsb-cs16.github.io/topics/csil_copying_files/).

   8. Once you see that you have a score of 100 for the lab on Gradescope, you are *done* with lab00.   If [lab01](/labs/lab01/) is ready, start on lab01.  Otherwise, ask a mentor or TA whether there is anything else to do today before you just take off.
   
