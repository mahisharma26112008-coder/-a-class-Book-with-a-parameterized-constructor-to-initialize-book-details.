# -a-class-Book-with-a-parameterized-constructor-to-initialize-book-details.

#include<iostream>
#include<string>
 using namespace std;
class book{
    public:
    string book_name;
    string author;
    int price;

    book(string b,string a,int p){
        book_name=b;
        author=a;
        price=p;
    }
    void display(){
        cout<<"book name : "<<book_name<<"\n";
        cout<<"author name : "<<author<<"\n";
        cout<<"price : "<<price<<"\n";
    }
};

int main(){
    book b1("c++","mahi sharma",200);

    b1.display();

    return 0;

    
}
