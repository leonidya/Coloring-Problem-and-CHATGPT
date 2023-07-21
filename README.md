**Coloring-Problem-and-CHATGPT**

I wanted to express an idea stimulated by an experimental study titled "Behavioral Experiments on a Network Formation Game" conducted by researchers Michael Kearns, Siddharth Suri, and Nick Montfort (https://pubmed.ncbi.nlm.nih.gov/16902134). Fundamentally, the inquiry is whether ChatGPT agents can be utilized to address and resolve real-world complications through self-interaction. This hypothetical scenario would entail the delegation of roles to each AI agent, reminiscent of experts in a brainstorming session, each providing insights based on their assigned expertise.

For instance, let's consider an investigation into the unfortunate explosion of the SpaceX Starship. The AI agents would be assigned roles akin to those of Aerospace Engineers, Material Scientists, Mechanical Engineers, Avionics Engineers, and Meteorologists, among others. Each agent, equipped with a fragment of relevant information, would interact with its counterparts, striving to deduce the cause of the mishap. Would such a collaboration yield the desired result?

In another light, could these ChatGPT agents be leveraged to establish a successful startup? This would imply assigning the AI agents roles common to a startup setting, such as Founder/CEO, CTO or Lead Developer, Sales/Business Development, Marketing Specialist, Finance Manager or CFO, and so on. Through consistent interaction, could the agents foster a startup that is capable of thriving in the real world?

But let's start with a more simple problem, the coloring problem.

```diff
🟢🔵 Coloring Problem 🟢🔵
```
Coloring Problem - In the field of computer science and mathematics, is a type of graph problem. It's a way of assigning colors to certain elements of a larger entity so that no two adjacent elements share the same color. It can be used in: Traffic Light Synchronization, Education - Timetabling, Marketing - Ad Scheduling, Urban Planning, Team Formation, Vaccination Strategy, Recycling Program, Coloring Maps, etc. Actually, we use it on a daily basis, for example, phone ringtone that differs from those of family members, friends, and colleagues. In the context of a disease outbreak, you might want to ensure the effective distribution of limited vaccine supplies. Let's say you've categorized people into high-risk (red), medium-risk (green), and low-risk (blue) based on factors such as age, medical history, occupation, etc. You aim to distribute the vaccines in such a way that no two high-risk individuals are adjacent to the social network, hence minimizing the potential for the disease to spread among them. 

Experiment:
```diff
 🟩 Experiment 🟩 
```
The only thing the agent of ChatGpt should do is choose a color that is different from their friends (there are only two colors - green or blue). For example, if your friend from the right is blue and your friend from the left is blue, and you are also blue, choose green. If you can't decide still chose green or blue. Two variants of information provision exist in this scenario: minimal information (restricted to the colors chosen by the friends to the left and right), and extensive information. So, Can ChatGPT agents solve the problems, when they are not related to each other and each of them will receive a specific part of the information to solve it? 

```diff
 🟩 6 nodes 🟩 
```

Defined graph:
![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/eb4edfcd-e728-4638-a14c-75bc95f869c2)
Result:
![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/8ab6c3ec-899a-425c-bf4a-068ff34d463d)


Simulation:

![6_nodes](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/b7cf573b-5cca-4a16-8d41-9936a0bc4d5b)
![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/c31a2de4-0942-4e3c-b57c-9f373dc1bea9)

```diff
 🟩 8 nodes 🟩 
```

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

Defined grapth: 

![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/523f280a-2e5e-4745-aa0c-9177c860aa1a)

Desirable result: 

![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/2d98fd76-f9dd-451d-bf5e-b87e7b5ca00c)

Result: 

![image](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/7d43f394-ba1f-4aca-8501-de353878d4a1)

Some insights: 
1. First, this simulation provides some human behavior insights - agents behave like humans - think about it, what if I want to order 32 people in a certain way, will it be easy? Especially when I'm only looking at a friend from the left and right. In addition, it is enough for one member to change his place, it destroys the whole order and everything starts again. Some think happen in Economic Networks: In economics, the network of trade between countries influences global economic dynamics. For instance, a disturbance in one part of the network (like an economic crisis in one country) can have ripple effects throughout the network (another example is Ecological Networks).
2. The initial graph has a huge influence on how fast the problem will be solved. Some things happen in social networks, where structure has a strong influence on behavior. For instance, your circle of friends (your immediate network structure) greatly influences your behavior, opinions, and even your health habits.
3. It demonstrates that if the system becomes more complex it more hard to ChatGPT to solve it. The same thing happens with people, it's more had to arrange a large number of people in some structure or way of thinking. More information also didn't solve the problem. 

Initially, it is vital to clarify that my findings are based on the application of the ChatGPT 3.5 model, as the ChatGPT 4.0 version is accessible solely on a trial basis and not readily available to all. This distinction is important, as advancements between versions may yield differing outcomes. Secondly, I encountered some complexities related to the model's temperature parameter. An attempt to mitigate this issue involved adjusting the temperature to a random value within the range of 1.5 to 2, a solution that unfortunately had its limitations. In several instances, the output from certain agents was a complete mess. One potential workaround for this complication might involve passing the generated output to another agent for further processing and refinement, an approach I did not employ during my analysis.

Drawing parallels with a similar human experiment, where a resolution was reached within five minutes, it is worth noting that the number of iterations required was not specified. This raises the question: Can ChatGPT successfully solve these problems? In my assessment, for relatively simple challenges, the answer leans toward the affirmative. For instance, fostering interactions between Marketing agents and a Product Manager could yield valuable marketing content. Furthermore, understanding the product's lifecycle from a customer's perspective (awareness, knowledge, liking, etc.) could provide critical insights.

However, when it comes to more complex issues, it seems we may still be on the precipice of a breakthrough. Still, it should not be summarily concluded that its effectiveness is confined to such issues alone. It is plausible that the application of ChatGPT could result in disparate levels of success across various fields. As for the anticipated timeline, until such advancements become feasible, that remains uncertain. Nevertheless, given the rapid pace of progress in the field, it is plausible that we may not be waiting long.

To summarize, while the current version of ChatGPT agents shows promise in handling relatively simpler tasks, its efficacy in resolving more complicated problems requires further investigation and possibly more sophisticated iterations of the model.
( All text was generated by CHATGPT - with some modifications)

![main-qimg-9935661f2ef938ba6a60d4e0c4447a09-lq](https://github.com/leonidya/Coloring-Problem-and-CHATGPT/assets/53173112/c58b6e4d-3a4e-41ae-829a-c7a854317919)
