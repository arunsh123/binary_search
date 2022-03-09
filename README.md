# binary_search

In this Binary Search we search an element in an array.
For Binary Search it is compulsory that array is in sorted order and then we divide array in two part from middle and check that our searching element (key) is smaller or greater then our middle element if it is smaller than go to right part of array, otherwise left. And recursively call function until we get key . 

Code of Binary Search is given below.

For more Knowledge visit [Geeksforgeeks](https://www.geeksforgeeks.org/linear-search/)

int main()
{
    
    vector<int> arr = {59,64,57,82,13,10};
     
   
    if (binary_search(arr.begin(), arr.end(), 15))
       cout << "15 exists in vector";
    else
       cout << "15 does not exist";
      
    cout << endl;
     
    
    if (binary_search(arr.begin(), arr.end(), 23))
         cout << "23 exists in vector";
    else
         cout << "23 does not exist";
      
    cout << endl;   
}
