# CCC
Various dynamic programming questions are solved here

Problem description for R 101: 
Marc loves cupcakes, but he also likes to stay fit. He eats n cupcakes in one sitting, and each cupcake i has a calorie count c[i] . After eating a cupcake with c calories, he must walk at least 2^j * c (where j is the number cupcakes he has already eaten) miles to maintain his weight.
Given the individual calorie counts for each of the cupcakes, find and print a long integer denoting the minimum number of miles Marc must walk to maintain his weight. Note that he can eat the cupcakes in any order.

Notes: Has to be done greedily so that you have to burn as less calories as possible

Input Format

The first line contains an integer, N , denoting the number of cupcakes. The second line contains N space-separated integers describing the respective calorie counts of each cupcake,c[1]...c[n].

Constraints

1<=n<=40 1<=ci<=1000

Output Format

Print a long integer denoting the minimum number of miles Marc must walk to maintain his weight.







Problem description for R 102:
Given an array of N integers, your task is to print the highest possible product by multiplying any three numbers from the array.

Input Format

First line contains an integer N.
Next line contains N space separated integers.

Constraints

1 <= N <= 106
0 <= |Ai| <= 103

Output Format

Output one numbers, the maximum product.






Problem description for R 103:
Pucca and Garu are playing a card game that is explained as follows :
1. N number of cards are placed in a straight line.
2. Cards are numbered 1 to N from left to right and the ith card has a number Ai written on it.
3. Pucca plays first, then Garu, then Pucca and so on.
4. In each turn a player can choose one card, either the rightmost card or the leftmost card.
5. Whatever card a player chooses, the number on that card is added to the players score and the card is removed from the game.
6. The game ends when there are no other cards to pick.
7. At the end of the game, the player with the maxmimum score wins.
8. If both players have equal scores, then Pucca wins.

Pucca and Garu are feeling lazy on this sunday afternoon and have asked you to write a program to determine who the winner of the game will be.

INPUT

First line contains the number of cards N. (1 <= N <= 105)
Second line contains N space separated integers, ith of them denoting Ai. (1 <= Ai <= 106)

OUTPUT

Print "Pucca" (without quotes) if Pucca wins or "Garu" (without quotes) if Garu wins.










