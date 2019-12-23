/*題目要求恰好為一個費氏數列，但改用陣列記錄的方法去執行減少時間的計算(PS:n=46時會超出範圍)*/
class Solution {
    public int climbStairs(int n) {
        
        if(n==1) return 1;
        
        int[] count_record = new int[n+1];
        count_record[1]=1; // 1
        count_record[2]=2; // 1+1 , 2
        
        for(int i=3;i<=n;i++){
             count_record[i]= count_record[i-1]+ count_record[i-2];
        }
        return  count_record[n];
    }
}
