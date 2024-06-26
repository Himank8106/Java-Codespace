# [Problem: Chef and Stones](https://www.codechef.com/problems/CHEFSTON)

Chef is playing a game. Currently in the game, he is at a field full of stones. There are total N kinds of stones. There is unlimited supply of each kind of stone.

Chef knows that one stone of kind i needs A<sub>i</sub> minutes to pick it from the ground and it will give Chef a profit of B<sub>i</sub> Rs.

Chef has K minutes of free time. During this free time, Chef want to pick stones so as to maximize his profit. But he can not pick stones of different kinds, he has to pick stones of a single kind.

Please help Chef to find the maximal possible profit.

## Input

- First line contains single integer T denoting the number of test cases.
- First line of each test case contains two integers N and K.
- Next line contains N integers A<sub>i</sub> denoting the time needed to pick one stone of kind i.
- Next line contains N integers B<sub>i</sub> denoting the profit due to picking i<sub>th</sub> stone.

## Constraints

- 1 ≤ T ≤ 5
- 1 ≤ N ≤ 10<sup>5</sup>
- 1 ≤ K ≤ 10<sup>9</sup>
- 1 ≤ A<sub>i</sub>, B<sub>i</sub> ≤ 10<sup>9</sup>

## Output

For each test case, print a single line containing maximal possible profit.

## Sample

- Input:
```
1
3 10
3 4 5
4 4 5
```

- Output:
```
12
```

## Explanation

If Chef picks stones of first kind he can pick 3 stones, he will get a profit of 3*4 = 12 Rs. If Chef picks stones of second kind he can pick 2 stones, he will get a profit of 2*4 = 8 Rs. If Chef picks stones of third kind he can pick 2 stones, he will get a profit of 2*5 = 10 Rs.

So the maximum possible profit is 12.
