#include <iostream>
using namespace std;

class Node {
public:
    int data;
    Node* next;
};

int main() {
    
    Node *first, *second;

    // Allocate nodes
    first = new Node();
    second = new Node();

    cout << "Enter data for first node: ";
    cin >> first->data;

    cout << "Enter data for second node: ";
    cin >> second->data;

    // Linking nodes
    first->next = second;
    second->next = NULL;

    // Traversal
    Node* temp = first;
    cout << "Linked List: ";

    while (temp != NULL) {
        cout << temp->data << " -> ";
        temp = temp->next;
    }

    cout << "NULL";

    return 0;
}
