//this program belongs to Ramin Roufeh

//Lab: Sales Bar chart

#include <iostream>
using namespace std;

int main()
{
 
   //Display my name header on the screen.

   cout << " /+++++++++++++++++++++++++++++++\\ "  << endl;
   cout << " {{        Ramin Roufeh         }} "  << endl;
   cout << " {{{     Sales Bar charge  }}} "  << endl;
 
   cout <<" ++++++++++++++++++++++++++++++++++++ " << endl;
   cout << endl;
   
   float store1,store2,store3,store4,store5;
   int stars1,stars2,stars3,stars4,stars5;
   double total;
   char repeat;
   
   do
   {
      

      cout<<"\nPlease Enter today's sales for store 1: ";
      cin>>store1;
	  cout<<endl;
      
	  if( ((store1/100) + 0.5) >= (int(store1/100) + 1) )
      stars1 = int(store1/100)+1;
      else
      stars1 = int(store1/100); 
      
      cout<<"Please Enter today's sales for store 2: ";
      cin>>store2;
	  cout<<endl;

      if( ((store2/100) + 0.5) >= (int(store2/100) + 1) )
      stars2 = int(store2/100)+1;
      else
      stars2 = int(store2/100); 
     
      cout<<"Please Enter today's sales for store 3: ";
      cin>>store3;
      cout<<endl;

      if( ((store3/100) + 0.5) >= (int(store3/100) + 1) )
      stars3 = int(store3/100)+1;
      else
      stars3 = int(store3/100); 

      cout<<"Please Enter today's sales for store 4: ";
      cin>>store4;
	  cout<<endl;

      if( ((store4/100) + 0.5) >= (int(store4/100) + 1) )
      stars4 = int(store4/100)+1;
      else
      stars4 = int(store4/100); 

      cout<<"Please Enter today's sales for store 5: ";
      cin>>store5;
	  cout<<endl;

      if( ((store5/100) + 0.5) >= (int(store5/100) + 1) )
      stars5 = int(store5/100)+1;
      else
      stars5 = int(store5/100); 
      

      cout<<"\nSALES BAR CHART"<<endl;
      cout<<"Each * = $100"<<endl;
      
      cout<<"\nstore 1: ";
      for(int i = 0;i<(stars1);i++)
      {cout<<"*";}
     
      cout<<"\nstore 2: ";
      for(int i = 0;i<(stars2);i++)
      {cout<<"*";}
      
      cout<<"\nstore 3: ";
      for(int i = 0;i<(stars3);i++)
      {cout<<"*";}
      
      cout<<"\nstore 4: ";
      for(int i = 0;i<(stars4);i++)
      {cout<<"*";}
      
      cout<<"\nstore 5: ";
      for(int i = 0;i<(stars5);i++)
      {cout<<"*";}

      total = store1 + store2 + store3 + store4 + store5;
      cout <<"\n\nTotal amout of sale of 5 stores is $"<<total<<endl;

      cout<<"\n Do You want to enter sales again (Y/N)?"<<endl;
      cin>>repeat;
   } 
   while( repeat == 'Y' || repeat == 'y');


   return 0;

}
