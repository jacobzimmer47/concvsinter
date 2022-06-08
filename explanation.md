## Concatenation vs Interpolation
<h1>Concatenation</h1>
<p> Concatenation is a way to put two or more strings together. for example...</p>

var greeting = "Hi there";
var name = "Jake";
var str;

<p> To put the two together you would..</p>

str = greeting + " " + name;
## output = "Hi there Jake"

<p> By using '+' you can combine strings!</p>

<h2>Interpolation</h2>
<p>Interpolation is also a way to combine two or more strings. for example...</p>

var greeting = "Hello";
var name = "Megan";
var str2;

<p> Combining the two would look like this </p>

str2 = `${greeting} ${name}` ;
##output = "Hello Megan"

<h3> Concatenation vs Interpolation </h3>
<p> In my opinion, I think that when coding with a team at a high level, Interpolation is the most optimal way to combine strings. This is because of the clean and clear look it presents. Also, there is no need to add " " when spacing words. Interpolation is more intuitive and is easier to read. </p>
