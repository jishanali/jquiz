LOADING JQUIZ

1) Load the CSS


&lt;CODE&gt;




&lt;link href='jquiz.css' type='text/css' rel='stylesheet' /&gt;




Unknown end tag for &lt;/code&gt;



2) Load jQuery locally or through Google.


&lt;Code&gt;




&lt;script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.min.js"&gt;



&lt;/script&gt;




Unknown end tag for &lt;/code&gt;



3) Load jQuiz JavaScript file.
```

<script type="text/javascript" src="jquiz.js">

Unknown end tag for &lt;/script&gt;


```

You may have to modify the href of the CSS and the src of the javascript files to make sure they are pointing to the right location. Please google the answer if you do not know how.

FORMATTING JQUIZ HTML

1) start off with an ordered list with the id "jquiz"
2) each following and immediated list item is one question.
3) the unordered list and list items within the previous list items are the question options.
4) make sure you put a 'class="correct"' next to the correct answer so the javascript knows which is right.
5) the div with classes 'explanation' and 'hidden' tell the person a little bit about the answer once they have answered.
6) the div with id of 'quizremarks' shows up at the end. by default, it shows how many they got correct, but can be modified to display whatever you want.

EXAMPLE HTML OF JQUIZ

```

<ol id="quiz">

<li>

<p>jQuiz is the coolest thing since sliced bread.

Unknown end tag for &lt;/p&gt;



<ul>

<li class="correct">True

Unknown end tag for &lt;/li&gt;



<li>False

Unknown end tag for &lt;/li&gt;





Unknown end tag for &lt;/ul&gt;



<div class="explanation hidden">

<p>Of course you're right. Now <a href="http://websitedesignernc.com">go back

Unknown end tag for &lt;/a&gt;

.

Unknown end tag for &lt;/p&gt;





Unknown end tag for &lt;/div&gt;





Unknown end tag for &lt;/li&gt;



<li>

<p>What website should jQuiz be featured on?

Unknown end tag for &lt;/p&gt;



<ul>

<li>Kumquat Lovers Anonymous

Unknown end tag for &lt;/li&gt;



<li class="correct">Smashing Magazine

Unknown end tag for &lt;/li&gt;



<li>Facebook Farmville Fanatics

Unknown end tag for &lt;/li&gt;







Unknown end tag for &lt;/ul&gt;



<div class="explanation hidden">

<p><a href="http://smashingmagazine.com">Smashing Magazine

Unknown end tag for &lt;/a&gt;

 is a pretty cool web site.

Unknown end tag for &lt;/p&gt;





Unknown end tag for &lt;/div&gt;





Unknown end tag for &lt;/li&gt;



<li>

<p>How much is jQuiz worth?

Unknown end tag for &lt;/p&gt;



<ul>

<li>$0

Unknown end tag for &lt;/li&gt;



<li>$100

Unknown end tag for &lt;/li&gt;



<li>$1,000

Unknown end tag for &lt;/li&gt;



<li>$1,000,000

Unknown end tag for &lt;/li&gt;



<li class="correct">$1,000,000,000,000,000,000

Unknown end tag for &lt;/li&gt;







Unknown end tag for &lt;/ul&gt;



<div class="explanation hidden">

<p>You know that's right!

Unknown end tag for &lt;/p&gt;





Unknown end tag for &lt;/div&gt;





Unknown end tag for &lt;/li&gt;







Unknown end tag for &lt;/ol&gt;





<div id="quizremarks">

<p id="quiztotal">&nbsp;

Unknown end tag for &lt;/p&gt;





Unknown end tag for &lt;/div&gt;


```