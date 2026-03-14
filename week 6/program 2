#include <iostream>
using namespace std;

class Node {
public:
    int data;
    Node* next;
};

int main() {

    Node *head = NULL, *temp = NULL, *newNode = NULL;
    int choice = 1;

    while(choice == 1) {

        newNode = new Node();

        cout << "Enter node: ";
        cin >> newNode->data;

        newNode->next = NULL;

        if(head == NULL) {
            head = newNode;
            temp = newNode;
        }
        else {
            temp->next = newNode;
            temp = newNode;
        }

        cout << "Do you want to create another node? (1 for Yes / 0 for No): ";
        cin >> choice;
    }

    // Traversal
    cout << "Linked List: ";
    temp = head;

    while(temp != NULL) {
        cout << temp->data << " -> ";
        temp = temp->next;
    }

    cout << "NULL";

    return 0;
}
