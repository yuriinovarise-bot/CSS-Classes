CSS Classes
Description

Classes in CSS allow you to assign different styles to elements of the same type.

Assign a class using the class attribute in HTML.

Class names can include letters, numbers, underscores (_), and hyphens (-).

In CSS, select a class using a period (.) followed by the class name.

Example:
<p class="eee">paragraph with class eee</p>
<p class="zzz">paragraph with class zzz</p>

.eee {
	color: green;
}

.zzz {
	color: red;
}

Task 1

Given the following code:

<ul>
	<li class="odd">text</li>
	<li class="eve">text</li>
	<li class="odd">text</li>
	<li class="eve">text</li>
	<li class="odd">text</li>
	<li class="eve">text</li>
</ul>


Color elements with class odd in red.

Color elements with class eve in green.

Task 2

Given the following code:

<h2 class="eee">Title</h2>
<p class="eee">paragraph</p>
<p class="eee">paragraph</p>
<p>paragraph without class</p>

<ul class="eee">
	<li>text</li>
	<li>text</li>
	<li>text</li>
</ul>


Color all elements with class eee in red.

Task 3

Explain why the <li> elements inside <ul class="eee"> inherit the red color, even though the class is applied to the <ul>.
