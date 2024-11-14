**Bingo Game Project**

This project is a graphical Bingo game implemented in Python. The game allows users to play Bingo through a graphical user interface (GUI).

**Features**
- Graphical interface for playing Bingo
- Random number generation for Bingo calls
- Interactive gameplay

**Prerequisites**
To run this project, you will need to have Python installed on your system. Additionally, you need the following Python libraries:
- `tkinter` (for the graphical user interface)
- `turtle` (for the graphical user interface)
- `random` (for random number generation)
- `pandas` (for data management and manipulation)
- `matplotlib` (for graphical representation)

You can install any missing libraries using `pip`:

> pip install tk

**How to Run the Project**
1. Clone the repository to your local machine:

> git clone https://github.com/ambarishtirumalai/Bingo-Game-with-GUI.git

2. Navigate to the project directory:

> cd bingo-game

3. Run the gui.py file to start the game:

> python gui.py

**Files in the Repository**
- Bingo.py: Contains the main logic for the Bingo game.
- gui.py: Contains the code for the graphical user interface.

**How to Play**
1. Start the game by running gui.py.
2. Follow the on-screen instructions to play Bingo.

**Running Simulations**
1. Enter the number of Bingo cards per simulation in the "Number of Bingo Cards per
        Simulation" field. Note: Please enter a positive integer number between “3 – 60”.
2. Enter the number of simulations you want to run in the "Number of Simulations"
	field. Note: Please enter a positive integer number between “1-110”.
3. Click the "Start Simulation" button to begin the simulations.

**Simulation Progress**
During the simulation:
* The program generates Bingo cards based on your input.
* It tracks the progress of each simulation, including Bingo and Full House wins.

**Viewing Results**
After simulations are complete:
* You can view the initial Bingo cards generated in a separate window by clicking the
    "Display Initial Cards" button. To view the initial Bingo cards in a CSV format, it is
    present in the file “generated_cards.csv” in the directory.
* To see a graph of Bingo vs. Turn, click the "Display Bingo vs. Turn Graph" button.
* To view a histogram of the first Bingo hits, click the "Display Histogram" button. To
    view the first bingo hit of each player in a CSV format, it is present in the file
    “first_bingo_turns.csv” in the directory.

**Interpreting Results**
* The "Bingo vs. Turn" graph shows the cumulative number of Bingo wins and Full
    House wins as the game progresses. It also consists of the standard deviation, upper
    and lower bound of both bingo and full house wins.
* The histogram displays the distribution of the turn numbers when the first Bingo was
    hit in each simulation.

**Team Members**

1. Ambarish Tirumalai (Standard deviation plot, backend code)
2. Jeyaram Muthukrishnan (Histogram plot, backend code)
3. Leena Mary Varghese (UML, User Manual, backend code)
4. Shirish Senthil Kumar (Display initial cards, GUI integration, backend code)

**Contributing**
If you would like to contribute to this project, please fork the repository and submit a pull request.
