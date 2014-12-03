# Using PowerShell Classes 

Use PowerShell Classes and Script to generate and manipulate combinations and permutations

Combinations
-
A combination is a way of selecting to members from a grouping, such that (unlike permutations) the order of selection does not matter.

For example, if you have the 5 items

	ant bug cat dog elk

then the 10 possible combinations of size 3 are

	ant   bug   cat  
	ant   bug   dog  
	ant   bug   elk  
	ant   cat   dog  
	ant   cat   elk  
	ant   dog   elk  
	bug   cat   dog  
	bug   cat   elk  
	bug   dog   elk  
	cat   dog   elk  

![image](https://raw.githubusercontent.com/dfinke/PowerShellCombinations/master/images/Combinations.png)

Permuations
-
It you have the three items

	Adam John Jane

then, the six permutations of these items are

	Adam John Jane
	Adam Jane John
	John Adam Jane
	John Jane Adam
	Jane Adam John
	Jane John Adam

![image](https://raw.githubusercontent.com/dfinke/PowerShellCombinations/master/images/Permutations.png)

Acknowledgments
-
I ported this from James McCaffrey's book [.NET Test Automation Recipes](http://www.apress.com/9781590596630)
