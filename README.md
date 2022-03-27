# Java Project 1
*Java Object Oriantation project for University Of Huddersfield By Caleb Bowden*

### Classes
**Main** - The Main class is responsible for the flow of the program it is used to add volunteers, teams, and team leaders. It acts as the backbone, as it provides all the data, and all methods are called here.

**Team** - This class responsibility is to create a team and store the volunteers. The class also sorts volunteers and creates a clean table that can be returned using a method.

**Volunteer** - Volunteers are essential to the program, this class is responsible for all the volunteer methods, this class is used to store volunteers’ data, calculate wages and boxes. There are also get methods which allow us to get data from that volunteer within another class at any time.

**Team Leader** - Because the team leader class is the same as the volunteer class with a few minor changes to the wage calculation and how it returns true for the team leader, its best to inherit the volunteer class this makes it, so you do not have to copy code.

### Methods Used
**Constructor** - A constructor initialise the classes, they are used to add volunteer values when a new volunteer object is created. There is another constructor used in the Team class where a new array list is created for the team. 

![Picture1](https://user-images.githubusercontent.com/100306913/160293606-558582af-3409-4f17-8367-ec39e684b59d.png)

**Update Boxes** - To update the boxes we must add the previous boxes to the boxes to add amount and then use .this to update that volunteers boxes.

![Picture2](https://user-images.githubusercontent.com/100306913/160293627-c139d7b9-d9c5-4f85-a074-d92a4e8bdf65.png)

**Getting Values** - there are a variety of get methods used these methods are simple and just return the data from that class.

![Picture3](https://user-images.githubusercontent.com/100306913/160293682-0a1acd07-9502-429d-a582-25c1b619ed47.png)

**Calculate Wages** - The brief specified that a volunteer gets 0.15p for the first 50 boxes and then 0.20p for the rest. If the volunteer is a team leader, they get a 20% increase.  They are 2 wage calculations 1 in team leader class and the other in the volunteer class. They preform the same calculations just the team leader one adds 20% increase.

Volunteer Calculation | Team Leader Calculation
---|---
![Picture4](https://user-images.githubusercontent.com/100306913/160293809-726251fd-3e43-43f4-a626-f611f9e39b07.png) | ![Picture5](https://user-images.githubusercontent.com/100306913/160293826-ebf058a8-8b98-4903-a30f-6149e26a7377.png)
