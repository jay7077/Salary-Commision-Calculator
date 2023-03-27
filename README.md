#include <iostream>
using namespace std;

int main()

{
   double sales, baseSalary, commission, gross_pay, fica, federal, net_pay;

    cout << "Enter base salary: ";
    cin >> baseSalary;
    
    cout << "Enter sales amount: ";
    cin >> sales;
    
   commission = 0 * sales;
   gross_pay = baseSalary;
   fica = 0.0765 * gross_pay;
   federal = 0.25 * gross_pay;
   net_pay = gross_pay - federal - fica;
    
   cout << "Base Salary: $" << baseSalary << endl;
   cout << "Commission: $" << commission << endl;
   cout << "Gross Pay: $" << gross_pay << endl;
   cout << "FICA: $" << fica << endl;
   cout << "Federal Withholding: $" << federal << endl;
   cout << "Net Pay: $" << net_pay << endl;

   return 0;
}
