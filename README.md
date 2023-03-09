##include <iostream>

using namespace std;

int main()
{
 int *a = new int (50);
 cout << "adress \t *a\n";
 (*a)++;adress   *a
 cout << a << "\t" << *a << endl; 
 *(a++);
 cout << a << "\t" << *a << endl;
 *a++;
 cout << a << "\t" << *a << endl;
    return 0;
}




adress   *a
0x55cf2162beb0  51
0x55cf2162beb4  0
0x55cf2162beb8  0
