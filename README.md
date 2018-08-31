# HackerRank-Contest-3
Test starts on 31-08-18(8.00 a.m) 
Ends on         03-09-18(6.00 p.m)
Your flight to the RIT Code Challenge Finals departs in a short time, and the only way to get to the airport is by bus.

Unfortunately, some of the bus drivers are considering going on strike, so you do not know whether you can get to the airport on time. Your goal is to plan your journey in such a way as to maximize the probability of catching your plane. You have a detailed map of the city, which includes all the bus stations. You are at station 0 and the airport is at station 1. You also have a complete schedule of when each bus leaves its start station and arrives at its destination station. Additionally, for each bus you know the probability that it is actually going to run as scheduled, as opposed to its driver going on strike and taking the bus out of service. Assume all these events are independent. That is, the probability of a given bus running as planned does not change if you know whether any of the other buses run as planned.

If you arrive before the departure time of a bus, you can transfer to that bus. But if you arrive exactly at the departure time, you will not have enough time to get on the bus. You cannot verify ahead of time whether a given bus will run as planned – you will find out only when you try to get on the bus. So if two or more buses leave a station at the same time, you can try to get on only one of them.

image

Figure 1: Bus schedule corresponding to Sample Input 1

Consider the bus schedule shown in Figure 1. It lists the start and destination stations of several bus routes along with the departure and arrival times. You have written next to some of these the probability that that route will run. Bus routes with no probability written next to them have a 100% chance of running. You can try catching the first listed bus. If it runs, it will take you straight to the airport, and you can stop worrying. If it does not, things get more tricky. You could get on the second listed bus to station 2. It is certain to leave, but you would be too late to catch the third listed bus which otherwise would have delivered you to the airport on time. The fourth listed bus – which you can catch – has only a 0.1 probability of actually running. That is a bad bet, so it is better to stay at station 0 and wait for the fifth listed bus. If you catch it, you can try to get onto the sixth listed bus to the airport; if that does not run, you still have the chance of returning to station 0 and catching the last listed bus straight to the airport.

Input Format

image

image

Constraints

.

Output Format

image

SAMPLE OUTPUT

0.3124

Sample Input 0

8 4
1000
0 1 0 900 0.2
0 2 100 500 1.0
2 1 500 700 1.0
2 1 501 701 0.1
0 3 200 400 0.5
3 1 500 800 0.1
3 0 550 650 0.9
0 1 700 900 0.1

Sample Output 0

0.3124

Your nemesis, the dashingly handsome spy Waco Powers, has at last fallen to your secret volcano base’s deathtraps (or so you assume, being a little too busy to witness it firsthand). At long last, you are all set to CONQUER THE PLANET!

Nothing will stand in your way! Well, nothing except a minor problem of logistics. Your evil armies have announced that they will not continue carving their relentless path of destruction across the puny nations of the world without being paid. And unfortunately you are running low on cash – a volcano lair has many wonderful qualities, but “reasonably affordable” is not one of them. You have had to pull funds from the travel budget to pay your ungrateful underlings. Now you are not sure how you will actually get your armies into position to CONQUER THE PLANET.

You have a map of the nations of the world and all your available transport routes between them. Each route connects two nations and has a fixed cost per army that uses it. The routes are laid out such that there is exactly one way to travel between any two nations. You know the current position of each of your armies and how many you will need to place permanently in each nation in order to subjugate it. How can you move the armies into place as cheaply as possible so you can CONQUER THE PLANET?

Input Format

image

Constraints

.

Output Format

Display the minimum cost to move your armies such that there are at least yi armies in nation i for all i.

Sample Input 0

3
1 2 5
3 1 5
2 1
5 0
1 3

Sample Output 0

15


