	# Computing-Homework

Task 1: 
  
	#include <iostream>
	using namespace std;

	int main()
	{
	    int number = 12, remainder;
	    cout << "enter the number : ";
	    cin >> number;
	    remainder = number % 2;
	    if (remainder == 0) {
		cout << number << "is it a even integer";
	    }else{
		cout << number << "is it a odd integer";
	    }



	}


 Task 2:

	  #include<iostream>
	using namespace std;

	int main()
	{
		int number = 4;
		cout << "enter the number needed to be checked : ";
		cin >> number;
		if (number >= 0) {
			cout << number << "is a positive number";
		}else{
			cout << number << "is a negative number";

		}

	}


 Task 3: 

	  #include<iostream>
	using namespace std;

	int main()
	{
		int purchaseprice = 1250, saleprice = 1000, loss = 250;
		cout << "enter purchaseprice of item : ";
		cin >> purchaseprice;
		cout << "enter saleprice of item : ";
		cin >> saleprice;

		loss = purchaseprice - saleprice;

		if (loss > 0) {
			cout << "profit : " << loss;
		}
		else {
			if (loss < 0) {
				cout << "loss : " << -(loss);
			}
			else {
				cout << "no profit no loss";
			}

		}
	}

 Task 4:

	    #include<iostream>
	using namespace std;

	int main()
	{
		int shapeSides;
		cout << "enter the sides of the shape : ";
		cin >> shapeSides;

		if (shapeSides == 3) {
			cout << "this is a triangle";

		}else{
			if (shapeSides == 4) {
				cout << "this is a square";

			}else{
				if (shapeSides == 5) {
					cout << "this is a pentagon";

				}else{
					if (shapeSides == 6) {
						cout << "this is a hexagon";

					}
					else {
						if (shapeSides == 7) {
							cout << "this is a heptagon";

						}else{
							if (shapeSides == 8) {
								cout << "this is a octagon";

							}
							else {
								if (shapeSides == 9) {
									cout << "this is a nonagon";

								}
								else {
									if (shapeSides == 10) {
										cout << "this is a decagon";


									}
								}
							}
						}
					}
				}
			}

		}
	}


