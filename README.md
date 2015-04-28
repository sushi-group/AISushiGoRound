# Artificial Intelligence for the game Sushi Go Round Version 1.0 27/04/2015
This A.I. wins all the levels with a score more than 50000.
## GENERAL USAGE NOTES

- **Install the joda time library** </br>
Download the file [here](http://sourceforge.net/projects/joda-time/files/joda-time/2.1/). Unzip it. Open Eclipse. Left click on the project. Go to Properties/Java Build Path/Libraries/Add External JARs... Then add the file Joda-time-2.1 (Executable Jar File) that is in the unzipped file.
- **Run the game** </br>
Open the game [here](http://www.freearcade.com/SushiGoRound.flash/SushiGoRound.html) and wait until it is fully loaded. Then put the browser on the left or the right side of the screen. On the other side put the java source code and click run. The AI will start playing the game.

## DESCRIPTION
The artificial intelligence is divided in 6 classes. The class StartServing is the class that contains the main method and that uses all the other classes to run the program.
### 1. Element
This is simple class that is used to represent an element with two coordinates.
### 2. Ingredient
This class represents the ingredients that we use to create a sushi. For an ingredient we need its order coordinates, its name and its order date.
### 3. Sushi
This class represents all the sushis. Pictures of these sushis are saved in the project, so we need an attribute String that has the same name as the picture. Also, there a string with the exact name of the sushi and an HashMap with its ingredients. Finally, there is boolean that is needed to know if we have enough ingredients to create this sushi.
### 4. Order
This class represents the orders of the customers. An order is about a sushi, so there is an attribute sushi, its preparation date and a boolean that is used to know if this order has been realised.
### 5. Restaurant
This class is mainly used to represent all the important coordinates of the game. has also other important methods, such as the method leftClick.
### 6. Chef
This class implements all the actions that we do : get the orders of the customers, make the orders, take the plates and order ingredients.
## 7. StartServing
This is the class that contains the main method and that uses all the other classes to run the program.
## CONTACTS
**Dimitrios Christaras-Papageorgiou** </br>
Email:  dimitris_xx@hotmail.com</br>
**Cheikh Ndiaye** </br>
Email:  mr-tagabunt@hotmail.fr</br>
**Ismail Boukili** </br>
Email:  </br>
**Hamza Gounteti** </br>
Email: gounteti16@gmail.com  </br>
## LICENSE
Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
