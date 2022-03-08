# binary_search

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
