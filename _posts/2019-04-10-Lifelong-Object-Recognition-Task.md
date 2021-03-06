# Lifelong Object Recognition 
- This task intends to explore how to leverage the knowledge learned from previous tasks that could help learn new task better, and also how to efficiently memorize of previously learned tasks. Making the robot behaves like the human with knowledge transfer, association, and combination capabilities.

- From instance-incremental; class-incremental; attribute-incremental. The goal is to test the model’s capability over continuous learning without forgetting learned patterns at several levels (instances/classes/attributes).

- The final score is obtained via averaging the 3 aspects scores. (1) accuracy over both new and old tasks, e.g. object recognition; (2) the memory efficiency. The model size should be fixed not exceeding our bounded value, and (3) the running time for inference under the same setting. An evaluation metric will be provided.

# Task-specific Rules
- The methods should be incremental, which means the model should be only trained over current task, and test over all learned tasks.
- The memory requirement of the model should be bounded by a finite bound, especially, the bound shall be independent of the number of training samples presented to the system, e.g. fixed model size.
- The computational demand of adding new training tasks or making a single inference should be bounded by a finite bound.
- The final score is obtained via averaging the 3 aspects scores. (1) accuracy over both new and old tasks, e.g. object recognitions; (2) the memory efficiency. The model size should be fixed not exceeding our bounded value; and (3) the running time for inference under same setting. An evaluation metric will be provided.

# Important Dates
*Dataset Release - June, 2019*
- The teams could choose the sensors and processing platforms. It is a virtual competition (software-level).

*First Round - Sept, 2019*
- Register for the competition first. 
- Download datasets, software tools, and upload the results before the deadline.
- Highest-scored teams will be invited to the final competition.

*Final Round - Nov, 2019*
- A new dataset will be used for the final competition.
- The algorithms from each team shall be run onsite. 
- Results will be visualized in real time for the audience.



