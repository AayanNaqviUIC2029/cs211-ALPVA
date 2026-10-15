# cs211-ALPVA
//Devilseyeee: Parth Patil
//662415581
//CS
//I chose the stairs question
URL: https://www.geeksforgeeks.org/problems/count-ways-to-nth-stairorder-does-not-matter5639/1?utm_source=geeksforgeeks&utm_medium=article_practice_tab&utm_campaign=article_practice_tab
class Solution {
  public:
    int nthStair(int n) {
        //  Code here
        int num = n;
        int final = nHelper(n, num);
        return final;
    }
    
    int nHelper(int n, int num){
        if(num==0||n==1){
            return 1;
        }
        else if(num<0){
            return 0;
        }
return 1 + nthStair(n - 2);    }
};


## Topics I'm Working On

| Topic | Confidence |
|-------|------------|
| Pointers | Medium |
| Recursion | High |
