- š Hi, Iām @Faizannnn666
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Faizannnn666/Faizannnn666 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You  can now acces azharali___x link to take a look at your changes.
--->
// C++ program to demonstrate the working 
// of a COPY CONSTRUCTOR 
#include <iostream> 

using namespace std; 

  

class Point { 

private: 

    int x, y; 

  

public: 

    Point(int x1, int y1) 

    { 

        x = x1; 

        y = y1; 

    } 

  

    // Copy constructor 

    Point(const Point& p1) 

    { 

        x = p1.x; 

        y = p1.y; 

    } 

  

    int getX() { return x; } 

    int getY() { return y; } 
}; 

  

int main() 
{ 

    Point p1(10, 15); // Normal constructor is called here 

    Point p2 = p1; // Copy constructor is called here 

  

    // Let us access values assigned by constructors 

    cout << "p1.x = " << p1.getX() 

         << ", p1.y = " << p1.getY(); 

    cout << "\np2.x = " << p2.getX() 

         << ", p2.y = " << p2.getY(); 

  
