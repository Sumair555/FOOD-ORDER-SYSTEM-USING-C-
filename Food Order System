#include <iostream>
#include <random>
#include <fstream>
#include <sstream>
#include <cstdlib>
#include <thread>
#include <chrono>
using namespace std;

int itemchoice,items, quantity;
class Icecream
{
	public:
	int price;
		string i1 ="Butterscotch" ,i2="Vanilla" ,i3="Chocolate" ,i4="Strawberry";
		void get_icecream()
		{
			icecream:
			 cout<<"\n\n"<<endl;
             cout<<"\t\t\t\t\033[44m\033[37m╔───────────────────────────────────────────────────────────────────────╗"<<endl;
             cout<<"\t\t\t\t│8888888                                                                │"<<endl;
             cout<<"\t\t\t\t│  888                                                                  │"<<endl;
             cout<<"\t\t\t\t│  888                                                                  │"<<endl;
             cout<<"\t\t\t\t│  888   .d8888b .d88b.   .d8888b 888d888 .d88b.   8888b.  88888b.d88b. │"<<endl;
             cout<<"\t\t\t\t│  888  d88P'   d8P  Y8b d88P'    888P'  d8P  Y8b     '88b 888 '888 '88b│"<<endl;
             cout<<"\t\t\t\t│  888  888     88888888 888      888    88888888 .d888888 888  888  888│"<<endl;
             cout<<"\t\t\t\t│  888  Y88b.   Y8b.     Y88b.    888    Y8b.     888  888 888  888  888│"<<endl;
             cout<<"\t\t\t\t│8888888 'Y8888P 'Y8888   'Y8888P 888     'Y8888  'Y888888 888  888  888│"<<endl;
             cout<<"\t\t\t\t╚───────────────────────────────────────────────────────────────────────╝\033[0m"<<endl;
             cout<<"\n\n"<<endl;
		    cout<<"\t\t\t\t\t\t╔═══════════════════════════════════════╗\n";
            cout<<"\t\t\t\t\t\t║              FLAVOUR                  ║ \n";
            cout<<"\t\t\t\t\t\t║═══════════════════════════════════════║\n";
			cout<<"\t\t\t\t\t\t║                                       ║ \n";
            cout<<"\t\t\t\t\t\t║        1) Butterscotch                ║ \n";
			cout<<"\t\t\t\t\t\t║                                       ║ \n";
            cout<<"\t\t\t\t\t\t║        2) Vanilla                     ║ \n";
			cout<<"\t\t\t\t\t\t║                                       ║ \n";
            cout<<"\t\t\t\t\t\t║        3) Chocolate                   ║ \n";
			cout<<"\t\t\t\t\t\t║                                       ║ \n";
            cout<<"\t\t\t\t\t\t║        4) Strawberry                  ║ \n";
			cout<<"\t\t\t\t\t\t║                                       ║ \n";
            cout<<"\t\t\t\t\t\t╚═══════════════════════════════════════╝\n";
			this_thread::sleep_for(chrono::seconds(1));
			cout<<"\n\n\t\t\t\tPlease Enter which Flavour would you like to have? : ";
			cin>>itemchoice;
		if(itemchoice>=1 && itemchoice<=4)
		{
			m:
			cout<<"\n\n\t\t\t\t╔══════════════════════════════════════════════════════════════════════════════╗\n";
            cout<<"\t\t\t\t║              SIZE                     ║              PRICE                   ║ \n";
            cout<<"\t\t\t\t║══════════════════════════════════════════════════════════════════════════════║\n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        1) Small                       ║              35                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        2) Medium                      ║              70                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        3) Large                       ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t╚══════════════════════════════════════════════════════════════════════════════╝\n";
			cout<<"\n\n\t\t\t\tPlease Enter which size would you like to have? : ";
			cin>>items;

				if(items>=1 && items<=3)
				{
					cout<<"\n\n\t\t\t\tEnter the Quantity you want to order: ";
					cin>>quantity;
				}
				else
				{
					cout<<"\n\nPlease choose a valid option!!!";
					goto m;	
				}
				switch(items)
				{
					case 1: price = 35*quantity;
					break;

					case 2: price = 70*quantity;
					break;
				
					case 3: price = 100*quantity;
					break;
				}
				switch(items)
				{
			 		case 1:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<i1;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Ice cream Bill is Rs."<<price;
			 			break;
			 		case 2:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<i2;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Ice cream Bill is Rs."<<price;
			 			break;
			 		case 3:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<i3;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Ice cream Bill is Rs."<<price;
			 			break;
			 		case 4:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<i4;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Ice cream Bill is Rs."<<price;
				 		break;
				}
			}
			else
			{
				cout<<"Please select a Vailid Option!!!\n\n";
				goto m;	
			}
		}
};
class Milkshakes: public Icecream 
{
	public:
		string m1="Chocolate",m2="Butterscotch",m3="Strawberry",m4="Pineapple",m5="Litchi",m6="BlueBerry",m7="Mango",m8="Kiwi",m9="Guava",m10="GreenApple",m11="BlackCurrent",m12="VeryBerry",m13="Vanilla",m14="Banana",m15="Belgium Chocolate",m16="Oreo/Kitkat",m17="Dry Fruits";
		void get_milkshakes()
		{
			Milkshakes:
            cout<<"\n\n"<<endl;
             cout<<"\t\t\t\t\033[44m\033[37m╔────────────────────────────────────────────────────────────────────────────────────╗"<<endl;
             cout<<"\t\t\t\t│888b     d888 d8b 888 888               888               888                       │"<<endl;
             cout<<"\t\t\t\t│8888b   d8888 Y8P 888 888               888               888                       │"<<endl;
             cout<<"\t\t\t\t│88888b.d88888     888 888               888               888                       │"<<endl;
             cout<<"\t\t\t\t│888Y88888P888 888 888 888  888 .d8888b  88888b.   8888b.  888  888  .d88b.  .d8888b │"<<endl;
             cout<<"\t\t\t\t│888 Y888P 888 888 888 888 .88P 88K      888 '88b     '88b 888 .88P d8P  Y8b 88K     │"<<endl;
             cout<<"\t\t\t\t│888  Y8P  888 888 888 888888K  'Y8888b. 888  888 .d888888 888888K  88888888 'Y8888b.│"<<endl;
             cout<<"\t\t\t\t│888   '   888 888 888 888 '88b      X88 888  888 888  888 888 '88b Y8b.          X88│"<<endl;
             cout<<"\t\t\t\t│888       888 888 888 888  888  88888P' 888  888 'Y888888 888  888  'Y8888   88888P'│"<<endl;
             cout<<"\t\t\t\t╚────────────────────────────────────────────────────────────────────────────────────╝\033[0m"<<endl;
             cout<<"\n\n\n"<<endl;
			
			cout<<"\t\t\t\t╔══════════════════════════════════════════════════════════════════════════════╗\n";
            cout<<"\t\t\t\t║              ITEMS                    ║              PRICE                   ║ \n";
            cout<<"\t\t\t\t║══════════════════════════════════════════════════════════════════════════════║\n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        1) Chocolate                   ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        2) Butterscotch                ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        3) Strawberry                  ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        4) Pineapple                   ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        5) Litchi                      ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        6) BlueBerry                   ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        7) Mango                       ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        8) Kiwi                        ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        9) Guava                       ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       10) GreenApple                  ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       11) BlackCurrent                ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       12) VeryBerry                   ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
			cout<<"\t\t\t\t║       13) Vanilla                     ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       14) Banana                      ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
			cout<<"\t\t\t\t║       15) Belgium Chocolate           ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       16) Oreo/Kitkat                 ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
			cout<<"\t\t\t\t║       17) Dry Fruits                  ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t╚══════════════════════════════════════════════════════════════════════════════╝\n";
			this_thread::sleep_for(chrono::seconds(1));
			cout<<"\n\n\t\t\t\tplease Enter which you would like to drink?: ";
			cin>>items;
			if(items<=17)
			{
				cout<<"\n\n\t\t\t\tPlease Enter Quantity: ";
				cin>>quantity;
				switch(items)
				{
					case 1: price = 80*quantity;
					break;

					case 2: price = 80*quantity;
					break;

					case 3: price = 80*quantity;
					break;
					
					case 4: price = 80*quantity;
					break;

                    case 5: price = 80*quantity;
					break;

					case 6: price = 80*quantity;
					break;

					case 7: price = 80*quantity;
					break;
					
					case 8: price = 80*quantity;
					break;

                    case 9: price = 80*quantity;
					break;

					case 10: price = 80*quantity;
					break;

					case 11: price = 80*quantity;
					break;
					
					case 12: price = 80*quantity;
					break;

                    case 13: price = 80*quantity;
					break;

					case 14: price = 80*quantity;
					break;

					case 15: price = 80*quantity;
					break;
					
					case 16: price = 100*quantity;
					break;

                    case 17: price = 100*quantity;
					break;

				}
				switch(items)
				{
			 		case 1:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m1;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 2:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m2;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 3:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m3;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 4:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m4;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
                    case 5:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m5;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 6:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m6;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 7:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m7;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 8:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m8;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
                    case 9:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m9;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 10:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m10;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 11:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m11;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 12:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m12;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
                    case 13:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m13;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 14:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m14;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 15:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m15;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
			 		case 16:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m16;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;
                    case 17:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<m17;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Milkshakes Bill is Rs."<<price;
			 			break;     
				}
 			}
			else
			{
				cout<<"Please select a Vailid Option!!!\n\n";
				goto Milkshakes;	
			}
		}	
};
class moctails: public Milkshakes
{
	public:
		string mc1="Ginger Lime",mc2="Mint Mojito",mc3="Blue Lagoon",mc4="Kokum",mc5="Pomegranage Punch",mc6="Tangy Orange",mc7="Strawberry Slush",mc8="Black Current",mc9="Lime Soda Sweet",mc10="Lime Soda Salt";
		void get_moctails()
		{
			moctails:
			cout<<"\n\n"<<endl;
             cout<<"\t\t\t\t\033[44m\033[37m╔─────────────────────────────────────────────────────────────────────────╗"<<endl;
             cout<<"\t\t\t\t│888b     d888                   888      888             d8b 888         │"<<endl;
             cout<<"\t\t\t\t│8888b   d8888                   888      888             Y8P 888         │"<<endl;
             cout<<"\t\t\t\t│88888b.d88888                   888      888                 888         │"<<endl;
             cout<<"\t\t\t\t│888Y88888P888  .d88b.   .d8888b 888  888 888888  8888b.  888 888 .d8888b │"<<endl;
             cout<<"\t\t\t\t│888 Y888P 888 d88''88b d88P'    888 .88P 888        '88b 888 888 88K     │"<<endl;
             cout<<"\t\t\t\t│888  Y8P  888 888  888 888      888888K  888    .d888888 888 888 'Y8888b.│"<<endl;
             cout<<"\t\t\t\t│888   '   888 Y88..88P Y88b.    888 '88b Y88b.  888  888 888 888      X88│"<<endl;
             cout<<"\t\t\t\t│888       888  'Y88P'   'Y8888P 888  888  'Y888 'Y888888 888 888  88888P'│"<<endl;
             cout<<"\t\t\t\t╚─────────────────────────────────────────────────────────────────────────╝\033[0m"<<endl;
             cout<<"\n\n\n"<<endl;

			 cout<<"\t\t\t\t╔══════════════════════════════════════════════════════════════════════════════╗\n";
            cout<<"\t\t\t\t║              ITEMS                    ║              PRICE                   ║ \n";
            cout<<"\t\t\t\t║══════════════════════════════════════════════════════════════════════════════║\n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        1) Ginger Lime                 ║              60                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        2) Mint Mojito                 ║              60                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        3) Blue Lagoon                 ║              60                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        4) Kokum                       ║              60                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        5) Pomegranate Punch           ║              60                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        6) Tangy Orange                ║              60                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        7) Strawberry Slush            ║              60                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        8) Black Current               ║              60                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        9) Lime Soda Sweet             ║              40                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       10) Lime Soda Salt              ║              40                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
			cout<<"\t\t\t\t╚══════════════════════════════════════════════════════════════════════════════╝\n";
			this_thread::sleep_for(chrono::seconds(1));
			cout<<"\n\n\t\t\t\tplease Enter which you would like to drink?: ";
			cin>>items;
			if(items>=1 && items<=10)
			{
				cout<<"\n\n\t\t\t\tPlease Enter Quantity: ";
				cin>>quantity;
				switch(items)
				{
                    case 1: price = 60*quantity;
					break;

					case 2: price = 60*quantity;
					break;

					case 3: price = 60*quantity;
					break;
					
					case 4: price = 60*quantity;
					break;

                    case 5: price = 60*quantity;
					break;

					case 6: price = 60*quantity;
					break;

					case 7: price = 60*quantity;
					break;
					
					case 8: price = 60*quantity;
					break;

                    case 9: price = 40*quantity;
					break;

					case 10: price = 40*quantity;
					break;
				}
				switch (items)
				{
			 		case 1:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc1;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
			 		case 2:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc2;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
			 		case 3:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc3;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
			 		case 4:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc4;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
                    case 5:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc5;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
			 		case 6:
			 		    cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc6;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
			 		case 7:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc7;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
			 		case 8:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc8;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
                    case 9:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc9;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
			 		case 10:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<mc10;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Mocktails Bill is Rs."<<price;
			 			break;
				}
			}
			else
			{
				cout<<"Please select a Vailid Option!!!\n\n";
				goto moctails;	
			}	
		}	
};

class thickshakes: public moctails
{
	public:
		string t1="Chocolate",t2="Butterscotch",t3="Strawberry",t4="Pineapple",t5="Litchi",t6="BlueBerry",t7="Mango",t8="Kiwi",t9="Guava",t10="GreenApple",t11="BlackCurrent",t12="VeryBerry",t13="Vanilla",t14="Banana",t15="Belgium Chocolate",t16="Oreo/Kitkat",t17="Dry Fruits";
		void get_thickshakes()
		{
			thickshakes:
			cout<<"\n\n"<<endl;
             cout<<"\t\t\t\033[44m\033[37m╔────────────────────────────────────────────────────────────────────────────────────────────────╗"<<endl;
             cout<<"\t\t\t│88888888888 888      d8b          888               888               888                       │"<<endl;
             cout<<"\t\t\t│    888     888      Y8P          888               888               888                       │"<<endl;
             cout<<"\t\t\t│    888     888                   888               888               888                       │"<<endl;
             cout<<"\t\t\t│    888     88888b.  888  .d8888b 888  888 .d8888b  88888b.   8888b.  888  888  .d88b.  .d8888b │"<<endl;
             cout<<"\t\t\t│    888     888 '88b 888 d88P'    888 .88P 88K      888 '88b     '88b 888 .88P d8P  Y8b 88K     │"<<endl;
             cout<<"\t\t\t│    888     888  888 888 888      888888K  'Y8888b. 888  888 .d888888 888888K  88888888 'Y8888b.│"<<endl;
             cout<<"\t\t\t│    888     888  888 888 Y88b.    888 '88b      X88 888  888 888  888 888 '88b Y8b.          X88│"<<endl;
             cout<<"\t\t\t│    888     888  888 888  'Y8888P 888  888  88888P' 888  888 'Y888888 888  888  'Y8888   88888P'│"<<endl;
             cout<<"\t\t\t╚────────────────────────────────────────────────────────────────────────────────────────────────╝\033[0m"<<endl;
             cout<<"\n\n"<<endl;
			
			cout<<"\t\t\t\t╔══════════════════════════════════════════════════════════════════════════════╗\n";
            cout<<"\t\t\t\t║              ITEMS                    ║              PRICE                   ║ \n";
            cout<<"\t\t\t\t║══════════════════════════════════════════════════════════════════════════════║\n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        1) Chocolate                   ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        2) Butterscotch                ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        3) Strawberry                  ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        4) Pineapple                   ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        5) Litchi                      ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        6) BlueBerry                   ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        7) Mango                       ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        8) Kiwi                        ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        9) Guava                       ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       10) GreenApple                  ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       11) BlackCurrent                ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       12) VeryBerry                   ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
			cout<<"\t\t\t\t║       13) Vanilla                     ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       14) Banana                      ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
			cout<<"\t\t\t\t║       15) Belgium Chocolate           ║              100                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       16) Oreo/Kitkat                 ║              120                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
			cout<<"\t\t\t\t║       17) Dry Fruits                  ║              120                     ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t╚══════════════════════════════════════════════════════════════════════════════╝\n";
			this_thread::sleep_for(chrono::seconds(1));
			cout<<"\n\n\t\t\t\tplease Enter which you would like to drink?: ";
			cin>>items;
				if(items>=1 && items<=17)
				{
					cout<<"\n\t\t\t\tEnter the quantity of juices that you want : ";
					cin>>quantity;
					switch(items)
					{
					case 1: price = 100*quantity;
					break;

					case 2: price = 100*quantity;
					break;

					case 3: price = 100*quantity;
					break;
					
					case 4: price = 100*quantity;
					break;

                    case 5: price = 100*quantity;
					break;

					case 6: price = 100*quantity;
					break;

					case 7: price = 100*quantity;
					break;
					
					case 8: price = 100*quantity;
					break;

                    case 9: price = 100*quantity;
					break;

					case 10: price = 100*quantity;
					break;

					case 11: price = 100*quantity;
					break;
					
					case 12: price = 100*quantity;
					break;

                    case 13: price = 100*quantity;
					break;

					case 14: price = 100*quantity;
					break;

					case 15: price = 100*quantity;
					break;
					
					case 16: price = 120*quantity;
					break;

                    case 17: price = 120*quantity;
					break;
					}
					switch(items)
					{
			 			case 1:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t1;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 2:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t2;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 3:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t3;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 4:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t4;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
                    case 5:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t5;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 6:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t6;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 7:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t7;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 8:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t8;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
                    case 9:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t9;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 10:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t10;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 11:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t11;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 12:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t12;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
                    case 13:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t13;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 14:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t14;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 15:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t15;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
			 		case 16:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t16;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;
                    case 17:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<t17;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour thickshakes Bill is Rs."<<price;
			 			break;	
					}
 				}
 				else
 				{
 					cout<<"Please select a Vailid Option!!!\n\n";
					goto thickshakes;		
				}
		}
};

class Coffee: public thickshakes
{
	public:
		string name,c1="Coffee", c2="Filter", c3="Nutty Hazzzlenut",c4 ="Wild Vanilla",c5="Creamy Caramel", c6="Ice Mint", c7="Espresso",c8 ="Smoky cinnamon",c9="Double chocolate mocha", c10="Blueberry chocolate mocha", c11="Mint chocolate mocha",c12 ="Cold Coffee";
		void get_coffee()
		{
			Coffee:
			 cout<<"\n\n"<<endl;
             cout<<"\t\t\t\t\t\t\033[44m\033[37m╔──────────────────────────────────────────────────╗"<<endl;
             cout<<"\t\t\t\t\t\t│ .d8888b.            .d888  .d888                 │"<<endl;
             cout<<"\t\t\t\t\t\t│d88P  Y88b          d88P'  d88P'                  │"<<endl;
             cout<<"\t\t\t\t\t\t│888    888          888    888                    │"<<endl;
             cout<<"\t\t\t\t\t\t│888         .d88b.  888888 888888 .d88b.   .d88b. │"<<endl;
             cout<<"\t\t\t\t\t\t│888         d88""88b  888    888   d8P  Y8b d8P  Y8b│"<<endl;
             cout<<"\t\t\t\t\t\t│888    888 888  888 888    888   88888888 88888888│"<<endl;
             cout<<"\t\t\t\t\t\t│Y88b  d88P Y88..88P 888    888   Y8b.     Y8b.    │"<<endl;
             cout<<"\t\t\t\t\t\t│ 'Y8888P'   'Y88P'  888    888    'Y8888   'Y8888 │"<<endl;
             cout<<"\t\t\t\t\t\t╚──────────────────────────────────────────────────╝\033[0m"<<endl;
             cout<<"\n\n"<<endl;
		    cout<<"\t\t\t\t╔══════════════════════════════════════════════════════════════════════════════╗\n";
            cout<<"\t\t\t\t║              ITEMS                    ║              PRICE                   ║ \n";
            cout<<"\t\t\t\t║══════════════════════════════════════════════════════════════════════════════║\n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        1) Coffee                      ║              20                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        2) Filter                      ║              20                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        3) Nutty Hazzzlenut            ║              50                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        4) Wild Vanilla                ║              50                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        5) Creamy Carame               ║              50                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        6) Ice Mint                    ║              50                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        7) Espresso                    ║              50                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        8) Smoky cinnamon              ║              50                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║        9) Double chocolate mocha      ║              50                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       10) Blueberry chocolate mocha   ║              50                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       11) Mint chocolate mocha        ║              50                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t║       12) Cold Coffee                 ║              80                      ║ \n";
			cout<<"\t\t\t\t║                                       ║                                      ║ \n";
            cout<<"\t\t\t\t╚══════════════════════════════════════════════════════════════════════════════╝\n";
			this_thread::sleep_for(chrono::seconds(1));
			cout<<"\n\n\t\t\t\tPlease Enter which Coffee you would like to have? : ";
			cin>>items;
			if(items>=1 && items<=12)
			{
				cout<<"\n\t\t\t\tPlease Enter Quantity: ";
				cin>>quantity;
				switch(items)
				{
					case 1: price = 20*quantity;
					break;

					case 2: price = 20*quantity;
					break;

					case 3: price = 50*quantity;
					break;
					
					case 4: price = 50*quantity;
					break;

                    case 5: price = 50*quantity;
					break;

					case 6: price = 50*quantity;
					break;

					case 7: price = 50*quantity;
					break;
					
					case 8: price = 50*quantity;
					break;

                    case 9: price = 50*quantity;
					break;

					case 10: price = 50*quantity;
					break;

					case 11: price = 50*quantity;
					break;
					
					case 12: price = 80*quantity;
					break;
				}
                this_thread::sleep_for(chrono::seconds(1));
				switch(items)
				{
			 		case 1:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c1;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
			 		case 2:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c2;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
			 		case 3:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c3;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
			 		case 4:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c4;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
                    case 5:
			 		    cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c5;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
			 		case 6:
			 		    cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c6;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
			 		case 7:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c7;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
			 		case 8:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c8;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
                    case 9:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c9;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
			 		case 10:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c10;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
			 		case 11:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c11;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
			 		case 12:
			 			cout<<"\n\n\t\t\t\t\t\t		--------Your Order---------\n";
			 			cout<<"\n\t\t\t\t\t\t\t\t"<<"Item = "<<quantity<<" "<<c12;
			 			cout<<"\n\n\t\t\t\t\t\t\t\tYour Coffee Bill is Rs."<<price;
			 			break;
				}
			}
			else
			{
				cout<<"Please select a Vailid Option!!!\n\n";
				goto Coffee;
			}
		}
};

class Bill{
	public:
	int c,discount=0;
	int totalBill=0,x;
	string name,phno,address,payment;
	  bool found = false;
  
	int rollDice() 
	{
    random_device rd;
    mt19937 gen(rd());
    uniform_int_distribution<int> dis(4, 10);
    return dis(gen);
    }
void appendUsername(const string& username) {
    ofstream file("pro.txt", ios::app);

    if (!file.is_open()) {
        cerr << "Error opening file!\n";
        return;
    }

    file << username << endl;
    cout << "\n\n\n\t\t\t\t\t\t    Welcome  ★ " << username << " ★ \n";

    file.close();
	name=username;
}

void searchUsername(const string& searchName) {
    ifstream readFile("pro.txt");
    
    if (!readFile.is_open()) {
        cerr << "Error opening file for reading!\n";
        return;
    }

    string line;
    while (getline(readFile, line)) {
        if (line == searchName) {
            found = true;
            break;
        }
    }
    readFile.close();
    name=searchName;
    if (found) {
        cout << "\n\n\t\t\t\t\t\t  Welcome back  : " << searchName << endl;
    } else {
		discount = rollDice();
        cout << "\n\t\t\t\t\t\t\tUsername not found : " << searchName << "\n"<<endl;
		cout<<searchName<<" \t\t\t\t\t\t\tWe have Registered your name."<<endl;
        appendUsername(searchName);

    }
}


 void getbill()
 {
    
       system("clear");
            cout<<"\n\n"<<endl;
             cout<<"\t\t\t\033[45m\033[37m╔──────────────────────────────────────────────────────────────────────────────────╗"<<endl;
             cout<<"\t\t\t│                     .d88b.  d8888b. d8888b. d88888b d8888b.                      │"<<endl;
             cout<<"\t\t\t│                    .8P  Y8. 88  `8D 88  `8D 88'     88  `8D                      │"<<endl;
             cout<<"\t\t\t│                    88    88 88oobY' 88   88 88ooooo 88oobY'                      │"<<endl;
			 cout<<"\t\t\t│                    88    88 88`8b   88   88 88~~~~~ 88`8b                        │"<<endl;
			 cout<<"\t\t\t│                    `8b  d8' 88 `88. 88  .8D 88.     88 `88.                      │"<<endl;
			 cout<<"\t\t\t│                     `Y88P'  88   YD Y8888D' Y88888P 88   YD                      │"<<endl;
			 cout<<"\t\t\t│                                                                                  │"<<endl;
			 cout<<"\t\t\t│d8888b. d8888b.  .d88b.   .o88b. d88888b .d8888. .d8888. d888888b d8b   db  d888b │"<<endl;
			 cout<<"\t\t\t│88  `8D 88  `8D .8P  Y8. d8P  Y8 88'     88'  YP 88'  YP   `88'   888o  88 88' Y8b│"<<endl;
			 cout<<"\t\t\t│88oodD' 88oobY' 88    88 8P      88ooooo `8bo.   `8bo.      88    88V8o 88 88     │"<<endl;
			 cout<<"\t\t\t│88~~~   88`8b   88    88 8b      88~~~~~   `Y8b.   `Y8b.    88    88 V8o88 88  ooo│"<<endl;
			 cout<<"\t\t\t│88      88 `88. `8b  d8' Y8b  d8 88.     db   8D db   8D   .88.   88  V888 88. ~8~│"<<endl;
			 cout<<"\t\t\t│88      88   YD  `Y88P'   `Y88P' Y88888P `8888Y' `8888Y' Y888888P VP   V8P  Y888P │"<<endl;
			 cout<<"\t\t\t╚──────────────────────────────────────────────────────────────────────────────────╝"<<endl;
             cout<<"\t\t\t\033[0m"<<endl;
             cout<<"\n\n\n\n\n"<<endl;
			cout<<"\t\t\t\t\tEnter Address: ";
			cin.ignore();
			getline(cin,address);
			cout<<"\n\n\n\t\t\t\t\t\t      \033[44m---------- Pay Using ---------\033[0m \n\n\n\n\t\t\t\t\t\t\t1.Pay On Delivery\n\n\t\t\t\t\t\t\t2.CreditCard\n\n\t\t\t\t\t\t\t3.UPI"<<endl;
			cout<<"\n\n\t\t\t\t\tEnter Choice: ";
			cin>>x;
			switch(x)
			{
			    case 1:
			    payment="Pay On Delivery";
			    break;
			    case 2:
			    payment="Credit Card";
			    break;
			    case 3:
			    payment="UPI(United Payment Interface)";
			    break;
			   default:
			   cout<<"Invalid Option";
			 
			}
			system("clear");
			this_thread::sleep_for(chrono::milliseconds(100));
            cout <<"\n\n\n\t\t\t\t\t\t    \033[41m  ╔────────────────────────────────╗\033[0m    "<<endl;
			this_thread::sleep_for(chrono::milliseconds(100));
	        cout <<"\t\t\t\t\t\t    \033[41m  │ ██████╗  ██╗ ██╗      ██╗      │\033[0m    "<<endl; 
			this_thread::sleep_for(chrono::milliseconds(100));
            cout <<"\t\t\t\t\t\t    \033[41m  │ ██╔══██╗ ██║ ██║      ██║      │\033[0m    "<<endl; 
			this_thread::sleep_for(chrono::milliseconds(100));
            cout <<"\t\t\t\t\t\t    \033[41m  │ ██████╔╝ ██║ ██║      ██║      │\033[0m    "<<endl; 
			this_thread::sleep_for(chrono::milliseconds(100));
            cout <<"\t\t\t\t\t\t    \033[41m  │ ██╔══██╗ ██║ ██║      ██║      │\033[0m    "<<endl;
			this_thread::sleep_for(chrono::milliseconds(100)); 
            cout <<"\t\t\t\t\t\t    \033[41m  │ ██████╔╝ ██║ ███████╗ ███████╗ │\033[0m    "<<endl; 
			this_thread::sleep_for(chrono::milliseconds(100));
            cout <<"\t\t\t\t\t\t    \033[41m  │ ╚═════╝  ╚═╝ ╚══════╝ ╚══════╝ │\033[0m    "<<endl; 
			this_thread::sleep_for(chrono::milliseconds(100));
            cout <<"\t\t\t\t\t\t    \033[41m  ╚────────────────────────────────╝\033[0m    "<<endl; 
			this_thread::sleep_for(chrono::milliseconds(200));

			cout << "\n\n\n\t\t\t\033[44m★ ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ -------- Hug A Mug Cafe ------- ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ \033[0m\n\n\n";
			if(discount>=1){
			  cout << "\n\t\t\tCongratulations ! "<<name<<"\n"<<endl;
			  cout<<"\t\t\tsince You're a first-time user Hug A Mug offering a discount of " << discount << "%.\n"<<endl;
              cout << "\t\t\tUse this discount on your first order!\n\n";
			  cout<<"\t\t\t★ ---------------------------------------------------------------------------------------- ★\033[0m\n\n\n\n"<<endl;
			}
			
			
		    cout<<"\t\t\t                   \033[44m★ ★ ★ ★ --------- Bill Details -------- ★ ★ ★ ★\033[0m\n\n\n\n";
			cout<<"\t\t\tName         : "<<name<<endl;
		    cout<<"\t\t\tPhone Number : "<<phno<<endl;
		    cout<<"\t\t\tAddress      : "<<address<<"\n"<<endl;
            cout<<"\t\t\t★ ---------------------------------------------------------------------------------------- ★\033[0m"<<endl;
		    cout<<"\n\t\t\tPayment Method : "<<payment<<endl;
			cout << "\t\t\tTotal Amount   : Rs." << totalBill <<"₹"<< "\n";
			cout<<"\t\t\tGST            : 4.5%"<<endl;
			cout<<"\t\t\tTotal Bill     : Rs."<<totalBill+(totalBill*0.045)<<"₹"<<endl;
			if(discount>=1){
			    float dp=totalBill*discount/100;
				cout<<"\t\t\tDiscount       : "<<discount<<"%"<<endl;
			    cout<<"\t\t\tTotal Bill with discount: Rs."<<(totalBill+(totalBill*0.045))-dp<<"₹"<<endl;}
			
            cout<<"\n\t\t\t★ ---------------------------------------------------------------------------------------- ★\033[0m"<<endl;

 }			

};

int main()
{
	Coffee B;
	Bill A;
	string name,phno;
    int c;
	char ch;
	system("clear");
	cout<<"\n\n\n"<<endl;
	this_thread::sleep_for(chrono::seconds(1));
	cout <<"\t\t\t\t      \033[44m\033[37m╔═══════════════════════════════════════════════════════════════════╗\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m║ Yb        dP  888888  88       dP""b8     dPYYb   8b    d8  888888  ║\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m║  Yb  db  dP   88__    88      dP       dP   Yb  88b  d88  88__    ║\033[0m"<<endl;  
    cout <<"\t\t\t\t      \033[44m\033[37m║   YbdPYbdP    88""      88      Yb       Yb   dP  88YbdP88  88""      ║\033[0m"<<endl;  
    cout <<"\t\t\t\t      \033[44m\033[37m║    YP  YP     888888  88ood8   YbodP    YbodP   88 YY 88  888888  ║\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m╚═══════════════════════════════════════════════════════════════════╝\033[0m"<<endl;
	cout<<"\n\n\n"<<endl;
	this_thread::sleep_for(chrono::seconds(1));
	cout <<"\t\t\033[41m     )  (                                                                                              )  (          \033[0m"<<endl;
	this_thread::sleep_for(chrono::milliseconds(200));
	cout <<"\t\t\033[41m      (   )  )                                                                                          (   )  )     \033[0m"<<endl;
	this_thread::sleep_for(chrono::milliseconds(200));
	cout <<"\t\t\033[41m       ) ( (                                                                                              ) ( (      \033[0m"<<endl;
	this_thread::sleep_for(chrono::milliseconds(200));
	cout <<"\t\t\033[41m     _(_____)_      ██╗  ██╗ ██╗   ██╗  ██████╗       █████╗      ███╗   ███╗ ██╗   ██╗ ██████╗         _(_____)_    \033[0m"<<endl;
	this_thread::sleep_for(chrono::milliseconds(200));
	cout <<"\t\t\033[41m  .-'---------|     ██║  ██║ ██║   ██║ ██╔════╝      ██╔══██╗     ████╗ ████║ ██║   ██║██╔════╝      .-'---------|   \033[0m"<<endl;
	this_thread::sleep_for(chrono::milliseconds(200));
	cout <<"\t\t\033[41m ( C| |=|=|=| |     ███████║ ██║   ██║ ██║  ███╗     ███████║     ██╔████╔██║ ██║   ██║██║  ███╗    ( C| |=|=|=| |   \033[0m"<<endl;
	this_thread::sleep_for(chrono::milliseconds(200));
	cout <<"\t\t\033[41m  '-. |=|=|=| |     ██╔══██  ██║   ██║ ██║   ██║     ██╔══██║     ██║╚██╔╝██║ ██║   ██║██║   ██║     '-. |=|=|=| |   \033[0m"<<endl;
	this_thread::sleep_for(chrono::milliseconds(200));
	cout <<"\t\t\033[41m    '_________'     ██║  ██║ ╚██████╔╝ ╚██████╔╝     ██║  ██║     ██║ ╚═╝ ██║ ╚██████╔╝╚██████╔╝       '_________'   \033[0m"<<endl;
	this_thread::sleep_for(chrono::milliseconds(200));
	cout <<"\t\t\033[41m     '-------'      ╚═╝  ╚═╝  ╚═════╝   ╚═════╝      ╚═╝  ╚═╝     ╚═╝     ╚═╝  ╚═════╝  ╚═════╝         '-------'    \033[0m"<<endl;
    cout<<" \n\n\n\n\n\n\n"<<endl;
	this_thread::sleep_for(chrono::seconds(1));
	cout << "\t\t\t\t\t \033[45m\033[37m                                                   \033[0m    "<<endl;   
    cout << "\t\t\t\t\t \033[45m\033[37m Are you a first-time user or already registered ? \033[0m    "<<endl;
	cout << "\t\t\t\t\t \033[45m\033[37m                                                   \033[0m\n\n"<<endl; 
	this_thread::sleep_for(chrono::milliseconds(900));
	cout<<"\t\t\t\t\t\t\t \033[45m\033[37m  1: First-time user \033[0m\n "<<endl;
	cout<<"\t\t\t\t\t\t\t \033[45m\033[37m  2: Registered user \033[0m \n\n\n"<<endl;
	this_thread::sleep_for(chrono::seconds(1));
	cout<<"\t\t\t\t\t  \033[45m\033[37m                 \033[0m"<<endl;
	cout<<"\t\t\t\t\t  \033[45m\033[37m Enter choice =  \033[0m";
    int choice;
    cin >> choice;
	system("clear");
    cout<<"\n\n\n\n"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m╔────────────────────────────────────────────────────────────╗\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m│ 8888888b.             888               d8b  888           │\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m│ 888   Y88b            888               Y8P  888           │\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m│ 888    888            888                    888           │\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m│ 888    888   .d88b.   888888   8888b    888  888  .d8888b  │\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m│ 888    888  d8P  Y8b  888         88b   888  888  88K      │\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m│ 888    888  88888888  888     .d888888  888  888  Y8888b.  │\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m│ 888  .d88P  Y8b.      Y88b.   888  888  888  888      X88  │\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m│ 8888888P     'Y8888    'Y888   Y888888  888  888  88888P'  │\033[0m"<<endl;
    cout <<"\t\t\t\t      \033[44m\033[37m╚────────────────────────────────────────────────────────────╝\033[0m"<<endl;

     cout<<"\n\n\n\n\n\n"<<endl;

    if (choice == 1) {
		sumair:
        string username;
        cout << "\t\t\t\t\t\tEnter your name : ";
        cin.ignore();
        getline(cin, username);
        A.appendUsername(username);
		A.discount=A.rollDice();
        
    } else if (choice == 2) {
        string searchName;
        cout << "\t\t\t\t\tEnter the username to search: ";
        cin.ignore();
        getline(cin, searchName);

        A.searchUsername(searchName);
    } else {
		goto sumair;
        cout << "Invalid choice.\n";
    }
     cout<<"\n"<<endl;
	cout<<"\n\t\t\t\t\tEnter Your Phone Number : ";
	getline(cin,A.phno);
	cout<<"\n"<<endl;
    start:  
	system("clear");
	cout<<"\n\n\n"<<endl;
	cout <<"\t\t\t\t\t    \033[41m╔═══════════════════════════════════════════════╗\033[0m    "<<endl;
	cout <<"\t\t\t\t\t    \033[41m║   888b     d888                               ║\033[0m    "<<endl; 
    cout <<"\t\t\t\t\t    \033[41m║   8888b   d8888                               ║\033[0m    "<<endl; 
    cout <<"\t\t\t\t\t    \033[41m║   88888b.d88888                               ║\033[0m    "<<endl; 
    cout <<"\t\t\t\t\t    \033[41m║   888Y88888P888   .d88b.   8888888.  888  888 ║\033[0m    "<<endl; 
    cout <<"\t\t\t\t\t    \033[41m║   888 Y888P 888  d8P  Y8b  888  88b  888  888 ║\033[0m    "<<endl; 
    cout <<"\t\t\t\t\t    \033[41m║   888  Y8P  888  88888888  888  888  888  888 ║\033[0m    "<<endl; 
    cout <<"\t\t\t\t\t    \033[41m║   888   '   888  Y8b.      888  888  888  888 ║\033[0m    "<<endl; 
    cout <<"\t\t\t\t\t    \033[41m║   888       888   'Y8888   888  888   888888  ║\033[0m    "<<endl; 
    cout <<"\t\t\t\t\t    \033[41m╚═══════════════════════════════════════════════╝\033[0m    "<<endl;


	
	cout<<"\n\n\n\n\t\t\t\t\t\t     What would you like to order?\n\n";
    cout<<"          \t\t\t\t\t    ╔═══════════════════════════════╗     "<<endl;
	cout<<"          \t\t\t\t\t    ║                               ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║         1) Coffee             ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║                               ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║         2) Milkshakes         ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║                               ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║         3) Moctails           ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║                               ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║         4) Thickshakes        ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║                               ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║         5) Icecreams          ║     "<<endl;
	cout<<"          \t\t\t\t\t    ║                               ║     "<<endl;
    cout<<"          \t\t\t\t\t    ╚═══════════════════════════════╝     "<<endl;
	cout<<"\n\n\t\t\t\t\t\t    Please Enter your Choice: ";
	cin>>c;
    system("clear");
	if(c==1)
	{
        B.get_coffee();
        A.totalBill += B.price;
		cout<<"\n\n\t\t\t\t\t\t		---------------------------\n";
		this_thread::sleep_for(chrono::seconds(1));
		cout<<"\n\n\n\n\t\t\t\tWould You like to order anything again? Y / N: ";
		cin>>ch;
		cout<<endl;
		if(ch=='Y' || ch=='y')
		{
			goto start;
		}
		else
		{
		 A.getbill();
		}
	}
	else if(c==2)
	{
		B.get_milkshakes();
		A.totalBill += B.price;

		cout<<"\n\n\t\t\t\t\t\t		---------------------------\n";
		this_thread::sleep_for(chrono::seconds(1));
		cout<<"\n\n\n\n\t\t\t\tWould You like to order anything again? Y / N: ";
		cin>>ch;
		if(ch=='Y' || ch=='y')
		{
		  goto start;
		}
		else
		{
		 A.getbill();
		}		
	}
	else if(c==3)
	{
		B.get_moctails();
		A.totalBill += B.price;
		cout<<"\n\n\t\t\t\t\t\t		---------------------------\n";
		this_thread::sleep_for(chrono::seconds(1));
		cout<<"\n\n\n\n\t\t\t\tWould You like to order anything again? Y / N: ";
		cin>>ch;
		if(ch=='Y' || ch=='y')
		{
			goto start;
		}
		else
		{
		 A.getbill();

	}
	}
	else if(c==4)
	{
		B.get_thickshakes();
		A.totalBill += B.price;
		
		this_thread::sleep_for(chrono::seconds(1));
		cout<<"\n\n\n\n\t\t\t\tWould You like to order anything again? Y / N: ";
		cin>>ch;
		if(ch=='Y' || ch=='y')
		{
			goto start;
		}
		else
		{
		 A.getbill();
		
		}
	}
	else if(c==5)
	{
        B.get_icecream();
        A.totalBill += B.price;
		this_thread::sleep_for(chrono::seconds(1));
		cout<<"\n\n\n\n\t\t\t\tWould You like to order anything again? Y / N: ";
		cin>>ch;
		if(ch=='Y' || ch=='y')
		{
			goto start;
		}
		else
		{
		 A.getbill();
			
		}
	}
	else if(c==6)
	{
		 A.getbill();
		
	}
	else
	{
		cout<<"Please Select Right Option: \n";
		this_thread::sleep_for(chrono::seconds(1));
		cout<<"\n\n\n\n\t\t\t\tWould You like to order anything again? Y / N: ";
		cin>>ch;
		if(ch=='Y' || ch=='y')
		{
			goto start;
		}
		else
		{
			 A.getbill();
		
		}
	}
		this_thread::sleep_for(chrono::seconds(1));
		cout<<"\n\n\n\n\t\t\t\tWould You like to order anything again? Y / N: ";
		cin>>ch;
		if(ch=='Y' || ch=='y')
		{
			goto start;
		}
		system("clear");
		cout<<"\n\n\n\n\n\n\n\t\t\t★ \033[44m----------------------------------------------------------------------------------------\033[0m ★\n\n\n"<<endl;
		cout<<"\t\t\t\t  Thanks for Ordering your order will be Delivered in 10 to 15 mins. "<<endl;
		cout<<"\n\n\t\t\t\t\t             ★ ★  Hug A Mug Cafe ★ ★\n"<<endl;
	    cout<<"\n\t\t\t★ \033[44m----------------------------------------------------------------------------------------\033[0m ★\n\n\n\n"<<endl;
	
	return 0;
}
