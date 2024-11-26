Task 1: Build a Menu Navigation System
We will implement a simple hierarchical menu system using a tree structure. Users will navigate through the menu using keyboard inputs.
Menu Class Design:
	Menu: A class representing a menu item. Each menu item will have a list of submenus (children).
	Navigation: We will implement navigation functionality, allowing users to navigate up, down, enter, and back.
	Menu Class: The Menu class represents each menu item. It has a name and a list of submenus.
	MenuSystem Class: Manages the navigation of the menus. Users can navigate down to a submenu by selecting an option, and go back to the previous menu by entering 0.

Task 2: Simulate an Instrument Cluster Data Display
We will create a system that simulates real-time updates of car data such as speed, fuel, and temperature. 
This will be done using classes, random number generation, and multithreading.
	VehicleData Class: Holds the vehicle parameters (speed, fuel, temperature). Random values are generated every second.
	Display Class: Displays the vehicle parameters, with warnings if the fuel is low or the temperature is high.
	Multithreading: Two threads run concurrently to update the vehicle data and display it in real-time.
 
Task 3: Event Handling System for Touchscreen Input
This system simulates touchscreen input events like tapping and swiping, processes them, and outputs the results.
	Event Class: Represents an event with type, coordinates, and timestamp.
	EventQueue Class: Stores and processes events in a queue.
	Event Handling: The program processes random events and outputs the result.
 
Task 4: HMI Skin Customization System
This task allows the user to choose between different display themes (like classic, sport, eco) and apply them.
	Theme Class: Represents a theme with properties like background color, font color, font size, and icon style.
	Map: A std::map stores the different themes.
	User Input: The user selects a theme from the list, and the program displays the details of the selected theme.
