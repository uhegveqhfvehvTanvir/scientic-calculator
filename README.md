# scientic-calculator


1. Imports:
    - I started off with code like numpy and np. 
    - I also used matplotlib.pyplot and plt. It helps draw nice pictures.

2. Function Definitions:
    - prompt_user(): Shows a menu for the user to pick up from and asks whatever they want to pick or put in. Then it shows what you choose.
    - calculate_area_triangle(base, height): It figures out how big a triangle or length also when I know its base and height.
     - calculate_area_circle(radius): It tells you the area of a circle when we know how far it is from the center to the edge.
    - calculator(): Asks what math you want to put in (for example adding, subtraction, etc.) and then with two numbers we have been given with.
    - graph_plotting(): It asks you if you want to draw a fancy line graph or a trigonometry one. Then it draws it for you.


3. Main Function (main()):
    - The main part of the program.
    - It asks you what we want to do (math or drawing) using the prompt_user() function.
    - Then it either does normal and simple math equations or it either draws graphs based on what you decided to pick.


4. Prompting User and Handling Choices:
    - prompt_user(): Gives us choices and waits for us to pick one. Then it tells the program on what we chose.
    - In main(), depending on what you decide to pick, it does it in different ways - either math or drawing the graph like I said earlier.


5. Mathematical Calculations:
    - In the math part of main(), it asks what shape we want to find the area of or what math we equation you want to do.
    - Then it uses the right function to figure it out based on what you want.


6. Graph Plotting:
    - In the drawing part of main(), it asks if we want a line graph or a trigonometry graph.
    - Then it uses the right function to draw what you want.

7. Error Handling:
    - The drawing function checks if we type in a weird math way to put in such as like random words for the graph, then it doesn't get confused.
    - We could add more checks in other parts of the program for when we type in stuff that doesn't make sense.

