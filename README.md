# lecture-11

rising star while loop

#include <iostream>
#include <string>
using namespace std;
int main()
{
	int i = 1, j = 1;
	while (i <= 5)
	{
		j = 1;
		while (j <= i)
		{
			cout << "*"; //print 5 stars
			j++;
		}
		cout << endl;
		i++;
	}

}
  
  falling stars while loop
 
  #include <iostream>
#include <string>
using namespace std;
int main()
{
	int i = 1, j = 1;
	while (i <= 5)
	{
		j = i;
		while (j <= 5)
		{
			cout << "*"; //print 5 stars
			j++;
		}
		cout << endl;
		i++;
	}

}
  
  rising and fall stars while loop
  
  #include <iostream>
#include <string>
using namespace std;
int main()
{
	int i = 1, j = 1;
	while (i <= 5)
	{
		j = 1;
		while (j <= i)
		{
			cout << "*"; //print 5 stars
			j++;
		}
		cout << endl;
		i++;
	}


	int x = 1, y = 1;
	while (x <= 5)
	{
		y = x;
		while (y <= 5)
		{
			cout << "*"; //print 5 stars
			y++;
		}
		cout << endl;
		x++;
	}
}
  
  
  table for loop
  
  #include <iostream>
#include <string>
using namespace std;
int main()
{
	int y;
	cout << "Enter a number you want the table of: " << endl;
	cin >> y;
	while (cin.fail())
	{
		cout << "Invalid command enter the numbers again: " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> y;
	}
	for (int x=0; x<= 10; x++)
	{
		cout << y << " x " << x << " = " << y * x << endl;
		
	}

}
                                                     
                                                     
 factorial while loop
                                                     
 #include <iostream>
#include <string>
using namespace std;
int main()
{
    cout << "Enter the number for factorial\n";
    int x, fact=1;
    cin >> x;
    for (int y = x; y > 0; y--)
    {
       fact = y*fact;
    }
    cout << "The factorial is: " << fact;
}                                                    
