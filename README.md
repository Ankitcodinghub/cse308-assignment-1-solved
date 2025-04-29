# cse308-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE308 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cse308-for-input-print-all-the-options-along-with-numbers-and-take-numeric-inputs-if-possible-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112772&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE308 Assignment 1  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
For input, print all the options along with numbers and take numeric inputs (if possible).

Observer Pattern

ABC Company provides server as a service to its clients. But as the company is very new and small, currently they have only one server. So, when maintenance or upgrading work is carried out, the server maybe partially or fully down. The company has two types of clients: premium user and regular user. Premium users have to pay more than the regular users and in return, they receive some benefits. As a part of an agreement, all the data of the premium users are backed up in a server of DEF Company. When the server of ABC Company is partially down (some functionalities are not available) or fully down, DEF Company helps to provide an uninterrupted service.

Previous State of server Current State of server For Premium users For Regular users

Operational Partially down ABC company asks the user whether he/she wants to use service from two servers (partially from the server of ABC and partially from the server of DEF) or from one server (DEF) ABC company asks the user whether he/she wants to continue using the limited functionality or pay $20 per hour to enjoy the full functionality taking service from server of DEF (this will copy all his/her data to the server of DEF)

Operational Fully down ABC company notifies the user about the fact that the service is now provided by their partner DEF company ABC company asks the user whether he/she wants to pay $20 per hour to take service from DEF company (this will copy all his/her data to the server of DEF)

Partially down Operational If the user was paying, send him/her the total bill since the last state change. *

Partially down Fully down If the user was taking service from two servers, ABC company shifts all the services to the server of DEF and notifies user about it.

Fully down Operational If the user was paying, send him/her the total bill since the last state change. *

Fully down Partially down

In addition to the notifications stated above, ABC company informs all the users of any state change.

*You don’t need to calculate the total bill. Just use some arbitrary placeholder variable like x. For simplicity, create one instance of premium user and one instance of regular user. Sending notifications from the ABC company to these two users will suffice. Code in Java using Observer Pattern to create the above scenario.

Input-Output:

Start with Operational state of the server. Take input to change the state of the server (for example, input “1” to change the state to Partially Down or “2” to change the state to Fully Down). You should be able to change the state of the server from every state to every other state from input. Notifications will be printed from the side of users (premium or regular) as prompts, i.e. “Do you want to use service from two servers?” User will select an option and the service will continue accordingly. Notification of data copying should also be printed from the user side. Communication from the users to ABC company need not follow any specific pattern, but the reverse communication should follow the observer pattern.

Mediator Pattern

Code in Java using Mediator Pattern to create the above scenario. Consider exam controller office as the mediator.

Input-Output:

In case of re-examine, take input to generate a re-examine request. The input will decide which student will apply for re-examine. The request should go through the student side (i.e. print “reexamine request sent from student id 1”) and should be printed from the exam controller side (i.e. print “re-examine request got from student id 1”). Same type of communication should be followed elsewhere.

Submission instructions:

• Enclose all the files inside a single folder named after your 7 digit student id. For example, 1605001 will enclose all the files in a folder named 1605001. Then, zip the folder (the name of the zipped file will also be the same as the folder, i.e., 1605001.zip).

• A submission at the sessional class won’t be accepted if there is no submission in moodle.
