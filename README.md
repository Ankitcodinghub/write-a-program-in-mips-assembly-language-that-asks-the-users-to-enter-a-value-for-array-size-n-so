# write-a-program-in-mips-assembly-language-that-asks-the-users-to-enter-a-value-for-array-size-n-so
**TO GET THIS SOLUTION VISIT:** [Write a program in MIPS assembly language that asks the users to enter a value for array size “n” So](https://www.ankitcodinghub.com/product/write-a-program-in-mips-assembly-language-that-asks-the-users-to-enter-a-value-for-array-size-n-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;9652&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Write a program in MIPS assembly language that asks the users to enter a value for array size “n” Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<strong>Programming Question:</strong>

Write a program in MIPS assembly language that asks the users to enter a value for array size “n” and fill up the array with n integers. Then reverse the array and print it on the screen. You are required to do the following in your program:

<ul>
<li>Create up to 80 bytes of space in your program</li>
<li>“n”, the array size, should be greater than zero and less than 20</li>
<li>Each element of the array should be positive and divisible by 3</li>
<li>Array should be reversed within itself. i.e. you must not create another array to place the elements in reverse order</li>
</ul>
You need to use following functions:

&nbsp;

int main( )

{

<strong><em>Begin:</em></strong> arraysize= <strong><em>readNum()</em></strong>

Ok=<strong><em>verifySize(arraySize)</em></strong>

if (ok==1)

<strong><em>creatArray(array-size)</em></strong>

else

Go to <strong><em>Begin</em></strong>

<strong><em>printArray(arraySize)</em></strong>

<strong><em>reverseArray(arraySize)</em></strong>

<strong><em>printArray (arraySize)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em></strong>

}

// ————————————————————

int&nbsp; readNum()

{

input an integer

return the integer to main program

}

&nbsp;

// ————————————————————

int versifySize( int arraySize)

{

if&nbsp; (0&lt;arraySize&lt; 20)

return 1

else

return 0

}

&nbsp;

// ————————————————————

&nbsp;

&nbsp;

void createArray(int arraySize)

{

counter = 0

<strong><em>making_array</em></strong>: arrayEntry = readNum()

ok = checkNumPositive(arrayEntry)

if (ok == 1)

validNum = divisibleBy3(arrayEntry)

if (validNum==1)

insert&nbsp; arrayEntry into the array

counter = counter + 1

else

go to <strong><em>making_array</em></strong>

else

go to <strong><em>making_array</em></strong>

if (counter &lt; arraySize)

go to&nbsp; <strong><em>making_array</em></strong>

}

&nbsp;

// ————————————————————

void reverseArray(int arraySize)

{

head = first index of the array

tail = last index of the array

<strong><em>swap:</em></strong>&nbsp;&nbsp; if (head &lt;=tail)

{

swap the content of head and tail (array[head] and array[tail] with each other

increment the head value by one word

decrement tail by one word

go to <strong><em>swap</em></strong>

}

}

&nbsp;

// ————————————————————

void printArray( int arraySize)

{

..

..

&nbsp;

}

// ————————————————————

int divisibleBy3(int arryEntry)

{

…

…

}

// ————————————————————

int checkNumPositive(int arrayEntry)

{…

}
