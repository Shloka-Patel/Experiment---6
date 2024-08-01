# Experiment---6

Aim -> To study and implement C++ deciision making statements loops.<br> 

Software -> Visual Studio Code<br> 

Theory -><br> 

Code:<br> 

(A) <br> 
```
#include<iostream>
using namespace std;
int main(){
    int i;
    for (i=0;i<10;i++) {
    cout<<"HELLO WORLD("<<i+1<<")"<<"\n";
    }
    return 0;
}
```

(B)<br>
```
#include<iostream>
using namespace std;

int main()
{
    int i;
    cout<<"Enter a number: "<<"\n";
    cin>>i;
    while(i<=10)
    {
        cout<<" "<<"\n"<<i++;
    
    }
    return 0;
}
```

(C)<br>
```
#include<iostream> 
using namespace std;

int main() 
{
    int a=0;
    do {
        cout<< a << "\n";
        a=a+2;
    }
    while (a<=50); 
    return 0; 
}
```

(D)<br>
```
```

(E)<br> 
```
```

(F) <br> 
```
```

(G)<br> 
```

#include<iostream>
using namespace std;
int main(){
    int i,j,k=0,n;
    cout<<"Enter number of rows:";
    cin>>n;
    for(i=1;i<=n;i++)
    {
        for (j=1;j<=(n-1);j++)
        {
            cout<<" ";
        }
        while(k!=(2*i-1))
        {
            cout<<"* ";
            k++;
        }
        k=0;
        }
        cout<<"end1";
    
} 
```

Output: <br> 

(A)<br> 
![](https://github.com/Shloka-Patel/Experiment---6/blob/main/Output_6A.png)

(B)<br>
![](https://github.com/Shloka-Patel/Experiment---6/blob/main/Output_6B.png)

(C)<br>
![]()

(D)<br>
![]()

(E)<br>
![]()

(F)<br>
![]()

(G)<br> 
![](https://github.com/Shloka-Patel/Experiment---6/blob/main/Output_6(G)%20.png) 

Conclusion -> <br> 
