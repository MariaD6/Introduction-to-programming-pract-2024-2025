
TASK 1

#include <iostream>
using namespace std;
int main() {
    double starting_sum,interest,years,final_amount ;
    cout << " Please enter thestarting sum ";
    cin >> starting_sum;

    cout << "Please enter the interest";
    cin >> interest;

    cout << "Please enter the years";
    cin >> years;

    final_amount = starting_sum * (1 + interest/100 * years);
   
    cout << "The full amount after "<< years << "years is :"<<final_amount<< "leva"<<endl;
}

TASK2
#include <iostream>
#include <cmath> 
using namespace std;

int main() {
    double t, h, td;

    cout << "Please enter the temperature : ";
    cin >> t;

    cout << "Please enter the relative humidity:   ";
    cin >> h;

    td = t - ((100 - h) / 5.0);

    cout << "Dew point: " << td << endl;

    
}

TASK 3

#include <iostream>
#include <math.h>

using namespace std;

int main()
{
    double a,s,t;
    cout << "Please enter the acceleration : ";
    cin >> a ;

    cout << "Please enter the target distance :";
    cin >> s;
     
    t = sqrt((2 * s) / a );

    cout << " the time is :  " << t << endl;

    
}

TASK 4
#include <iostream>
using namespace std;

int main() {
    double Q,m,Q_kJ;
    cout <<"please enter the mass ";
    cin >>m;
    const double λ = 334000;

    Q = λ * m;
    Q_kJ = Q / 1000; 

    cout << " The required heat is: " << Q << " J = " << Q_kJ << " kJ" << endl;

   
}

TASK 5
#include <iostream>
using namespace std;

int main() {
  double euro,leva,leva_after_fees,exchange_rate;
  cout << "please enter the amount in euro";
  cin >> euro;

  cout << " please enter the exchange rate ";
  cin >> exchange_rate;

  leva = euro *  exchange_rate;

  leva_after_fees = leva * 0.98;

  cout << "The in leva is :" << leva << "leva" << endl;
  cout << "After 2% exchange rate you will recive: " << leva_after_fees << "leva"<< endl;

 

}

TASK 6
#include <iostream>
#include <cmath>
using namespace std;

int main(){
    const double R = 6371.0;
    const double PI = 3.14;
    double D,width,lenght;
    cout << "Please enter the width: ";
    cin >> width;
    cout << "Please enter the lenght: ";
    cin >> lenght;
    D = 2 * R * sin((width - lenght)/2);
    cout << "the approximate distance is: " << D << "km" << endl;
    

  
}
TASK7
#include <iostream>
using namespace std;

int main() {
  double U,R,I,P;

  cout << "Please enter the voltage: ";
  cin >> U;
  cout << " Please enter the resistence: ";
  cin >> R;

  I = U / R;
  P = U * I;

  cout << "The current is : " << I << "A "<< endl;
  cout << "The power is : " << P << "W" << endl;
  
  
}
TASK 8 
#include <iostream>
using namespace std;

int main(){
   const double density = 2400.0;
   double length,width,height;
   double volume,mass_of_the_block,weight;
   
   cout << "Please enter the lenght: ";
   cin >> length;

   cout << "Please enter the width: ";
   cin >> width;

   cout << "Please enter the height : ";
   cin >> height;
   volume = length * width * height;
   mass_of_the_block = volume * density;
   weight = mass_of_the_block * 9.81; 

   cout << "The volume is : " << volume << endl;
   cout << " The mass is : " << mass_of_the_block << endl;
   cout << "The weight is : " << weight << endl;
   
}
TASK 9
#include <iostream>
using namespace std;

int main() 
{
    double km,time,speed_in_kmh;

    cout << "Please enter the kilometers traveled: ";
    cin >> km;

    cout << "Plese enter the time for the trip: ";
    cin >> time;
   
    speed_in_kmh = km/time;

    cout << "the avarage speed is : " << speed_in_kmh << endl;

    
    


}


TASK 10
#include <iostream>
using namespace std;

int main() {
 double price_for_one_product,number_of_products,price_for_manifacture;
 double profit,profitability;
 
 cout <<" Please enter the price";

 cin >> price_for_one_product;

 cout << "Please enter the number";
 cin >> number_of_products;

 cout << " Please enter the price for manifacture";
 cin >> price_for_manifacture;

 profit =  price_for_one_product * number_of_products - price_for_manifacture;
 profitability = (profit/price_for_manifacture)*100;
 
 cout << "The profit is : " << profit << endl;
 cout << "The profitability is : " << profitability << endl;



}
