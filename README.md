
#include<iostream>
#include"LinkedList.hh"
using namespace std;

int main() {

	sd::vector<int> vec;
	vec.add(1);
	vec.add(2);
	vec.add(3);
	vec.add(4);


	sd::Node<int>* currentNode = vec.getRoot();
	while (currentNode!=nullptr){
		cout << currentNode->val << endl;
		currentNode = currentNode->next;
	}

	system("pause");
	return 0;
}
