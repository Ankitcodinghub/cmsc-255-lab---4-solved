# cmsc-255-lab---4-solved
**TO GET THIS SOLUTION VISIT:** [CMSC-255 Lab – 4 Solved](https://www.ankitcodinghub.com/product/cmsc-255-lab-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;36383&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC-255  Lab - 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (3 votes)    </div>
    </div>
Big Java, Late Objects / Java for Everyone, 2e

Chapter Number: 3 Decisions

&nbsp;

1) Copy and run the following program. Explain how the program compares the two strings. How can you modify the program so that str2 and str3 are equal when they are compared?

&nbsp;

public class StringEqual{&nbsp;&nbsp; public static void main(String[] args)&nbsp;&nbsp; {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; String str1 = “abcd”;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; String str2 = “abcdefg”;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; String str3 = str1 + “efg”;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.println(“str2 = ” + str2);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.println(“str3 = ” + str3);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (str2 == str3)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.println(“The strings are equal”);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; else&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.println(“The strings are not equal”);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }&nbsp;&nbsp; }}

&nbsp;

&nbsp;

&nbsp;

2) Remember the childhood game “Rock, Paper, Scissors”? It is a two-player game in which each person simultaneously chooses either rock, paper, or scissors. Rock beats scissors but loses to paper, paper beats rock but loses to scissors, and scissors beats paper but loses to rock. The following code prompts player 1 and player 2 to each enter a string: rock, paper, or scissors. Finish the code by adding nested if statements to appropriately report “Player 1 wins”, “Player 2 wins”, or “It is a tie.”

&nbsp;

import java.util.Scanner;public class RockPaperScissors{ &nbsp;&nbsp;&nbsp;&nbsp;public static void main(String[] args)&nbsp;&nbsp;&nbsp; {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Scanner scan = new Scanner(System.in);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.println(“Player 1: Choose rock, scissors, or paper:”);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; String player1 = scan.next().toLowerCase();&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.println(“Player 2: Choose rock, scissors, or paper:”);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; String player2 = scan.next().toLowerCase(); &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(your code goes here…)&nbsp;&nbsp;&nbsp; }}

&nbsp;

&nbsp;

3) The program in Lab 3.7 was heavily nested with if statements, and it can be difficult to follow the logic of any program that is heavily nested in this way. By constructing complex conditions with the &amp;&amp; operator, it is possible to simplify the code and remove some of the else alternatives. Rewrite the program in Lab 3.7 using complex conditions and omitting the else construct.

&nbsp;

&nbsp;

4) Draw a flowchart for a program that reads two integers and prints the smaller number.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

5.1) Write a program that prompts the user to enter three strings. Compare the String objects lexicographically and print the middle-valued string. For example, if the three strings were “abcd”, “wxyz”, and “pqrs”, the program would print “pqrs”. Limit yourself to simple, nested if statements that don’t use the Boolean operators &amp;&amp; or ||. Be sure and test your code by giving it input data that tests every path through your code. Make a list of values for str1, str2, and str3 that would thoroughly test the code.

&nbsp;

&nbsp;

5.2) Rewrite the program solution for Lab 3.10.1 using the Boolean operator &amp;&amp; to simplify the logical structure.

&nbsp;

&nbsp;

6.1) Build and run the following program. What happens when the two points have the same <em>x</em>-coordinate?

&nbsp;

import java.util.Scanner;&nbsp;public class Slope {&nbsp;&nbsp; public static void main(String[] args)&nbsp;&nbsp; {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Scanner in = new Scanner(System.in);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.print(“Input x coordinate of the first point: “);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; double xcoord1 = in.nextDouble();&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.print(“Input y coordinate of the first point: “);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; double ycoord1 = in.nextDouble();&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.print(“Input x coordinate of the second point: “);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; double xcoord2 = in.nextDouble();&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System.out.print(“Input y coordinate of the second point: “);&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;double ycoord2 = in.nextDouble();&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; double slope = (ycoord2 – ycoord1) / (xcoord2 – xcoord1);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.out.println(“The slope of the line is ” + slope);&nbsp;&nbsp; } }

&nbsp;

&nbsp;

6.2) Correct and rebuild the slope program to disallow a vertical line (denominator = 0).

&nbsp;

&nbsp;

&nbsp;
