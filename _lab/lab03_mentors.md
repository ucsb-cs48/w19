---
layout: lab
num: lab03_mentors
ready: false
desc: "Mentor instructions for lab03"
mentor_due: 2019-02-24 17:00
ta_due: 2019-03-01 12:00
github_org: "ucsb-cs48-w19"
---

<div style="display:none">
https://ucsb-cs48.github.io/w19/lab/lab03_mentors/
</div>

{% capture lab %}{{ page.num | replace: '_mentors','' }}{% endcapture %}
{% capture lab_url_raw %}/lab/{{lab}}/{% endcapture %}
{% capture lab_url %}{{lab_url_raw | relative_url }}{% endcapture %}


# These instructions are for mentors/TAs only

Students, you are welcome to read them; there are no secrets here.   But there are probably better uses of your time. :-)

# Setting up templates for {{lab}}

Due {{page.mentor_due}}

The evaluation of [{{lab}}]({{lab_url}}) is divided into two parts:

| Part | Template to Use | Where to Put It |
|------|-----------------|-----------------|
| Team | [<tt>{{lab}}-T</tt>](https://github.com/{{page.github_org}}/FEEDBACK_TEMPLATES/blob/master/{{lab}}-T.md) | team `_FEEDBACK` repos |
| Individual | [<tt>{{lab}}-I</tt>](https://github.com/{{page.github_org}}/FEEDBACK_TEMPLATES/blob/master/{{lab}}-I.md) | individual `_FEEDBACK` repos |

See [/lab/lab00_mentors]({{'/lab/lab00_mentors/' | relative_url }}) for:
* an explanation of the two kinds of repos
* where to find them if they are already setup
* how to set them up if you haven't done that yet.

You can copy the contents of the templates file into each of the respective feedback repos, and then fill it out.

# TA Review/Grading of {{lab}}

Due {{page.ta_due}}
