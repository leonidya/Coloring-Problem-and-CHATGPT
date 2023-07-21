**Coloring-Problem-and-CHATGPT**

I wanted to express an idea stimulated by an experimental study titled "Behavioral Experiments on a Network Formation Game" conducted by researchers Michael Kearns, Siddharth Suri, and Nick Montfort (https://pubmed.ncbi.nlm.nih.gov/16902134). Fundamentally, the inquiry is whether ChatGPT agents can be utilized to address and resolve real-world complications through self-interaction. This hypothetical scenario would entail the delegation of roles to each AI agent, reminiscent of experts in a brainstorming session, each providing insights based on their assigned expertise.

For instance, let's consider an investigation into the unfortunate explosion of the SpaceX Starship. The AI agents would be assigned roles akin to those of Aerospace Engineers, Material Scientists, Mechanical Engineers, Avionics Engineers, and Meteorologists, among others. Each agent, equipped with a fragment of relevant information, would interact with its counterparts, striving to deduce the cause of the mishap. Would such a collaboration yield the desired result?

In another light, could these ChatGPT agents be leveraged to establish a successful startup? This would imply assigning the AI agents roles common to a startup setting, such as Founder/CEO, CTO or Lead Developer, Sales/Business Development, Marketing Specialist, Finance Manager or CFO, and so on. Through consistent interaction, could the agents foster a startup that is capable of thriving in the real world?

But let's start with a more simple problem, the coloring problem.
🟢🔵
```diff
 Coloring Problem
```
Coloring Problem - In the field of computer science and mathematics, the coloring problem is a type of graph problem. It's a way of assigning colors to certain elements of a larger entity so that no two adjacent elements share the same color. It can be used in: Traffic Light Synchronization, Education - Timetabling, Marketing - Ad Scheduling, Urban Planning, Team Formation, Vaccination Strategy, Recycling Program, Coloring Maps, etc. Actually, we use it on a daily basis, for example, phone ringtone that differs from those of family members, friends, and colleagues. In the context of a disease outbreak, you might want to ensure the effective distribution of limited vaccine supplies. Let's say you've categorized people into high-risk (red), medium-risk (green), and low-risk (blue) based on factors such as age, medical history, occupation, etc. You aim to distribute the vaccines in such a way that no two high-risk individuals are adjacent to the social network, hence minimizing the potential for the disease to spread among them


The only thing the agent of ChatGpt should do is choose a color that is different from their friends (there are only two colors - green or blue). For example, if your friend from the right is blue and your friend from the left is blue, and you are also blue, choose green. If you can't decide still chose green or blue. 

Can ChatGPT agents solve problems, when they are not related to each other and each of them will receive a specific part of the information to solve this problem? L

Cycle with 6 nodes: 

Defined graph:

![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/dc9005c5-e86a-4799-a3a8-529fb7ae9700)

Result:

![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/d2b7f14a-f90e-45d2-bc95-4dd735a45f96)

Simulation:

![6_nodes](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/b7cf573b-5cca-4a16-8d41-9936a0bc4d5b)
![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/c31a2de4-0942-4e3c-b57c-9f373dc1bea9)

Cycle with 8 nodes: 

Defined graph:

![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/8494e96e-69e1-4391-96fb-dfbe5f5157f3)

Result:

![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/e09a4c5b-6068-4204-8102-6e5063903a16)

Simulation:
![rabdom_8](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/b4cf0863-e6bd-49a3-bd75-f72f27e47467)
![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/39b4a2f7-de63-4209-b9eb-931d73047bc1)

Cycle with 16 nodes - no results - low information:

Defined graph: 

![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/bc63dfbd-bb7b-49a8-946e-e3651aea8411)

Results: 

![filename_1](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/419375fe-4709-4983-90d1-f829826858d0)
![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/3a40f860-fe47-468d-801e-9506c274c7d6)

Just for fun Cycle with 32 nodes - no results:

![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/0b2238ab-b6fe-404d-8412-c3736833d0e3)

This modeling can be used in different fields and give some additional insights, for example: 

1. The initial graph has a huge influence on how fast the problem will be solved. Some things happen in social networks, where structure has a strong influence on behavior. For instance, your circle of friends (your immediate network structure) greatly influences your behavior, opinions, and even your health habits. 
2. It demonstrates that if the system becomes more complex it more hard to ChatGPT to solve it. The same thing happens with people, it's more had to arrange a large number of people in some structure or way of thinking (for example theater). More information also didn't solve the problem. 
3. One node decision can have an impact on the all the system. For example Economic Networks: In economics, the network of trade between countries influences global economic dynamics. For instance, a disturbance in one part of the network (like an economic crisis in one country) can have ripple effects throughout the network (another example is Ecological Networks).

Other insights in progress.... 







