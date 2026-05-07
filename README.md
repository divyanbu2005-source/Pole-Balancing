# EX.1  Pole Balancing using Reinforcement Learning
## Date:

## Aim
The aim of this project is to develop a Reinforcement Learning agent that learns to balance a pole on a moving cart by interacting with the environment and maximizing cumulative rewards.



# Algorithm

## Q-Learning Algorithm for Pole Balancing

### Step 1
Initialize the CartPole environment.

### Step 2
Initialize the Q-table with zeros.

### Step 3
Observe the current state of the environment.

### Step 4
Choose an action using the epsilon-greedy policy:
- Exploration → Random action
- Exploitation → Best action from Q-table

### Step 5
Perform the selected action.

### Step 6
Receive:
- Reward
- Next state
- Done status

### Step 7
Update the Q-value using:

Q(s,a) = Q(s,a) + α [ r + γ max Q(s',a') − Q(s,a) ]

Where:
- α → Learning rate
- γ → Discount factor

### Step 8
Repeat the process until the episode ends.

### Step 9
Train the agent for multiple episodes to improve balancing performance.

---

# Program

```
```

---

# Output

```text

```

---

# Result

The Reinforcement Learning agent successfully learned to balance the pole using the Q-Learning algorithm.  
The reward increased gradually with training episodes, demonstrating that the agent improved its balancing strategy through learning and interaction with the environment.


