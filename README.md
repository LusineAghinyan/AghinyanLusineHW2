# AghinyanLusineHW2

Bandit_Reward=[1,2,3,4] 
NumberOfTrials: 20000
Required Steps:
1. Create a Bandit Class
2. Create EpsilonGreedy() and ThompsonSampling() classes and methods (inherited
from Bandit()).
Epsilon-greedy Class:
1. decay epsilon by 1/t
2. design the experiment
Thompson Sampling Class:
1. design with known precision
2. 2. design the experiment
  
Final Steps:
Report:
1. Visualize the learning process for each algorithm (plot1())
2. Visualize cumulative rewards from E-Greedy and Thompson Sampling. 3. Store the rewards in a CSV file ({Bandit, Reward, Algorithm})
4. Print cumulative reward
5. Print cumulative regret
Note the values of epsilon and precision are up to you to decide.

BONUS- Suggest better implementation plan (10 points )
Consider using a modular design approach to improve clarity and reusability while developing a strong and scalable 
solution for comparing bandit algorithms. This may be accomplished by organising your code into discrete modules, such as a
Bandit Base Class for common functions, subclasses for each algorithm (e.g., Epsilon Greedy and Thompson Sampling), and separate 
modules for data administration and visualisation. Implementing a configuration management system with JSON, XML, or INI files can
make it easier to alter simulation settings. Enhance visualisations using interactive plots created with libraries like as Plotly,
and consider adding a dashboard for real-time experiment monitoring using Dash or Streamlit.

Use modern statistical analysis tools to create performance measures and make scientific comparisons using statistical tests.
Improve your implementation by incorporating complete error handling, logging, and speed optimisation. Ensure dependability via a 
suite of unit tests and detailed documentation for both code and user instructions. Finally, building a collaborative atmosphere by 
open-sourcing the project on sites such as GitHub may encourage community contributions while also improving the project's stability 
and feature set. This strategic approach not only provides effective simulation management, but it also improves the educational and 
practical value of the bandit algorithm comparison tool.


