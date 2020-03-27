# currency

#include <iostream>

#include <iomanip>

#include <conio.h>

#include <string>

 

using namespace std;

 

int main()

{

  int dollar;

  float INR;

  string str;

  cout<<"Enter currency code"<<endl;

  cin>>str;

  if(str=="CAD")

  {

      cout<<"Enter no. of dollars"<<endl;

      cin>>dollar;

      INR=dollar*52.08;

      cout<<"Canada dollar"<<dollar<<"equal to"<<INR<<"Indian rupee"<<endl;

  }

  else if(str=="HKD")

  {

      cout<<"Enter no. of dollars"<<endl;

      cin>>dollar;

      INR=dollar*8.86;

      cout<<"Hong Kong dollar"<<dollar<<"equal to"<<INR<<"Indian rupee"<<endl;

}

else if(str=="SGD")

{

     cout<<"Enter no. of dollars"<<endl;

     cin>>dollar;

     INR=dollar*51.29;

     cout<<"Singapore dollars"<<dollar<<"equals to"<<INR<<"Indian rupee"<<endl;

}

else if(str=="USD")

{

     cout<<"Enter no. of dollars"<<endl;

     cin>>dollar;

     INR=dollar*69.55;

     cout<<"USA dollars"<<dollar<<"equals to"<<INR<<"Indian rupee"<<endl;

}

else

{

     cout<<"Invalid currency code"<<endl;

}

getch();

return 0;

}

 

