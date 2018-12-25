# Online Class: Arrays

<pre>
/*
+---+
| 1 |
+---+
Declare and assign the indexed array with your favourite food 
(at least 4 array elements). Name the array <em><strong>food</strong></em>.
*/

/*
Print every array element in a new line.
*/



/*
+---+
| 2 |
+---+
Print the array elements from the previous exercise in unordered list.
&lt;ul&gt;
  &lt;li&gt;...&lt;/li&gt;
  &lt;li&gt;...&lt;/li&gt;
  &lt;li&gt;...&lt;/li&gt;
  &lt;li&gt;...&lt;/li&gt;
&lt;/ul&gt;
*/



/*
+---+
| 3 |
+---+
Turn the indexed array <em><strong>food</strong></em> from task 1 into associative array named <em><strong>food_assoc</strong></em>. 
Every array element of <em><strong>food</strong></em> becomes the key of <em><strong>food_assoc</strong></em>.
Every key of <em><strong>food_assoc</strong></em> has the value that describes the type of food (salad, main course or dessert).
*/

/*
Print every food and type in the separate lines so it renders like this:
pizza | main counrse 
cheesesake | desert 
*/



/*
+---+
| 4 |
+---+
Break down the <em><strong>food_assoc</strong></em> from the task 3 to type (salad, main course, dessert, ...) 
and country of origin (Italy, Spain, India, ...)
food_assoc:
  pizza:
    type: main course
    origin: Italy
  cheesesake: 
    type:desert
    origin: Greece
  
So, <em><strong>food_assoc</strong></em> is still going to be an associative array. 
Every key of <em><strong>food_assoc</strong></em> (<em><strong>pizza</strong></em>, <em><strong>cheesecake</strong></em>) will now have the value that is associative array itself 
and carries the information about the <em><strong>type</strong></em> and <em><strong>origin</strong></em>
*/

/*
Print every food, type and origin in the separate lines so it renders like this:
pizza | main counrse | Italy
cheesesake | desert | Greece
*/



/*
+---+
| 5 |
+---+
Print the array from task 4 in html table:
&lt;table&gt;
  &lt;tr>
    &lt;th&gt;food&lt;/th&gt;
    &lt;th&gt;type&lt;/th&gt;
    &lt;th&gt;origin&lt;/th&gt;
  &lt;/tr&gt;
  &lt;tr&gt;
    &lt;td&gt;pizza&lt;/td&gt;
    &lt;td&gt;main course&lt;/td&gt;
    &lt;td&gt;Italy&lt;/td&gt;
  &lt;/tr&gt;
  &lt;tr&gt;
    &lt;td&gt;cheesecake&lt;/td&gt;
    &lt;td&gt;desert&lt;/td&gt;
    &lt;td&gt;Greece&lt;/td&gt;
  &lt;/tr&gt;
&lt;/table&gt;
*/
</pre>

## Table should render like this:
| food        | type           | origin  |
|:------------|:---------------|:--------|
| pizza       | main course    | Italy   |
| cheesecake  | dessert        | Greece  |
