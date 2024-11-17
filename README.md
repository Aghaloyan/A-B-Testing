A/B Testing 
Scenario 
You have four advertisement options (bandits), and your task is to design an experiment using Epsilon Greedy and Thompson Sampling. 
Design of Experiment 
A bandit class has already been created for you. It is an abstract class with abstract methods. You 
must not exclude anything from the Bandit() class. However, you can add more stuff if you need.
Bandit_Reward=[1,2,3,4] 
NumberOfTrials: 20000 
Create a Bandit Class 

Create EpsilonGreedy() and ThompsonSampling() classes and methods (inherited 
from Bandit()).  
1. Epsilon-greedy:  
     decay epsilon by 1/t 
     design the experiment 

Thompson Sampling  
  design with known precision 
  design the experiment  

Report:  
  Visualize the learning process for each algorithm (plot1()) 
  Visualize cumulative rewards from E-Greedy and Thompson Sampling. 
  Store the rewards in a CSV file ({Bandit, Reward, Algorithm}) 
  Print cumulative reward  
  Print cumulative regret 
Note the values of epsilon and precision are up to you to decide. 

Submission  
1. The code must be well documented, I’d recommend using pyment package 
2. We will not continue checking after the error message (regardless of the error). 
3. Late submissions will be treated according to the rules written in the syllabus. 
4. Push the codes to GitHub and submit only the link of a repo to Moodle
