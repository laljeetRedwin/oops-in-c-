// # oops-in-c-
//addition of Array in c++

class Solution{
    public:
    int getSum(int a[], int n) {
        // Your code goes here
        int sum=0;
        for(int i=0;i<n;i++){
            sum = sum+a[i];
        }
        return sum;
    }   
};
