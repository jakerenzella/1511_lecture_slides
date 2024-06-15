## Winter is coming
	Assignment 2 releasing soon
---
	### End of this week or early next week
	* Linked lists
	* Dynamic memory
	* Structs
---
## Week 8 Revision Sessions
	* Sign up here: https://www.eventbrite.com/e/23t2-week-8-revision-sessions-tickets-675799653957?aff=oddtdtcreator
	- Wednesday 2pm-4pm (online)
	- Thursday 12pm-2pm (Ainsworth 201 - BYOD)
---
## `malloc()`
	* `malloc` -> Memory Allocation (allocate memory on the heap)
	* Returns a pointer to the location on the heap
	* We can decide how large the allocation
---
## Calling `malloc`
	* `ptr = (cast-type*) malloc(byte-size)`
## Example:
```c
#include <stdio.h>

int main(void) {
	malloc(1000);
	malloc(sizeof(int));
	malloc(sizeof(char) * 50);

	return 0;
}
```
---
## Heap memory cheat sheet
	* Allocate memory: `malloc()`
	* Deallocate: `free()`
	* Grow/shrink memory `realloc`
	* All require `stdlib.h`
---
## Dynamic arrays on the heap
	A common way of using malloc is to create dynamic arrays:
```c
int main(void) {
	int num_elements;
	scanf("%d", num_elements);
	
	int *data = malloc(num_elements * sizeof(int));
	
	return 0;
}
```
---
## Demo
---

### Feedback
	[https://forms.office.com/r/K3PjvWebtD](https://forms.office.com/r/K3PjvWebtD)
/assets/QRCode for COMP1511 Lecture Feedback.png
size: contain