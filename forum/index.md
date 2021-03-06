---
title: Assignments &amp; Forum
layout: page
---

Welcome to the *Integrated Musicianship: Theory* Assignments & Forum! 
Links to all assignments for the course will be posted on this page, please follow the link for the description of the homework and a help forum.
For other discussion and questions, check our general forum threads.
This discussion space is intended to help students learn, communicate, and collaborate.

We will be notified when you post, so feel free to ask any questions. 
Between all of the instructors, this will decrease response time so that you get answers when you need them. 
And remember that you should help your classmates if you think you know the answer to their questions!

For information about getting started with [Disqus](https://disqus.com/) and our community guidelines, please check the [help page]({{ "/forum/help.html" | absolute_url }}).

## Assignments:

<div id="fallSemester" class="assignments">
<h2>Fall Semester Homework</h2>
{% assign fall = site.assignments | where_exp: "item","item.relative_path contains 'Fall-semester'" %}
<ul id="fallSemesterList">
{% for item in fall %}
<li>{{ item.due }}: <a href="{{ item.url | absolute_url }}">{{ item.title }}</a> (<a href="{{ item.url | absolute_url }}#disqus_thread">0 Comments</a>)</li>{% endfor %}
</ul>
</div>

<div id="springSemester" class="assignments">
<h2>Spring Semester Homework</h2>
{% assign spring = site.assignments | where_exp: "item","item.relative_path contains 'Spring-semester'" %}
<ul id="springSemesterList" style="display:block;">
{% for item in spring %}
<li>{{ item.due }}: <a href="{{ item.url | absolute_url }}">{{ item.title }}</a> (<a href="{{ item.url | absolute_url }}#disqus_thread">0 Comments</a>)</li>{% endfor %}
</ul>
</div>

## General discussions:

- [General Concepts]({{ "/forum/concepts.html" | absolute_url }}) ([0 Comments]({{ "/forum/concepts.html#disqus_thread" | absolute_url }}))
- [Typos and Website Suggestions]({{ "/forum/suggestions.html" | absolute_url }}) ([0 Comments]({{ "/forum/suggestions.html#disqus_thread" | absolute_url }}))

<script id="dsq-count-scr" src="//intmus.disqus.com/count.js" async></script>
<script>
/* toggle */
function assignmentsToggle(element) {
    document.getElementById(element).style.display = (document.getElementById(element).style.display === "block") ? "none" : "block";
}
/* open + close */
document.getElementById("fallSemester").onclick = function () { assignmentsToggle("fallSemesterList"); };
document.getElementById("springSemester").onclick = function () { assignmentsToggle("springSemesterList"); };
</script>