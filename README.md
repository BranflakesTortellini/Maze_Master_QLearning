# Maze_Master_QLearning

The Maze_Master_QLearning Python script trains an agent using Q-Learning tables to explore and memorize a way out of a maze. The agent does not know the maze in advance but learns its details through exploration. 

## Features

- Allows customization of the maze and various starting parameters, including exploration rate, discount value, learning rate, maximum number of steps before giving up, and maximum number of episodes before stopping the training session.
- Supports loading previously saved Q-tables from successful runs, as long as the new maze has the same dimensions. However, there is currently no converter to change Q-tables from one maze type to another.
- Provides starting Q-tables for Maze 6 and Maze 7, which are of the same dimensions. These Q-tables have been trained on both mazes.
- Allows users to view run history to determine the most successful run based on the number of steps taken (ignoring negative values, which indicate failures).
- Generates videos of successful runs, which can be found in the frames folder. Users can manually convert these frames to videos using the final cell of the script.
- Provides the option to change the frequency of image and video saves in the starting parameters section at the start of the script. Fewer saves result in faster trials.

## Usage

1. Customize the maze and starting parameters as needed.
2. Set the starting parameters to point to a previously saved Q-table in the starting_q_tables folder (optional). Comment out this section to perform a "fresh run" without loading a Q-table.
3. Run the script.
4. Review the run history and videos of successful runs for analysis and evaluation.

For more information, please contact Btorrigino@gmail.com.
