Program

#include <stdio.h>

#include <malloc.h> #include <stdlib.h>

Struct node {

int value

struct node *next;

ns

void insert ();

word display();

void delete (),

int count 11;

typedef struct node DATA-NODE;

DATA-NODE head_node, * first_node, temp_node = 0,

* prev_node, next_node

int data;

int main () {

int option = 0;

mintf("songly linked list Example -All

while (option 26) {

operation in),
"Print f(" in options \n");

printf(" 1: Insert into linked list \n"); Printf 2: Delete from linked list \n");

printf(" 3: Display linked list \n");

printf ("4: count linked list \n"); Printf(" Others: Exit ()\n");

printf("Enter option :"); Scanf ("d", & option);

Switch Loption {

case 1: insest ();

break;

case 2:

delete (),

break;

case 3: display (1)

break

Case 4%.

count (); break;

default:

break;

3
return 0;

3 void insert () {

Print f(" In Enter Element for insert linked list: In), scanf("%d", & data);

temp_node (DATA_NODE *)malloc (size of (DATA_NODE)

temp_node-> value data;

if (first_node ==0) { first_node- temp_node;

} else {

head node next = temp_node,

3 temp_node->next = 0; head- node = temp_node Slush (stain),

void delete () {

int countvalue, pos, i=0; Countvalue count();

temp-node-first-node; printf ("In Display linked list:

printf ("In Enter position for Delete element: \n");

scanf ("d", & pos);

is (Pos JOAR POS <= count value) {

if (Pos == 1) {

temp-node - temp_node->next; first_node = temp -node;

printf("In Deleted successfully in \n");

else {

while (temp_node 1 = 0) {

if (i == (p0s -1)) {

Prev_node->next = temp_node->next; head- node - prev_node;

if (i == Count value - ))

{

3 printf(" in Deleted successfully in in");

break;

else &

Prev_node = temp_node;

temp_node = temp_node-> >next;

}
