# fundamental-algorithms-assignment-5-search-operation-in-hash-tables-solved
**TO GET THIS SOLUTION VISIT:** [Fundamental-Algorithms Assignment 5-Search Operation in Hash Tables Solved](https://www.ankitcodinghub.com/product/fundamental-algorithms-assignment-5-search-operation-in-hash-tables-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97162&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Fundamental-Algorithms Assignment 5-Search Operation in Hash Tables Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Search Operation in Hash Tables Open Addressing with Quadratic Probing

Allocated time:​​ 2 hours Implementation

You are required to implement correctly and efficiently the ​insert a​ nd ​search ​operations in a hash table using​ open addressing​ and ​quadratic probing​. You may find relevant information and pseudo-code in your course notes, or in the book, in section ​11.4 Open addressing​.

Addressing (refers to the final position of the element with respect to its initial position)

</div>
</div>
<div class="layoutArea">
<div class="column">
●

○

</div>
</div>
<div class="layoutArea">
<div class="column">
Open Addressing

The final address is not completely determined by the hash code, it also depends on the elements which are already in the hash table e.g linear/quadratic probing

</div>
</div>
<div class="layoutArea">
<div class="column">
●

○

</div>
</div>
<div class="layoutArea">
<div class="column">
Closed Addressing

The final address is always the one initially calculated (there is no probing) e.g. chaining

</div>
</div>
<div class="layoutArea">
<div class="column">
Hashing (refers to the hash table)

For the purpose of this assignment, the hash table will not contain integers, but a custom data structure defined as follows:

typedef​​ ​struct​​ { ​int​​ id;

​char​​ name[​30​]; } Entry;

The position of each Entry in the Hash Table will be calculated by applying the required hash function on the ​id member of the struct. The ​name ​member of the struct will be used only to exemplify the correctness of the search operation, and is not needed when evaluating the performance (i.e the ​name member will be printed to the console if the search operation finds the ​id, ​otherwise print “not found”).

</div>
</div>
<div class="layoutArea">
<div class="column">
●

○

</div>
</div>
<div class="layoutArea">
<div class="column">
Open Hashing

Free to leave the hash table to hold more elements at a certain index (e.g. chaining)

</div>
</div>
<div class="layoutArea">
<div class="column">
●

○

</div>
</div>
<div class="layoutArea">
<div class="column">
Closed Hashing

Not more than one element can be stored at a certain index (e.g. linear/​quadratic probing​)

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Evaluation

! Before you start to work on the algorithms evaluation code, make sure you have a correct

algorithm! You will have to prove your algorithm(s) work on a small-sized input.

You are required to evaluate the ​search ​operation for hash tables using open addressing and quadratic probing, in the average case (remember to perform 5 runs for this). You will do this in the following manner:

1. Select ​N​, the size of your hash table, as a prime number around 10000 (e.g. 9973, or 10007);

2. For each of several values for the filling factor ​α​∈{0.8, 0.85, 0.9, 0.95, 0.99}, do:

<ol>
<li>Insert n random elements, such that you reach the required value for ​α ​(​α = n/N​)</li>
<li>Search, in each case, ​m random elements (​m ~ 3000), such that approximately half of the searched elements will be ​found in the table, and the rest will ​not be ​found (in the table). Make sure that you sample uniformly the elements in the ​found category, i.e. you should search elements which have been inserted at different moments with equal probability (there are several ways in which you could ensure this – it is up to you to figure this out)</li>
<li>Count the operations performed by the search procedure (i.e. the number of cells accessed during the search)</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3. Output a table of the form:

</div>
</div>
<div class="layoutArea">
<div class="column">
Filling factor

0.8 0.85 …

4.

</div>
<div class="column">
Avg. Effort

found

…

</div>
<div class="column">
Max. Effort

found

</div>
<div class="column">
Avg. Effort

not-found

…

</div>
<div class="column">
Max. Effort

not-found

</div>
</div>
<div class="layoutArea">
<div class="column">
Avg. Effort = total_effort / no_elements

Max. Effort = maximum number of accesses performed by one search operation

Interpret your results.

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Thresholds

Grade Requirements

5 Demo for the insert and search operations using the required data structure.

10 Evaluation and personal interpretations of the results

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Evaluate the search operation for a single fill factor, with non-uniform selection of the elements

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Complete evaluation for all fill factors with uniform selection of the found elements.

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
