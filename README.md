# xar-zar-wars

The kingdom of Xars is not so well planned. It has **N** troops spread around the kingdom. They are spread in such a way that it takes **1 hour** to transfer information from one troop to any other troop and also from the king's castle.

The Xars kingdom is now having threat from the Zars kingdom. The king of Xars received this information. He sends the information to one of the **N** troops and tell them to alert all other groups. A soldier from the troop that received information is set to alert as many troops as possible. They maintain mutual communication and do not waste time in alerting the troops that already received the information.

Once Zars kingdom enters territory of Xars, all the army of Xars that received the information will be set into fight and stop spreading the message. Xars and Zars are equally powerful that even if one troop of Xars do not receive information and are not involved in the war, they lose. So the question for you is, for Zars to win the war, within how many hours should they enter the territory of Xars kingdom?

Explanation with Sample </br>
**Case 1:** For only one troop, it takes 1 hour to transfer information from king's castle to the troop.  
**Case 2:** For two troops, it takes 1 hour to transfer information from king's castle to the troop. A soldier of this troop takes another hour to alert the other troop.  
**Case 3:** For three troops, it takes 1 hour for soldier **X1** to transfer information from king's castle to the troop. A soldier(**X2**) of this troop takes another hour to alert one other troop. In the mean while **X1** alerts the third troop.

**Task**</br>
Create a program that reads a file with the following format:</br>
First line of input file has an integer **T**(number of test cases).  </br>
**T** lines follows having an integer in each **N**(number of troops in Xars kingdom).
</br></br>
As output the program should for each test case, print an integer answer within how many hours should Zars should enter Xars kingdom to win de war.

**Constraints:**  
1 &le; T &le; 10<sup>5</sup>  
1 &le; N &le; 10<sup>18</sup>


<b>Limitations:</b>
<ul>
<li>Time 1sec per file</li>
<li>Memory 256</li>
<li>Source code Limit 1mb</li>
</ul>




