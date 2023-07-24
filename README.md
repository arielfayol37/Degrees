# Six Degrees of Kevin Bacon - Hollywood Film Industry Network

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Overview

Welcome to the Six Degrees of Kevin Bacon project! This project explores the intricate network of the Hollywood film industry by connecting any two actors within the industry using the concept of the Six Degrees of Kevin Bacon game.

The Six Degrees of Kevin Bacon game is a fun and intriguing way to discover how closely related actors are to the legendary Kevin Bacon. The game posits that anyone in the Hollywood film industry can be linked to Kevin Bacon within six steps, where each step consists of finding a movie that two actors both starred in.

## Key Features

- **Breadth-First Search Algorithm:** We've implemented an efficient Breadth-First Search (BFS) algorithm to find the shortest path between any two actors. The algorithm explores the network of actors and movies to discover the connection between them, revealing the fascinating interconnectedness of the Hollywood world.

- **CSV Data Processing:** Our codebase handles CSV data files containing information about actors, movies, and their relationships. It utilizes Python's built-in libraries to load and process the data efficiently, making it easy to expand the dataset for further analysis.

- **Graph Representation:** We've modeled the Hollywood film industry as a graph, where actors are nodes, and movies are edges connecting them. This powerful representation allows us to traverse the network and identify the shortest path between any pair of actors.
## Getting Started

1. Clone this repository to your local machine using `git clone`.

2. Navigate to the project directory.

3. Install the required dependencies by running:
4.  Run the main.py script to start the Six Degrees of Kevin Bacon exploration:
5. Follow the instructions on the screen to input the names of two actors and discover their connection!

## Data Files

The `small` directory contains a small dataset for ease of testing and experimentation. If you want to use a larger dataset, you can replace the files in the `small` directory with your own CSV files following the same format.

The data files are organized as follows:
- `people.csv`: Contains information about people (actors) in the film industry, including unique ids, names, and birth years.
- `movies.csv`: Contains information about movies, including unique ids, titles, and release years.
- `stars.csv`: Establishes a relationship between people and movies, indicating which person starred in which movie.
