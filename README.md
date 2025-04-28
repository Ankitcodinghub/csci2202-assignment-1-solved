# csci2202-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2202 Assignment 1 Solved](https://www.ankitcodinghub.com/product/computer-modelling-for-scientists-csci-2202-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116949&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2202 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Enter num sides : 8 Enter num sides of polygon: 20

Enter num polygons: 10 Enter num polygons: 20

1

2

(3) In the book Liber Abaci, Leonardo of Pisa (better known as Fibonacci) considers pairs of breeding rabbits in an enclosure.

• At the start of month zero there is a single infant pair of rabbits.

• A pair of rabbits matures in 2 months.

• Rabbits do not breed in their first month of life.

• Each mature pair of rabbits produces an infant pair of rabbits on the last day of each month, starting with the second month.

• Rabbits are not mortal.

Leonardo asks: How many pairs will there be one year after this pair begins breeding. For more information about Fibonacci’s problem see: https://tinyurl.com/y5sadcpb

Let F[j] denote the number of pairs in month j. A slight modification of the above problem gives:

F[0] = 0, F[1] = 1,and F[j] = F[j − 1] + F[j − 2], n ≥ 2

(a) Write program FibonacciSeq.py that prompts the user for a positive integer n and then computes and prints out the Fibonacci sequence up to F[n]. You program should print the sequence with 5 Fibonacci numbers per line (except in the last line). The Fibonacci numbers for the range above are at most 4 digits. Use print(’{:5d}’.format(F[j]), end=””) to print values with widths of 5 digits. This will give a reasonable display (we will examine formatted output in the next lab). What is the answer to Leonardo’s question?

3

You will need to refer to:

https://docs.python.org/3/tutorial/datastructures.html for list methods.

(b) Make your program print compute the ratio: for 2 ≤ j ≤ 20.

The limiting value of is known as the Golden Ratio. It appears in

unexpected places

(see https://www.mathsisfun.com/numbers/golden-ratio.html scroll down to ”FIbonacci Sequence”).

(c) Sketch the Fibonacci Spiral. The Fibonacci spiral is made up of quarter circles (i.e. arc of a circle subtended by a 90o angle) passing through the diagonally opposite vertices of squares that have sides in the Fibonacci sequence. Use the functions you wrote in Lab 5 to draw the arc. The figure on the left, with the squares, is to illustrate the drawing. The figure on the right is what your curve should look like ( the first arc is drawn with the turtle facing East). To illustrate, each quarter circle arc is a different colour. The side lengths are scaled by a factor of 5 (i.e. a square of side length ` will be 5 · ` in the drawing. Your function goldenSpiral.py, takes a turtle as a parameter and have a default parameter n = 10 for the number of arcs that make up your spiral.

Ex. of Spiral with squares drawn in Golden Spiral with n=10 &amp; scale = 5
