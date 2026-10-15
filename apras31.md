# CS 211

- **NetID:** apras31
- **Major:** CS
- **Question that I chose from the memoization exercise:** Count Ways to reaach the n'th stair
- **Link to the question article:** (https://www.geeksforgeeks.org/problems/count-ways-to-nth-stairorder-does-not-matter5639/1?utm_source=geeksforgeeks&utm_medium=article_practice_tab&utm_campaign=article_practice_tab)
- **My solution:**

class Solution {
  public:
    int nthStair(int n) {
        //  Code here
        if(n < 0){
            return 0;
        }
        if(n == 0){
            return 1;
        }
        return 1 + nthStair(n-2);
    }
};

