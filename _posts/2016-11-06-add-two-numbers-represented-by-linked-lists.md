---
layout: single
---
I found the problem at this <a href="http://www.geeksforgeeks.org/sum-of-two-linked-lists/">link</a>.

<p>I have solved a similar problem from leetcode, but the digits in the linked lists were backwards, so it was easier since I can do regular addition starting at the beginning of the lists. </p>

<p>For this one, there are two approach:
<li>Find two pointers to end of two lists and continue like the old problem</li>
<li>Recursively add sum of next nodes to sum of currents node until we reach ends of lists which are null</li>
</p>

<p>Since method 1 is easy, we can have look at method 2</p>

<p>Accroding to geeksforgeeks, we need to watch out for the case that one link list is longer than the other. In that case, we will move the shorter list's last node to the position of the longer list's last node. Perform addition on two linked lists for the length of the shorter list. After that, we add the remaining digits in the longer lists to our result.</p>
