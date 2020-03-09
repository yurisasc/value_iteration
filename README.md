# Assignment 3: Value Iteration and Q-Learning

##### Work by:
1. Yuris Aryansyah Shalichin Cakranegara
2. Alexander Bayusuto Wanengkirtyo
3. Vincentius Aditya Sundjaja

Support code provided by Course Coordinator.

##### Instructions to run
In the directory, run commands directly from command prompt.

To experience Gridworld in manual control mode, use:

`python3 gridworld.py -m`

A full list of options for GridWorld or Pacman is available by running:

`python3 gridworld.py -h`
`python3 pacman.py -h`

The default agent moves randomly. You should see the random agent bounce around the grid until it happens upon an exit:

`python3 gridworld.py -g MazeGrid`


##### Examples:

Run the gridworld value iteration agent with 5 iterations

`python3 gridworld.py -a value -i 5`

Run the gridworld value iteration agent with 100 iterations on a BrideGrid map with 0.9 discount value and 0.2 noise

`python3 gridworld.py -a value -i 100 -g BridgeGrid --discount 0.9 --noise 0.2`

Run the pacman agent with 2000 iterations and 2010 games on a specific map

`python3 pacman.py -p PacmanQAgent -x 2000 -n 2010 -l smallGrid`

