# Algorithm

Algorithms are a crucial component when designing an AI. In simple terms, an algorithm is a description of the different actions that should be followed to solve a problem, or carry out a task, similar to a recipe used when cooking.

Developers use a combination of algorithms to build human-like machines that display artificial intelligence in order to carry out a specific task. Building an AI system or model is complex.

# Complexity

When building an AI machine, developers not only aim to make the machine respond like a human; they want to make it 'think' like a human before it responds. That is where complexity arises.

Developers need to consider the complexities of the real world when they program an artificially intelligent robot - the different experiences and reactions related to a particular view of the environment. This introduces a vast amount of variables that the develop needs to take into account like "What objects need to be navigated?" or "How should a human-robot respond if a human asks for coffee?" With an increasing number of variables and scenarios, the complexity increases. 
Hence, certain techniques are needed to manage these complexities.

# Heuristics

Human queries cannot be defined logically or mathematically most of the time. So how should an AI react to a question that is relative to the 'human' environment? The answer is through the use of heuristics, or by giving a response that is a good approximation of a "perfect" response, Heuristics, as a key principle, is aimed at simplifying a task. It is used when classic methods cannot be used in practice to deliver an ideal solution.

# To show these principles in action; let's consider "The Travelling Salesman Problem"

**Given:** A list of cities and the distance between each pair of cities.

**Question:** What is the shortest possible route that goes through each city and returns to the origin city?

**The Problem:** If the salesman is to pass through 3 cities, starting and ending in one "home city", then there are only two possible trip options. If the number of cities rises to 10, then the number of trip options exceed 180k permutations/combinations. IF the number of cities to be visited is in the thousands, it's quite difficult for even a computer to come up with an answer.

**The Heuristic Solution:** To solve this problem, the "nearest neighbour" heuristic can be used. Here, it is taken that the salesman starts at a random city and he will repeatedly visit the nearest city, then the next, until every city is visited.  

This kind of heuristic approach is often used in AI to reduce the complexity of a given problem and to produce an approximate, acceptable solution when a precise calculation using classical methods is not possible