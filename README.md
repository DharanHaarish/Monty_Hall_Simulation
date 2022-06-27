# Monty_Hall_Simulation

Monty Hall problem is a famous problem/brain teaser is the field of mathematics
3 DOORS THAT CONFUSED MATHEMATICIANS.


Most of the times our intuition with a real life problems goes along with the mathematical approach to the problem but sometimes when the mathematical approach says otherwise it sounds so absurd that the human mind never wants to believe the approach and this is what happened when Marilyn vos savant an american columnist's answer to a question outraged lot including PhD's including Paul erdos who is referred as Father of Discrete Mathematics.


Question:
“”Suppose you’re on a game show, and you’re given the choice of three doors. Behind one door is a car, behind the others, goats. You pick a door, say #1, and the host, who knows what’s behind the doors, opens another door, say #3, which has a goat. He says to you, “Do you want to pick door #2?” Is it to your advantage to switch your choice of doors?””

![image](https://user-images.githubusercontent.com/78015090/175975205-a0c65ddd-c113-47f2-9911-feabbf26137c.png)

and Marilyn’s answer was switching would be the best option and long story short she received around 10000 letters from the public as well as some well known researchers asking her to retract her answer.


Solution:
So let’s take the 2 cases where you switch your option and where you will not switch the option.

Not-Switch:
If you do not switch and has to win a car you should pick a car and the host revealing one of the doors has nothing to do with it so there is an 1/3 ~ 33% chance that you will choose the correct door that has the car and 2/3 ~ 66% you will choose the wrong door that has the goat.


![image](https://user-images.githubusercontent.com/78015090/175975300-a82f391f-00bd-4343-a6e0-e8521d631354.png)

Switch:
So to be able to switch and win the car you should pick the wrong door first so there is an 2/3 ~ 66% chance you would pick the wrong door (i.e. that is the door with the goat behind it) and there is an 1/3~33% chance that you will pick the correct door first and switching that will get you the goat.


![image](https://user-images.githubusercontent.com/78015090/175975370-cc046be4-4d95-4b4e-bc37-25d44ef61e87.png)

So by switching the door you increase your chance of winning a Car from 33% — 66%(i.e you have doubled it).

So if you are still not convinced here is a same scenario with 100 doors.Let’s say you choose one of the doors randomly. Your chance of choosing the door with the car is 1 / 100 which is 1%. The host then reveals to you 98 other doors that contain a goat leaving just your first choice and one other unopened door, so we know one of them contains the prize and the other contains the goat.

Do you still think, given this scenario that you have only a 50% chance of winning by switching or not switching since there are two unrevealed doors left ? Do you think it would be better for you to switch or stay with your original choice ?

By switching your choice you are given an extra 98% chance of getting the prize (meaning by switching you will have a 99% chance of getting the prize) , and your first choice still has only a 1% chance of being right.



Here is the Article Pubished in the Medium - [Monty Hall](https://medium.com/analytics-vidhya/monty-hall-problem-with-python-simulation-4af54fc14737#11cc-d4546e3a865b)
