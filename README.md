# Magical-Candy-Bags
<h1>Magical Candy Bags problem using C++</h1>
<p>Facebook coding interview practice Magical Candy Bags in C++ [<a href="https://www.facebookrecruiting.com/portal/coding_practice_question/?problem_id=513590792640579">https://www.facebookrecruiting.com/portal/coding_practice_question/?problem_id=513590792640579</a>]</p>
<p>You have N bags of candy. The ith bag contains arr[i] pieces of candy, and each of the bags is magical!</p>
<p>It takes you 1 minute to eat all of the pieces of candy in a bag (irrespective of how many pieces of candy are inside), and as soon as you finish, the bag mysteriously refills. If there were x pieces of candy in the bag at the beginning of the minute, then after you've finished you'll find that floor(x/2) pieces are now inside.
You have k minutes to eat as much candy as possible. How many pieces of candy can you eat?</p>
<h3>Signature</h3>
int maxCandies(int[] arr, int K)
<h3>Input</h3>
1 ≤ N ≤ 10,000</n>
1 ≤ k ≤ 10,000</n>
1 ≤ arr[i] ≤ 1,000,000,000</n>
<h3>Output</h3>
A single integer, the maximum number of candies you can eat in k minutes.</n>
<h3>Example 1</h3>
N = 5 </n>
k = 3</n>
arr = [2, 1, 7, 4, 2]</n>
output = 14</n>
<p>In the first minute you can eat 7 pieces of candy. That bag will refill with floor(7/2) = 3 pieces.</p>
<p>In the second minute you can eat 4 pieces of candy from another bag. That bag will refill with floor(4/2) = 2 pieces.</p>
<p>In the third minute you can eat the 3 pieces of candy that have appeared in the first bag that you ate.</p>
<p>In total you can eat 7 + 4 + 3 = 14 pieces of candy.</p>
