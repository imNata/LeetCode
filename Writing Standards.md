**Follow this template**

# Approach
Explain the intution here
**Example:** As the question says we have to find the total number of odds number in between the range, we can first increment lower bound and decrement the upper bound. And, then subtract new lower and upper bound and divide it by 2. This would give us the total number of odd numbers in the range. But, as we have decremented and incremented a point. So we will check for those 2 points again and if they are odd, then increment the number of oddsFound.


## Example & Explanation (optional)
Can explain using the sample test case.

# Algorithm
Explain the Algorithm
**Example**
**Step1:** Init the oddFound = 0.
**Step2:** Increment if the lower and upper bound are odd.
**Step3:** Increment the lower bound by 1 and decrement the upper bound by 1. After that subtract both of them and divide by two. Store the result in oddFound.
**Step4:** Return the oddFound.

# Code
```
//Code Here
```

# Snapshot (optional)
Snapshot of submission 

**Other Things to consider**
![image](https://user-images.githubusercontent.com/98302924/166709133-09d039e4-da6d-41ec-b377-331097466fdf.png)
* Write "Using Approach"
Example: using map and vector
