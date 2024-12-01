---
layout: page
title: Assignments 
permalink: /assignments/
order: 3
exclude_from_nav: false 
---

* Course Setup
{% comment %}
* Course Setup <a data-toggle="collapse" data-target="#css">(Click to expand/hide)</a>
<div id = "css" class = "collapse" style = "margin:0px">
{% endcomment %}
<ul>
<ul>
    <li>Install the necessary software for your personal computer (instructions are on the <a href = "../info/">Course Information</a> page).</li>
    <li>Look through the <a href = "../data/notes/notebooks.ipynb">"Notebook" Notebook</a> (not collected)</li> 
</ul></ul>
{% comment %}
</div>
{% endcomment %}
* Lab 1 (Due: <strike>Monday, 09/09/2024</strike> Wednesday, 09/11/2024; turn in a hard copy at the beginning of class)
	* [Lab 1, Question 1]({{ site.baseurl }}/data/hw/hw1_algorithms.pdf) 
	* [Lab 1 Notebook]({{ site.baseurl }}/data/hw/lab1.ipynb) 
* [Lab 2]({{ site.baseurl }}/data/hw/lab2.ipynb) (Due: Monday, 09/16/2024; <strike>turn in a hard copy at the beginning of class</strike> submit through [blackboard](https://easternct.blackboard.com))
* [Lab 3]({{ site.baseurl }}/data/hw/lab3.ipynb) (Due: Monday, 09/23/2024, by 8:00 AM; submit through [blackboard](https://easternct.blackboard.com))
* Lab 4 (Due: Monday, 10/07/2024)
	* [Lab 4, Part 1]({{ site.baseurl }}/data/hw/lab4.pdf) (Submit hardcopy at beginning of class)
	* [Lab 4, Python]({{ site.baseurl }}/data/hw/lab4.ipynb) (Subit through [blackboard](https://easternct.blackboard.com))
* [Lab 5]({{ site.baseurl }}/data/hw/lab5.pdf) (Due: Wednesday, 10/16/2024; turn in a hard copy at the beginning of class)
* [Lab 6]({{ site.baseurl }}/data/hw/lab6.pdf) (Due: Wednesday, 10/23/2024; turn in a hard copy at the beginning of class)
* [Lab 7]({{ site.baseurl }}/data/hw/lab7.pdf) (Due: Monday, 10/28/2024; turn in a hard copy at the beginning of class)
* Lab 8 (Due: Friday, 11/15/2024; turn in a hard copy of the questions; submit code through [blackboard](https://easternct.blackboard.com))
    * [Lab 8 Questions]({{ site.baseurl }}/data/hw/lab8.docx) 
    * [Lab 8 Notebook]({{ site.baseurl }}/data/hw/lab8.ipynb) 
* [Lab 9]({{ site.baseurl }}/data/hw/lab9.docx) (Due: Friday, 11/22/2024; turn in a hard copy of the questions at the beginning of class)
<hr style = "margin:5px; height:1px; background-color:red;">
{% comment %}
{% endcomment %}

<script>
const pattern = RegExp('Due:.*([0-9]{2}/[0-9]+/[0-9]{4})');
elements = document.getElementsByTagName('li');

for (el of elements) {
        var res = pattern.exec(el.innerText);
        if (res != null && res.length >= 2) {
                if (new Date(res[1]) >= new Date()) {
                        el.className = 'due';
                }
        }
}
</script>


<style>

.hide {
  display:none
}

table, th, td {
  border: 0px solid black;
  border-collapse: collapse;
  text-align: center;
}

td.left {
    text-align: left;
}

a.hide, tr.hide {
    display: none;
}

.due {
    background-color: yellow
}

</style>
