Download Link: https://assignmentchef.com/product/solved-comp2113-module4-self-review-exercise
<br>



<ol>

 <li>Evaluate the following expressions:</li>

</ol>

Give the (i) function header; (ii) function prototype (without parameter names), for each of the following functions:

<ul>

 <li>Function hypotenuse​ ​ that takes two double-precision, floating-point arguments, side1​            and side2​      ​, and returns a double-precision, floating-point result.</li>

 <li>Function smallest​ ​ that takes three integers, x​ ​, y​ ​ and z​ ​, and returns an integer.</li>

 <li>Function instructions​ that does not receive any arguments and does not return a​             [Note: Such functions are commonly used to display instructions to a user.]</li>

 <li>Function intToDouble​ ​ that takes an integer argument, number​    ​, and returns a double-precision, floating-point result.</li>

</ul>




Example solution for (a):

<ul>

 <li>double hypotenuse( double side1, double side2 )</li>

 <li>double hypotenuse( double, double );</li>

</ul>

<ol start="2">

 <li>Define a function hypotenuse​ ​ that calculates the length of the hypotenuse of a right triangle when the other two sides are given. Use this function in a program to determine the length of the hypotenuse for each of the following triangles. The function should take two arguments of type double​    ​ and return the hypotenuse as a double​    ​.</li>

</ol>




<ol start="3">

 <li>Find the error(s) in each of the following program segments, and explain how the error(s) can be corrected:</li>

</ol>




<ul>

 <li>int g()</li>

</ul>

{ cout &lt;&lt; “Inside function g” &lt;&lt; endl;  int h()

{ cout &lt;&lt; “Inside function h” &lt;&lt; endl;  }

}




<ul>

 <li>int sum( int x, int y )</li>

</ul>

{ int result;

result = x + y;

}




<ul>

 <li>double square( double number )</li>

</ul>

{ double number;

return number * number;

}

<ol start="4">

 <li>What is the output of the following program?</li>

</ol>




#include &lt;iostream&gt; using namespace std;




void find(int a, int &amp;b, int &amp;c);




Self-Review Exercise         Module 5               p. 1/2 int main()

{ int one, two, three;




one = 5;

two = 10;

three = 15;




find(one, two, three);

cout &lt;&lt; one &lt;&lt; “, ” &lt;&lt; two &lt;&lt; “,” &lt;&lt; three &lt;&lt; endl;




find(two, one, three);

cout &lt;&lt; one &lt;&lt; “, ” &lt;&lt; two &lt;&lt; “,” &lt;&lt; three &lt;&lt; endl;




find(three, two, one);

cout &lt;&lt; one &lt;&lt; “, ” &lt;&lt; two &lt;&lt; “,” &lt;&lt; three &lt;&lt; endl;




find(two, three, one);

cout &lt;&lt; one &lt;&lt; “, ” &lt;&lt; two &lt;&lt; “,” &lt;&lt; three &lt;&lt; endl;

return 0;

}

void find(int a, int&amp; b, int&amp; c)

{ int temp;




c = a + b;

temp = a;     a = b;     b = 2 * temp;

}

<ol start="5">

 <li>Consider the following program that will generate a random number between 1 and 3.</li>

</ol>

int computerChoice = rand() % 3 + 1;




Write a program that allows a user to play the Rock Paper Scissors game with computer continuously. Take a look at the following sample run.




What do you choose? [1: Rock| 2: Paper| 3: Scissors| 4: Exit]: 1

Computer: 2, User: 1

The computer won!

What do you choose? [1: Rock| 2: Paper| 3: Scissors| 4: Exit]: 2

Computer: 1, User: 2

You won!

What do you choose? [1: Rock| 2: Paper| 3: Scissors| 4: Exit]: 3

Computer: 3, User: 3

It was a tie!

What do you choose? [1: Rock| 2: Paper| 3: Scissors| 4: Exit]: 4


