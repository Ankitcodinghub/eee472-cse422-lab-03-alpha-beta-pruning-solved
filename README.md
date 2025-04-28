# eee472-cse422-lab-03-alpha-beta-pruning-solved
**TO GET THIS SOLUTION VISIT:** [EEE472-CSE422 Lab 03-Alpha-Beta Pruning Solved](https://www.ankitcodinghub.com/product/eee472-cse422-artificial-intelligence-lab-03-alpha-beta-pruning-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120342&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEE472-CSE422  Lab 03-Alpha-Beta Pruning Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
(Winner finding problem)

Optimus Prime Megatron

This is 2082. Robots have taken over the world. The International Robot Sports Committee (IRSC) has been arranging Olympics for recreations of fellow robots for the last 10 years.

In Robot Olympic 2082, there is a game called ‘ROBO Sword-Fight’. In this game, two robots fight against each other using swords.

One of the participants in the ROBO Sword-Fight is Optimus Prime. Optimus Prime convincingly won each of his previous games. There is only one game left for him to reach glory, and he will have to fight Megatron in that game. In order to win the game, Optimus Prime will have to achieve a certain amount of points.

You have to perform the two tasks given below by using Alpha-Beta pruning.

Task 1: Calculate the points and find if Optimus Prime won or not. [6]

Task 2: Shuffle the generated list by S times and find how many times Optimus Prime won. [4]

[Hint: This will be a 4-level binary tree. On Level 0(MAX), it will be Optimus Prime’s

Turn. On Level 1(MIN) it will be Megatron’s Turn. On Level 2(MAX), again it will be Optimus Prime’s Turn. On Level 3, there will be Terminal Nodes]

NOTE: If any digit in your id is 0 consider it as 8

———————————————————————————————————-Sample Input 1 :

Enter your student ID

25485465

Sample Output 1(For Task-1):

Generated 8 random points between the minimum and maximum point limits: [66, 74, 14, 73, 19, 26, 32, 40]

Achieved point by applying alpha-beta pruning = 73

The winner is Optimus Prime

Sample Output 1(For Task-2):

After the shuffle:

List of all points values from each shuffles: [66, 73, 66, 73, 73, 66, 40, 66]

The maximum value of all shuffles: 73 Won 7 times out of 8 number of shuffles Explanation:

25485465 = 5

( 5th digit of your student ID) Minimum points the Optimus Prime can achieve from the game is 5

25485465 = 56*1.5 = 84

( Reverse last 2 digits of your student ID and multiply that number with 1.5 and

take nearest integer (upper)) 1. Maximum points the Optimus Prime can achieve from the game = 84

(reverse of last two digits of the ID)

25485465 = 8

(4th digit of your student ID) Total number of shuffles, S = 8 (for Task-2)

———————————————————————————————————— Sample Input 2 :

Enter your student ID

17564039

Sample Output 2:

Generated 8 random points between the minimum and maximum point

limits: [36, 26, 112, 57, 85, 80, 107, 28]

Achieved point by applying alpha-beta pruning = 85

The Winner is Megatron

After the shuffle:

List of all points values from each shuffle: [107, 80, 85, 80, 85, 107]

The maximum value of all shuffles: 107

Won 2 times out of 6 number of shuffles
