# Erick-Sorting-Arrays

  #include <iostream>
  usinf namespace std; 
  
  void buubleSort(int a[], int size)
  {
    for(int i=0; i<size; i++)
    {
       for (int j=0;j<size;j++)
       {
          if(a[i]<a[j])
          {
            int temp = a[i];
            a[i] = a[j];
            a[j] = temp;
           }
         }
       cout << endl <<"Pass " << (i+1) << ": "<< endl;
       for(int k=0; k<8; k++)
       cout<<a[k]<<" ";
      }
    }
 
                        
             
