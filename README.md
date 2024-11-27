The assignment requires designing a zoo ecosystem in Python, using object-oriented programming principles like inheritance, encapsulation, and method overriding. Here’s an outline of how to approach it:

Steps to Solve:

	1.	Create Parent Classes:
	•	Animal: Base class for all animals, with common features like number_of_legs and number_of_hands.
	•	Bird: Base class for all birds, with features like number_of_legs and number_of_wings.
	2.	Create Derived Classes:
	•	For Animals:
	•	Feline (inherits from Animal): Add specific characteristic like family = 'Cat Family'.
	•	Canine (inherits from Animal): Add family = 'Dog Family'.
	•	Tiger (inherits from Feline): Add characteristics like can_roar = True.
	•	WildCat (inherits from Feline): Add can_climb_trees = True.
	•	Wolf (inherits from Canine): Add hunts_in_pack = True and pack_leader = True/False.
	•	For Birds:
	•	FlightBird (inherits from Bird): Add can_fly = True.
	•	Eagle (inherits from FlightBird): Add flies_high = True.
	3.	Encapsulation:
	•	Use private attributes for animal features, and provide getter methods to access them.
	4.	Zoo Class:
	•	Maintain a list to store animals and birds.
	•	Methods:
	•	add_animal_or_bird: Check if the zoo is full before adding.
	•	view_all: Display details of all animals and birds in the zoo.
	5.	Demonstration:
	•	Create instances for 2 animals and 1 bird, add them to the zoo, and display their details.
